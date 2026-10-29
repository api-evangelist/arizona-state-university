# Arizona State University

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

Arizona State University (ASU) is a large public research university based in Tempe, Arizona, United States, and one of the largest by enrolment in the country. Its programmable footprint is real but narrow, and almost none of it is presented as a developer product. ASU operates no public developer portal, no self-service API keys and no open data portal — api.asu.edu, data.asu.edu, open.asu.edu and developer.asu.edu do not resolve. What it does operate, verified by live probe on 2026-09-01, is an identity and metadata layer: a Shibboleth SAML 2.0 Identity Provider registered in the InCommon Federation under entityID urn:mace:incommon:asu.edu, serving its own signed metadata from shibboleth2.asu.edu; a CAS single sign-on service at weblogin.asu.edu; and THREE independent OAI-PMH 2.0 repositories on ASU's own hosts — the Library Research Data Repository (a self-built Dataverse, build string asu-6.11-oai-rights, 104 datasets under DOI prefix 10.48349/ASU) plus KEEP and PRISM, the ASU Library Islandora deployments developed in public at github.com/asulibraries. ASU also runs its own course-catalog microservices API and a myASU data platform on its own hosts, but both are OAuth-gated and undocumented for outside developers. It is a registrant in DataCite (member ASU, repository ASU.ASUL), Crossref (member 37851, prefix 10.58875) and ROR (03efmqc40). No vendor contract is held under this slug: the repository software ASU runs is open source and self-hosted, and the specification for it belongs to the projects that wrote it, not to ASU.

**Areas:** University · Higher Education · Education · United States · Arizona · Public Research University · Research Data · Research Repository · Identity Federation · OAI-PMH · Course Catalog · Library

## Arizona State University on APIs.io

Everything profiled for Arizona State University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/arizona-state-university/](https://apis.io/providers/arizona-state-university/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [ASU Shibboleth SAML 2.0 Identity Provider](https://apis.io/apis/arizona-state-university/shibboleth-idp/) — ASU's own Shibboleth Identity Provider, entityID urn:mace:incommon:asu.edu, asserting the scope asu.edu. ASU publishes the signed entity descriptor from its…
- [InCommon Federation registration (urn:mace:incommon:asu.edu)](https://apis.io/apis/arizona-state-university/incommon-federation-registration/) — ASU's registration in the InCommon Federation, retrievable as signed SAML metadata from the InCommon MDQ service and flowing onward into eduGAIN. This is…
- [ASU Library Research Data Repository API (Dataverse)](https://apis.io/apis/arizona-state-university/dataverse-api/) — The ASU Library Research Data Repository runs on the open-source Dataverse platform, on ASU's own host, from an ASU-local build — /api/info/version returns…
- [ASU Research Data Repository OAI-PMH](https://apis.io/apis/arizona-state-university/dataverse-oai/) — OAI-PMH 2.0 metadata harvesting endpoint for the ASU Library Research Data Repository. repositoryName "ASU Library Research Data Repository Dataverse OAI…
- [ASU Library KEEP OAI-PMH](https://apis.io/apis/arizona-state-university/keep-oai/) — OAI-PMH 2.0 endpoint for KEEP, the ASU Library digital repository, running on Islandora that ASU Library builds and deploys itself in public at…
- [ASU Library PRISM OAI-PMH](https://apis.io/apis/arizona-state-university/prism-oai/) — OAI-PMH 2.0 endpoint for PRISM, ASU Library's second Islandora digital-collections repository. repositoryName "ASU Library | PRISM", adminEmail…
- [ASU Course Catalog microservices API](https://apis.io/apis/arizona-state-university/course-catalog-api/) — ASU's own course, class and subject search API, running at eadvs-cscc-catalog-api.apps.asu.edu/catalog-microservices/api/v1 and consumed by the public…
- [myASU Data Platform API (api.myasuplat-dpl.asu.edu)](https://apis.io/apis/arizona-state-university/myasu-data-platform/) — ASU's internal data-platform API gateway, the issuer of the OAuth scopes the course-catalog application requests (scopes/acad-plan/read, scopes/person/read,…
- [ASU WebAuth (CAS single sign-on)](https://apis.io/apis/arizona-state-university/sso-cas/) — ASU operates an enterprise single sign-on service using the Central Authentication Service (CAS) protocol for authenticating ASURITE accounts across…
- [DataCite membership and repository registration](https://apis.io/apis/arizona-state-university/datacite-registration/) — ASU is a DataCite member (provider symbol ASU, memberType consortium_organization, created 2020-09-22) and mints DOIs through the institutional repository…
- [Crossref membership (member 37851)](https://apis.io/apis/arizona-state-university/crossref-registration/) — ASU is a Crossref member, id 37851, primary-name "Arizona State University", located in Tempe, AZ, depositing under DOI prefix 10.58875 with 351 DOIs…
- [ROR organization record (03efmqc40)](https://apis.io/apis/arizona-state-university/ror-registration/) — ASU's Research Organization Registry record, ror.org/03efmqc40, established 1885, status active, domain asu.edu, carrying 11 Crossref Funder IDs, GRID…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Arizona State University Context](https://apis.io/jsonld/arizona-state-university/arizona-state-university-context/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Arizona State University Authentication](https://apis.io/security/arizona-state-university/arizona-state-university-authentication/)
- [Arizona State University Domain Security](https://apis.io/security/arizona-state-university/arizona-state-university-domain-security/)
- [Arizona State University Vulnerability Disclosure](https://apis.io/security/arizona-state-university/arizona-state-university-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Arizona State University Plans Pricing](https://apis.io/plans/arizona-state-university/arizona-state-university-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Arizona State University Rate Limits](https://apis.io/rate-limits/arizona-state-university/arizona-state-university-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Arizona State University Finops](https://apis.io/finops/arizona-state-university/arizona-state-university-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.asu.edu/)
- [Support](https://links.asu.edu/)
- [Blog](https://news.asu.edu/)
- [Privacy policy](https://www.asu.edu/privacy/)
- [GitHub](https://github.com/ASU)

## API Evangelist rating

**Kin Score 22.6** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 17.3 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 28.6 |
| Access clarity | 15.8 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 26.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/arizona-state-university/](https://apis.io/providers/arizona-state-university/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Arizona State University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/arizona-state-university/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
