---
name: gitlab-manage-project-webhooks
description: Create, list, retrieve, update, and delete webhooks for a GitLab project.
api: openapi/gitlab-project-webhooks-api-openapi.yml
operations:
- addProjectWebhook
- listProjectWebhooks
- getProjectWebhook
- updateProjectWebhook
- deleteProjectWebhook
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/gitlab-project-webhooks-api-openapi.yml ; every operationId checked against the contract
---

# gitlab-manage-project-webhooks

Create, list, retrieve, update, and delete webhooks for a GitLab project.

## Steps

1. 1. `addProjectWebhook` – provide the project `id` path parameter and webhook configuration fields in the request body; include the authentication header (e.g., `Private-Token` or `Authorization: Bearer <token>`).
2. 2. `listProjectWebhooks` – provide the project `id` path parameter; optional pagination query parameters (`page`, `per_page`) may be used; include the authentication header.
3. 3. `getProjectWebhook` – provide the project `id` and `hook_id` path parameters; include the authentication header.
4. 4. `updateProjectWebhook` – provide the project `id` and `hook_id` path parameters and the fields to modify in the request body; include the authentication header.
5. 5. `deleteProjectWebhook` – provide the project `id` and `hook_id` path parameters; include the authentication header.

## Rules

- Authentication: send a valid token using either the `Private-Token` header, `PRIVATE-TOKEN` header, or an `Authorization: Bearer <token>` header as defined by the supported auth schemes.
- Rate limiting: maximum 160 calls per 8 hours per authenticated user; exceeding this limit results in an HTTP response with no specific status code defined.
- Pagination: `listProjectWebhooks` supports standard GitLab pagination parameters (`page`, `per_page`).
