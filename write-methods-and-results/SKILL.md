---
name: write-methods-and-results
description: "Draft, revise, and audit methods sections, results sections, robustness-check writeups, and claim-evidence alignment for social-science papers, especially management-journal empirical manuscripts. Use when Codex needs to explain sample construction, measures, controls, model choice, descriptive statistics, hypothesis tests, interaction plots, effect sizes, robustness checks, or why a methods/results section feels incomplete, unclear, or not credible. NOT for theory drafting, construct definitions, introduction hooks, abstracts, or discussion/conclusion sections."
---

# Write Methods And Results

## Overview

Use this skill to write the empirical middle of a paper: the methods section that convinces readers the design and measurement are credible, and the results section that convinces readers the evidence supports the claims actually being made.

This is a writing and diagnostic skill, not a full econometrics encyclopedia. Use it to express design, evidence, and limitations clearly; if the real bottleneck is estimator choice or identification strategy, surface that instead of pretending the issue is only prose.

Typical triggers include:

- `帮我重写 methods，让评审看得懂而且信得过`
- `这段 results 太像念表了`
- `我的 interaction 结果怎么写才清楚`
- `稳健性检验和 post hoc analysis 应该怎么分开写`
- `评审说因果语言过强，帮我收口`

## Inputs

Collect the minimum workable set from these buckets:

- `question and outlet`: topic, target field or journal, manuscript language
- `design and data`: setting, sample, time window, data source, observational or experimental design
- `measures`: DV, IVs, moderators, mediators, controls, how they are operationalized
- `analysis`: models, software, diagnostics, identification logic, key threats to validity
- `results artifacts`: tables, figures, interaction plots, descriptive statistics, robustness checks, post hoc analyses
- `draft artifacts`: current methods/results text, reviewer comments, notes on what the user thinks is weak

If information is missing, make the minimum reasonable assumptions and label them. Do not invent sample sizes, effect sizes, significance levels, diagnostics, or robustness outcomes.

## Router

Resolve the route in this order: `task -> section -> output`.

### Task

- `methods mode`: write or revise sample, measures, controls, or analysis subsections
- `results mode`: write or revise descriptive statistics, hypothesis tests, effect interpretation, or figure discussion
- `robustness mode`: write robustness-check or post hoc analysis sections
- `alignment mode`: diagnose whether the empirical prose outruns the design
- `QC mode`: diagnose why the section feels incomplete, unclear, or not credible

### Section

- `sample and context`
- `dependent variables`
- `independent variables and controls`
- `analysis strategy`
- `descriptive statistics`
- `hypothesis tests`
- `robustness checks`
- `post hoc analysis`

### Output

- `one subsection`
- `one results block`
- `a diagnostic report`
- `a section outline`

### Default Routing

- wording such as `causal language`, `overclaim`, `credibility`, `validity`, `reviewer doesn't buy it` -> `alignment mode`
- wording such as `robustness`, `alternative measure`, `post hoc`, `supplement` -> `robustness mode`
- wording such as `results`, `table`, `interaction`, `supported`, `effect size` -> `results mode`
- wording such as `sample`, `measure`, `control`, `model`, `method` -> `methods mode`
- otherwise -> `QC mode`

## Core Rules

- Methods and results must persuade, not merely describe.
- Use methods prose to show completeness, clarity, and credibility.
- Use results prose to show what was tested, what was found, and what the evidence does and does not support.
- Write empirical paragraphs as mini-pyramids rather than as table-reading or procedure dumps.
- Match claim strength to design strength. If the design supports association rather than causation, the prose must do the same.
- Explain sample construction as a funnel, not as an unexplained final N.
- Keep variable descriptions aligned with the order used in tables and models.
- Report hypothesis tests in a repeatable rhythm: remind the reader what was predicted, point to the relevant model or figure, state the result, then say whether the hypothesis was supported.
- Do not let tables do the argument's job. Translate coefficients, probabilities, or effect sizes into meaningful language.
- Plot and interpret interactions; do not infer interaction support from coefficient signs alone.
- Separate robustness checks from post hoc analyses. The former defend the result; the latter explore what the result might additionally imply.
- Prefer active, readable prose over jargon-heavy sentences that assume the reader can reconstruct the design or the result unaided.
- If the user is really asking for theory, introduction, or discussion drafting, route to the appropriate specialized skill instead of forcing an empirical-section answer.

## Outputs

- `methods mode`: return one clean subsection that states what was done, why it was done, and why the choice is defensible
- `results mode`: return one results block that states the hypothesis, points to the evidence, reports the result, and interprets it in bounded terms
- `robustness mode`: return a section that clearly distinguishes threat, test, and implication
- `alignment mode`: return a findings-first diagnosis of where the prose outruns the design
- `QC mode`: return findings first, then the minimum repairs needed

## Reference Loading

Use progressive loading rather than preloading the whole folder.

- Always load [empirical-validity-and-tradeoffs.md](references/empirical-validity-and-tradeoffs.md) for substantive drafting, revision, or QC.
- Load [paragraph-and-prose.md](references/paragraph-and-prose.md) for paragraph-level logic, sentence clarity, and section-specific expression in methods or results.
- Load [methods-credibility.md](references/methods-credibility.md) when writing sample, measures, controls, or analysis strategy.
- Load [results-exposition.md](references/results-exposition.md) when writing descriptive statistics, hypothesis tests, effect interpretation, or interaction results.
- Load [robustness-and-posthoc.md](references/robustness-and-posthoc.md) when writing robustness checks, supplementary analyses, or post hoc sections.
- Load [claim-evidence-alignment.md](references/claim-evidence-alignment.md) when the user asks about overclaiming, causal language, validity threats, or empirical credibility.

## Assets

Load these templates when drafting to maintain stable output quality:

- Use [assets/methods-subsection-shell.md](assets/methods-subsection-shell.md) when drafting any methods subsection from scratch.
- Use [assets/results-block-shell.md](assets/results-block-shell.md) when reporting individual hypothesis tests.
- Use [assets/robustness-writeup-shell.md](assets/robustness-writeup-shell.md) when writing robustness or post hoc sections.

## Execution

### Methods Drafting

1. State the empirical setting and sample frame.
2. Walk the reader through sample construction and attrition.
3. Describe the variables in a stable order: DV, focal IVs, moderators or mediators, then controls.
4. Explain how each key measure was constructed and why it is appropriate.
5. State the analysis method, software or command family when relevant, and why that approach fits the data.

### Results Drafting

1. Open with the local job of the subsection: descriptives, main tests, interaction, robustness, or post hoc.
2. For each hypothesis, restate the prediction in compact form.
3. Point to the relevant model, table, or figure.
4. Report the result with enough numerical detail to be credible.
5. State whether the hypothesis is supported, partially supported, or not supported.
6. Translate the result into substantive meaning without overstating it.

### Robustness And Post Hoc

1. State the threat, alternative explanation, or unexplored issue.
2. Explain what additional test was run and why.
3. Report the result.
4. State what the additional analysis does and does not establish.
5. Keep robustness and exploration conceptually separate even if they appear in the same section.

### Alignment And QC

1. Identify the main threat to persuasion: incompleteness, clarity, credibility, or overclaim.
2. Decide whether the root cause sits in sample logic, measurement, model explanation, hypothesis reporting, or interpretation.
3. Surface the smallest repair that would materially improve the section.

## Boundaries

- Do not fabricate diagnostics, coefficients, significance levels, or robustness outcomes.
- Do not let technical jargon substitute for explanation.
- Do not write causal language that the design cannot support.
- Do not hide null or mixed results behind vague summary prose.
- Do not collapse robustness checks and post hoc analyses into one undifferentiated bucket.

## Gotchas

> 这里记录实战中只有踩过坑才知道的经验。请在明天补充你遇到的真实案例。

<!-- TODO: 补充你在管理学期刊投稿中踩过的方法/结果写作坑 -->
