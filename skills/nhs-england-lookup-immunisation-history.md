---
name: Look up a patient's NHS immunisation history
description: Retrieve a patient's immunisation record (COVID-19, influenza, HPV and more) from the NHS Immunisation History FHIR R4 API.
api: openapi/nhs-immunisation-history-openapi.yaml
operations: [get-immunisation-history]
---

# Look up a patient's NHS immunisation history

Use the NHS **Immunisation History - FHIR R4 API** to read a patient's vaccination record.

## Preconditions
- OAuth 2.0 bearer token from the NHS API platform. This API is user-restricted or application-restricted; production access requires onboarding, assurance and a connection agreement.
- The patient's valid NHS number (10 digits, Modulus 11 checksum).

## Steps
1. Acquire an access token (application-restricted signed-JWT client credentials, or user-restricted via NHS login / CIS2). Set `Authorization: Bearer <token>`.
2. Set a fresh `X-Correlation-ID` header for request tracing.
3. Call **`get-immunisation-history`** against `/immunisation-history/FHIR/R4` with the patient identifier and any procedure/date filters. Test against `https://sandbox.api.service.nhs.uk/immunisation-history/FHIR/R4` (no token) before production.
4. Parse the returned FHIR **Bundle** of `Immunization` resources; follow `Bundle.link` (next) if paged.

## Error handling
- `401` missing/invalid token, `403` insufficient role/agreement, `404` no record, `429` throttled (honour `Retry-After`). Errors come back as a FHIR **OperationOutcome** (see errors/nhs-england-problem-types.yml).
