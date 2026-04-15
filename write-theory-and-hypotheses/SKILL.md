---
name: write-theory-and-hypotheses
description: "Draft, revise, and audit theory sections, construct definitions, mechanism logic, and testable hypotheses for social-science papers, especially management-journal empirical manuscripts. Use when Codex needs to respond to feedback such as under-theorized argument, obvious hypotheses, unclear constructs, citation-dump theory sections, weak mechanism explanation, directionally ambiguous hypotheses, or disorganized theory-to-hypothesis flow. NOT for introduction hooks, titles, abstracts, methods sections, results sections, or discussion/conclusion sections."
---

# Write Theory And Hypotheses

## Overview

Use this skill to build the middle of the paper's front end: the theory logic that explains `why` the expected relationships should hold, the construct work that clarifies who the main characters are, and the hypotheses that translate that logic into clear empirical predictions.

Use it after the introduction-level conversation is roughly set. Do not use it for titles, abstracts, opening hooks, methods, results, or discussion drafting unless the user only needs local alignment with those later sections.

Typical triggers include:

- `这个理论部分太像文献综述了，帮我补why`
- `评审说 under-theorized，帮我诊断`
- `这几个假设太obvious了，帮我改`
- `这个构念和相近构念分不清`
- `我的DV是时间/延迟，假设方向怎么写才不乱`

## Inputs

Collect the minimum workable set from these buckets:

- `question and outlet`: topic, research question, target field or journal, manuscript language
- `conversation and gap`: key literature, exact blind spot, intended contribution
- `core constructs`: focal IV, DV, moderators, mediators, adjacent constructs, whether any construct is new
- `evidence and design`: data, measures, model form, whether the study can support directional, curvilinear, mediated, or moderated claims
- `draft artifacts`: current theory section, hypothesis list, model figure, outline, reviewer comments

If information is missing, make the minimum reasonable assumptions and label them. Do not invent citations, findings, mechanisms, or construct definitions.

## Router

Resolve the route in this order: `task -> structure -> output`.

### Task

- `construct mode`: define a construct, clarify scope conditions, or distinguish neighboring constructs
- `mechanism mode`: explain why the focal relationship should hold
- `hypothesis mode`: draft or rewrite H1-Hn
- `architecture mode`: reorganize the theory-and-hypotheses section
- `QC mode`: diagnose why the section feels under-theorized, obvious, repetitive, or citation-driven

### Structure

- `single-stream theory`: one main literature or mechanism
- `multi-stream theory`: two or more literatures that must be integrated or contrasted
- `new-construct case`: at least one focal construct requires original definition or stronger differentiation
- `existing-construct case`: constructs are established and mainly need positioning and linkage

### Output

- `construct note`
- `one mechanism paragraph`
- `one or more hypotheses`
- `a theory-section outline`
- `a diagnostic report`

### Default Routing

- reviewer language such as `under-theorized`, `too obvious`, `unclear construct`, `weak hypotheses` -> `QC mode`
- definition, boundary, or construct confusion request -> `construct mode`
- hypothesis wording or direction request -> `hypothesis mode`
- ordering, outline, or section rewrite request -> `architecture mode`
- otherwise -> `mechanism mode`

## Core Rules

- Treat theory as an explanation of `why`, not as a storage area for citations, data summaries, variable lists, figures, or bare hypotheses.
- Build the section around main characters, supporting characters, and their storylines. The reader should be able to tell who acts on whom and why.
- Use citations to support a claim about a mechanism or construct, not as a substitute for explanation.
- Write theory paragraphs as mini-pyramids: claim -> optional narrowing -> support -> analysis -> hypothesis bridge.
- Distinguish what the literature has found from why those findings should occur.
- Define every focal construct. If multiple definitions exist, state or imply why this paper uses one rather than another.
- When a construct is new, define it early, bound its scope, and distinguish it from its nearest neighbors.
- Make hypotheses match the actual relationship being theorized and tested: direction, shape, comparison, moderation, mediation, or timing.
- Distinguish conceptual direction from operational coding. If the DV is delay, duration, hazard, speed, or timing, state both the substantive expectation and how it maps onto the modeled variable.
- Keep claim strength aligned with the design. Do not theorize fine-grained causal structure if the study cannot carry that burden.
- Prefer one clear mechanism chain over several thin, decorative ones.
- Prefer active, readable prose over heavy noun chains and citation-dependent sentences.
- If the user is really asking for introduction work, route to `write-social-science-introduction` instead of forcing an introduction-shaped answer here.

## Outputs

- `construct mode`: return a definition, scope conditions, lineage or neighboring constructs, and a short explanation of why this construct belongs in the paper
- `mechanism mode`: return one or two compact paragraphs that explain the relationship, not just report prior findings
- `hypothesis mode`: return numbered hypotheses with wording that matches the modeled relationship and, when needed, a note on how conceptual direction maps to variable coding
- `architecture mode`: return a block-level outline that orders literature, constructs, context, hypotheses, and model figure placement
- `QC mode`: return findings first, then the minimum repairs needed

## Reference Loading

Use progressive loading rather than preloading the whole folder.

- Always load [theory-core-logic.md](references/theory-core-logic.md) for substantive drafting, revision, or QC.
- Load [paragraph-and-prose.md](references/paragraph-and-prose.md) for paragraph-level logic, literature-synthesis sentences, and language cleanup in theory sections.
- Load [construct-clarity.md](references/construct-clarity.md) when a construct is new, disputed, overloaded, or too close to another construct.
- Load [hypothesis-design.md](references/hypothesis-design.md) when writing or auditing formal hypotheses.
- Load [section-architecture.md](references/section-architecture.md) when the user needs an outline, reordering, or guidance on where to place context, constructs, or model figures.
- Load [qc-diagnosis.md](references/qc-diagnosis.md) when the user asks why the section feels weak, under-theorized, obvious, or misaligned.

## Assets

Load these templates when drafting to maintain stable output quality:

- Use [assets/mechanism-paragraph-shell.md](assets/mechanism-paragraph-shell.md) when drafting mechanism paragraphs from scratch.
- Use [assets/hypothesis-templates.md](assets/hypothesis-templates.md) when drafting or rewording hypotheses.
- Use [assets/construct-definition-shell.md](assets/construct-definition-shell.md) when defining a new or disputed construct.

## Execution

### Mechanism Drafting

1. State the focal relationship or question in plain terms.
2. Identify the main characters and supporting characters.
3. Explain why the focal actor, condition, or mechanism should generate the expected outcome.
4. Use literature to support the mechanism, not to replace it.
5. End on the specific implication that naturally yields the hypothesis or proposition.

### Construct Work

1. Define the construct.
2. State its scope conditions when they matter.
3. Place it in its lineage or conversation.
4. Distinguish it from the closest neighboring constructs.
5. Explain why this construct, rather than a nearby alternative, is the right one for the paper.

### Hypothesis Drafting

1. Identify the relationship type: `if-then`, `continuous`, or `difference`.
2. Match the wording to the construct type and the actual model.
3. State the direction, shape, or comparison explicitly.
4. If the DV is time-, delay-, speed-, or hazard-based, translate the conceptual prediction into the operational sign carefully.
5. Check that the hypothesis reflects what the theory paragraph actually argued.
6. If moderation or mediation is involved, state the altered strength, direction, or pathway clearly.

### Architecture and QC

1. Decide whether the section is single-stream or multi-stream.
2. Decide whether a new construct must be introduced early.
3. Decide whether context should appear before, within, or after the core theory logic.
4. Decide whether the model figure is explanatory and local, or summary-level and better placed late.
5. If the draft feels weak, diagnose whether the main problem is missing `why`, weak construct clarity, hypothesis mismatch, or bad ordering.
6. In QC mode, separate surface symptoms from root causes and propose the minimum repair that would actually change the section.

## Boundaries

- Do not write introduction hooks, titles, or abstracts here.
- Do not let a model figure or variable inventory stand in for theory.
- Do not write hypotheses that are more precise than the paper's constructs or design justify.
- Do not polish around a weak mechanism; fix the logic first.

## Gotchas

> 这里记录实战中只有踩过坑才知道的经验。请在明天补充你遇到的真实案例。

<!-- TODO: 补充你在管理学期刊投稿中踩过的理论写作坑 -->
