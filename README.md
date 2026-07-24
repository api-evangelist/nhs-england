# NHS England (nhs-england)

NHS England (which absorbed NHS Digital in 2023) is the national body that runs England's public health and social care API platform at digital.nhs.uk and api.service.nhs.uk. It publishes a large catalogue of internet-facing APIs — most of them HL7 FHIR R4 built to the FHIR UK Core profile — spanning the national spine services and citizen-facing products. Home market is the United Kingdom (England).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nhs-england/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nhs-england/refs/heads/main/apis.yml)

## Tags

- Healthcare
- United Kingdom
- National Health System
- FHIR
- HL7
- Interoperability
- SMART on FHIR
- Health Data
- e-Prescribing
- EHR

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### Personal Demographics Service (PDS) - FHIR API

National electronic database of NHS patient demographic details, exposed as HL7 FHIR R4. Production endpoint confirmed live and auth-gated (HTTP 401 without a token).

- **Human URL:** [https://digital.nhs.uk/developer/api-catalogue/personal-demographics-service-fhir](https://digital.nhs.uk/developer/api-catalogue/personal-demographics-service-fhir)
- **Base URL:** `https://api.service.nhs.uk/personal-demographics/FHIR/R4`

### GP Connect Access Record - Structured - FHIR API

Retrieve a patient's GP practice record as structured HL7 FHIR resources from EMIS and TPP SystmOne GP systems.

- **Human URL:** [https://digital.nhs.uk/developer/api-catalogue/gp-connect-access-record-structured-fhir](https://digital.nhs.uk/developer/api-catalogue/gp-connect-access-record-structured-fhir)

### Electronic Prescription Service (EPS) - FHIR API

National service for sending electronic prescriptions from prescribers to dispensers, as HL7 FHIR R4. Sandbox FHIR endpoint confirmed live.

- **Human URL:** [https://digital.nhs.uk/developer/api-catalogue/electronic-prescription-service-fhir](https://digital.nhs.uk/developer/api-catalogue/electronic-prescription-service-fhir)
- **Base URL:** `https://api.service.nhs.uk/electronic-prescriptions/FHIR/R4`

### e-Referral Service (e-RS) - FHIR API

Paperless referrals from primary to secondary care. OpenAPI harvested verbatim (38 paths).

- **Human URL:** [https://digital.nhs.uk/developer/api-catalogue/e-referral-service-fhir](https://digital.nhs.uk/developer/api-catalogue/e-referral-service-fhir)
- **Base URL:** `https://api.service.nhs.uk/referrals/FHIR`
- **OpenAPI:** [openapi/nhs-e-referral-service-openapi.yaml](openapi/nhs-e-referral-service-openapi.yaml)

### Booking and Referral Standard (BaRS) - FHIR API

Sends booking and referral information between NHS service providers. OpenAPI harvested verbatim (8 paths).

- **Human URL:** [https://github.com/NHSDigital/booking-and-referral-fhir-api](https://github.com/NHSDigital/booking-and-referral-fhir-api)
- **Base URL:** `https://api.service.nhs.uk/booking-and-referral/FHIR/R4`
- **OpenAPI:** [openapi/nhs-booking-and-referral-fhir-openapi.yaml](openapi/nhs-booking-and-referral-fhir-openapi.yaml)

### Immunisation History - FHIR API

Access a patient's immunisation record as HL7 FHIR R4. OpenAPI harvested verbatim.

- **Human URL:** [https://digital.nhs.uk/developer/api-catalogue/immunisation-fhir-api](https://digital.nhs.uk/developer/api-catalogue/immunisation-fhir-api)
- **Base URL:** `https://api.service.nhs.uk/immunisation-history/FHIR/R4`
- **OpenAPI:** [openapi/nhs-immunisation-history-openapi.yaml](openapi/nhs-immunisation-history-openapi.yaml)

### Organisation Data Service (ODS) - FHIR API

Reference data on NHS and healthcare organisations, roles and terminology, as HL7 FHIR R4. OpenAPI harvested verbatim (8 paths).

- **Human URL:** [https://github.com/NHSDigital/organisation-data-service-fhir-api](https://github.com/NHSDigital/organisation-data-service-fhir-api)
- **Base URL:** `https://beta.ods.dc4h.link/fhir/`
- **OpenAPI:** [openapi/nhs-organisation-data-service-fhir-r4-openapi.yaml](openapi/nhs-organisation-data-service-fhir-r4-openapi.yaml)

### NHS App API

Deliver messages and content to citizens and link into NHS App journeys. OpenAPI harvested verbatim (4 paths).

- **Human URL:** [https://github.com/NHSDigital/nhs-app-api](https://github.com/NHSDigital/nhs-app-api)
- **Base URL:** `https://api.service.nhs.uk/nhs-app`
- **OpenAPI:** [openapi/nhs-app-openapi.yaml](openapi/nhs-app-openapi.yaml)

### NHS Notify (Communications Manager) API

National service for sending messages to people about their health and care across channels. OpenAPI harvested verbatim (7 paths).

- **Human URL:** [https://github.com/NHSDigital/communications-manager-api](https://github.com/NHSDigital/communications-manager-api)
- **Base URL:** `https://api.service.nhs.uk/comms`
- **OpenAPI:** [openapi/nhs-communications-manager-openapi.yaml](openapi/nhs-communications-manager-openapi.yaml)

### Service Search (Directory of Healthcare Services) API

Search the national Directory of Healthcare Services. OpenAPI harvested verbatim.

- **Human URL:** [https://github.com/NHSDigital/service-search-api](https://github.com/NHSDigital/service-search-api)
- **Base URL:** `https://api.service.nhs.uk/service-search-api`
- **OpenAPI:** [openapi/nhs-service-search-openapi.yaml](openapi/nhs-service-search-openapi.yaml)

## Common Properties

- [Website](https://digital.nhs.uk/)
- [Developer Portal](https://digital.nhs.uk/developer)
- [API Catalogue](https://digital.nhs.uk/developer/api-catalogue)
- [GitHub Organization](https://github.com/NHSDigital)
- [Help and Support](https://digital.nhs.uk/developer/help-and-support)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
