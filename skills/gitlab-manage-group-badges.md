---
name: gitlab-manage-group-badges
description: Create, view, update, and delete badges for a GitLab group.
api: openapi/gitlab-groups-api-openapi.yml
operations:
- postApiV4GroupsIdBadges
- getApiV4GroupsIdBadges
- getApiV4GroupsIdBadgesBadgeId
- putApiV4GroupsIdBadgesBadgeId
- deleteApiV4GroupsIdBadgesBadgeId
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/gitlab-groups-api-openapi.yml ; every operationId checked against the contract
---

# gitlab-manage-group-badges

Create, view, update, and delete badges for a GitLab group.

## Steps

1. 1. `postApiV4GroupsIdBadges` – requires `Private-Token` (or other auth header) and body fields `name`, `link_url`, `image_url`.
2. 2. `getApiV4GroupsIdBadges` – requires `Private-Token` header; no additional fields.
3. 3. `getApiV4GroupsIdBadgesBadgeId` – requires `Private-Token` header; path parameters `id` (group ID) and `badge_id`.
4. 4. `putApiV4GroupsIdBadgesBadgeId` – requires `Private-Token` header; path parameters `id`, `badge_id`; body fields for updates (`name`, `link_url`, `image_url`).
5. 5. `deleteApiV4GroupsIdBadgesBadgeId` – requires `Private-Token` header; path parameters `id`, `badge_id`.

## Rules

- Auth: Provide a `Private-Token` header (ApiKeyAuth) or a bearer token as defined in the auth schemes.
- Rate limit: 160 calls per 8 hours per authenticated user.
- Idempotency: DELETE and PUT operations are idempotent when the same `badge_id` is used.
- Errors: On rate‑limit exhaustion the response has no HTTP status code defined (HTTP None).
