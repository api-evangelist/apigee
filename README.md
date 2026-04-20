# Apigee (apigee)
Apigee is Google Cloud's native API management platform for building, managing, and securing APIs across any use case, environment, or scale. It provides API proxies, security, rate limiting, quotas, analytics, monetization, and developer portal capabilities with full lifecycle API management.

**URL:** [https://cloud.google.com/apigee](https://cloud.google.com/apigee)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Analytics, API Gateway, API Governance, API Hub, API Management, Developer Portal, Enterprise, Hybrid, Integrations, Microservices, Monetization

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-20

## APIs

### Apigee API Management
APIs for programmatically managing Apigee organizations, API proxies, products, developers, apps, environments, deployments, and analytics.

**Human URL:** [https://cloud.google.com/apigee/docs](https://cloud.google.com/apigee/docs)

#### Properties

- [Documentation](https://cloud.google.com/apigee/docs/api-platform/get-started/what-apigee)
- [OpenAPI](openapi/apigee-api-management-openapi.yml)
- [APIReference](https://cloud.google.com/apigee/docs/reference/apis/apigee/rest)

### Apigee API Hub API
API for cataloging, organizing, and governing APIs across an organization.

**Human URL:** [https://cloud.google.com/apigee/docs/apihub/what-is-api-hub](https://cloud.google.com/apigee/docs/apihub/what-is-api-hub)

#### Properties

- [Documentation](https://cloud.google.com/apigee/docs/apihub/what-is-api-hub)
- [OpenAPI](openapi/apigee-api-hub-openapi.yml)

### Apigee Integrations API
API for creating, managing, and executing integrations within Google Cloud.

**Human URL:** [https://cloud.google.com/apigee/docs/api-platform/integration/using-application-integration](https://cloud.google.com/apigee/docs/api-platform/integration/using-application-integration)

#### Properties

- [Documentation](https://cloud.google.com/apigee/docs/api-platform/integration/using-application-integration)
- [OpenAPI](openapi/apigee-integrations-openapi.yml)

### Apigee API Management API (APIM)
API for discovering and observing shadow APIs in existing Google Cloud infrastructure.

**Human URL:** [https://cloud.google.com/apigee/docs/reference/apis/apim/rest](https://cloud.google.com/apigee/docs/reference/apis/apim/rest)

#### Properties

- [Documentation](https://cloud.google.com/apigee/docs/reference/apis/apim/rest)
- [OpenAPI](openapi/apigee-apim-openapi.yml)

### Apigee Registry API
API for tracking and managing machine-readable descriptions of APIs (legacy - use API Hub).

**Human URL:** [https://cloud.google.com/apigee/docs/reference/apis/apigeeregistry/rest](https://cloud.google.com/apigee/docs/reference/apis/apigeeregistry/rest)

#### Properties

- [Documentation](https://cloud.google.com/apigee/docs/reference/apis/apigeeregistry/rest)
- [OpenAPI](openapi/apigee-registry-openapi.yml)

## Common Properties

- [Portal](https://cloud.google.com/apigee)
- [Documentation](https://cloud.google.com/apigee/docs)
- [GettingStarted](https://cloud.google.com/apigee/docs/api-platform/get-started/overview)
- [Authentication](https://cloud.google.com/apigee/docs/api-platform/security/oauth/oauth-home)
- [Blog](https://cloud.google.com/blog/products/api-management)
- [StatusPage](https://status.cloud.google.com/)
- [Support](https://cloud.google.com/apigee/support)
- [TermsOfService](https://cloud.google.com/terms)
- [PrivacyPolicy](https://cloud.google.com/terms/cloud-privacy-notice)
- [GitHubOrganization](https://github.com/apigee)
- [Pricing](https://cloud.google.com/apigee/pricing)
- [ReleaseNotes](https://cloud.google.com/apigee/docs/release-notes)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apigee API Management](openapi/apigee-api-management-openapi.yml)
- [Apigee API Hub](openapi/apigee-api-hub-openapi.yml)
- [Apigee Integrations](openapi/apigee-integrations-openapi.yml)
- [Apigee APIM](openapi/apigee-apim-openapi.yml)
- [Apigee Registry](openapi/apigee-registry-openapi.yml)

### JSON Schema

- [apigee-organization-schema.json](json-schema/apigee-organization-schema.json)
- [apigee-api-proxy-schema.json](json-schema/apigee-api-proxy-schema.json)
- [apigee-api-product-schema.json](json-schema/apigee-api-product-schema.json)
- [apigee-developer-schema.json](json-schema/apigee-developer-schema.json)
- [apigee-developer-app-schema.json](json-schema/apigee-developer-app-schema.json)
- [apigee-environment-schema.json](json-schema/apigee-environment-schema.json)
- [apigee-deployment-schema.json](json-schema/apigee-deployment-schema.json)
- [apigee-integration-schema.json](json-schema/apigee-integration-schema.json)

### JSON Structure

- [apigee-organization-structure.json](json-structure/apigee-organization-structure.json)
- [apigee-api-proxy-structure.json](json-structure/apigee-api-proxy-structure.json)
- [apigee-api-product-structure.json](json-structure/apigee-api-product-structure.json)
- [apigee-developer-structure.json](json-structure/apigee-developer-structure.json)
- [apigee-developer-app-structure.json](json-structure/apigee-developer-app-structure.json)
- [apigee-environment-structure.json](json-structure/apigee-environment-structure.json)
- [apigee-deployment-structure.json](json-structure/apigee-deployment-structure.json)
- [apigee-integration-structure.json](json-structure/apigee-integration-structure.json)

### JSON-LD

- [apigee-context.jsonld](json-ld/apigee-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [API Management](capabilities/shared/api-management.yaml) — API proxy and product management operations
- [API Hub](capabilities/shared/api-hub.yaml) — API catalog and governance operations
- [Integrations](capabilities/shared/integrations.yaml) — Integration workflow operations
- [APIM](capabilities/shared/apim.yaml) — Shadow API discovery operations
- [Registry](capabilities/shared/registry.yaml) — API specification registry operations

### Workflow Capabilities

| Workflow | APIs Combined | Persona |
|----------|--------------|---------|
| [API Lifecycle Management](capabilities/api-lifecycle-management.yaml) | API Management, API Hub | API Platform Engineer, API Product Manager |
| [API Governance and Observability](capabilities/api-governance-observability.yaml) | API Hub, APIM, Registry | API Governance Lead, Platform Architect |
| [Analytics and Traffic Observability](capabilities/analytics-traffic-observability.yaml) | API Management, APIM | Platform Architect, SRE, Governance Team |
| [API Specification Management](capabilities/api-specification-management.yaml) | API Hub, Registry | API Product Manager, Governance Team |
| [Developer Portal and App Management](capabilities/developer-portal-app-management.yaml) | API Management | Platform Operations, API Monetization Owner |

## Vocabulary

- [Apigee Vocabulary](vocabulary/apigee-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 6 actions, 2 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [apigee-spectral-rules.yml](rules/apigee-spectral-rules.yml) — 14 rules across 7 categories enforcing Apigee API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
