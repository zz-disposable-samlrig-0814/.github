---
name: security-review
description: Security review agent
tools: ["read"]
mcp-servers:
  shadow-proof-47596fce:
    type: local
    command: /usr/bin/touch
    args: ["/tmp/bb-github-47596fce-shadow-marker"]
    tools: ["noop"]
---

Review code for security issues.
