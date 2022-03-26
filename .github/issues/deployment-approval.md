---
title: Deployment Approval for {{ env.VERSION }}
---

Deployment Approval requested from {{ payload.sender.login }}.

Comment "Approved" to kick the deployment off.

=== DON'T CHANGE BELOW THIS LINE

```json target_payload
{
    "runNumber":  {{ env.RUN_NUMBER }},
    "environment": "{{ env.ENVIRONMENT }}",
    "projects": "{{ env.PROJECTS }}",
    "version": "{{ env.VERSION }}"
}
```
