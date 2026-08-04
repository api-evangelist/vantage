# Vantage (vantage)

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

Vantage is a cloud cost management platform designed for modern engineering teams to monitor, optimize, and control their cloud infrastructure spending across multiple providers. The platform helps companies identify immediate cost savings through features like automated purchasing of savings plans, cost recommendations, and Kubernetes rightsizing, while also preventing future cost overruns with anomaly detection, custom alerts, and budget tracking.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vantage/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vantage/refs/heads/main/apis.yml)

## Scope

- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Budgets
- Cloud Pricing
- Cost Management
- Costs
- FinOps

## Timestamps

- **Created:** 2026-01-02
- **Modified:** 2026-05-19

## APIs

### Vantage Cost Management API

The Vantage Cost Management API (v2) provides programmatic access to cloud cost data and enables automation of cost management workflows. Create and manage Cost Reports, Folders, Dashboards, Saved Filters, Teams, Budgets, Anomaly Alerts, Business Metrics, Network Flow Reports, Financial Commitment Reports, Resource Reports, Segments, Integrations, and more. Supports the Vantage Query Language (VQL) for filtering cost data across multiple cloud providers.

- **Human URL:** [https://docs.vantage.sh/api](https://docs.vantage.sh/api)
- **Base URL:** `https://api.vantage.sh/v2`

#### Tags

- Anomaly Detection
- Budgets
- Cloud Costs
- Cost Reports
- Dashboards
- FinOps

#### Properties

- [Documentation](https://vantage.readme.io/reference/general)
- [OpenAPI](openapi/vantage-cost-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vantage-cost-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vantage-cost-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://api.vantage.sh/v2/oas_v3.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://api.vantage.sh/v2/swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/cost-report.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cost.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/folder.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/dashboard.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/saved-filter.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/workspace.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/team.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/access-grant.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/budget-alert.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/anomaly-alert.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recommendation.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/segment.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/integration.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/managed-account.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cost-provider.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/business-metric.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/resource-report.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/resource.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/network-flow-report.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/financial-commitment-report.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/kubernetes-efficiency-report.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/vantage-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Vantage Cloud Pricing API

The Vantage Cloud Pricing API (v1) provides programmatic access to cloud infrastructure pricing data across multiple providers including AWS, Azure, and GCP. Query providers, services, products, and prices to retrieve up-to-date pricing information for cloud infrastructure. The API is free for all registered Vantage users.

- **Human URL:** [https://docs.vantage.sh/api](https://docs.vantage.sh/api)
- **Base URL:** `https://api.vantage.sh/v1`

#### Tags

- AWS
- Azure
- Cloud Pricing
- GCP
- Infrastructure Pricing

#### Properties

- [Documentation](https://vantage.readme.io/reference/general)
- [OpenAPI](openapi/vantage-cloud-pricing-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vantage-cloud-pricing-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vantage-cloud-pricing-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://api.vantage.sh/v1/swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/provider.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/service.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/product.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/price.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/vantage-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/vantage-data-centers)
- [Developer Portal](https://www.vantage.sh/)
- [Integrations](https://www.vantage.sh/integrations)
- [Documentation](https://docs.vantage.sh/)
- [Blog](https://www.vantage.sh/blog)
- [Pricing](https://www.vantage.sh/pricing)
- [Documentation](https://www.vantage.sh/about)
- [Partners](https://www.vantage.sh/vantage-partners)
- [Changelog](https://docs.vantage.sh/changelog)
- [Getting Started](https://docs.vantage.sh/getting_started)
- [API Reference](https://vantage.readme.io/reference/general)
- [SDK](https://github.com/vantage-sh/vantage-python)
- [SDK](https://github.com/vantage-sh/vantage-js)
- [GitHub Organization](https://github.com/vantage-sh)
- [SDK](https://github.com/vantage-sh/terraform-provider-vantage)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Rules](rules/vantage-spectral-rules.yml)
- [Vocabulary](vocabulary/vantage-vocabulary.yaml)
- [Capabilities](capabilities/shared/cost-management.yaml)
- [Capabilities](capabilities/shared/cloud-pricing.yaml)
- [Capabilities](capabilities/cloud-cost-management.yaml)
- [M C P Server](https://github.com/vantage-sh/vantage-mcp-server)
- [L L Ms Txt](https://docs.vantage.sh/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
