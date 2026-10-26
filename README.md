# NHS England (nhs-england)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
