---
name: Failed GC
title: Gradle Check Failed Post Merge.
assignees: 
  - {{ github.event.push.sender }}
labels: test-failure
about: GC Failure autocut
---

Gradle check failure.
Author: {{ github.event.push.head_commit.author.username }}
Pusher: {{ github.event.push.sender }}
pusher: {{ github.event.push.pusher.username }}
PR: {{ env.WORKFLOW_URL }} 
CommitId: {{ env.PR_FROM_SHA }}
