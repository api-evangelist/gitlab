---
title: "Consolidate your GitLab stack with Gitaly on Kubernetes"
url: "https://about.gitlab.com/blog/gitaly-on-kubernetes-generally-available/"
date: "2026-05-07"
author: "Olivier Campeau"
feed_url: "https://about.gitlab.com/atom.xml"
---
With GitLab 18.11 came good news for teams running GitLab on Kubernetes: Gitaly on Kubernetes is now generally available. Teams hosting GitLab on Kubernetes previously faced the challenge of maintaining a hybrid setup — running most GitLab components in Kubernetes while keeping Gitaly on virtual machines. This hybrid architecture made day-to-day operations more complex for those teams. Those days are over; Gitaly on Kubernetes is now an officially supported deployment option.The road to KubernetesGitaly has some hard requirements that don't translate naturally into a Kubernetes environment.
