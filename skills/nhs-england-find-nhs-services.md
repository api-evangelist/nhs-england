---
name: Find NHS services and organisations
description: Search the national Directory of Healthcare Services and resolve organisation reference data from the ODS FHIR API.
api: openapi/nhs-service-search-openapi.yaml
operations: [search-GET, search-POST, get-single-organization, get-organization-resources]
---

# Find NHS services and organisations

Combine **Service Search** (Directory of Healthcare Services) with the **Organisation Data Service (ODS) FHIR API** to locate NHS services and resolve organisation details.

## Preconditions
- OAuth 2.0 bearer token (application-restricted is typical for reference-data reads).
- Service Search base `/service-search-api`; ODS FHIR base `https://beta.ods.dc4h.link/fhir/`.

## Steps
1. Acquire an access token and set `Authorization: Bearer <token>` plus an `X-Correlation-ID`.
2. Search services with **`search-GET`** (query-string form) or **`search-POST`** (structured query) against Service Search.
3. For an organisation code returned by the search, call **`get-single-organization`** on the ODS FHIR API to resolve the full `Organization` resource, or **`get-organization-resources`** to search organisations.
4. Read the FHIR `Organization` / service resources; page via `Bundle.link` where returned.

## Error handling
- `400` malformed query, `401`/`403` auth, `404` unknown code, `429` throttled. FHIR endpoints return an **OperationOutcome**.
