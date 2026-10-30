# NHS England

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

NHS England (which absorbed NHS Digital in 2023) is the national body that runs England's public health and social care API platform at digital.nhs.uk and api.service.nhs.uk. It publishes a large catalogue of internet-facing APIs - most of them HL7 FHIR R4 built to the FHIR UK Core profile - covering the national spine services: the Personal Demographics Service (PDS), GP Connect, the e-Referral Service (e-RS), the Electronic Prescription Service (EPS), the Organisation Data Service (ODS), Booking and Referral Standard (BaRS), immunisation history, the NHS App, NHS Notify, and the Directory of Healthcare Services. Access is governed centrally: applications onboard through the NHS API platform and authenticate with OAuth 2.0 bearer tokens - application-restricted (signed-JWT client credentials / API key) or user-restricted via NHS login (OIDC) and NHS CIS2 - with production access gated behind registration, assurance, and connection agreements. Home market is the United Kingdom (England). Positioning: a single national health system operating public, standards-based (FHIR UK Core) interoperability APIs rather than a commercial API vendor.

**Areas:** Healthcare · United Kingdom · National Health System · FHIR · HL7 · Interoperability · SMART on FHIR · Health Data · e-Prescribing · Electronic Health Records · Clinical · Demographics

## NHS England on APIs.io

Everything profiled for NHS England is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nhs-england/](https://apis.io/providers/nhs-england/)** — or go straight to one of the APIs or properties below.

### APIs (25)

- [Personal Demographics Service (PDS) - FHIR API](https://apis.io/apis/nhs-england/nhs-personal-demographics-service-fhir/) — National electronic database of NHS patient demographic details - name, address, date of birth, related people, registered GP, nominated pharmacy and NHS…
- [GP Connect Access Record - Structured - FHIR API](https://apis.io/apis/nhs-england/nhs-gp-connect-access-record-structured-fhir/) — Lets authorised health and social care staff retrieve a patient's GP practice record as structured HL7 FHIR resources (medications, allergies, problems,…
- [Electronic Prescription Service (EPS) - FHIR API](https://apis.io/apis/nhs-england/nhs-electronic-prescription-service-fhir/) — National service for sending electronic prescriptions from prescribers to dispensers (pharmacies), exposed as an HL7 FHIR R4 API. Sandbox FHIR endpoint…
- [NHS England Booking API](https://apis.io/apis/nhs-england/nhs-england-booking-api/) — The Booking API from NHS England — 2 operation(s) for booking.
- [NHS England Callbacks API](https://apis.io/apis/nhs-england/nhs-england-callbacks-api/) — The Callbacks API from NHS England — 3 operation(s) for callbacks.
- [NHS England Channels API](https://apis.io/apis/nhs-england/nhs-england-channels-api/) — The Channels API from NHS England — 1 operation(s) for channels.
- [NHS England Code System API](https://apis.io/apis/nhs-england/nhs-england-codesystem-api/) — The CodeSystem API from NHS England — 1 operation(s) for codesystem.
- [NHS England Communication API](https://apis.io/apis/nhs-england/nhs-england-communication-api/) — The communication API from NHS England — 4 operation(s) for communication.
- [NHS England Immunization API](https://apis.io/apis/nhs-england/nhs-england-immunization-api/) — The Immunization API from NHS England — 1 operation(s) for immunization.
- [NHS England List{id} API](https://apis.io/apis/nhs-england/nhs-england-list-id-api/) — The List{id} API from NHS England — 1 operation(s) for list{id}.
- [NHS England Message API](https://apis.io/apis/nhs-england/nhs-england-message-api/) — The Message API from NHS England — 1 operation(s) for message.
- [NHS England Message Batches API](https://apis.io/apis/nhs-england/nhs-england-message-batches-api/) — The Message Batches API from NHS England — 1 operation(s) for message batches.
- [NHS England Messages API](https://apis.io/apis/nhs-england/nhs-england-messages-api/) — The Messages API from NHS England — 2 operation(s) for messages.
- [NHS England Metadata API](https://apis.io/apis/nhs-england/nhs-england-metadata-api/) — The Metadata API from NHS England — 2 operation(s) for metadata.
- [NHS England Organisation API](https://apis.io/apis/nhs-england/nhs-england-organisation-api/) — The Organisation API from NHS England — 1 operation(s) for organisation.
- [NHS England Organization API](https://apis.io/apis/nhs-england/nhs-england-organization-api/) — The Organization API from NHS England — 2 operation(s) for organization.
- [NHS England Organization Affiliation API](https://apis.io/apis/nhs-england/nhs-england-organizationaffiliation-api/) — The OrganizationAffiliation API from NHS England — 2 operation(s) for organizationaffiliation.
- [NHS England R4 API](https://apis.io/apis/nhs-england/nhs-england-r4-api/) — The R4 API from NHS England — 6 operation(s) for r4.
- [NHS England Referral API](https://apis.io/apis/nhs-england/nhs-england-referral-api/) — The Referral API from NHS England — 2 operation(s) for referral.
- [NHS England Slots API](https://apis.io/apis/nhs-england/nhs-england-slots-api/) — The Slots API from NHS England — 1 operation(s) for slots.
- [NHS England STU3 API](https://apis.io/apis/nhs-england/nhs-england-stu3-api/) — The STU3 API from NHS England — 32 operation(s) for stu3.
- [NHS England Value Set API](https://apis.io/apis/nhs-england/nhs-england-valueset-api/) — The ValueSet API from NHS England — 1 operation(s) for valueset.
- [e-Referral Service (e-RS) FHIR API](https://apis.io/apis/nhs-england/e-referral-service/) — The NHS e-Referral Service combines electronic booking with a choice of place, date and time for first hospital or clinic appointments. The e-RS FHIR API…
- [Summary Care Record (SCR) API](https://apis.io/apis/nhs-england/summary-care-record/) — The Summary Care Record holds essential patient information from the GP record. The SCR API enables authorised health and care professionals to retrieve a…
- [NHS Login API](https://apis.io/apis/nhs-england/nhs-login/) — NHS login provides a single, secure way for citizens to access NHS digital services. The NHS login API enables relying parties to authenticate users, verify…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Nhs England Webhooks](https://apis.io/asyncapis/nhs-england/nhs-england-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [nhs-england](https://apis.io/servers/nhs-england/nhs-england/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Nhs England Agentic Access](https://apis.io/agentic-access/nhs-england/nhs-england-agentic-access/)

#### Overlays (7)

OpenAPI overlays, including conversational phrasing for each operation.

- [Nhs App Overlay](https://apis.io/overlays/nhs-england/nhs-app-overlay/)
- [Nhs Booking And Referral Fhir Overlay](https://apis.io/overlays/nhs-england/nhs-booking-and-referral-fhir-overlay/)
- [Nhs Communications Manager Overlay](https://apis.io/overlays/nhs-england/nhs-communications-manager-overlay/)
- [Nhs E Referral Service Overlay](https://apis.io/overlays/nhs-england/nhs-e-referral-service-overlay/)
- [Nhs Immunisation History Overlay](https://apis.io/overlays/nhs-england/nhs-immunisation-history-overlay/)
- [Nhs Organisation Data Service Fhir R4 Overlay](https://apis.io/overlays/nhs-england/nhs-organisation-data-service-fhir-r4-overlay/)
- [Nhs Service Search Overlay](https://apis.io/overlays/nhs-england/nhs-service-search-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Nhs England Authentication](https://apis.io/security/nhs-england/nhs-england-authentication/)
- [Nhs England Domain Security](https://apis.io/security/nhs-england/nhs-england-domain-security/)
- [Nhs England Vulnerability Disclosure](https://apis.io/security/nhs-england/nhs-england-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://digital.nhs.uk/)
- [Documentation](https://digital.nhs.uk/developer/guides-and-documentation/reference-guide)
- [Getting started](https://digital.nhs.uk/developer/guides-and-documentation)
- [API reference](https://digital.nhs.uk/developer/api-catalogue)
- [Support](https://digital.nhs.uk/developer/help-and-support)
- [Blog](https://digital.nhs.uk/blog)
- [Security](https://www.england.nhs.uk/security-vulnerability-disclosure/)
- [Compliance](https://www.england.nhs.uk/long-read/digital-clinical-safety-assurance/)
- [GitHub](https://github.com/NHSDigital)

## API Evangelist rating

**Kin Score 46.1** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 55.9 |
| Contract governance | 18.2 |
| Operational transparency | 44.7 |
| Developer ergonomics | 66.1 |
| Access clarity | 7.9 |

**Agent readiness 35.3** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | mostly |

**Regulatory alignment 32.8** — Health

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nhs-england/](https://apis.io/providers/nhs-england/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for NHS England: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nhs-england/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
