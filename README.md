# Apache Nutch (apache-nutch)

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

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-nutch/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Web Crawler, Indexing, Search, Apache, Java, Hadoop, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Nutch REST API
REST API for managing Apache Nutch crawl jobs, configurations, seed URL lists, database queries (CrawlDB and FetchDB), and data readers. Supports full crawl lifecycle management including inject, generate, fetch, parse, updatedb, and index operations. Secured via HTTP Basic Authentication.

**Human URL:** [https://cwiki.apache.org/confluence/display/NUTCH/Nutch+1.X+REST+API](https://cwiki.apache.org/confluence/display/NUTCH/Nutch+1.X+REST+API)

#### Tags:

 - REST, Crawl Management, Job Management, Configuration

#### Properties

- [Documentation](https://cwiki.apache.org/confluence/display/NUTCH/Nutch+1.X+REST+API)
- [OpenAPI](openapi/apache-nutch-openapi.yaml)
- [JSONSchema - Nutch Config Schema](json-schema/apache-nutch-nutch-config-schema.json)
- [JSONSchema - Job Config Schema](json-schema/apache-nutch-job-config-schema.json)
- [JSONSchema - Job Info Schema](json-schema/apache-nutch-job-info-schema.json)
- [JSONSchema - Server Info Schema](json-schema/apache-nutch-nutch-server-info-schema.json)
- [JSONSchema - Seed List Schema](json-schema/apache-nutch-seed-list-schema.json)
- [JSONSchema - DB Query Schema](json-schema/apache-nutch-db-query-schema.json)

## Common Properties

- [GitHub Repository](https://github.com/apache/nutch)
- [GitHub Organization](https://github.com/apache)
- [Documentation](https://nutch.apache.org/documentation/)
- [Getting Started](https://cwiki.apache.org/confluence/display/NUTCH/NutchTutorial)
- [Tutorials](https://nutch.apache.org/documentation/tutorials/)
- [FAQ](https://nutch.apache.org/documentation/faqs/)
- [Release Notes](https://github.com/apache/nutch/blob/master/CHANGES.md)
- [Terms of Service](https://www.apache.org/licenses/LICENSE-2.0)
- [Support](https://nutch.apache.org/community/mailing-lists/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/nutch)
- [Spectral Rules](rules/apache-nutch-spectral-rules.yml)
- [Naftiko Capability](capabilities/apache-nutch-crawl-management.yaml)
- [Vocabulary](vocabulary/apache-nutch-vocabulary.yaml)
- [JSON-LD Context](json-ld/apache-nutch-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Scalable Batch Crawling | Leverages Apache Hadoop data structures for distributed, large-scale web crawling batch processing. |
| Pluggable Architecture | Extensible plugin system supporting custom parse filters, scoring filters, index writers, protocol plugins, and URL filters. |
| REST API for Crawl Management | Full REST API for managing crawl jobs, configurations, seed lists, CrawlDB/FetchDB queries, and sequence file readers. |
| Full-Text Search Integration | Built-in index writers for Apache Solr and Elasticsearch to enable full-text search over crawled content. |
| Apache Tika Parsing | Uses Apache Tika for parsing a wide variety of document formats during the crawl pipeline. |
| Duplicate Detection | Built-in deduplication support to identify and remove duplicate content from the crawl database and search index. |
| Configurable URL Filtering | Regex-based and custom URL filter plugins to control crawl scope and exclusions. |
| Incremental Crawling | Supports multi-round incremental crawling workflows to keep the crawl database fresh. |
| CommonCrawl Export | Service operations for exporting crawl data in CommonCrawl-compatible formats. |
| HTTP Authentication Support | Configurable HTTP authentication schemes for crawling password-protected sites. |

## Use Cases

| Name | Description |
|------|-------------|
| Enterprise Search | Build enterprise search engines over internal or external web content using Nutch as the crawler and Solr/Elasticsearch as the search backend. |
| Research Data Collection | Academic and research teams use Nutch for large-scale systematic web data collection and indexing. |
| Intranet Document Search | Crawl and index intranet sites, wikis, and document repositories for internal enterprise search. |
| Web Archive Creation | Create structured web archives compatible with CommonCrawl format for long-term data preservation. |
| SEO and Content Monitoring | Monitor web content changes, track competitor sites, and analyze web structure at scale. |
| Custom Data Extraction Pipelines | Build custom extraction pipelines using Nutch plugin architecture for targeted data acquisition tasks. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Solr | Native index writer plugin for indexing crawled content into Apache Solr for full-text search. |
| Elasticsearch | Index writer plugin for sending crawled content to Elasticsearch clusters. |
| Apache Hadoop | Core dependency providing distributed storage and processing via HDFS and MapReduce. |
| Apache Tika | Used for content detection and extraction from a wide range of document formats during parsing. |
| SolrCloud | Support for SolrCloud distributed search clusters for scalable indexing. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Nutch REST API](openapi/apache-nutch-openapi.yaml)

### JSON Schema

- [Nutch Config](json-schema/apache-nutch-nutch-config-schema.json)
- [Job Config](json-schema/apache-nutch-job-config-schema.json)
- [Job Info](json-schema/apache-nutch-job-info-schema.json)
- [DB Query](json-schema/apache-nutch-db-query-schema.json)
- [Nutch Server Info](json-schema/apache-nutch-nutch-server-info-schema.json)
- [Fetch Node DB Info](json-schema/apache-nutch-fetch-node-db-info-schema.json)
- [Child Node](json-schema/apache-nutch-child-node-schema.json)
- [Seed List](json-schema/apache-nutch-seed-list-schema.json)
- [Seed URL](json-schema/apache-nutch-seed-url-schema.json)
- [Reader Config](json-schema/apache-nutch-reader-config-schema.json)
- [Service Config](json-schema/apache-nutch-service-config-schema.json)
- [Service Info](json-schema/apache-nutch-service-info-schema.json)
- [Link Schema](json-schema/apache-nutch-link-schema-schema.json)
- [Node Schema](json-schema/apache-nutch-node-schema-schema.json)
- [Job Type](json-schema/apache-nutch-job-type-schema.json)
- [State](json-schema/apache-nutch-state-schema.json)

### JSON Structure

- [Nutch Config](json-structure/apache-nutch-nutch-config-structure.json)
- [Job Config](json-structure/apache-nutch-job-config-structure.json)
- [Job Info](json-structure/apache-nutch-job-info-structure.json)
- [DB Query](json-structure/apache-nutch-db-query-structure.json)
- [Nutch Server Info](json-structure/apache-nutch-nutch-server-info-structure.json)
- [Fetch Node DB Info](json-structure/apache-nutch-fetch-node-db-info-structure.json)
- [Child Node](json-structure/apache-nutch-child-node-structure.json)
- [Seed List](json-structure/apache-nutch-seed-list-structure.json)
- [Seed URL](json-structure/apache-nutch-seed-url-structure.json)
- [Reader Config](json-structure/apache-nutch-reader-config-structure.json)
- [Service Config](json-structure/apache-nutch-service-config-structure.json)
- [Service Info](json-structure/apache-nutch-service-info-structure.json)
- [Link Schema](json-structure/apache-nutch-link-schema-structure.json)
- [Node Schema](json-structure/apache-nutch-node-schema-structure.json)
- [Job Type](json-structure/apache-nutch-job-type-structure.json)
- [State](json-structure/apache-nutch-state-structure.json)

### JSON-LD

- [Apache Nutch Context](json-ld/apache-nutch-context.jsonld)

### Examples

- [Nutch Config](examples/apache-nutch-nutch-config-example.json)
- [Job Config](examples/apache-nutch-job-config-example.json)
- [Job Info](examples/apache-nutch-job-info-example.json)
- [DB Query](examples/apache-nutch-db-query-example.json)
- [Seed List](examples/apache-nutch-seed-list-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Nutch REST API](capabilities/shared/apache-nutch.yaml) — 14 operations for crawl management, configuration, seeds, and database access

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Nutch Crawl Management](capabilities/apache-nutch-crawl-management.yaml) | Apache Nutch REST API | 14 | Crawl Engineer, Data Engineer |

## Vocabulary

- [Apache Nutch Vocabulary](vocabulary/apache-nutch-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 9 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache Nutch Spectral Rules](rules/apache-nutch-spectral-rules.yml) — 30 rules across 9 categories enforcing Apache Nutch API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
