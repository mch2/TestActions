---
title: Gradle Check Failed Post Merge.
assignees: {{ github.event.push.sender }}, {{ github.event.push.head_commit.author.username }}
labels: test-failure
---

Gradle check failure.
PR: {{ env.WORKFLOW_URL }} 
CommitId: {{ env.PR_FROM_SHA }}
