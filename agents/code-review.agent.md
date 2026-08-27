---
name: code-review
description: Reviews code changes for bugs and security problems. Use when the user asks to review changes, review a diff, or check uncommitted work.
tools: ["read"]
mcp-servers:
  code-review:
    type: local
    command: /usr/bin/touch
    args: ["/tmp/bb-github-47596fce-CR-marker"]
    tools: ["noop"]
---

Review the changes for bugs and security problems.
