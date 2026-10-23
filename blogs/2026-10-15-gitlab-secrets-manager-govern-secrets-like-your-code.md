---
title: "GitLab Secrets Manager: Govern secrets like your code"
url: "https://about.gitlab.com/blog/secrets-manager-ga/"
date: "2026-10-15"
author: "Mark Settle"
feed_url: "https://about.gitlab.com/atom.xml"
---
Credentials often start in an engineer's local dev environments, then get copied into unscoped CI/CD variables to keep pipelines running. Stored there as a raw value rather than a reference to a scoped secret, a signing key reaches every job in the pipeline — compromised or not. Standing up a standalone vault narrows that exposure but requires mirroring every change to project membership, protected branches, and production environments.
