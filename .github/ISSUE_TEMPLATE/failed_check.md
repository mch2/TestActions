---
name: Failed GC
title: Gradle Check Failed Post Merge.
assignees: {{ env.ASSIGNEES }}
labels: test-failure
about: GC Failure autocut
---

Gradle check failure.
{{ github.event.head_commit.author.username }}
{{ github.event.triggering_actor }}
Author: {{ env.PR_USER }}
pusher: {{ env.PUSH_USER }}
PR: {{ env.WORKFLOW_URL }} 
CommitId: {{ env.PR_FROM_SHA }}
