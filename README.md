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

Johns Hopkins University is a private research university in Baltimore, Maryland, founded in 1876 and ranked #21 in the QS World University Rankings 2026. This repository catalogs its public developer and API footprint as an APIs.json provider profile for the API Evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/johns-hopkins-university/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=johns-hopkins-university-api-evangelist&utm_content=repo

## Type

- University / Private Research University / Index / Consumer / 3rd-Party

## Who operates what

A university is a federation of buyers, not a producer, so every surface in this profile carries an `x-operator` saying **who runs the thing the contract describes** — not merely where we found it.

| Surface | Host | Operator | Contract saved? |
|---|---|---|---|
| JHU Hub API | api.hub.jhu.edu | institution | Yes — derived from the operator's own public docs |
| SIS Classes API | sis.jhu.edu/api | institution | Yes |
| SIS Codes API | sis.jhu.edu/api | institution | Yes |
| JHU API Portal (MuleSoft Anypoint) | api.jh.edu | institution | No — catalog gated to affiliates |
| Shibboleth Identity Provider | login.jh.edu | institution | Yes — SAML 2.0 metadata |
| Project MUSE OAI-PMH | muse.jhu.edu/oai | institution | Yes — live Identify / ListMetadataFormats |
| Johns Hopkins Research Data Repository | archive.data.jhu.edu | institution | **No** — Dataverse software; the contract is the Dataverse Project's |
| Johns Hopkins Research Portal | pure.johnshopkins.edu | **tenant** | **No** — Elsevier Pure tenancy; the contract is Elsevier's |

Two things deliberately did **not** get credited to Johns Hopkins:

- **Dataverse and Pure contracts.** The repository, its data and its DOIs are the institution's. The API contract is the vendor's, and saving it under this slug is exactly the misattribution that produced eight universities scoring the same Figshare document in the June 2026 cohort.
- **A Figshare tenancy.** `jhu.figshare.com` resolves and answers HTTP 202 — but so does `zzznotarealtenant.figshare.com`. The DNS record is a wildcard, not evidence. No Figshare relationship is claimed.

## APIs

- **JHU Hub API** — news, announcements, events, photo galleries and faculty experts from the Hub database. Fifteen resource families, each with a collection, object and subcollection endpoint, in HAL JSON. Docs: https://api.hub.jhu.edu/docs/ (API key issued by email to JHU affiliates; `v=1` required)
- **Self-Service Public Course Search API (SIS)** — course catalog data as JSON, filterable by school, department, course/section number and term. Docs: https://sis.jhu.edu/api/help (API key required)
- **JHU API Portal (MuleSoft Anypoint)** — enterprise integration APIs, gated to JHU affiliates. https://api.jh.edu/
- **Shibboleth Identity Provider** — SAML 2.0 IdP metadata published by JHU itself at https://login.jh.edu/idp/shibboleth, scoped to johnshopkins.edu and jh.edu, and registered in InCommon as `urn:mace:incommon:johnshopkins.edu` with Research & Scholarship entity categories and SIRTFI assurance.
- **Project MUSE OAI-PMH** — operated by Johns Hopkins University Press. 897,938 records across 971 sets in `oai_dc`, **no authentication**. https://muse.jhu.edu/oai?verb=Identify

## Education-regime domain standard conformance

Scored against the Kin Score `education` regime. Reward-only, and every hit is anchored to a probed URL — see `conformance/johns-hopkins-university-education-standards-conformance.yml`.

| Standard | Status | Evidence |
|---|---|---|
| shibboleth | conformant | `shibmd:Scope` in the IdP metadata at login.jh.edu |
| saml | conformant | SAML 2.0 `protocolSupportEnumeration`, signed InCommon entity |
| oai-pmh | conformant | `protocolVersion` 2.0 from muse.jhu.edu/oai |
| datacite | conformant | DataCite direct member, symbol `JHU`, 8 registered repositories |
| scim, lti, oneroster, ed-fi, caliper, qti, orcid, crossref | not found | no institution-operated evidence |

## Coverage

`covered` — three institution-operated APIs, two SAML identity artifacts and one fully open OAI-PMH repository all verified live on 2026-08-19. The profile is genuinely thin, not under-researched: key issuance is gated to JHU affiliates on both documented APIs and there is no central public developer portal, no changelog, no deprecation policy and no working status page (`status.jh.edu` returns 500).

One caveat, and it is about us rather than about them: Cloudflare bot management returns 403 to automated clients across the JHU WordPress estate (`www.jhu.edu`, `ai.jhu.edu`, `it.johnshopkins.edu`, `teaching.jhu.edu`, `press.jhu.edu`) and across `jscholarship.library.jhu.edu` and `archive.data.jhu.edu`. Those hosts grade **live**, not dead — the OAI-PMH endpoint that re3data records for the Research Data Repository simply could not be exercised from here.

## Known defect on the JHU surface

`GET https://sis.jhu.edu/api/classes` with no key returns **HTTP 500** with the plain-text body `Unable to authenticate: API Key parameter is missing in URL ...`. A missing API key is a client error and belongs at 401 or 403. As it stands an agent cannot tell an auth failure from a server outage without parsing prose. See `errors/johns-hopkins-university-errors.yml`.

## Artifacts

- `openapi/` — SIS Classes, SIS Codes, and the Hub API (all `method: derived` from the operators' published documentation, with pristine copies in `openapi/_original/`)
- `identity-federation/` — IdP + InCommon SAML metadata, and a manifest of entity IDs, bindings and scopes
- `conformance/` — education-regime standard conformance with per-standard evidence, plus raw OAI-PMH responses
- `errors/`, `lifecycle/`, `json-schema/`, `json-structure/`, `json-ld/`, `vocabulary/`, `rules/`, `examples/`, `collections/`, `authentication/`, `agentic-access/`, `plans/`, `rate-limits/`, `finops/`, `security/`

Every artifact carries `generated`, `method` and `source`. Nothing here is published by Johns Hopkins University.

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Common Properties

- Website: https://www.jhu.edu/
- Developer Portal: https://api.jh.edu/
- API Reference: https://api.hub.jhu.edu/docs/
- Course Catalog: https://sis.jhu.edu/api/help
- Research Repository: https://archive.data.jhu.edu/
- Research Computing: https://www.arch.jhu.edu/
- Open Data / Data Services: https://dataservices.library.jhu.edu/
- AI Policy: https://teaching.jhu.edu/university-teaching-policies/generative-ai/guidelines/
- GitHub: https://github.com/johnshopkins, https://github.com/jhu-data-services, https://github.com/JHUAPL
- LinkedIn: https://www.linkedin.com/school/johns-hopkins-university/
- ROR: https://ror.org/00za53h95

## Notes

Re-profiled 2026-08-19 under the API Evangelist university pipeline, which settles operator attribution before saving any contract. No endpoint was fabricated. The Hub API OpenAPI was derived from the operator's own documentation at https://api.hub.jhu.edu/docs/ and was not executed, because key issuance is restricted to Johns Hopkins affiliates.

## Maintainers

- Kin Lane — kin@apievangelist.com
