# ai-agent-workflow

[English](./README.md)

> Repeatable AI workflows with prompts, tools, MCP integrations, and evaluation loops.

中文简介：这是一个面向 AI 工作流设计的 Codex skill，适合把一次性提示词任务沉淀成可复用的 prompts、tools、MCP 集成和评测闭环。

A Codex skill for turning one-off AI ideas into repeatable workflows with prompts, tools, MCP integrations, checks, and evaluation loops.

## What This Skill Does

This skill helps design AI workflows that can be reused, inspected, and improved over time. It is built for prompt pipelines, local LLM setups, tool-using agents, workflow decomposition, and deciding when something should become a skill, script, or MCP server.

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
- one-off content generation only
- generic code fixes unrelated to AI workflows
- UI polish or presentation deliverables
- unstructured AI hype with no operating model

## Example Prompts

- `Help me turn this local LLM document workflow into something reusable.`
- `Should this be a skill, a script, or an MCP server?`
- `Design an eval loop for this agent workflow.`
- `Map inputs, tools, outputs, and failure checks for this AI task.`

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
