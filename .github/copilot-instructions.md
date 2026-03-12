# Agent Ops - project instructions

## Purpose
This repo stores reusable orchestration assets for GitHub Copilot agents:
agent profiles, workflow policies, task templates, and skill playbooks.

## Structure rules
- Agent profiles (.agent.md) live in .github/agents/
- Human-readable runbooks live in /agents/
- Task templates live in /tasks/ - never edit, only copy to /local/
- Live working files live in /local/ - gitignored, never committed
- Skills live in /skills/, tools in /tools/

## File naming
- Copilot agents: [role]-agent.agent.md
- Runbooks: [role]-agent.md
- Templates: [name].template.md
- Local working files: [name].md (gitignored)

## Rules
- Never commit anything from /local/
- Never modify *.template.md files directly - they are placeholders
- Keep agent profiles focused - one responsibility per agent
- Do not duplicate instructions already in copilot-instructions.md
