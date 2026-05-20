---
title: "Build an automated detection testing framework with GitLab CI/CD and Duo"
url: "https://about.gitlab.com/blog/automated-detection-testing-framework/"
date: "2026-04-30T00:00:00.000Z"
author: "Evan Baltman"
feed_url: "https://about.gitlab.com/atom.xml"
---
When it comes to managing a healthy alerting system for your security operations center (SOC), tuning false positives is only half the battle. An often overlooked aspect of a healthy alerting system is making sure that critical detections which rarely fire haven’t simply broken completely without anybody noticing. At GitLab, the Signals Engineering team tests detections by simulating real malicious behavior on infrastructure we own to validate that our detections fire end-to-end — from the log source, through ingestion, into the SIEM, and all the way through our security orchestration,…
