---
name: Book an appointment with the Booking and Referral Standard
description: Discover bookable slots and submit a booking/referral message using the NHS Booking and Referral Standard (BaRS) FHIR R4 API.
api: openapi/nhs-booking-and-referral-fhir-openapi.yaml
operations: [getMessageDefinition, getSlots, processMessage, getBooking, getBookingByPatient]
---

# Book an appointment with the Booking and Referral Standard (BaRS)

Use the **BaRS FHIR R4 API** to move booking and referral information between NHS service providers.

## Preconditions
- OAuth 2.0 bearer token; base `/booking-and-referral/FHIR/R4`. Sandbox: `https://sandbox.api.service.nhs.uk/booking-and-referral/FHIR/R4`.
- BaRS is message-based FHIR; you exchange FHIR **Bundle** messages.

## Steps
1. Acquire an access token; set `Authorization: Bearer <token>` and an `X-Correlation-ID`.
2. Retrieve the message contract with **`getMessageDefinition`** to confirm the expected Bundle shape.
3. Discover availability with **`getSlots`** for the target HealthcareService.
4. Submit the booking/referral message with **`processMessage`** (a `$process-message` FHIR operation carrying the Bundle).
5. Confirm with **`getBooking`** (by id) or **`getBookingByPatient`** (by patient).

## Error handling
- `400` invalid Bundle, `401`/`403` auth, `404` slot/booking not found, `429` throttled. Responses are FHIR **OperationOutcome** (errors/nhs-england-problem-types.yml).
