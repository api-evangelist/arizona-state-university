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

Arizona State University (ASU) is a large public research university in Tempe, Arizona, United States. This repository catalogs ASU's confirmed public programmable footprint as an [APIs.json](https://apisjson.org) profile, re-profiled on 2026-09-01 under the API Evangelist **university pipeline**, which settles *who operates* each surface before anything is credited to the institution.

ASU operates no public developer portal, no self-service API keys and no open data portal — `api.asu.edu`, `data.asu.edu`, `open.asu.edu`, `developer.asu.edu` and `status.asu.edu` do not resolve. What it does operate is an identity and metadata layer: a Shibboleth SAML 2.0 Identity Provider registered in the InCommon Federation, a CAS single sign-on service, and **three** independent OAI-PMH 2.0 repositories on its own hosts.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/arizona-state-university/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=arizona-state-university-api-evangelist&utm_content=repo

## Type

- **Type:** Index (`x-type: university`)
- **Category:** Public Research University
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

University, Higher Education, Education, United States, Arizona, Public Research University, Research Data, Research Repository, Identity Federation, OAI-PMH, Course Catalog, Library

## Surfaces, by operator

Every entry carries an `x-operator` saying **who runs the thing it describes** — not how we came to hold it.

### `institution` — ASU's own hosts, ASU's own operation (8)

| Surface | Base | Probe |
|---|---|---|
| ASU Shibboleth SAML 2.0 Identity Provider | `https://shibboleth2.asu.edu/idp/shibboleth` | 200 |
| ASU Library Research Data Repository API (Dataverse) | `https://dataverse.asu.edu/api` | 200 on operations |
| ASU Research Data Repository OAI-PMH | `https://dataverse.asu.edu/oai` | 200 |
| ASU Library **KEEP** OAI-PMH | `https://keep.lib.asu.edu/oai/request` | 200 |
| ASU Library **PRISM** OAI-PMH | `https://prism.lib.asu.edu/oai/request` | 200 |
| ASU Course Catalog microservices API | `https://eadvs-cscc-catalog-api.apps.asu.edu/catalog-microservices/api/v1` | 401 (gated) |
| myASU Data Platform API | `https://api.myasuplat-dpl.asu.edu` | live, no public entry point |
| ASU WebAuth (CAS SSO) | `https://weblogin.asu.edu/cas` | 401 (gated) |

### `federation` — shared by definition, the entity inside it is ASU's (1)

- **InCommon Federation registration**, entityID `urn:mace:incommon:asu.edu` — `https://mdq.incommon.org/entities/urn%3Amace%3Aincommon%3Aasu.edu` (200, signed SAML metadata, saved locally)

### `registry` — identifier registries ASU is registered in (3)

- **DataCite** — member `ASU`, repository `ASU.ASUL` (Arizona State University Library), DOI prefix `10.48349`
- **Crossref** — member `37851`, DOI prefix `10.58875`, 351 DOIs
- **ROR** — `https://ror.org/03efmqc40`

### `tenant` / `vendor` — none

No tenant relationship and **no vendor contract** is held under this slug. Dataverse and Islandora are open-source projects ASU deploys and patches itself (the Dataverse build string is `6.11 asu-6.11-oai-rights`; the Islandora work is public at [github.com/asulibraries](https://github.com/asulibraries)). The deployments are ASU's; the product specifications belong to the upstream projects and are deliberately not saved here.

## Domain standard conformance (`education` regime)

Five of twelve evidenced, each pointing at a fetched location with a status code — see [conformance/arizona-state-university-conformance.yml](conformance/arizona-state-university-conformance.yml).

- **oai-pmh** — three live repositories (Dataverse, KEEP, PRISM)
- **shibboleth** / **saml** — InCommon-registered IdP, metadata served from ASU's own host
- **datacite** — member + institutional repository account + DataCite kernel-4 metadata prefix
- **crossref** — member 37851

Not found: `scim`, `lti`, `oneroster`, `ed-fi`, `caliper`, `qti`, `orcid`.

## Artifacts

- Authentication: [authentication/arizona-state-university-authentication.yml](authentication/arizona-state-university-authentication.yml)
- SAML IdP metadata: [authentication/arizona-state-university-saml-idp-metadata.xml](authentication/arizona-state-university-saml-idp-metadata.xml)
- Conformance: [conformance/arizona-state-university-conformance.yml](conformance/arizona-state-university-conformance.yml)
- Plans & Pricing: [plans/arizona-state-university-plans-pricing.yml](plans/arizona-state-university-plans-pricing.yml)
- Rate Limits: [rate-limits/arizona-state-university-rate-limits.yml](rate-limits/arizona-state-university-rate-limits.yml)
- FinOps: [finops/arizona-state-university-finops.yml](finops/arizona-state-university-finops.yml)
- Review: [review.yml](review.yml)

## Timestamps

- **Created:** 2026-06-03
- **Modified:** 2026-09-01

## Common Properties

- Website: https://www.asu.edu/
- Blog: https://news.asu.edu/
- Privacy Policy: https://www.asu.edu/privacy/
- Support: https://links.asu.edu/
- GitHub Organization: https://github.com/ASU
- Source Code (Libraries): https://github.com/asulibraries
- LinkedIn: https://www.linkedin.com/school/arizona-state-university/
- Twitter: https://twitter.com/ASU
- Identity Federation: https://mdq.incommon.org/entities/urn%3Amace%3Aincommon%3Aasu.edu
- Research Repository: https://lib.asu.edu/research/research-data-repository
- Library: https://lib.asu.edu/
- Course Catalog: https://catalog.apps.asu.edu/catalog/classes
- AI Policy: https://provost.asu.edu/generative-ai
- AI Tooling: https://ai.asu.edu/ai-tools

## Notes

Every pointer and every base URL in this profile was probed live on 2026-09-01, with negative probes to rule out soft-404 credit. Two findings worth keeping:

- `dataverse.asu.edu` and `keep.lib.asu.edu` return **403 "ASU error page"** to a scripted User-Agent on their HTML paths while their API and OAI paths return 200. That is an edge bot rule, not an outage.
- The previously recorded documentation pointer `getprotected.asu.edu/services/identity-and-access-management/authentication-services` has gone to a hard **403 Access denied** and was replaced from the site's own sitemap.

The course-catalog API was found by reading the public single-page-application bundle at `catalog.apps.asu.edu` — the page itself is a 391-byte SPA shell, and link presence alone would have shown a "public course catalog API" that does not exist. No endpoints were fabricated; gated and undocumented surfaces are described as such.

## Maintainers

- Kin Lane — kin@apievangelist.com
