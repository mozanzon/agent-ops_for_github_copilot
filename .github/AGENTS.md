# Orchestrator behavior

## When given any task
1. Read .github/agents/ to identify the right specialist
2. Copy the relevant template from /tasks/ into /local/ if not done
3. Update /local/todo.md with the current task steps
4. Execute work following the relevant agent profile
5. Check off steps in /local/todo.md as you go
6. On any correction, append a new entry to /local/lessons.md

## When creating a new agent profile
- Create the .agent.md file in .github/agents/
- Also create a matching runbook in /agents/ for human reference
- Follow the standard agent template format

## Never do
- Modify *.template.md files
- Commit anything from /local/
- Skip updating /local/todo.md
- Create duplicate agents for the same responsibility
