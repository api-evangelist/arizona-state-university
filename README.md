# Arizona State University (arizona-state-university)

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
