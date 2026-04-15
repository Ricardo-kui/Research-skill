---
name: write-social-science-introduction
description: "Draft, revise, and audit introduction prose for social-science papers, especially English management journals. Use when Claude needs stage-specific introduction writing or rewriting, hook/gap/contribution/roadmap drafting, paragraph-logic diagnosis, AI-sounding filler cleanup, full-introduction QC, or exemplar paragraph analysis and transfer. Supports management-journal and generic social-science modes. NOT for theory sections, hypothesis drafting, methods sections, results sections, or discussion/conclusion sections."
---

# Write Social Science Introduction

## Overview

Use this skill as the prose layer once the paper's audience, conversation, and contribution are roughly set.

Default funnel:

1. background hook
2. literature turn
3. contribution focus
4. structure roadmap
5. funnel QC

Default to concrete facts, institutional change, or theoretical tension. Do not open with generic time markers such as `近年来`, `随着科技的发展`, `现如今`, `在当今社会`, or `自古以来`.

Strongest default: English management-journal introductions for `ASQ`, `AMJ`, `SMJ`, `Organization Science`, and `Journal of Operations Management`.

- `ASQ` / `Organization Science` -> `theory-tension mode`
- `AMJ` / `SMJ` / `JOM` -> `empirical-contribution mode`

If the user provides an exemplar paragraph or asks about authorial logic, switch to `paragraph-analysis mode` before drafting. If the outlet is outside management, strategy, organization, or operations, keep the funnel but switch to `generic social-science mode`.

## Inputs

Collect the minimum workable set from these buckets:

- `question and audience`: topic, research question, target discipline or journal, manuscript language
- `conversation and mechanism`: literature notes, intended conversation, theory, mechanism, gap
- `evidence and design`: method, data, variables, identification, main findings
- `draft materials`: outline, existing draft, exemplar paragraph or named author

If information is missing, make the minimum reasonable assumptions and label them. Do not invent facts, dates, policies, citations, or findings.

## Router

Resolve the route in this order: `outlet -> task -> scope`.

### Outlet

- `management-journal mode`: management, strategy, organization, and operations journals
- `theory-tension mode`: `ASQ` and `Organization Science`
- `empirical-contribution mode`: `AMJ`, `SMJ`, and `JOM`
- `generic social-science mode`: non-management outlets or unclear management signal

### Task

- `drafting mode`: new prose or targeted rewrite
- `paragraph-analysis mode`: exemplar or sentence-function analysis
- `QC mode`: diagnosis of logic, filler, and flow before rewriting

### Scope

- `fresh full introduction`
- `opening paragraph only`
- `gap paragraph only`
- `purpose or contribution paragraph only`
- `roadmap paragraph only`
- `full-draft QC`

### Default Routing

- `ASQ` or `Organization Science` -> `management-journal mode` + `theory-tension mode`
- `AMJ`, `SMJ`, or `JOM` -> `management-journal mode` + `empirical-contribution mode`
- exemplar present -> `paragraph-analysis mode`
- diagnosis or QC request -> `QC mode`
- otherwise -> `drafting mode` with the closest defensible outlet assumption

## Core Rules

- Preserve the funnel order: context -> current knowledge -> precise blind spot -> paper move -> navigation.
- Build substantive paragraphs as mini-pyramids: topic sentence -> optional elaboration -> support -> analysis -> transition.
- Put the paragraph's claim early. Do not open paragraphs with topic-announcing filler.
- Make the paper's move visible before the roadmap.
- Prefer thematic synthesis over author-by-author listing unless the user explicitly asks for a literature map.
- Prefer a puzzle, paradox, controversy, or unresolved relationship over generic `gap filling` language.
- In Pollock-style openings, use `hook -> opening paraphrase -> focal question -> stakes`, not atmosphere plus delayed relevance.
- In Pollock-like literature turns, use `current implication -> inadequacy or incompleteness -> why the omission matters`.
- Make the value of the blind spot explicit. Do not state the omission without saying what theoretical inference, practical evaluation, or causal interpretation remains unstable because of it.
- Keep claims aligned with the available evidence and design strength.
- Make support answer the reader's first key question triggered by the claim.
- Default to `support -> interpretation -> bridge`, not `support -> stop`.
- Treat named authors as overlays, not default templates.
- If the user provides only one exemplar, label any style inference as tentative.
- If the user discusses the project in Chinese but the manuscript is for an English journal, keep the diagnosis in Chinese and draft manuscript-facing prose in the manuscript language unless the user asks otherwise.

Mode priorities:

- `management-journal mode`: make the conversation, exact blind spot, paper move, and reason to care legible by the end of the first three paragraphs.
- `theory-tension mode`: prioritize conceptual novelty and assumption revision over design novelty.
- `empirical-contribution mode`: reveal the headline answer and why the evidence should move the reader early and in bounded terms.
- `generic social-science mode`: keep the question, gap, and answer clear without importing management-journal mannerisms the user did not ask for.

## Outputs

- `stage 1`: return two or three hook options, usually `事实/数据驱动型`, `理论悖论型`, and `学术对话/共识型`
- `stages 2-4`: return one compact paragraph each unless the user asks for variants
- `stage 5`: return diagnosis, not a silent full rewrite
- `paragraph-analysis mode`: return function maps, support-sentence roles, sequencing diagnosis, transferable rules, evidence boundary, and an imitation rewrite only if the user asks

## Reference Loading

Use progressive loading rather than preloading the whole folder.

- Always load [paragraph-pyramid-structure.md](references/paragraph-pyramid-structure.md) for substantive drafting, revision, or QC.
- Load exactly one outlet overlay:
  - [management-journal-mode.md](references/management-journal-mode.md)
  - [generic-social-science-mode.md](references/generic-social-science-mode.md)
- Add one management submode only when needed:
  - [management-theory-tension-mode.md](references/management-theory-tension-mode.md)
  - [management-empirical-contribution-mode.md](references/management-empirical-contribution-mode.md)
- Load only the current stage file:
  - [stage-1-background-hook.md](references/stage-1-background-hook.md)
  - [stage-2-literature-turn.md](references/stage-2-literature-turn.md)
  - [stage-3-contribution-focus.md](references/stage-3-contribution-focus.md)
  - [stage-4-structure-roadmap.md](references/stage-4-structure-roadmap.md)
  - [stage-5-funnel-qc.md](references/stage-5-funnel-qc.md)
- Load [paragraph-analysis-mode.md](references/paragraph-analysis-mode.md) only for exemplar or sentence-level analysis.
- For Pollock work, start with [pollock-introduction-framework.md](references/pollock-introduction-framework.md). Add:
  - [pollock-case-patterns.md](references/pollock-case-patterns.md) for multi-paper or cross-case synthesis
  - [pollock-paragraph-support-patterns.md](references/pollock-paragraph-support-patterns.md) for sentence mechanics
  - [pollock-self-audit.md](references/pollock-self-audit.md) first for fast Pollock QC
  - [pollock-beorchia-checklist.md](references/pollock-beorchia-checklist.md) only when building a worksheet, outline, or line-by-line audit
  - [pollock-alignment-matrix.md](references/pollock-alignment-matrix.md) only when comparing handbook principles, checklist logic, and case evidence

## Assets

Load these templates when drafting to maintain stable and consistent output:

- Use [assets/hook-options-shell.md](assets/hook-options-shell.md) when drafting Stage 1 hook options from scratch or when the opening feels generic.
- Use [assets/gap-paragraph-shell.md](assets/gap-paragraph-shell.md) when drafting Stage 2 literature-turn paragraphs or diagnosing a weak gap.
- Use [assets/contribution-paragraph-shell.md](assets/contribution-paragraph-shell.md) when drafting Stage 3 contribution paragraphs or auditing whether the paper move is visible.

## Execution

### Drafting and Rewriting

1. Choose the strongest hook logic for the outlet and evidence available.
2. Establish the conversation, isolate the blind spot, and state why that omission matters.
3. If helpful, let one direct research question serve as the hinge into the paper move.
4. Answer that hinge by stating what the paper does, why the setting or design can answer it, and what readers will learn.
5. Add a roadmap only if it genuinely helps; do not force one in `ASQ` or `Organization Science`.
6. Run funnel and paragraph QA before polishing.

### Paragraph Analysis

1. Identify the paragraph's local job, or the introduction's front-end job if the sample spans multiple paragraphs.
2. Segment the text into topic sentence, elaboration, support, analysis, and transition.
3. Label each support sentence by function.
4. If the sample is an introduction, also label hook type, opening paraphrase, literature synthesis, gap, gap-value sentence, paper move, setting justification, and contribution preview.
5. Separate generic writing rules from sample-specific observations.
6. Extract transferable rules before any rewrite.
7. Rewrite only if the user asks for transfer into new prose.

### QC Checklist

Before finalizing, verify all five stages hold:

- [ ] Stage 1 (Hook): opens with concrete fact, paradox, or conversation — not a time-marker filler; hook is converted to argument within 2 sentences
- [ ] Stage 2 (Literature turn): gap is a puzzle or unresolved relationship, not just "nobody studied this"; gap-value sentence explains what remains theoretically or practically unstable
- [ ] Stage 3 (Contribution): paper move is explicit — `We examine`, `We argue`, or `We show`; setting or design justification is present; contribution is bounded
- [ ] Stage 4 (Roadmap): absent or short; structure description does not consume more than 2-3 sentences
- [ ] Pollock three questions answered: `Who cares?`, `What do we know / not know / so what?`, `What will we learn?`

## Boundaries

- Do not draft theory sections, hypotheses, or methods prose here.
- Do not convert a weak contribution into a strong-sounding claim by adjusting the language alone; flag the underlying issue instead.
- Do not produce author-by-author literature lists when thematic synthesis is feasible.
- Do not add a roadmap paragraph just because one is conventional; confirm it adds navigation value.
- Do not let a Pollock overlay override the user's outlet if Pollock's style does not match the target journal.
- Do not rewrite silently in QC mode; diagnose first.

## Gotchas

> 这里记录只有实战中踩过才知道的坑。请补充你在管理学期刊投稿（AMJ/ASQ/SMJ/JOM/OS 等）中真实遇到的引言写作案例。

<!-- TODO: 在这里添加你的真实 Introduction Gotchas -->
