---
name: apigee-create-developer-app
description: Create a new developer app and retrieve its details.
api: openapi/apigee-developer-apps-api-openapi.yml
operations:
- createDeveloperApp
- getDeveloperApp
- listDeveloperApps
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/apigee-developer-apps-api-openapi.yml ; every operationId checked against the contract
---

# apigee-create-developer-app

Create a new developer app and retrieve its details.

## Steps

1. 1. Call `createDeveloperApp` with the required body fields `name`, `apiProducts`, and optional fields such as `callbackUrl`.
2. 2. Call `getDeveloperApp` using the `appId` returned from the create step to fetch the app's details.
3. 3. (Optional) Call `listDeveloperApps` to verify the new app appears in the developer's app list.

## Rules

- Authorization: Include an OAuth2 Bearer token in the `Authorization` header for all calls.
- Pagination: `listDeveloperApps` supports `pageSize` and `pageToken` query parameters for paging through results.
