# Johns Hopkins University (johns-hopkins-university)

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
