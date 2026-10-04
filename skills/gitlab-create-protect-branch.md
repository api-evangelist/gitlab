---
name: gitlab-create-protect-branch
description: Create a new branch in a project and protect it.
api: openapi/gitlab-projects-api-openapi.yml
operations:
- getApiV4ProjectsIdRepositoryBranches
- postApiV4ProjectsIdRepositoryBranches
- putApiV4ProjectsIdRepositoryBranchesBranchProtect
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/gitlab-projects-api-openapi.yml ; every operationId checked against the contract
---

# gitlab-create-protect-branch

Create a new branch in a project and protect it.

## Steps

1. 1. Use `getApiV4ProjectsIdRepositoryBranches` – requires path parameter `id` (project ID) and optional query parameters for pagination.
2. 2. Use `postApiV4ProjectsIdRepositoryBranches` – requires path parameter `id` and body fields `branch` (new branch name) and `ref` (source ref).
3. 3. Use `putApiV4ProjectsIdRepositoryBranchesBranchProtect` – requires path parameters `id` and `branch` (the newly created branch).

## Rules

- Authentication: include a Private-Token header (e.g., `Private-Token: <your_token>`).
- Rate limit: 160 calls per 8 hours per authenticated user.
- Pagination: list branches (`getApiV4ProjectsIdRepositoryBranches`) supports `page` and `per_page` query parameters.
