# Claude Code

> Anthropic's terminal-based coding agent.

**Category:** Coding assistants · **Official site:** https://docs.anthropic.com/en/docs/claude-code

## What it is
Anthropic's terminal-based coding agent. You describe the task in plain English; it reads, edits, tests, and commits code itself.

## Best for
Autonomous coding tasks, repo-wide refactors, working from the terminal, developers who live in the shell.

## Pricing
Usage-based via Anthropic API or Pro/Max subscription; terminal and IDE integrations available.

## How to use it
1. Install and run 'claude' in your project directory.
2. Describe the outcome, not the steps: 'add rate limiting to the API endpoints.'
3. Let it run tests itself and iterate on failures.

## Prompting tips
- Start with read-only exploration: 'explore how auth works and summarize' before asking for changes.
- Keep tasks scoped — one feature per session works far better than five.

## Gotchas
- It can execute shell commands — review what it plans to run on destructive operations.
- Costs scale with task size; small focused tasks are dramatically cheaper.

---
*Pricing and features change fast — verified October 2026. Check the official site for current details.*
*Found something outdated? [Contribute a fix](../CONTRIBUTING.md).*
