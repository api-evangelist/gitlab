# GitLab (gitlab)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

GitLab Inc. is an open-core company that develops GitLab, a DevOps software platform for building, securing, and managing applications. Created by Ukrainian developer Dmytro Zaporozhets and Dutch developer Sytse Sijbrandij, GitLab became the first partly-Ukrainian unicorn in 2018. Known for promoting remote work, it is one of the largest all-remote companies globally. GitLab has approximately 30 million registered users, including 1 million active licensed users.

**APIs.json:** [https://raw.githubusercontent.com/api-search/code/main/_apis/gitlab/apis.md](https://raw.githubusercontent.com/api-search/code/main/_apis/gitlab/apis.md)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Code
- Platform
- Software Development
- Source Control

## Timestamps

- **Created:** 2023/11/10
- **Modified:** 2026-05-19

## APIs

### GitLab GraphQL API

GraphQL is a query language for APIs. You can use it to request the exact data you need, and therefore limit the number of requests you need. GraphQL data is arranged in types, so your client can use client-side GraphQL libraries to consume the API and avoid manual parsing. There are no fixed endpoints and no data model, so you can add to the API without creating breaking changes. This enables us to have a versionless API.

- **Human URL:** [https://docs.gitlab.com/ee/api/graphql/](https://docs.gitlab.com/ee/api/graphql/)
- **Base URL:** `https://gitlab.com/api/graphql`

#### Tags

- Data
- GraphQL
- Query Language

#### Properties

- [Documentation](https://docs.gitlab.com/ee/api/graphql/)
- [Deprecation](https://docs.gitlab.com/ee/api/graphql/#deprecation-and-removal-process)
- [Documentation](https://docs.gitlab.com/ee/api/graphql/#deprecation-and-removal-process)
- [Rate Limits](https://docs.gitlab.com/ee/api/graphql/#limits)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [API Reference](https://docs.gitlab.com/api/graphql/reference/)
- [Getting Started](https://docs.gitlab.com/api/graphql/getting_started/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Groups API

The GitLab Groups API allows you to create, read, update, and delete groups and subgroups. Groups are used to manage access control and organize projects within a GitLab instance, enabling teams to collaborate with shared access permissions and settings.

- **Human URL:** [https://docs.gitlab.com/api/groups/](https://docs.gitlab.com/api/groups/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Access Control
- Groups
- Organizations

#### Properties

- [OpenAPI](openapi/gitlab-api-v4-groups-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.gitlab.com/api/groups/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)

### GitLab Projects API

The GitLab Projects API provides programmatic access to GitLab projects, enabling you to create, list, update, and delete projects. It supports managing project settings, members, forks, stars, and other project-level resources across GitLab.com and self-managed instances.

- **Human URL:** [https://docs.gitlab.com/api/projects/](https://docs.gitlab.com/api/projects/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Projects
- Repositories
- Source Control

#### Properties

- [OpenAPI](openapi/gitlab-api-v4-projects-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.gitlab.com/api/projects/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)

### GitLab Admin API

The GitLab Admin API provides administrative endpoints for managing a GitLab instance. It includes operations for managing runners, CI/CD variables, Sidekiq queues, and other instance-level administrative tasks that require administrator privileges.

- **Human URL:** [https://docs.gitlab.com/api/admin/](https://docs.gitlab.com/api/admin/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Admin
- Administration
- Management

#### Properties

- [OpenAPI](openapi/gitlab-api-v4-admin-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.gitlab.com/api/admin/)

### GitLab Applications API

The GitLab Applications API allows you to manage OAuth applications registered in GitLab. You can create, list, and delete OAuth applications that enable third-party services to access GitLab resources on behalf of users using the OAuth 2.0 protocol.

- **Human URL:** [https://docs.gitlab.com/api/applications/](https://docs.gitlab.com/api/applications/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Applications
- Authentication
- OAuth

#### Properties

- [OpenAPI](openapi/gitlab-api-v4-applications-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.gitlab.com/api/applications/)

### GitLab Avatar API

The GitLab Avatar API allows you to retrieve avatar images for users and groups. It returns avatar URLs based on user email addresses, enabling applications to display profile images for GitLab users without requiring authentication.

- **Human URL:** [https://docs.gitlab.com/api/avatar/](https://docs.gitlab.com/api/avatar/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Avatars
- Profile
- Users

#### Properties

- [OpenAPI](openapi/gitlab-api-v4-avatar-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.gitlab.com/api/avatar/)

### GitLab Broadcast Messages API

The GitLab Broadcast Messages API allows administrators to create and manage broadcast messages that appear as banners across all GitLab pages. These messages are used to communicate announcements, maintenance notices, and other important information to all users of a GitLab instance.

- **Human URL:** [https://docs.gitlab.com/api/broadcast_messages/](https://docs.gitlab.com/api/broadcast_messages/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Administration
- Broadcast Messages
- Notifications

#### Properties

- [OpenAPI](openapi/gitlab-api-v4-broadcast-messages-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.gitlab.com/api/broadcast_messages/)

### GitLab Bulk Imports API

The GitLab Bulk Imports API enables migration of groups and projects between GitLab instances. It provides endpoints for initiating bulk import operations and tracking their progress, facilitating large-scale data migrations between GitLab environments.

- **Human URL:** [https://docs.gitlab.com/api/bulk_imports/](https://docs.gitlab.com/api/bulk_imports/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Bulk Imports
- Data Transfer
- Migration

#### Properties

- [OpenAPI](openapi/gitlab-api-v4-bulk-imports-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.gitlab.com/api/bulk_imports/)

### GitLab Application Settings API

The GitLab Application Settings API provides access to instance-wide configuration settings for a GitLab installation. Administrators can retrieve and modify application settings such as sign-up restrictions, default project visibility, and other instance-level preferences.

- **Human URL:** [https://docs.gitlab.com/api/settings/](https://docs.gitlab.com/api/settings/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Administration
- Application Settings
- Configuration

#### Properties

- [OpenAPI](openapi/gitlab-api-v4-application-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.gitlab.com/api/settings/)

### GitLab Metadata API

The GitLab Metadata API provides information about the GitLab instance, including the version, revision, and other metadata about the running installation. It is useful for verifying connectivity and identifying the version of a GitLab instance programmatically.

- **Human URL:** [https://docs.gitlab.com/api/metadata/](https://docs.gitlab.com/api/metadata/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Instance Information
- Metadata
- System

#### Properties

- [OpenAPI](openapi/gitlab-api-v4-metadata-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.gitlab.com/api/metadata/)

### GitLab Version API

The GitLab Version API returns version and revision information for the GitLab instance. This endpoint is useful for verifying what version of GitLab is running and for checking compatibility with specific API features before making requests.

- **Human URL:** [https://docs.gitlab.com/api/version/](https://docs.gitlab.com/api/version/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Instance Information
- System
- Version

#### Properties

- [OpenAPI](openapi/gitlab-api-v4-version-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.gitlab.com/api/version/)

### GitLab REST API

The GitLab REST API provides programmatic access to GitLab resources, enabling you to build integrations, automate repetitive tasks, and extract data for custom reports. The API supports projects, groups, issues, merge requests, CI/CD pipelines, and many other GitLab features through standard HTTP methods and JSON responses.

- **Human URL:** [https://docs.gitlab.com/api/rest/](https://docs.gitlab.com/api/rest/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- DevOps
- Integration
- REST

#### Properties

- [OpenAPI](openapi/gitlab-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://docs.gitlab.com/api/rest/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [SDK](https://docs.gitlab.com/api/rest/third_party_clients/)
- [API Reference](https://docs.gitlab.com/api/api_resources/)
- [Rate Limits](https://docs.gitlab.com/security/rate_limits/)
- [Interactive  Documentation](https://docs.gitlab.com/api/openapi/openapi_interactive/)

### GitLab OAuth 2.0 API

The GitLab OAuth 2.0 API enables third-party services to access GitLab resources on behalf of users using the OAuth 2.0 protocol. It supports authorization code with PKCE, device authorization grant, and resource owner password credentials flows, allowing secure delegation of access to GitLab resources.

- **Human URL:** [https://docs.gitlab.com/api/oauth2/](https://docs.gitlab.com/api/oauth2/)
- **Base URL:** `https://gitlab.com`

#### Tags

- Authentication
- Authorization
- OAuth

#### Properties

- [OpenAPI](openapi/gitlab-oauth2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.gitlab.com/api/oauth2/)
- [Authentication](https://docs.gitlab.com/integration/oauth_provider/)

### GitLab Webhooks

GitLab Webhooks allow you to receive real-time HTTP POST notifications when events occur in GitLab projects or groups. Webhooks can be configured to trigger on events such as push events, merge requests, issues, comments, and pipeline status changes, enabling integrations with external systems.

- **Human URL:** [https://docs.gitlab.com/user/project/integrations/webhooks.html](https://docs.gitlab.com/user/project/integrations/webhooks.html)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Events
- Integrations
- Webhooks

#### Properties

- [OpenAPI](openapi/gitlab-webhooks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/gitlab-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Documentation](https://docs.gitlab.com/user/project/integrations/webhooks.html)
- [API Reference](https://docs.gitlab.com/api/project_webhooks/)

### GitLab Issues API

The GitLab Issues API provides programmatic access to manage issues across projects and groups. It supports creating, listing, updating, and deleting issues, as well as managing issue assignments, labels, milestones, and related metadata for tracking work in GitLab.

- **Human URL:** [https://docs.gitlab.com/api/issues/](https://docs.gitlab.com/api/issues/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Bug Tracking
- Issues
- Project Management

#### Properties

- [Documentation](https://docs.gitlab.com/api/issues/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Merge Requests API

The GitLab Merge Requests API enables programmatic management of merge requests across projects and groups. It supports creating, listing, updating, approving, and merging merge requests, as well as managing reviewers, assignees, and merge request metadata for code review workflows.

- **Human URL:** [https://docs.gitlab.com/api/merge_requests/](https://docs.gitlab.com/api/merge_requests/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Code Review
- Collaboration
- Merge Requests

#### Properties

- [Documentation](https://docs.gitlab.com/api/merge_requests/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Pipelines API

The GitLab Pipelines API provides programmatic access to CI/CD pipelines in GitLab projects. It supports listing, creating, retrying, and canceling pipelines, as well as retrieving pipeline details and variables for automating continuous integration and delivery workflows.

- **Human URL:** [https://docs.gitlab.com/api/pipelines/](https://docs.gitlab.com/api/pipelines/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- CI/CD
- Continuous Integration
- Pipelines

#### Properties

- [Documentation](https://docs.gitlab.com/api/pipelines/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Jobs API

The GitLab Jobs API allows you to interact with CI/CD jobs in GitLab projects. It supports listing, retrieving, canceling, retrying, and erasing jobs, as well as downloading job artifacts and viewing job logs for build and deployment automation.

- **Human URL:** [https://docs.gitlab.com/api/jobs/](https://docs.gitlab.com/api/jobs/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Build
- CI/CD
- Jobs

#### Properties

- [Documentation](https://docs.gitlab.com/api/jobs/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Runners API

The GitLab Runners API provides endpoints for managing CI/CD runners registered to a GitLab instance. It supports listing, registering, updating, and deleting runners, as well as managing runner configurations and viewing jobs assigned to specific runners.

- **Human URL:** [https://docs.gitlab.com/api/runners/](https://docs.gitlab.com/api/runners/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- CI/CD
- Infrastructure
- Runners

#### Properties

- [Documentation](https://docs.gitlab.com/api/runners/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Users API

The GitLab Users API provides programmatic access to manage user accounts on a GitLab instance. It supports listing, creating, updating, and deleting users, managing SSH keys and GPG keys, viewing user activity, and administering user-level settings and permissions.

- **Human URL:** [https://docs.gitlab.com/api/users/](https://docs.gitlab.com/api/users/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Access Management
- Identity
- Users

#### Properties

- [Documentation](https://docs.gitlab.com/api/users/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Repositories API

The GitLab Repositories API provides access to Git repository data within GitLab projects. It supports listing repository tree structures, retrieving file contents, comparing branches and tags, downloading archives, and accessing contributor statistics.

- **Human URL:** [https://docs.gitlab.com/api/repositories/](https://docs.gitlab.com/api/repositories/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Git
- Repositories
- Source Control

#### Properties

- [Documentation](https://docs.gitlab.com/api/repositories/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Commits API

The GitLab Commits API provides programmatic access to Git commits within GitLab projects. It supports listing, creating, and retrieving commits, viewing commit diffs and comments, cherry-picking commits, and accessing commit status information for CI/CD integration.

- **Human URL:** [https://docs.gitlab.com/api/commits/](https://docs.gitlab.com/api/commits/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Commits
- Git
- Source Control

#### Properties

- [Documentation](https://docs.gitlab.com/api/commits/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Branches API

The GitLab Branches API enables programmatic management of Git branches within GitLab projects. It supports listing, creating, and deleting branches, as well as retrieving branch details including the latest commit and protection status.

- **Human URL:** [https://docs.gitlab.com/api/branches/](https://docs.gitlab.com/api/branches/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Branches
- Git
- Source Control

#### Properties

- [Documentation](https://docs.gitlab.com/api/branches/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Tags API

The GitLab Tags API provides programmatic access to manage Git tags within GitLab projects. It supports listing, creating, and deleting tags, as well as retrieving tag details for version management and release workflows.

- **Human URL:** [https://docs.gitlab.com/api/tags/](https://docs.gitlab.com/api/tags/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Git
- Source Control

#### Properties

- [Documentation](https://docs.gitlab.com/api/tags/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Releases API

The GitLab Releases API enables programmatic management of project releases. It supports creating, listing, updating, and deleting releases, as well as managing release assets and links for distributing software versions and release notes.

- **Human URL:** [https://docs.gitlab.com/api/releases/](https://docs.gitlab.com/api/releases/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Distribution
- Releases
- Versioning

#### Properties

- [Documentation](https://docs.gitlab.com/api/releases/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Environments API

The GitLab Environments API provides programmatic access to manage deployment environments within GitLab projects. It supports creating, listing, updating, stopping, and deleting environments used to track deployments across different stages such as staging and production.

- **Human URL:** [https://docs.gitlab.com/api/environments/](https://docs.gitlab.com/api/environments/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- CI/CD
- Deployments
- Environments

#### Properties

- [Documentation](https://docs.gitlab.com/api/environments/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Deployments API

The GitLab Deployments API enables programmatic access to deployment records in GitLab projects. It supports listing, creating, and updating deployments, as well as retrieving deployment details and merge requests associated with specific deployments.

- **Human URL:** [https://docs.gitlab.com/api/deployments/](https://docs.gitlab.com/api/deployments/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- CI/CD
- Deployments
- Release Management

#### Properties

- [Documentation](https://docs.gitlab.com/api/deployments/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Pipeline Schedules API

The GitLab Pipeline Schedules API provides programmatic access to manage scheduled CI/CD pipelines. It supports creating, listing, updating, and deleting pipeline schedules, as well as managing schedule variables and triggering scheduled pipeline runs.

- **Human URL:** [https://docs.gitlab.com/api/pipeline_schedules/](https://docs.gitlab.com/api/pipeline_schedules/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Automation
- CI/CD
- Pipeline Schedules

#### Properties

- [Documentation](https://docs.gitlab.com/api/pipeline_schedules/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Labels API

The GitLab Labels API provides programmatic access to manage project labels. It supports creating, listing, updating, deleting, and subscribing to labels used for categorizing issues, merge requests, and other project resources.

- **Human URL:** [https://docs.gitlab.com/api/labels/](https://docs.gitlab.com/api/labels/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Labels
- Organization
- Project Management

#### Properties

- [Documentation](https://docs.gitlab.com/api/labels/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Milestones API

The GitLab Milestones API provides programmatic access to manage project milestones. It supports creating, listing, updating, and deleting milestones, as well as retrieving issues and merge requests associated with specific milestones for sprint and release planning.

- **Human URL:** [https://docs.gitlab.com/api/milestones/](https://docs.gitlab.com/api/milestones/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Milestones
- Planning
- Project Management

#### Properties

- [Documentation](https://docs.gitlab.com/api/milestones/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Notes API

The GitLab Notes API provides programmatic access to manage comments and system notes on issues, merge requests, epics, and snippets. It supports creating, listing, updating, and deleting notes for collaboration and discussion within GitLab resources.

- **Human URL:** [https://docs.gitlab.com/api/notes/](https://docs.gitlab.com/api/notes/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Collaboration
- Comments
- Notes

#### Properties

- [Documentation](https://docs.gitlab.com/api/notes/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Snippets API

The GitLab Snippets API provides programmatic access to manage code snippets. It supports creating, listing, updating, and deleting both personal and project snippets, enabling sharing of code fragments and configuration examples across teams and projects.

- **Human URL:** [https://docs.gitlab.com/api/snippets/](https://docs.gitlab.com/api/snippets/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Code Sharing
- Collaboration
- Snippets

#### Properties

- [Documentation](https://docs.gitlab.com/api/snippets/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Packages API

The GitLab Packages API provides programmatic access to the GitLab Package Registry. It supports listing, retrieving, and deleting packages across projects and groups, with support for multiple package formats including NPM, Maven, PyPI, NuGet, Conan, Helm, and more.

- **Human URL:** [https://docs.gitlab.com/api/packages/](https://docs.gitlab.com/api/packages/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Artifacts
- Package Registry
- Packages

#### Properties

- [Documentation](https://docs.gitlab.com/api/packages/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Container Registry API

The GitLab Container Registry API provides programmatic access to manage container images stored in the GitLab Container Registry. It supports listing repositories and tags, deleting images, and managing registry visibility settings for containerized application deployments.

- **Human URL:** [https://docs.gitlab.com/api/container_registry/](https://docs.gitlab.com/api/container_registry/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Container Registry
- Containers
- Docker

#### Properties

- [Documentation](https://docs.gitlab.com/api/container_registry/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Vulnerabilities API

The GitLab Vulnerabilities API provides programmatic access to manage security vulnerabilities detected in GitLab projects. It supports retrieving, confirming, resolving, and dismissing vulnerabilities found by SAST, DAST, container scanning, and dependency scanning tools.

- **Human URL:** [https://docs.gitlab.com/api/vulnerabilities/](https://docs.gitlab.com/api/vulnerabilities/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- DevSecOps
- Security
- Vulnerabilities

#### Properties

- [Documentation](https://docs.gitlab.com/api/vulnerabilities/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Deploy Keys API

The GitLab Deploy Keys API provides programmatic access to manage deploy keys for GitLab projects. It supports listing, creating, updating, and deleting SSH deploy keys that grant read-only or read-write access to repositories for automated deployment workflows.

- **Human URL:** [https://docs.gitlab.com/api/deploy_keys/](https://docs.gitlab.com/api/deploy_keys/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Deploy Keys
- Security
- SSH

#### Properties

- [Documentation](https://docs.gitlab.com/api/deploy_keys/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Protected Branches API

The GitLab Protected Branches API provides programmatic access to manage branch protection rules. It supports listing, creating, updating, and removing protection settings that control who can push, merge, and force push to specific branches in a project.

- **Human URL:** [https://docs.gitlab.com/api/protected_branches/](https://docs.gitlab.com/api/protected_branches/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Access Control
- Protected Branches
- Source Control

#### Properties

- [Documentation](https://docs.gitlab.com/api/protected_branches/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Wikis API

The GitLab Wikis API provides programmatic access to manage project wiki pages. It supports listing, creating, updating, and deleting wiki pages, as well as uploading attachments, enabling teams to maintain project documentation programmatically.

- **Human URL:** [https://docs.gitlab.com/api/wikis/](https://docs.gitlab.com/api/wikis/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Documentation
- Knowledge Base
- Wikis

#### Properties

- [Documentation](https://docs.gitlab.com/api/wikis/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Events API

The GitLab Events API provides programmatic access to review event activity across GitLab. It supports listing all events, retrieving user contribution events, and viewing project-specific events such as pushes, comments, issue updates, and merge request actions.

- **Human URL:** [https://docs.gitlab.com/api/events/](https://docs.gitlab.com/api/events/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Activity
- Audit
- Events

#### Properties

- [Documentation](https://docs.gitlab.com/api/events/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Search API

The GitLab Search API enables programmatic search across a GitLab instance, group, or project. It supports searching for projects, issues, merge requests, milestones, code blobs, commits, notes, wiki pages, and users with scope-based filtering.

- **Human URL:** [https://docs.gitlab.com/api/search/](https://docs.gitlab.com/api/search/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Discovery
- Query
- Search

#### Properties

- [Documentation](https://docs.gitlab.com/api/search/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitLab Namespaces API

The GitLab Namespaces API provides programmatic access to manage namespaces in GitLab. It supports listing namespaces, retrieving namespace details, and verifying namespace existence, which is essential for organizing projects and groups within the GitLab hierarchy.

- **Human URL:** [https://docs.gitlab.com/api/namespaces/](https://docs.gitlab.com/api/namespaces/)
- **Base URL:** `https://gitlab.com/api/v4`

#### Tags

- Namespaces
- Organization
- Structure

#### Properties

- [Documentation](https://docs.gitlab.com/api/namespaces/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [Postman Collection](collections/gitlab-oauth2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-oauth2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/gitlab-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitlab-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/gitlab-com)
- [Website](https://about.gitlab.com/)
- [Portal](https://docs.gitlab.com/api/)
- [Documentation](https://docs.gitlab.com/)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [GitHub Organization](https://github.com/gitlabhq)
- [Blog](https://about.gitlab.com/blog/)
- [Status Page](https://status.gitlab.com/)
- [Pricing](https://about.gitlab.com/pricing/)
- [Terms of Service](https://about.gitlab.com/terms/)
- [Privacy Policy](https://about.gitlab.com/privacy/)
- [Support](https://about.gitlab.com/company/contact/)
- [I D E Support](https://docs.gitlab.com/ee/editor_extensions/)
- [Release Notes](https://about.gitlab.com/releases/categories/releases/)
- [Portal](https://developer.gitlab.com/)
- [Documentation](https://docs.gitlab.com/)
- [Getting Started](https://about.gitlab.com/get-started/)
- [Status Page](https://status.gitlab.com/)
- [Sign Up](https://gitlab.com/users/sign_up)
- [Blog](https://about.gitlab.com/blog/)
- [Support](https://about.gitlab.com/support/)
- [Changelog](https://gitlab.com/gitlab-org/gitlab/blob/master/CHANGELOG.md)
- [Authentication](https://docs.gitlab.com/api/rest/authentication/)
- [SDK](https://docs.gitlab.com/api/rest/third_party_clients/)
- [Support](https://forum.gitlab.com/)
- [Rate Limits](https://docs.gitlab.com/security/rate_limits/)
- [JSON-LD](json-ld/gitlab-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/gitlab-project-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitlab-merge-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitlab-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gitlab-pipeline-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Pricing](https://about.gitlab.com/pricing/)
- [Security](https://about.gitlab.com/security/)
- [Security](https://about.gitlab.com/security/disclosure/)
- [Documentation](https://about.gitlab.com/direction/)
- [Integrations](https://about.gitlab.com/integrations/)
- [Partners](https://about.gitlab.com/partners/technology-partners/)
- [Documentation](https://about.gitlab.com/solutions/open-source/)
- [Marketplace](https://marketplace.gitlab.com/)
- [Tools](https://docs.gitlab.com/api/openapi/openapi_interactive/)
- [GitHub Repository](https://gitlab.com/gitlab-org/gitlab)
- [Features](undefined)
- [Use Cases](undefined)
- [Solutions](undefined)
- [L L Ms Txt](https://docs.gitlab.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** http://apievangelist.com
