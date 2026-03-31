# ai-agent-workflow

🔥 A Codex skill for building repeatable AI agent workflows with prompts, tools, and MCP integrations.  
🚀 Designed for workflow decomposition, tool grounding, evaluation loops, and reusable execution specs.  
⭐ Helps teams move from one-off prompts to production-minded agent systems.

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827?style=flat-square)](./SKILL.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-22c55e?style=flat-square)](./LICENSE)
[![Public Repo](https://img.shields.io/badge/Repo-Public-2563eb?style=flat-square)](https://github.com/however-yir/codex-skill-ai-agent-workflow)
[![Last Commit](https://img.shields.io/github/last-commit/however-yir/codex-skill-ai-agent-workflow?style=flat-square)](https://github.com/however-yir/codex-skill-ai-agent-workflow/commits/main)

> Repeatable AI workflows with prompts, tools, MCP integrations, and evaluation loops.

中文简介：这是一个面向 AI 工作流设计的 Codex skill，适合把一次性提示词任务沉淀成可复用的 prompts、tools、MCP 集成和评测闭环。

A Codex skill for turning one-off AI ideas into repeatable workflows with prompts, tools, MCP integrations, checks, and evaluation loops.

Use this when the main stack direction is already mostly known. If the bigger question is still local model choice, deployment path, or LM Studio versus Ollama versus MLX, [local-ai-systems-studio](https://github.com/however-yir/codex-skill-local-ai-systems-studio) is the better first stop. If the main request is to create, rewrite, benchmark, or optimize a skill itself, [skill-creator](https://github.com/search?q=evoscientist-skill-creator&type=repositories) is the better fit.

## What This Skill Does

This skill helps design AI workflows that can be reused, inspected, and improved over time. It is built for prompt pipelines, tool-using agents, workflow decomposition, and deciding when something should become a prompt stack, script, or MCP server once the stack direction is already clear.

## Best For

- prompt pipeline design
- local LLM workflows
- MCP integration planning
- skill vs script vs tool decisions
- evaluation loop design
- reusable AI task packaging

## Inputs

Typical inputs:
- the repeatable task to solve
- any current prompt, script, or workflow draft
- available tools or MCP servers
- model constraints
- quality expectations and failure modes

## Outputs

Typical outputs:
- workflow specification
- prompt or prompt-stack design
- tool integration plan
- eval loop or rubric
- minimal implementation path

## Non-goals

This skill is not aimed at:
- creating or benchmarking a skill artifact itself
- optimizing skill triggering or skill packaging
- local model-stack choice or hardware-first deployment decisions
- one-off content generation only
- generic code fixes unrelated to AI workflows
- UI polish or presentation deliverables
- unstructured AI hype with no operating model

## Example Prompts

- `Help me turn this local LLM document workflow into something reusable.`
- `Should this be a skill, a script, or an MCP server?`
- `Design an eval loop for this agent workflow.`
- `Map inputs, tools, outputs, and failure checks for this AI task.`

## Routing Notes

- Use this skill after the stack direction is already mostly known.
- If the main task becomes "create a skill", "improve this skill", or "benchmark this skill", route to `skill-creator`.
- If the main task is "LM Studio vs Ollama vs MLX" or other local stack tradeoffs, route to `local-ai-systems-studio`.

## Repository Structure

```text
.
├── .gitignore
├── LICENSE
├── README.md
├── SKILL.md
├── assets/
│   └── .gitkeep
├── examples/
│   └── showcase.md
├── references/
│   └── checklist.md
└── scripts/
    └── .gitkeep
```

## Showcase Examples

See [examples/showcase.md](./examples/showcase.md) for three stronger, public-facing examples that highlight workflow design, reuse, and evaluation.

## Included Files

- [SKILL.md](./SKILL.md): trigger logic, workflow, examples, and pairing guidance
- [examples/showcase.md](./examples/showcase.md): display-ready examples for public presentation
- [references/checklist.md](./references/checklist.md): compact workflow design checklist
- [LICENSE](./LICENSE): MIT license for standalone publication

## Pair Well With

- `mcp-server-builder`
- `skill-creator`
- `skill-reviewer`
- `skills-search`
- `prompt-optimizer`
- `deep-research`

## License

Released under the MIT License. See [LICENSE](./LICENSE).

## Notes

This skill is built to reduce ambiguity. The goal is not to make AI work sound impressive, but to make it repeatable and testable.
