# V7 (v7-labs)

V7 is an AI training-data and document-automation company. V7 Darwin is a training-data platform for labeling images, video, and documents and orchestrating human-in-the-loop annotation workflows; V7 Go automates document-intensive knowledge work with agentic AI. The Darwin REST API at https://darwin.v7labs.com/api manages datasets, items, annotations, classes, workflow stages, and exports using ApiKey authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/v7-labs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/v7-labs/refs/heads/main/apis.yml)

## Tags

- AI
- Training Data
- Data Labeling
- Annotation
- Document AI
- Computer Vision

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### V7 Darwin Datasets API

Create and manage Darwin datasets that hold the images, video, and documents being annotated, including external-storage configuration and dataset releases.

- **Human URL:** [https://docs.v7labs.com/reference/introduction](https://docs.v7labs.com/reference/introduction)
- **Base URL:** `https://darwin.v7labs.com/api`

#### Tags

- Datasets
- Training Data
- Computer Vision

#### Properties

- [Documentation](https://docs.v7labs.com/docs/getting-started-1)
- [API Reference](https://docs.v7labs.com/reference/introduction)
- [OpenAPI](openapi/v7-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/v7-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/v7-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### V7 Darwin Items & Upload API

Register, sign, and confirm uploads of locally or externally stored files as dataset items, list and filter items, and archive, restore, move, or delete them across datasets.

- **Human URL:** [https://docs.v7labs.com/reference/introduction](https://docs.v7labs.com/reference/introduction)
- **Base URL:** `https://darwin.v7labs.com/api`

#### Tags

- Items
- Upload
- Registration

#### Properties

- [Documentation](https://docs.v7labs.com/docs/getting-started-1)
- [API Reference](https://docs.v7labs.com/reference/introduction)
- [OpenAPI](openapi/v7-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/v7-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/v7-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### V7 Darwin Annotations API

Read the annotations attached to an item and import annotations created outside of V7 in the Darwin JSON v2.0 format.

- **Human URL:** [https://docs.v7labs.com/reference/introduction](https://docs.v7labs.com/reference/introduction)
- **Base URL:** `https://darwin.v7labs.com/api`

#### Tags

- Annotations
- Labels
- Import

#### Properties

- [Documentation](https://docs.v7labs.com/docs/import-annotations-made-outside-of-v7)
- [API Reference](https://docs.v7labs.com/reference/introduction)
- [OpenAPI](openapi/v7-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/v7-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/v7-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### V7 Darwin Workflows & Stages API

Create, list, and manage multi-stage annotation workflows, link datasets, set the workflow stage of items, and assign items to annotators for human-in-the-loop review.

- **Human URL:** [https://docs.v7labs.com/reference/introduction](https://docs.v7labs.com/reference/introduction)
- **Base URL:** `https://darwin.v7labs.com/api`

#### Tags

- Workflows
- Stages
- Human in the Loop

#### Properties

- [API Reference](https://docs.v7labs.com/reference/introduction)
- [OpenAPI](openapi/v7-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/v7-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/v7-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### V7 Darwin Annotation Classes API

List and update the team's annotation classes (bounding box, polygon, keypoint, tag, and other label types) that define the labeling taxonomy used across datasets.

- **Human URL:** [https://docs.v7labs.com/reference/introduction](https://docs.v7labs.com/reference/introduction)
- **Base URL:** `https://darwin.v7labs.com/api`

#### Tags

- Classes
- Taxonomy
- Labels

#### Properties

- [API Reference](https://docs.v7labs.com/reference/introduction)
- [OpenAPI](openapi/v7-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/v7-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/v7-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### V7 Darwin Exports API

Request, list, show, and delete dataset exports (releases) that package the labeled annotations asynchronously for download as training data.

- **Human URL:** [https://docs.v7labs.com/reference/introduction](https://docs.v7labs.com/reference/introduction)
- **Base URL:** `https://darwin.v7labs.com/api`

#### Tags

- Exports
- Releases
- Datasets

#### Properties

- [API Reference](https://docs.v7labs.com/reference/introduction)
- [OpenAPI](openapi/v7-labs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/v7-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/v7-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/v7labs)
- [LinkedIn](https://www.linkedin.com/company/v7labs)
- [Website](https://www.v7labs.com)
- [Documentation](https://docs.v7labs.com)
- [Plans](plans/v7-labs-plans-pricing.yml)
- [Rate Limits](rate-limits/v7-labs-rate-limits.yml)
- [Fin Ops](finops/v7-labs-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
