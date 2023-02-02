---
name: Failed GC
title: '[AUTOCUT] Failed check on push to {{ env.BRANCH }}'
labels: '>test-failure, bug'
about: GC Failure autocut
---

Gradle check failure.
{{ github.event.head_commit.author.username }}
{{ github.event.triggering_actor }}
Author: {{ env.PR_USER }}
pusher: {{ env.PUSH_USER }}
PR: {{ env.WORKFLOW_URL }} 
CommitId: {{ env.PR_FROM_SHA }}
Is the failure [a flaky test](https://github.com/opensearch-project/OpenSearch/blob/main/DEVELOPER_GUIDE.md#flaky-tests) unrelated to your change?
