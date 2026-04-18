# GitLab (gitlab)
GitLab is an open-core DevOps software platform for building, securing, and managing applications. The GitLab API provides comprehensive REST v4 and GraphQL access to projects, groups, users, issues, merge requests, CI/CD pipelines, container registry, package registry, security scanning, and all GitLab resources.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/gitlab/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Code, DevOps, Platform, Software Development, Source Control

## Timestamps

- **Created:** 2023-11-10
- **Modified:** 2026-04-17

## APIs

41 APIs covering REST v4 endpoints (Groups, Projects, Issues, Merge Requests, Pipelines, Jobs, Runners, Users, Packages, Container Registry, Vulnerabilities, and more), GraphQL, OAuth2, and Webhooks.

See [apis.yml](apis.yml) for the complete API inventory.

## Common Properties

- [Portal](https://docs.gitlab.com/api/)
- [Documentation](https://docs.gitlab.com/)
- [Getting Started](https://about.gitlab.com/get-started/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Rate Limits](https://docs.gitlab.com/security/rate_limits/)
- [Status Page](https://status.gitlab.com/)
- [Pricing](https://about.gitlab.com/pricing/)
- [Terms of Service](https://about.gitlab.com/terms/)
- [Privacy Policy](https://about.gitlab.com/privacy/)
- [Blog](https://about.gitlab.com/blog/)
- [Support](https://about.gitlab.com/support/)
- [Change Log](https://gitlab.com/gitlab-org/gitlab/blob/master/CHANGELOG.md)
- [Release Notes](https://about.gitlab.com/releases/categories/releases/)
- [GitHub Organization](https://github.com/gitlabhq)
- [Sign Up](https://gitlab.com/users/sign_up)
- [SDK / Client Libraries](https://docs.gitlab.com/api/rest/third_party_clients/)
- [IDE Support](https://docs.gitlab.com/ee/editor_extensions/)
- [Marketplace](https://marketplace.gitlab.com/)
- [Interactive API Docs](https://docs.gitlab.com/api/openapi/openapi_interactive/)

## Features

| Name | Description |
|------|-------------|
| REST API v4 | Comprehensive REST API for managing projects, groups, users, issues, merge requests, pipelines, and all GitLab resources. |
| GraphQL API | Flexible query language API for requesting exactly the data you need with a versionless, non-breaking schema. |
| CI/CD Pipelines | Programmatically manage pipelines, jobs, runners, and deployment workflows. |
| Container Registry | Manage container images and repositories for Docker image lifecycle management. |
| Package Registry | Publish and manage packages across npm, Maven, PyPI, NuGet, Conan, and other formats. |
| Webhooks | Receive real-time notifications for events across projects, groups, and system-level actions. |
| OAuth 2.0 Authentication | Standards-based OAuth 2.0 and OpenID Connect authentication for third-party applications. |
| Security Scanning | Access SAST, DAST, dependency scanning, and container scanning results through APIs. |
| Merge Request Management | Full lifecycle management of merge requests including creation, review, approval, and merge. |
| Issue Tracking | Create, manage, and query issues with labels, milestones, weights, and custom fields. |
| Repository Management | Manage repository files, branches, tags, commits, and merge operations. |
| Group and Project Management | Create and configure groups, subgroups, and projects with membership and permissions. |

## Use Cases

| Name | Description |
|------|-------------|
| DevOps Automation | Automate CI/CD pipeline creation, runner management, and deployment workflows. |
| Project Management | Programmatically manage issues, milestones, boards, and merge requests. |
| Infrastructure as Code | Manage GitLab configuration, groups, projects, and settings through APIs. |
| Security and Compliance | Access vulnerability reports, security scan results, and compliance data. |
| Migration and Integration | Bulk import projects, users, and data from other platforms. |
| Custom Tooling | Build custom developer tools, dashboards, and bots for GitLab workflows. |
| Container Management | Manage Docker images, Kubernetes clusters, and container deployments. |
| Analytics and Reporting | Extract project analytics, contribution data, and productivity metrics. |

## Solutions

| Name | Description |
|------|-------------|
| GitLab Free | Core DevOps platform with unlimited repositories, CI/CD, issue tracking, and API access. |
| GitLab Premium | Advanced DevOps with merge request approvals, code owners, and priority support. |
| GitLab Ultimate | Enterprise DevOps with security scanning, compliance, and advanced API features. |
| GitLab Dedicated | Single-tenant SaaS deployment with dedicated infrastructure and enhanced security. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

13 OpenAPI specifications in [openapi/](openapi/) covering Groups, Projects, Admin, Broadcast Messages, Bulk Imports, OAuth2, Webhooks, and the main REST API.

### JSON Schema

52 standalone JSON Schema files in [json-schema/](json-schema/).

### JSON Structure

52 JSON Structure files in [json-structure/](json-structure/).

### JSON-LD

- [GitLab API Context](json-ld/gitlab-context.jsonld) — 52 types, 268 properties

### Examples

52 realistic example JSON files in [examples/](examples/).

## Vocabulary

- [GitLab Vocabulary](vocabulary/gitlab-vocabulary.yaml) — Unified taxonomy mapping 12 resources, 4 API types, 5 domains, and 6 personas

## Rules

- [GitLab Spectral Rules](rules/gitlab-spectral-rules.yml) — 24 rules enforcing GitLab API conventions including snake_case paths and properties, Title Case tags

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
