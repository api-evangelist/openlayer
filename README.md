# Openlayer (openlayer)

Openlayer is an AI evaluation, testing, and observability platform for machine learning and LLM applications. Its REST API lets teams create projects, commit model versions and datasets, run tests, stream production inference data into monitoring pipelines, and retrieve test results - with official SDKs generated from a Stainless OpenAPI definition.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/openlayer/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/openlayer/refs/heads/main/apis.yml)

## Tags

- AI
- Evaluation
- Testing
- Observability
- LLM
- MLOps

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Openlayer Projects API

Create, list, and delete projects, and manage the tests defined within a project. Projects are the top-level container for models, datasets, commits, and inference pipelines.

- **Human URL:** [https://www.openlayer.com/docs/api-reference/rest/overview](https://www.openlayer.com/docs/api-reference/rest/overview)
- **Base URL:** `https://api.openlayer.com/v1`

#### Tags

- Projects
- Workspaces
- Tests

#### Properties

- [Documentation](https://www.openlayer.com/docs)
- [API Reference](https://www.openlayer.com/docs/api-reference/rest/overview)
- [OpenAPI](openapi/openlayer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openlayer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openlayer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Openlayer Inference Pipelines API

Create, retrieve, update, and delete inference pipelines for monitoring production models, plus manage pipeline rows, sessions, and users used in production observability.

- **Human URL:** [https://www.openlayer.com/docs/api-reference/rest/overview](https://www.openlayer.com/docs/api-reference/rest/overview)
- **Base URL:** `https://api.openlayer.com/v1`

#### Tags

- Inference Pipelines
- Monitoring
- Observability

#### Properties

- [Documentation](https://www.openlayer.com/docs/monitoring)
- [API Reference](https://www.openlayer.com/docs/api-reference/rest/overview)
- [OpenAPI](openapi/openlayer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openlayer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openlayer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Openlayer Data Stream API

Publish production inference data (rows) to an inference pipeline via the data-stream endpoint, mapping input variables, outputs, token counts, costs, timestamps, and ground truth for continuous monitoring.

- **Human URL:** [https://www.openlayer.com/docs/monitoring/publishing-data](https://www.openlayer.com/docs/monitoring/publishing-data)
- **Base URL:** `https://api.openlayer.com/v1`

#### Tags

- Data Stream
- Production Data
- Monitoring

#### Properties

- [Documentation](https://www.openlayer.com/docs/monitoring/publishing-data)
- [API Reference](https://www.openlayer.com/docs/api-reference/rest/overview)
- [OpenAPI](openapi/openlayer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openlayer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openlayer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Openlayer Commits and Test Results API

Create and list project commits (versions), retrieve a single commit, evaluate tests, and fetch commit and inference-pipeline test results to gate deployments on evaluation outcomes.

- **Human URL:** [https://www.openlayer.com/docs/api-reference/rest/overview](https://www.openlayer.com/docs/api-reference/rest/overview)
- **Base URL:** `https://api.openlayer.com/v1`

#### Tags

- Commits
- Versions
- Test Results

#### Properties

- [Documentation](https://www.openlayer.com/docs)
- [API Reference](https://www.openlayer.com/docs/api-reference/rest/overview)
- [OpenAPI](openapi/openlayer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openlayer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openlayer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/openlayer-ai)
- [LinkedIn](https://www.linkedin.com/company/openlayer)
- [Website](https://www.openlayer.com)
- [Documentation](https://www.openlayer.com/docs)
- [Plans](plans/openlayer-plans-pricing.yml)
- [Rate Limits](rate-limits/openlayer-rate-limits.yml)
- [Fin Ops](finops/openlayer-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
