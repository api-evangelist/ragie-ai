# Ragie (ragie-ai)

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

Ragie is a fully-managed Retrieval-Augmented Generation (RAG) as-a-service platform. Its REST API ingests documents (file upload, raw, or from URL), processes them into searchable chunks, and serves low-latency semantic retrieval, agentic responses, entity extraction, and managed data connectors to sources like Google Drive, Notion, and Confluence.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ragie-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ragie-ai/refs/heads/main/apis.yml)

## Tags

- AI
- RAG
- Retrieval
- Vector Search
- Document Ingestion

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Ragie Documents API

Create documents by file upload, raw text, or remote URL; list, get, update, and delete documents; and read processed content, summaries, chunks, and chunk content as the document moves through Ragie's ingestion pipeline to a ready state.

- **Human URL:** [https://docs.ragie.ai/reference/createdocument](https://docs.ragie.ai/reference/createdocument)
- **Base URL:** `https://api.ragie.ai`

#### Tags

- Documents
- Ingestion
- Chunks

#### Properties

- [Documentation](https://docs.ragie.ai/docs/getting-started)
- [API Reference](https://docs.ragie.ai/reference/createdocument)
- [OpenAPI](openapi/ragie-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ragie-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ragie-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ragie Retrievals API

Semantic retrieval over indexed chunks via POST /retrievals with top_k, metadata filters, reranking, and recency bias, plus agentic /responses generation that grounds answers in retrieved context.

- **Human URL:** [https://docs.ragie.ai/reference/retrieve](https://docs.ragie.ai/reference/retrieve)
- **Base URL:** `https://api.ragie.ai`

#### Tags

- Retrievals
- Semantic Search
- Responses

#### Properties

- [Documentation](https://docs.ragie.ai/docs/retrievals-guide)
- [API Reference](https://docs.ragie.ai/reference/retrieve)
- [OpenAPI](openapi/ragie-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ragie-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ragie-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ragie Connections API

Managed data connectors that continuously sync content from sources such as Google Drive, Notion, and Confluence - create OAuth connections and authenticators, list source types, sync on demand, set page limits, and enable or disable connections.

- **Human URL:** [https://docs.ragie.ai/docs/connections](https://docs.ragie.ai/docs/connections)
- **Base URL:** `https://api.ragie.ai`

#### Tags

- Connections
- Connectors
- Data Sync

#### Properties

- [Documentation](https://docs.ragie.ai/docs/connections)
- [API Reference](https://docs.ragie.ai/reference/createconnection)
- [OpenAPI](openapi/ragie-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ragie-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ragie-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ragie Entities and Extraction API

Define extraction instructions with a JSON schema and read the structured entities Ragie extracts from documents, including per-instruction and per-document extracted entities and extraction logs.

- **Human URL:** [https://docs.ragie.ai/reference/createinstruction](https://docs.ragie.ai/reference/createinstruction)
- **Base URL:** `https://api.ragie.ai`

#### Tags

- Entities
- Extraction
- Instructions

#### Properties

- [Documentation](https://docs.ragie.ai/docs/entity-extraction)
- [API Reference](https://docs.ragie.ai/reference/createinstruction)
- [OpenAPI](openapi/ragie-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ragie-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ragie-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ragie Partitions API

Logical isolation boundaries for multi-tenant data - create, list, get, update, and delete partitions, and set per-partition page and hosted-pages limits to scope documents and retrievals per tenant.

- **Human URL:** [https://docs.ragie.ai/reference/createpartition](https://docs.ragie.ai/reference/createpartition)
- **Base URL:** `https://api.ragie.ai`

#### Tags

- Partitions
- Multi-Tenancy
- Isolation

#### Properties

- [Documentation](https://docs.ragie.ai/docs/partitions)
- [API Reference](https://docs.ragie.ai/reference/createpartition)
- [OpenAPI](openapi/ragie-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ragie-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ragie-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/ragieai)
- [LinkedIn](https://www.linkedin.com/company/ragie)
- [Website](https://www.ragie.ai)
- [Documentation](https://docs.ragie.ai)
- [Plans](plans/ragie-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/ragie-ai-rate-limits.yml)
- [Fin Ops](finops/ragie-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
