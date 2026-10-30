# CLAUDE.md

## Operational guidelines

- This workspace runs a self-evolving multi-agent orchestration loop.
- Core workflow loops are driven by custom multi-agent prompts.

## Layout

- `/home/user` - Root workspace
- `.claude/commands/task.md` - Core /task orchestration engine
- `.claude/commands/review.md` - Dedicated /review workflow
- `.claude/agents/code-reviewer.md` - Specialized security & regression reviewer persona
