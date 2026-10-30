# Johns Hopkins University

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

Johns Hopkins University is a private research university in Baltimore, Maryland, founded in 1876 and ranked #21 in the QS World University Rankings 2026. Its programmable footprint is small but real and, unusually for this cohort, it is genuinely its own: Johns Hopkins operates three APIs on hosts under its own registrable domains and publishes two live machine-readable identity artifacts. The Hub API (api.hub.jhu.edu) serves news, announcements, events, photo galleries and faculty experts from the Hub database across fifteen resource families, and the Self-Service Public Course Search API (sis.jhu.edu/api) returns course catalog data as JSON; both are documented in public but issue keys only to Johns Hopkins affiliates. A MuleSoft Anypoint portal at api.jh.edu fronts integration APIs and is gated entirely. Beyond those, the institution runs a Shibboleth SAML 2.0 identity provider whose metadata it publishes itself at login.jh.edu and which is registered in the InCommon Federation with Research and Scholarship and SIRTFI attributes; Project MUSE, operated by Johns Hopkins University Press, answers OAI-PMH 2.0 over 897,938 harvestable records with no authentication at all — the only fully open machine-readable surface the university has. The Johns Hopkins Research Data Repository (archive.data.jhu.edu) is Dataverse software administered by JHU Data Services, and the university's research portal at pure.johnshopkins.edu is an Elsevier Pure tenancy: both hold Johns Hopkins data, and neither contract is Johns Hopkins engineering. No central public developer portal, no changelog, no deprecation policy and no working status page exist for any of it.

**Areas:** University · Higher Education · Education · United States · Private Research University · Association of American Universities · Research · Research Data · Course Catalog · Identity Federation · OAI-PMH · Research Repository

## Johns Hopkins University on APIs.io

Everything profiled for Johns Hopkins University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/johns-hopkins-university/](https://apis.io/providers/johns-hopkins-university/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Johns Hopkins University SIS Classes API](https://apis.io/apis/johns-hopkins-university/johns-hopkins-university-classes-api/) — Course and section lookup and advanced search against the Self-Service Public Course Search API, which returns the Johns Hopkins course catalog as JSON.…
- [Johns Hopkins University SIS Codes API](https://apis.io/apis/johns-hopkins-university/johns-hopkins-university-codes-api/) — Reference code lists — schools, terms and departments — from the Self-Service Public Course Search API. The lookup vocabulary that makes the Classes API's…
- [JHU API Portal (MuleSoft Anypoint)](https://apis.io/apis/johns-hopkins-university/api-portal/) — Central API management platform built on MuleSoft Anypoint, where Johns Hopkins developers and consumers view and request access to enterprise integration…
- [Johns Hopkins Shibboleth Identity Provider](https://apis.io/apis/johns-hopkins-university/identity-federation/) — Johns Hopkins operates its own Shibboleth SAML 2.0 identity provider and publishes the entity metadata itself at login.jh.edu, scoped to johnshopkins.edu…
- [Project MUSE OAI-PMH Repository](https://apis.io/apis/johns-hopkins-university/project-muse-oai/) — Project MUSE, operated by Johns Hopkins University Press, exposes an OAI-PMH 2.0 harvesting endpoint that answers Identify, ListMetadataFormats, ListSets…
- [Johns Hopkins Research Data Repository](https://apis.io/apis/johns-hopkins-university/research-data-repository/) — Institutional research data repository at archive.data.jhu.edu, administered by Johns Hopkins University Data Services within the Sheridan Libraries,…
- [Johns Hopkins Research Portal (Elsevier Pure tenancy)](https://apis.io/apis/johns-hopkins-university/pure-research-portal/) — The Johns Hopkins research information portal at pure.johnshopkins.edu, which CNAMEs to jhu.elsevierpure.com. This is an Elsevier Pure tenancy: the…
- [Johns Hopkins University Content API](https://apis.io/apis/johns-hopkins-university/johns-hopkins-university-content-api/) — Content endpoints: announcements, articles, events, files, galleries and people.
- [Johns Hopkins University Taxonomy API](https://apis.io/apis/johns-hopkins-university/johns-hopkins-university-taxonomy-api/) — Taxonomy endpoints: the vocabularies used to categorize and attribute Hub content.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Johns Hopkins University Agentic Access](https://apis.io/agentic-access/johns-hopkins-university/johns-hopkins-university-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Course](https://apis.io/schemas/johns-hopkins-university/johns-hopkins-university-course/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Johns Hopkins University Course Structure](https://apis.io/json-structure/johns-hopkins-university/johns-hopkins-university-course-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Johns Hopkins University Context](https://apis.io/jsonld/johns-hopkins-university/johns-hopkins-university-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [JHU SIS Public Course Search Vocabulary](https://apis.io/vocabularies/johns-hopkins-university/johns-hopkins-university-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Johns Hopkins University Advanced Search Example](https://apis.io/examples/johns-hopkins-university/johns-hopkins-university-advanced-search-example/)
- [Johns Hopkins University Hub Article Example](https://apis.io/examples/johns-hopkins-university/johns-hopkins-university-hub-article-example/)
- [Johns Hopkins University Schools Example](https://apis.io/examples/johns-hopkins-university/johns-hopkins-university-schools-example/)

#### Collections (2)

Postman and Open Collection request collections.

- [Self-Service Public Course Search API (SIS) Classes API](https://apis.io/collections/johns-hopkins-university/open-johns-hopkins-university-classes-api/)
- [Self-Service Public Course Search API (SIS) Classes Codes API](https://apis.io/collections/johns-hopkins-university/open-johns-hopkins-university-codes-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Johns Hopkins University — jsonschema rules](https://apis.io/rules/johns-hopkins-university/johns-hopkins-university-jsonschema-spectral-rules/)
- [Johns Hopkins University API Rules](https://apis.io/rules/johns-hopkins-university/johns-hopkins-university-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Johns Hopkins University Authentication](https://apis.io/security/johns-hopkins-university/johns-hopkins-university-authentication/)
- [Johns Hopkins University Domain Security](https://apis.io/security/johns-hopkins-university/johns-hopkins-university-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Johns Hopkins University Plans Pricing](https://apis.io/plans/johns-hopkins-university/johns-hopkins-university-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Johns Hopkins University Rate Limits](https://apis.io/rate-limits/johns-hopkins-university/johns-hopkins-university-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Johns Hopkins University Finops](https://apis.io/finops/johns-hopkins-university/johns-hopkins-university-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.jhu.edu/)
- [Documentation](https://sis.jhu.edu/api/help)
- [API reference](https://api.hub.jhu.edu/docs/)
- [Blog](https://hub.jhu.edu/)
- [GitHub](https://github.com/johnshopkins)

## API Evangelist rating

**Kin Score 32.0** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 55.0 |
| Contract governance | 9.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 40.5 |
| Access clarity | 5.3 |

**Agent readiness 20.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/johns-hopkins-university/](https://apis.io/providers/johns-hopkins-university/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Johns Hopkins University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/johns-hopkins-university/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
