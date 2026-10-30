---
description: Run a basic agent execution routine for the given task
argument-hint: <task description>
---

Run this task through the workspace's agent execution routine:

$ARGUMENTS

Steps:

1. **Plan** — Restate the goal in one line and break it into small, concrete steps.
2. **Execute** — Work through the steps in order. Use subagents only when a step is clearly independent and parallelisable.
3. **Evaluate** — Check the result against the goal: run tests or commands where they exist and note what passed or failed.
4. **Evolve** — Record anything learned that should change how future runs work (prompts, steps, checks) and propose the change; do not apply it to CLAUDE.md or this command without approval.
5. **Report** — Summarise what was done, the evaluation outcome, and any proposed changes.
