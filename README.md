# Vantage (vantage)

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
