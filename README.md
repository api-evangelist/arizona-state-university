# Arizona State University (arizona-state-university)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Arizona State University (ASU) is a large public research university in Tempe, Arizona, United States, ranked #200 in the QS World University Rankings 2025. This repository catalogs ASU's confirmed public developer and API footprint as an [APIs.json](https://apisjson.org) profile. ASU's strongest documented public API surface is its Library Research Data Repository, a Dataverse instance exposing a native REST API and OAI-PMH metadata harvesting, alongside a public course catalog, CAS/Shibboleth single sign-on, and an official GitHub organization.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/arizona-state-university/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=arizona-state-university-api-evangelist&utm_content=repo

## Type

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Education, Higher Education, University, Research Data, Open Data, United States, Arizona

## APIs

- **ASU Library Research Data Repository API** — Dataverse 6.10.1 native REST API for datasets and metadata. Docs: https://guides.dataverse.org/en/latest/api/ — Base: https://dataverse.asu.edu/api
- **ASU Research Data Repository OAI-PMH** — OAI-PMH 2.0 metadata harvesting endpoint. Docs: https://guides.dataverse.org/en/latest/admin/harvestserver.html — Base: https://dataverse.asu.edu/oai
- **ASU Course Catalog & Class Search** — public course/class search (no officially documented public API). Docs: https://catalog.apps.asu.edu/catalog/classes
- **ASU WebAuth (CAS / Shibboleth SSO)** — enterprise single sign-on, gated to approved service providers. Docs: https://getprotected.asu.edu/services/identity-and-access-management/authentication-services

## Plans, Rate Limits & FinOps

- Plans & Pricing: [plans/arizona-state-university-plans-pricing.yml](plans/arizona-state-university-plans-pricing.yml)
- Rate Limits: [rate-limits/arizona-state-university-rate-limits.yml](rate-limits/arizona-state-university-rate-limits.yml)
- FinOps: [finops/arizona-state-university-finops.yml](finops/arizona-state-university-finops.yml)

## Timestamps

- **Created:** 2026-06-03
- **Modified:** 2026-06-03

## Common Properties

- Website: https://www.asu.edu/
- GitHub: https://github.com/ASU
- LinkedIn: https://www.linkedin.com/school/arizona-state-university/
- Twitter: https://twitter.com/ASU
- Authentication: https://getprotected.asu.edu/services/identity-and-access-management/authentication-services
- Source Code (Libraries): https://github.com/asulibraries
- Review: [review.yml](review.yml)

## Notes

All endpoints in this profile were probed live during cataloging (see [review.yml](review.yml)). The Dataverse REST API and OAI-PMH endpoints returned HTTP 200 with valid responses. The course catalog resolves publicly but has no officially documented public API — third-party tools consume it via scraping and undocumented endpoints, so no base URL is asserted here. CAS/Shibboleth SSO is live but restricted to approved ASU service providers. No endpoints were fabricated; gated or undocumented surfaces are described honestly.

## Maintainers

- Kin Lane — kin@apievangelist.com
