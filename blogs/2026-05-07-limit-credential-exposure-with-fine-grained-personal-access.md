---
title: "Limit credential exposure with fine-grained personal access tokens"
url: "https://about.gitlab.com/blog/fine-grained-pats/"
date: "2026-05-07"
author: "Nelly Vahab"
feed_url: "https://about.gitlab.com/atom.xml"
---
Personal access tokens (PATs) authenticate most of the automation that runs in GitLab. When a token is issued with a broad scope like api or read_api, it extends permissions across many projects and groups. Fine-grained permissions for PATs, now in beta, let you scope a token to exactly the privileges the job requires — read access to one project's code, say, instead of read access across every project the user can reach.
