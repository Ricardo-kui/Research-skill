# Research Playbook Skills

Three focused Codex skills for business-school research and journal-facing academic writing.

This repository packages a narrow skill stack for high-value research tasks:

- build or rewrite introductions
- build theory logic and hypothesis chains
- run preflight checks and revision support

## Skills

| Skill | What it does | Best used for |
|---|---|---|
| `research-intro-builder` | Rewrites and sharpens scholarly introductions | opening hooks, first paragraphs, full introduction rewrites, contribution previews |
| `research-theory-builder` | Builds theory logic, mechanisms, and hypotheses | theory sections, mechanism chains, alternative logic, hypothesis development |
| `research-revision-preflight` | Runs late-stage diagnostics and revision support | desk-reject checks, discussion rewrites, reviewer response drafts, revision plans |

## Repository Layout

Each skill folder includes:

- `SKILL.md`
- `agents/openai.yaml`
- `references/standard-input-template.md`

Repository tree:

```text
research-playbook-skills/
  research-intro-builder/
    SKILL.md
    agents/openai.yaml
    references/standard-input-template.md
  research-theory-builder/
    SKILL.md
    agents/openai.yaml
    references/standard-input-template.md
  research-revision-preflight/
    SKILL.md
    agents/openai.yaml
    references/standard-input-template.md
```

## Intended Audience

These skills were designed for:

- strategy and organization researchers
- management and international business scholars
- doctoral students writing journal-facing papers
- AI-assisted research workflows inside local knowledge vaults

## Installation

Copy one or more skill folders into either:

- a global Codex skills directory, or
- a workspace-local `.agents/skills/` directory

Example workspace installation:

```text
your-workspace/
  .agents/
    skills/
      research-intro-builder/
      research-theory-builder/
      research-revision-preflight/
```

## Quick Start

Explicit invocation examples:

```text
Use $research-intro-builder to rewrite the introduction for this paper.
Use $research-theory-builder to tighten the mechanism and hypothesis logic.
Use $research-revision-preflight to run a desk-reject preflight on this draft.
```

## Input Style

Each skill includes a short standard input template in `references/standard-input-template.md`.

The templates are there to stabilize usage when requests are underspecified. They help normalize:

- current draft stage
- target journal or audience
- current text under revision
- main claim
- design or empirical context
- what the user wants right now

## Design Principles

These skills are intentionally narrow.

- They prefer producing concrete research output over generic advice.
- They are optimized for business-school research rather than generic academic writing.
- They separate introduction work, theory work, and revision work so each skill stays small and predictable.

## Notes

- The skills were extracted from a larger local research vault and then packaged as standalone units.
- They are most useful when the user already has a topic, draft, or active research problem.
- They are designed to work well with Chinese discussion and English journal-facing output.
