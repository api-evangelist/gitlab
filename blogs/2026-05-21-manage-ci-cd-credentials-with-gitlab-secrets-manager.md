---
title: "Manage CI/CD credentials with GitLab Secrets Manager"
url: "https://about.gitlab.com/blog/secrets-manager-in-public-beta/"
date: "2026-05-21"
author: "Joe Randazzo"
feed_url: "https://about.gitlab.com/atom.xml"
---
Many credential leaks start with a developer who needs a credential, doesn’t have a good place to put it, and improvises. It lands in an over-scoped CI/CD variable, a config file, or a .env committed “just for a moment.” GitLab Secrets Manager, now in public beta with GitLab 19.0, keeps credentials in the same platform that runs your code and pipelines. Each secret is scoped to the jobs that need it and governed by the access controls you already use.
