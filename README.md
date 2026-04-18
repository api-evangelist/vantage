# Vantage (vantage)
Vantage is a cloud cost management platform designed for modern engineering teams to monitor, optimize, and control their cloud infrastructure spending across multiple providers. The platform helps companies identify immediate cost savings through features like automated purchasing of savings plans, cost recommendations, and Kubernetes rightsizing, while also preventing future cost overruns with anomaly detection, custom alerts, and budget tracking.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/vantage/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract 
- **Position:** Consumer 
- **Access:** 3rd-Party 

## Tags:

 - Budgets, Cloud Pricing, Cost Management, Costs, FinOps

## Timestamps

- **Created:** 2026-01-02 
- **Modified:** 2026-04-18 

## APIs

### Vantage Cost Management API
The Vantage Cost Management API (v2) provides programmatic access to cloud cost data and enables automation of cost management workflows. Create and manage Cost Reports, Folders, Dashboards, Saved Filters, Teams, Budgets, Anomaly Alerts, Business Metrics, Network Flow Reports, Financial Commitment Reports, Resource Reports, Segments, Integrations, and more. Supports the Vantage Query Language (VQL) for filtering cost data across multiple cloud providers.

**Human URL:** [https://docs.vantage.sh/api](https://docs.vantage.sh/api)

**Base URL:** https://api.vantage.sh/v2

#### Tags:

 - Anomaly Detection, Budgets, Cloud Costs, Cost Reports, Dashboards, FinOps

#### Properties

- [Documentation](https://vantage.readme.io/reference/general)
- [OpenAPI](openapi/vantage-cost-management-api-openapi.yml)
- [OpenAPI](https://api.vantage.sh/v2/oas_v3.json)
- [OpenAPI](https://api.vantage.sh/v2/swagger.json)
- [JSONSchema](json-schema/cost-report.json)
- [JSONSchema](json-schema/cost.json)
- [JSONSchema](json-schema/folder.json)
- [JSONSchema](json-schema/dashboard.json)
- [JSONSchema](json-schema/saved-filter.json)
- [JSONSchema](json-schema/workspace.json)
- [JSONSchema](json-schema/team.json)
- [JSONSchema](json-schema/access-grant.json)
- [JSONSchema](json-schema/budget-alert.json)
- [JSONSchema](json-schema/anomaly-alert.json)
- [JSONSchema](json-schema/recommendation.json)
- [JSONSchema](json-schema/segment.json)
- [JSONSchema](json-schema/integration.json)
- [JSONSchema](json-schema/managed-account.json)
- [JSONSchema](json-schema/cost-provider.json)
- [JSONSchema](json-schema/business-metric.json)
- [JSONSchema](json-schema/resource-report.json)
- [JSONSchema](json-schema/resource.json)
- [JSONSchema](json-schema/network-flow-report.json)
- [JSONSchema](json-schema/financial-commitment-report.json)
- [JSONSchema](json-schema/kubernetes-efficiency-report.json)
- [JSONLD](json-ld/vantage-context.jsonld)

### Vantage Cloud Pricing API
The Vantage Cloud Pricing API (v1) provides programmatic access to cloud infrastructure pricing data across multiple providers including AWS, Azure, and GCP. Query providers, services, products, and prices to retrieve up-to-date pricing information for cloud infrastructure. The API is free for all registered Vantage users.

**Human URL:** [https://docs.vantage.sh/api](https://docs.vantage.sh/api)

**Base URL:** https://api.vantage.sh/v1

#### Tags:

 - AWS, Azure, Cloud Pricing, GCP, Infrastructure Pricing

#### Properties

- [Documentation](https://vantage.readme.io/reference/general)
- [OpenAPI](openapi/vantage-cloud-pricing-api-openapi.yml)
- [OpenAPI](https://api.vantage.sh/v1/swagger.json)
- [JSONSchema](json-schema/provider.json)
- [JSONSchema](json-schema/service.json)
- [JSONSchema](json-schema/product.json)
- [JSONSchema](json-schema/price.json)
- [JSONLD](json-ld/vantage-context.jsonld)

## Common Properties

- [DeveloperPortal](https://www.vantage.sh/)
- [Integrations](https://www.vantage.sh/integrations)
- [Documentation](https://docs.vantage.sh/)
- [Blog](https://www.vantage.sh/blog)
- [Pricing](https://www.vantage.sh/pricing)
- [Documentation](https://www.vantage.sh/about)
- [Partners](https://www.vantage.sh/vantage-partners)
- [ChangeLog](https://docs.vantage.sh/changelog)
- [GettingStarted](https://docs.vantage.sh/getting_started)
- [APIReference](https://vantage.readme.io/reference/general)
- [SDK](https://github.com/vantage-sh/vantage-python)
- [SDK](https://github.com/vantage-sh/vantage-js)
- [GitHubOrganization](https://github.com/vantage-sh)
- [SDK](https://github.com/vantage-sh/terraform-provider-vantage)

## Capabilities

| Capability | Type | APIs | Tools |
|---|---|---|---|
| [Cloud Cost Management](capabilities/cloud-cost-management.yaml) | Workflow | 2 | 28 |

### Shared Definitions

| Definition | API |
|---|---|
| [cost-management](capabilities/shared/cost-management.yaml) | Vantage Cost Management API |
| [cloud-pricing](capabilities/shared/cloud-pricing.yaml) | Vantage Cloud Pricing API |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
