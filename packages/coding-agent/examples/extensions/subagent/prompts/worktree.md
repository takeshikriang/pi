---
description: Create a git worktree via the worker agent
---
Use the subagent tool to create a git worktree for: $@

1. Use the "worker" agent to symlink any gitignored env files (`.env` etc.) from the main worktree — never read or print their contents.
2. Use the "worker" agent to install dependencies as needed within the new worktree.

Relay the worker's report.
