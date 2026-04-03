---
name: research-playbook-methods
description: Route multi-stage business-school research tasks through this skill stack. Use when Codex needs to diagnose which stage of the research workflow the user is in, choose the right local subskill across multiple stages, or coordinate introduction work, theory-building work, and revision or preflight work together.
---

# Research Playbook Methods

## Overview

Use this skill as the orchestration layer for the published skill stack. Prefer it for cross-stage routing and broad diagnosis. For narrow tasks, prefer the specialized local subskills.

## Core Rule

Do not bulk-load every subskill or every bundled playbook note.

Prefer these local subskills when the task is clearly scoped:

- `./../research-intro-builder/SKILL.md`
- `./../research-theory-builder/SKILL.md`
- `./../research-revision-preflight/SKILL.md`

## Default Workflow

1. Read the local workspace guidance if one exists.
2. Diagnose the user's task stage before reading more notes.
3. Choose the matching subskill or subskill combination.
4. Load only the matching subskill and its bundled references.
5. Produce the requested artifact, not just high-level advice.

## Stage Routing

### 1. Idea and topic formation

- Route to:
  - `research-intro-builder`
  - `research-theory-builder`
- Trigger examples:
  - "Is this topic worth pursuing?"
  - "Help me sharpen the research question."
  - "Turn this phenomenon into a researchable question."

### 2. Puzzle, problematization, and literature positioning

- Route to:
  - `research-intro-builder`
  - `research-theory-builder`
- Trigger examples:
  - "This gap feels too weak."
  - "How do I make this problem more compelling?"
  - "What is the real contribution of this paper?"

### 3. Introduction writing and front-end framing

- Route to:
  - `research-intro-builder`
- Trigger examples:
  - "Rewrite the introduction."
  - "How should the first paragraph open?"
  - "How should I write the what-do-we-learn paragraph?"

### 4. Theory building and hypothesis development

- Route to:
  - `research-theory-builder`
- Trigger examples:
  - "Why does this theory section feel incoherent?"
  - "How should these hypotheses be developed?"
  - "How do I integrate multiple theories?"

### 5. Design, measurement, and empirical interpretation

- Route to:
  - `research-theory-builder`
  - `research-revision-preflight`
- Trigger examples:
  - "Is this design credible?"
  - "Is this proxy drifting from the construct?"
  - "How should I explain this interaction term?"

### 6. Full paper writing, discussion, and revision

- Route to:
  - `research-intro-builder`
  - `research-revision-preflight`
- Trigger examples:
  - "How should I write the discussion?"
  - "Why does this draft feel desk-rejectable?"
  - "Help me draft the response letter."

## Operating Heuristics

- Prefer the narrowest skill that can handle the task well.
- Use the router when the task spans multiple stages or when the user has not yet diagnosed the real bottleneck.
- Separate clearly:
  - source-backed facts
  - your synthesis
  - speculative next-step ideas
- Stay calibrated to what the draft, data, and design can actually support.

## What This Skill Should Produce

- A clean decision about which subskill should handle the task
- A cross-stage diagnosis when the task spans introduction, theory, and revision issues
- A short action sequence for the next best move

## Avoid

- Loading every bundled playbook note by default
- Acting like a generic writing helper instead of a router
- Repeating "there is a gap" without explaining why the gap matters
- Overclaiming what the data or theory can support
