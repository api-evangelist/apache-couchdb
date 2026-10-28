# Apache CouchDB

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

Apache CouchDB is an open-source distributed document-oriented NoSQL database governed by the Apache Software Foundation. It uses JSON for data storage, a RESTful HTTP/JSON API for all database operations, and the Couch Replication Protocol for multi-primary synchronization across servers, mobile devices, and browsers. CouchDB supports Mango queries, MapReduce views, and offline-first application architectures.

**Areas:** Apache · Database · Document Store · JSON · NoSQL · Open Source · Replication · REST

## Apache CouchDB on APIs.io

Everything profiled for Apache CouchDB is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/apache-couchdb/](https://apis.io/providers/apache-couchdb/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Apache CouchDB Authentication API](https://apis.io/apis/apache-couchdb/apache-couchdb-authentication-api/) — Session and authentication management
- [Apache CouchDB Changes API](https://apis.io/apis/apache-couchdb/apache-couchdb-changes-api/) — Database changes feed
- [Apache CouchDB Cluster API](https://apis.io/apis/apache-couchdb/apache-couchdb-cluster-api/) — Cluster membership and configuration
- [Apache CouchDB Database API](https://apis.io/apis/apache-couchdb/apache-couchdb-database-api/) — Database management operations
- [Apache CouchDB Design Documents API](https://apis.io/apis/apache-couchdb/apache-couchdb-design-documents-api/) — Design documents, views, and indexes
- [Apache CouchDB Documents API](https://apis.io/apis/apache-couchdb/apache-couchdb-documents-api/) — Document CRUD and bulk operations
- [Apache CouchDB Mango API](https://apis.io/apis/apache-couchdb/apache-couchdb-mango-api/) — Mango declarative JSON query API
- [Apache CouchDB Replication API](https://apis.io/apis/apache-couchdb/apache-couchdb-replication-api/) — Replication management
- [Apache CouchDB Server API](https://apis.io/apis/apache-couchdb/apache-couchdb-server-api/) — Server-level information and utilities

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Apache CouchDB _changes Feed](https://apis.io/asyncapis/apache-couchdb/apache-couchdb-changes-feed-asyncapi/)

#### Event channels (4)

Individual events and webhooks the provider emits.

- [{db}/_changes#feed=continuous](https://apis.io/channels/apache-couchdb/db-changes-feed-continuous/)
- [{db}/_changes#feed=eventsource](https://apis.io/channels/apache-couchdb/db-changes-feed-eventsource/)
- [{db}/_changes#feed=longpoll](https://apis.io/channels/apache-couchdb/db-changes-feed-longpoll/)
- [{db}/_changes#feed=normal](https://apis.io/channels/apache-couchdb/db-changes-feed-normal/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Apache Couchdb Agentic Access](https://apis.io/agentic-access/apache-couchdb/apache-couchdb-agentic-access/)

#### JSON Schema (24)

The data models the API reads and writes.

- [AllDocsResponse](https://apis.io/schemas/apache-couchdb/apache-couchdb-all-docs-response/)
- [BulkDocsRequest](https://apis.io/schemas/apache-couchdb/apache-couchdb-bulk-docs-request/)
- [ChangeRow](https://apis.io/schemas/apache-couchdb/apache-couchdb-change-row/)
- [ChangesResponse](https://apis.io/schemas/apache-couchdb/apache-couchdb-changes-response/)
- [ClusterSetupResponse](https://apis.io/schemas/apache-couchdb/apache-couchdb-cluster-setup-response/)
- [CreateIndexRequest](https://apis.io/schemas/apache-couchdb/apache-couchdb-create-index-request/)
- [CreateIndexResponse](https://apis.io/schemas/apache-couchdb/apache-couchdb-create-index-response/)
- [DatabaseInfo](https://apis.io/schemas/apache-couchdb/apache-couchdb-database-info/)
- [DocRow](https://apis.io/schemas/apache-couchdb/apache-couchdb-doc-row/)
- [Document](https://apis.io/schemas/apache-couchdb/apache-couchdb-document/)
- [DocumentInput](https://apis.io/schemas/apache-couchdb/apache-couchdb-document-input/)
- [ErrorResponse](https://apis.io/schemas/apache-couchdb/apache-couchdb-error-response/)
- [FindRequest](https://apis.io/schemas/apache-couchdb/apache-couchdb-find-request/)
- [FindResponse](https://apis.io/schemas/apache-couchdb/apache-couchdb-find-response/)
- [IndexesResponse](https://apis.io/schemas/apache-couchdb/apache-couchdb-indexes-response/)
- [KeysRequest](https://apis.io/schemas/apache-couchdb/apache-couchdb-keys-request/)
- [OkResponse](https://apis.io/schemas/apache-couchdb/apache-couchdb-ok-response/)
- [ReplicationRequest](https://apis.io/schemas/apache-couchdb/apache-couchdb-replication-request/)
- [ReplicationResponse](https://apis.io/schemas/apache-couchdb/apache-couchdb-replication-response/)
- [ServerInfo](https://apis.io/schemas/apache-couchdb/apache-couchdb-server-info/)
- [SessionInfo](https://apis.io/schemas/apache-couchdb/apache-couchdb-session-info/)
- [SessionRequest](https://apis.io/schemas/apache-couchdb/apache-couchdb-session-request/)
- [ViewResponse](https://apis.io/schemas/apache-couchdb/apache-couchdb-view-response/)
- [WriteResponse](https://apis.io/schemas/apache-couchdb/apache-couchdb-write-response/)

#### JSON Structure (24)

Data models expressed in JSON Structure.

- [Apache Couchdb All Docs Response Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-all-docs-response-structure/)
- [Apache Couchdb Bulk Docs Request Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-bulk-docs-request-structure/)
- [Apache Couchdb Change Row Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-change-row-structure/)
- [Apache Couchdb Changes Response Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-changes-response-structure/)
- [Apache Couchdb Cluster Setup Response Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-cluster-setup-response-structure/)
- [Apache Couchdb Create Index Request Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-create-index-request-structure/)
- [Apache Couchdb Create Index Response Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-create-index-response-structure/)
- [Apache Couchdb Database Info Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-database-info-structure/)
- [Apache Couchdb Doc Row Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-doc-row-structure/)
- [Apache Couchdb Document Input Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-document-input-structure/)
- [Apache Couchdb Document Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-document-structure/)
- [Apache Couchdb Error Response Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-error-response-structure/)
- [Apache Couchdb Find Request Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-find-request-structure/)
- [Apache Couchdb Find Response Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-find-response-structure/)
- [Apache Couchdb Indexes Response Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-indexes-response-structure/)
- [Apache Couchdb Keys Request Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-keys-request-structure/)
- [Apache Couchdb Ok Response Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-ok-response-structure/)
- [Apache Couchdb Replication Request Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-replication-request-structure/)
- [Apache Couchdb Replication Response Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-replication-response-structure/)
- [Apache Couchdb Server Info Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-server-info-structure/)
- [Apache Couchdb Session Info Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-session-info-structure/)
- [Apache Couchdb Session Request Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-session-request-structure/)
- [Apache Couchdb View Response Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-view-response-structure/)
- [Apache Couchdb Write Response Structure](https://apis.io/json-structure/apache-couchdb/apache-couchdb-write-response-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Apache Couchdb Http Api Context](https://apis.io/jsonld/apache-couchdb/apache-couchdb-http-api-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Apache Couchdb Vocabulary](https://apis.io/vocabularies/apache-couchdb/apache-couchdb-vocabulary/)

#### Examples (24)

Example requests and responses.

- [Apache Couchdb All Docs Response Example](https://apis.io/examples/apache-couchdb/apache-couchdb-all-docs-response-example/)
- [Apache Couchdb Bulk Docs Request Example](https://apis.io/examples/apache-couchdb/apache-couchdb-bulk-docs-request-example/)
- [Apache Couchdb Change Row Example](https://apis.io/examples/apache-couchdb/apache-couchdb-change-row-example/)
- [Apache Couchdb Changes Response Example](https://apis.io/examples/apache-couchdb/apache-couchdb-changes-response-example/)
- [Apache Couchdb Cluster Setup Response Example](https://apis.io/examples/apache-couchdb/apache-couchdb-cluster-setup-response-example/)
- [Apache Couchdb Create Index Request Example](https://apis.io/examples/apache-couchdb/apache-couchdb-create-index-request-example/)
- [Apache Couchdb Create Index Response Example](https://apis.io/examples/apache-couchdb/apache-couchdb-create-index-response-example/)
- [Apache Couchdb Database Info Example](https://apis.io/examples/apache-couchdb/apache-couchdb-database-info-example/)
- [Apache Couchdb Doc Row Example](https://apis.io/examples/apache-couchdb/apache-couchdb-doc-row-example/)
- [Apache Couchdb Document Example](https://apis.io/examples/apache-couchdb/apache-couchdb-document-example/)
- [Apache Couchdb Document Input Example](https://apis.io/examples/apache-couchdb/apache-couchdb-document-input-example/)
- [Apache Couchdb Error Response Example](https://apis.io/examples/apache-couchdb/apache-couchdb-error-response-example/)
- [Apache Couchdb Find Request Example](https://apis.io/examples/apache-couchdb/apache-couchdb-find-request-example/)
- [Apache Couchdb Find Response Example](https://apis.io/examples/apache-couchdb/apache-couchdb-find-response-example/)
- [Apache Couchdb Indexes Response Example](https://apis.io/examples/apache-couchdb/apache-couchdb-indexes-response-example/)
- [Apache Couchdb Keys Request Example](https://apis.io/examples/apache-couchdb/apache-couchdb-keys-request-example/)
- [Apache Couchdb Ok Response Example](https://apis.io/examples/apache-couchdb/apache-couchdb-ok-response-example/)
- [Apache Couchdb Replication Request Example](https://apis.io/examples/apache-couchdb/apache-couchdb-replication-request-example/)
- [Apache Couchdb Replication Response Example](https://apis.io/examples/apache-couchdb/apache-couchdb-replication-response-example/)
- [Apache Couchdb Server Info Example](https://apis.io/examples/apache-couchdb/apache-couchdb-server-info-example/)
- [Apache Couchdb Session Info Example](https://apis.io/examples/apache-couchdb/apache-couchdb-session-info-example/)
- [Apache Couchdb Session Request Example](https://apis.io/examples/apache-couchdb/apache-couchdb-session-request-example/)
- [Apache Couchdb View Response Example](https://apis.io/examples/apache-couchdb/apache-couchdb-view-response-example/)
- [Apache Couchdb Write Response Example](https://apis.io/examples/apache-couchdb/apache-couchdb-write-response-example/)

#### Collections (18)

Postman and Open Collection request collections.

- [Apache CouchDB HTTP Authentication API](https://apis.io/collections/apache-couchdb/open-apache-couchdb-authentication-api/)
- [Apache CouchDB HTTP Authentication Changes API](https://apis.io/collections/apache-couchdb/open-apache-couchdb-changes-api/)
- [Apache CouchDB HTTP Authentication Cluster API](https://apis.io/collections/apache-couchdb/open-apache-couchdb-cluster-api/)
- [Apache CouchDB HTTP Authentication Database API](https://apis.io/collections/apache-couchdb/open-apache-couchdb-database-api/)
- [Apache CouchDB HTTP Authentication Design Documents API](https://apis.io/collections/apache-couchdb/open-apache-couchdb-design-documents-api/)
- [Apache CouchDB HTTP Authentication Documents API](https://apis.io/collections/apache-couchdb/open-apache-couchdb-documents-api/)
- [Apache CouchDB HTTP Authentication Mango API](https://apis.io/collections/apache-couchdb/open-apache-couchdb-mango-api/)
- [Apache CouchDB HTTP Authentication Replication API](https://apis.io/collections/apache-couchdb/open-apache-couchdb-replication-api/)
- [Apache CouchDB HTTP Authentication Server API](https://apis.io/collections/apache-couchdb/open-apache-couchdb-server-api/)
- [Apache CouchDB HTTP Authentication API](https://apis.io/collections/apache-couchdb/postman-apache-couchdb-authentication-api/)
- [Apache CouchDB HTTP Authentication Changes API](https://apis.io/collections/apache-couchdb/postman-apache-couchdb-changes-api/)
- [Apache CouchDB HTTP Authentication Cluster API](https://apis.io/collections/apache-couchdb/postman-apache-couchdb-cluster-api/)
- [Apache CouchDB HTTP Authentication Database API](https://apis.io/collections/apache-couchdb/postman-apache-couchdb-database-api/)
- [Apache CouchDB HTTP Authentication Design Documents API](https://apis.io/collections/apache-couchdb/postman-apache-couchdb-design-documents-api/)
- [Apache CouchDB HTTP Authentication Documents API](https://apis.io/collections/apache-couchdb/postman-apache-couchdb-documents-api/)
- [Apache CouchDB HTTP Authentication Mango API](https://apis.io/collections/apache-couchdb/postman-apache-couchdb-mango-api/)
- [Apache CouchDB HTTP Authentication Replication API](https://apis.io/collections/apache-couchdb/postman-apache-couchdb-replication-api/)
- [Apache CouchDB HTTP Authentication Server API](https://apis.io/collections/apache-couchdb/postman-apache-couchdb-server-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Apache CouchDB — asyncapi rules](https://apis.io/rules/apache-couchdb/apache-couchdb-asyncapi-spectral-rules/)
- [Apache CouchDB — jsonschema rules](https://apis.io/rules/apache-couchdb/apache-couchdb-jsonschema-spectral-rules/)
- [Apache CouchDB API Rules](https://apis.io/rules/apache-couchdb/apache-couchdb-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Apache Couchdb Authentication](https://apis.io/security/apache-couchdb/apache-couchdb-authentication/)
- [Apache Couchdb Domain Security](https://apis.io/security/apache-couchdb/apache-couchdb-domain-security/)
- [Apache Couchdb Vulnerability Disclosure](https://apis.io/security/apache-couchdb/apache-couchdb-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Apache Couchdb Plans Pricing](https://apis.io/plans/apache-couchdb/apache-couchdb-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Apache Couchdb Rate Limits](https://apis.io/rate-limits/apache-couchdb/apache-couchdb-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Apache Couchdb Finops](https://apis.io/finops/apache-couchdb/apache-couchdb-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Documentation](https://docs.couchdb.org/en/stable/)
- [Getting started](https://docs.couchdb.org/en/stable/intro/)
- [Support](https://couchdb.apache.org/#mailing-list)
- [Blog](https://blog.couchdb.org/)
- [GitHub](https://github.com/apache)

## API Evangelist rating

**Unrated** — no public website could be reached for this company, so there was almost nothing to measure and nothing a reader could check.

This is not a score of zero. No rating is published for this company. If that is wrong because something public exists that we missed, say so on this repository or email [info@apievangelist.com](mailto:info@apievangelist.com) and it will be re-run — free, and no justification needed.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Apache CouchDB: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/apache-couchdb/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
