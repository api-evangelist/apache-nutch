# Apache Nutch

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

Apache Nutch is a highly extensible and scalable open-source web crawler software project built on Apache Hadoop data structures for batch processing. It provides a pluggable architecture supporting custom parse filters, scoring filters, index writers, and protocol implementations. Nutch integrates with Apache Solr and Elasticsearch for full-text search and exposes a REST API for managing crawl jobs, configurations, seed lists, and database queries. Governed by the Apache Software Foundation under the Apache License 2.0.

**Areas:** Web Crawler · Indexing · Search · Apache · Java · Hadoop · Open Source

## Apache Nutch on APIs.io

Everything profiled for Apache Nutch is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/apache-nutch/](https://apis.io/providers/apache-nutch/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Apache Nutch Admin API](https://apis.io/apis/apache-nutch/apache-nutch-admin-api/) — Server administration operations
- [Apache Nutch Configuration API](https://apis.io/apis/apache-nutch/apache-nutch-configuration-api/) — Manage Nutch configurations
- [Apache Nutch Database API](https://apis.io/apis/apache-nutch/apache-nutch-database-api/) — Query the CrawlDB and FetchDB
- [Apache Nutch Job API](https://apis.io/apis/apache-nutch/apache-nutch-job-api/) — Manage crawl jobs
- [Apache Nutch Reader API](https://apis.io/apis/apache-nutch/apache-nutch-reader-api/) — Read sequence files and webgraph data
- [Apache Nutch Seed API](https://apis.io/apis/apache-nutch/apache-nutch-seed-api/) — Manage seed URL lists
- [Apache Nutch Services API](https://apis.io/apis/apache-nutch/apache-nutch-services-api/) — Auxiliary service operations such as CommonCrawl data dumps

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Apache Nutch Agentic Access](https://apis.io/agentic-access/apache-nutch/apache-nutch-agentic-access/)

#### JSON Schema (16)

The data models the API reads and writes.

- [ChildNode](https://apis.io/schemas/apache-nutch/apache-nutch-child-node/)
- [DbQuery](https://apis.io/schemas/apache-nutch/apache-nutch-db-query/)
- [FetchNodeDbInfo](https://apis.io/schemas/apache-nutch/apache-nutch-fetch-node-db-info/)
- [JobConfig](https://apis.io/schemas/apache-nutch/apache-nutch-job-config/)
- [JobInfo](https://apis.io/schemas/apache-nutch/apache-nutch-job-info/)
- [JobType](https://apis.io/schemas/apache-nutch/apache-nutch-job-type/)
- [LinkSchema](https://apis.io/schemas/apache-nutch/apache-nutch-link-schema/)
- [NodeSchema](https://apis.io/schemas/apache-nutch/apache-nutch-node-schema/)
- [NutchConfig](https://apis.io/schemas/apache-nutch/apache-nutch-nutch-config/)
- [NutchServerInfo](https://apis.io/schemas/apache-nutch/apache-nutch-nutch-server-info/)
- [ReaderConfig](https://apis.io/schemas/apache-nutch/apache-nutch-reader-config/)
- [SeedList](https://apis.io/schemas/apache-nutch/apache-nutch-seed-list/)
- [SeedUrl](https://apis.io/schemas/apache-nutch/apache-nutch-seed-url/)
- [ServiceConfig](https://apis.io/schemas/apache-nutch/apache-nutch-service-config/)
- [ServiceInfo](https://apis.io/schemas/apache-nutch/apache-nutch-service-info/)
- [State](https://apis.io/schemas/apache-nutch/apache-nutch-state/)

#### JSON Structure (16)

Data models expressed in JSON Structure.

- [Apache Nutch Child Node Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-child-node-structure/)
- [Apache Nutch Db Query Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-db-query-structure/)
- [Apache Nutch Fetch Node Db Info Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-fetch-node-db-info-structure/)
- [Apache Nutch Job Config Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-job-config-structure/)
- [Apache Nutch Job Info Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-job-info-structure/)
- [Apache Nutch Job Type Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-job-type-structure/)
- [Apache Nutch Link Schema Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-link-schema-structure/)
- [Apache Nutch Node Schema Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-node-schema-structure/)
- [Apache Nutch Nutch Config Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-nutch-config-structure/)
- [Apache Nutch Nutch Server Info Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-nutch-server-info-structure/)
- [Apache Nutch Reader Config Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-reader-config-structure/)
- [Apache Nutch Seed List Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-seed-list-structure/)
- [Apache Nutch Seed Url Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-seed-url-structure/)
- [Apache Nutch Service Config Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-service-config-structure/)
- [Apache Nutch Service Info Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-service-info-structure/)
- [Apache Nutch State Structure](https://apis.io/json-structure/apache-nutch/apache-nutch-state-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Apache Nutch Context](https://apis.io/jsonld/apache-nutch/apache-nutch-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Apache Nutch Vocabulary](https://apis.io/vocabularies/apache-nutch/apache-nutch-vocabulary/)

#### Examples (16)

Example requests and responses.

- [Apache Nutch Child Node Example](https://apis.io/examples/apache-nutch/apache-nutch-child-node-example/)
- [Apache Nutch Db Query Example](https://apis.io/examples/apache-nutch/apache-nutch-db-query-example/)
- [Apache Nutch Fetch Node Db Info Example](https://apis.io/examples/apache-nutch/apache-nutch-fetch-node-db-info-example/)
- [Apache Nutch Job Config Example](https://apis.io/examples/apache-nutch/apache-nutch-job-config-example/)
- [Apache Nutch Job Info Example](https://apis.io/examples/apache-nutch/apache-nutch-job-info-example/)
- [Apache Nutch Job Type Example](https://apis.io/examples/apache-nutch/apache-nutch-job-type-example/)
- [Apache Nutch Link Schema Example](https://apis.io/examples/apache-nutch/apache-nutch-link-schema-example/)
- [Apache Nutch Node Schema Example](https://apis.io/examples/apache-nutch/apache-nutch-node-schema-example/)
- [Apache Nutch Nutch Config Example](https://apis.io/examples/apache-nutch/apache-nutch-nutch-config-example/)
- [Apache Nutch Nutch Server Info Example](https://apis.io/examples/apache-nutch/apache-nutch-nutch-server-info-example/)
- [Apache Nutch Reader Config Example](https://apis.io/examples/apache-nutch/apache-nutch-reader-config-example/)
- [Apache Nutch Seed List Example](https://apis.io/examples/apache-nutch/apache-nutch-seed-list-example/)
- [Apache Nutch Seed Url Example](https://apis.io/examples/apache-nutch/apache-nutch-seed-url-example/)
- [Apache Nutch Service Config Example](https://apis.io/examples/apache-nutch/apache-nutch-service-config-example/)
- [Apache Nutch Service Info Example](https://apis.io/examples/apache-nutch/apache-nutch-service-info-example/)
- [Apache Nutch State Example](https://apis.io/examples/apache-nutch/apache-nutch-state-example/)

#### Collections (14)

Postman and Open Collection request collections.

- [Apache Nutch REST Admin API](https://apis.io/collections/apache-nutch/open-apache-nutch-admin-api/)
- [Apache Nutch REST Admin Configuration API](https://apis.io/collections/apache-nutch/open-apache-nutch-configuration-api/)
- [Apache Nutch REST Admin Database API](https://apis.io/collections/apache-nutch/open-apache-nutch-database-api/)
- [Apache Nutch REST Admin Job API](https://apis.io/collections/apache-nutch/open-apache-nutch-job-api/)
- [Apache Nutch REST Admin Reader API](https://apis.io/collections/apache-nutch/open-apache-nutch-reader-api/)
- [Apache Nutch REST Admin Seed API](https://apis.io/collections/apache-nutch/open-apache-nutch-seed-api/)
- [Apache Nutch REST Admin Services API](https://apis.io/collections/apache-nutch/open-apache-nutch-services-api/)
- [Apache Nutch REST Admin API](https://apis.io/collections/apache-nutch/postman-apache-nutch-admin-api/)
- [Apache Nutch REST Admin Configuration API](https://apis.io/collections/apache-nutch/postman-apache-nutch-configuration-api/)
- [Apache Nutch REST Admin Database API](https://apis.io/collections/apache-nutch/postman-apache-nutch-database-api/)
- [Apache Nutch REST Admin Job API](https://apis.io/collections/apache-nutch/postman-apache-nutch-job-api/)
- [Apache Nutch REST Admin Reader API](https://apis.io/collections/apache-nutch/postman-apache-nutch-reader-api/)
- [Apache Nutch REST Admin Seed API](https://apis.io/collections/apache-nutch/postman-apache-nutch-seed-api/)
- [Apache Nutch REST Admin Services API](https://apis.io/collections/apache-nutch/postman-apache-nutch-services-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Apache Nutch — jsonschema rules](https://apis.io/rules/apache-nutch/apache-nutch-jsonschema-spectral-rules/)
- [Apache Nutch API Rules](https://apis.io/rules/apache-nutch/apache-nutch-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Apache Nutch Authentication](https://apis.io/security/apache-nutch/apache-nutch-authentication/)
- [Apache Nutch Domain Security](https://apis.io/security/apache-nutch/apache-nutch-domain-security/)
- [Apache Nutch Vulnerability Disclosure](https://apis.io/security/apache-nutch/apache-nutch-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Apache Nutch Plans Pricing](https://apis.io/plans/apache-nutch/apache-nutch-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Apache Nutch Rate Limits](https://apis.io/rate-limits/apache-nutch/apache-nutch-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Apache Nutch Finops](https://apis.io/finops/apache-nutch/apache-nutch-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://apache.org)
- [Documentation](https://nutch.apache.org/documentation/)
- [Getting started](https://cwiki.apache.org/confluence/display/NUTCH/NutchTutorial)
- [Support](https://nutch.apache.org/community/mailing-lists/)
- [Blog](https://nutch.apache.org/index.xml)
- [Terms of service](https://www.apache.org/licenses/LICENSE-2.0)
- [GitHub](https://github.com/apache)

## API Evangelist rating

**Kin Score 40.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 50.7 |
| Contract governance | 13.6 |
| Operational transparency | 36.8 |
| Developer ergonomics | 44.8 |
| Access clarity | 18.4 |

**Agent readiness 17.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
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
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 26.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/apache-nutch/](https://apis.io/providers/apache-nutch/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Apache Nutch: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/apache-nutch/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
