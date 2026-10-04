---
name: apigee-create-api-proxy
description: Create a new API proxy, verify its creation, list proxies, and clean up by deleting it.
api: openapi/apigee-api-proxies-api-openapi.yml
operations:
- createApiProxy
- getApiProxy
- listApiProxies
- deleteApiProxy
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/apigee-api-proxies-api-openapi.yml ; every operationId checked against the contract
---

# apigee-create-api-proxy

Create a new API proxy, verify its creation, list proxies, and clean up by deleting it.

## Steps

1. 1. Call `createApiProxy` with the required request body defining the proxy and include the OAuth2 `Authorization` header.
2. 2. Call `getApiProxy` with `organizationId` and the newly created `apiId` to retrieve the proxy details, providing the OAuth2 `Authorization` header.
3. 3. Call `listApiProxies` with `organizationId` to confirm the proxy appears in the list, using the OAuth2 `Authorization` header.
4. 4. Call `deleteApiProxy` with `organizationId` and `apiId` to remove the proxy, supplying the OAuth2 `Authorization` header.

## Rules

- Authentication: Include an OAuth2 `Authorization: Bearer <token>` header on every request.
- Idempotency: `createApiProxy` is not idempotent; repeat calls will create duplicate proxies unless the same `apiId` is used.
- Pagination: `listApiProxies` supports standard pagination parameters (`pageSize`, `pageToken`).
