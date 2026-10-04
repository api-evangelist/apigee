---
name: apigee-create-api-product
description: Create a new API Product in an organization and verify its creation.
api: openapi/apigee-api-products-api-openapi.yml
operations:
- listApiProducts
- createApiProduct
- getApiProduct
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/apigee-api-products-api-openapi.yml ; every operationId checked against the contract
---

# apigee-create-api-product

Create a new API Product in an organization and verify its creation.

## Steps

1. 1. Call `listApiProducts` to retrieve existing products (requires `organizationId` path parameter).
2. 2. Call `createApiProduct` with the required request body fields (`name`, `displayName`, `approvalType`, etc.) and `organizationId` path parameter.
3. 3. Call `getApiProduct` using the newly created `apiProductId` and `organizationId` to confirm the product details.

## Rules

- Include an OAuth2 bearer token in the `Authorization` header for all requests.
- Requests that modify state (`createApiProduct`, `updateApiProduct`, `deleteApiProduct`) are not idempotent; avoid duplicate submissions.
