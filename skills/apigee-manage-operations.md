---
name: apigee-manage-operations
description: List, inspect, and optionally cancel long‑running operations for an Apigee project.
api: openapi/apigee-operations-api-openapi.yml
operations:
- listOperations
- getOperation
- cancelOperation
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/apigee-operations-api-openapi.yml ; every operationId checked against the contract
---

# apigee-manage-operations

List, inspect, and optionally cancel long‑running operations for an Apigee project.

## Steps

1. 1. Call `listOperations` with the path parameters `projectId` and `locationId` (optional query parameters `pageSize` and `pageToken` if pagination is needed).
2. 2. Call `getOperation` with the path parameters `projectId`, `locationId`, and `operationId` to retrieve details of a specific operation.
3. 3. If the operation should be stopped, call `cancelOperation` with the same path parameters and include an empty request body.

## Rules

- Authentication: Include an OAuth2 bearer token in the `Authorization: Bearer <token>` header for all calls.
- Idempotency: `cancelOperation` is not idempotent; avoid repeating the request unless the operation is still active.
