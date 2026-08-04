# Johns Hopkins University (johns-hopkins-university)

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

Johns Hopkins University is a private research university in Baltimore, Maryland, ranked #22 in the QS World University Rankings 2025. This repository catalogs its public developer and API footprint as an APIs.json provider profile for the API Evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/johns-hopkins-university/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=johns-hopkins-university-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Course Catalog, News, United States

## APIs

- **JHU Hub API** — News, announcements, events, photo galleries, and faculty experts from the Hub database. Docs: https://api.hub.jhu.edu/docs/ (API key required; issuance limited to JHU affiliates)
- **Self-Service Public Course Search API (SIS)** — Course catalog data in JSON, filterable by school, department, course/section number, and term. Docs: https://sis.jhu.edu/api and https://sis.jhu.edu/api/help (API key required)
- **JHU API Portal (MuleSoft Anypoint)** — Central API management platform for integration APIs, gated to JHU affiliates. Docs: https://api.jh.edu/

## Plans

- plans/johns-hopkins-university-plans-pricing.yml

## Rate Limits

- rate-limits/johns-hopkins-university-rate-limits.yml

## FinOps

- finops/johns-hopkins-university-finops.yml

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.jhu.edu/
- Developer Portal: https://api.jh.edu/
- GitHub: https://github.com/jhu-sheridan-libraries
- LinkedIn: https://www.linkedin.com/school/johns-hopkins-university/

## Notes

All entries reflect publicly documented APIs verified on 2026-06-03. No endpoints were fabricated. The Hub API and SIS Course Search API are documented and live but both require an API key; the Hub API restricts key issuance to JHU affiliates. The api.jh.edu portal resolves (HTTP 200) but is a gated MuleSoft Anypoint platform. SIS `/api/classes` returns HTTP 500 without a key (expected behavior). JHU operates many public GitHub organizations (e.g., jhu-sheridan-libraries, jhu-data-services, JHUAPL); the Sheridan Libraries org is listed as the representative GitHub property.

## Maintainers

- Kin Lane — kin@apievangelist.com
