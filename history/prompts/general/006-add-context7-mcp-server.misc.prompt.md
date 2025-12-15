---
name: add-context7-mcp-server
description: Add Context7 MCP Server via CLI command
agent: agent

---

## Prompt

```text
claude mcp add --transport stdio context7 npx @upstash/context7-mcp
```

## Response snapshot

Added stdio MCP server context7 with command: npx @upstash/context7-mcp to local config.

## Outcome

- ✅ Impact: MCP server 'context7' added to local configuration.
- 🧪 Tests: N/A
- 📁 Files: Modified 1 file: `C:\Users\HP\.claude.json`
- 🔁 Next prompts: Awaiting next user instruction.
- 🧠 Reflection: Successfully executed the `claude mcp add` command and created the PHR.

## Evaluation notes (flywheel)

- Failure modes observed: null
- Graders run and results (PASS/FAIL): null
- Prompt variant (if applicable): null
- Next experiment (smallest change to try): null
