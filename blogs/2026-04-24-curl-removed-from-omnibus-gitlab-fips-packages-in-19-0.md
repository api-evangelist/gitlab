---
title: "curl removed from Omnibus-GitLab FIPS packages in 19.0"
url: "https://about.gitlab.com/blog/curl-removed-from-omnibus-gitlab-fips-packages-in-19-0/"
date: "2026-04-24T00:00:00.000Z"
author: "Adam Chu"
feed_url: "https://about.gitlab.com/atom.xml"
---
Starting with Omnibus-GitLab 19.0 (and the subsequent patch release to existing supported versions), FIPS packages will no longer include a GitLab-built version of curl. Instead, they will use the curl package provided by the customer’s Linux distribution, in the same way that FIPS packages already use the distribution's OpenSSL. Why is this change happening?
