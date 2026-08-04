# V7 (v7-labs)

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
