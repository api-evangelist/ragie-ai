# Ragie (ragie-ai)

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
