---
name: write-discussion-and-conclusion
description: "Draft, revise, and audit discussion sections, theoretical implications, practical implications, limitations, future research directions, and concluding paragraphs for social-science papers, especially management-journal empirical manuscripts. Use when Codex needs to move beyond result restatement, connect findings back to the paper's opening promises, articulate contribution without overclaiming, or close the paper in a way that feels earned. NOT for theory drafting, construct definitions, introduction hooks, methods sections, or results sections."
---

# Write Discussion And Conclusion

## Overview

Use this skill to write the closing arc of a paper: the discussion section that explains what the results mean for the larger conversation, the limitations and future research that show the author understands the study's boundaries, and the conclusion that closes the story at a higher level rather than merely repeating the findings.

This skill is for interpretation and closure, not for re-running theory, methods, or results. Use it when the user has findings in hand and now needs to turn them into contribution, implication, limitation, and ending.

Typical triggers include:

- `discussion 现在只是重复结果，帮我改`
- `怎么把 findings 接回引言里的贡献承诺`
- `实践意义太空，帮我写得更像真的 implications`
- `局限和 future research 现在很敷衍`
- `结尾收不住，帮我写 concluding paragraph`

## Inputs

Collect the minimum workable set from these buckets:

- `question and outlet`: topic, target field or journal, manuscript language
- `front-end promise`: research question, stated contributions, opening claims, theory conversation
- `findings`: supported hypotheses, nulls, reversals, surprising results, post hoc insights
- `design boundaries`: context, sample, measure, and identification limitations
- `draft artifacts`: current discussion, limitation section, future research, or conclusion

If information is missing, make the minimum reasonable assumptions and label them. Do not invent contributions, managerial implications, or stronger claims than the findings can support.

## Router

Resolve the route in this order: `task -> section -> output`.

### Task

- `discussion mode`: write or revise the main discussion logic
- `contribution mode`: articulate theoretical or methodological contribution
- `implications mode`: write practical, policy, or broader implications
- `limitations mode`: write limitations and future research directions
- `conclusion mode`: write the final closing paragraph or conclusion section
- `QC mode`: diagnose why the back end feels weak, repetitive, scattered, or overclaimed

### Section

- `opening of discussion`
- `theoretical implications`
- `methodological contribution`
- `practical implications`
- `limitations`
- `future research`
- `final conclusion`

### Output

- `one subsection`
- `one integrated discussion block`
- `a diagnostic report`
- `a closing paragraph`

### Default Routing

- wording such as `too repetitive`, `just restates results`, `afterthought`, `doesn't close` -> `QC mode`
- wording such as `contribution`, `theoretical implications`, `so what` -> `contribution mode`
- wording such as `practical implications`, `managerial implications`, `policy implications` -> `implications mode`
- wording such as `limitations`, `future research` -> `limitations mode`
- wording such as `conclusion`, `ending`, `final paragraph` -> `conclusion mode`
- otherwise -> `discussion mode`

## Core Rules

- A discussion section must interpret, not merely repeat.
- Return to the paper's opening promises. The back end should answer the same `what will we learn?` question the front end raised.
- Narrow overbroad opening promises when the findings or design support a smaller claim. Do not carry an inflated front-end statement unchanged into the back end.
- Organize discussion around contribution, not around a second narration of every coefficient.
- Write discussion paragraphs as mini-pyramids: finding or implication -> interpretation -> contribution or boundary -> bridge.
- Explain what supported findings, nulls, and surprises mean for the larger conversation.
- Distinguish theoretical implications from practical implications; do not merely restate one in different words.
- Acknowledge limitations candidly, but do not turn the section into a self-destruction exercise.
- Make future research directions grow from the study's actual findings and limits, not from generic filler.
- Close at a higher level than the raw results. A good ending returns to the research question or larger problem and shows how the conversation has moved.
- Prefer active, concrete prose over abstract uplift language and management platitudes.
- If the user is really asking for introduction, theory, or results drafting, route to the appropriate specialized skill instead of forcing a discussion-shaped answer.

## Outputs

- `discussion mode`: return a coherent interpretation block that reconnects findings to the paper's question and contribution
- `contribution mode`: return one or more paragraphs that explain what the paper changes in the literature
- `implications mode`: return a practical or policy implications block that is specific and not merely decorative
- `limitations mode`: return a limits-and-next-steps block with credible boundaries and plausible future directions
- `conclusion mode`: return a closing paragraph that elevates rather than repeats
- `QC mode`: return findings first, then the minimum repairs needed

## Reference Loading

Use progressive loading rather than preloading the whole folder.

- Always load [discussion-core.md](references/discussion-core.md) for substantive drafting, revision, or QC.
- Load [paragraph-and-prose.md](references/paragraph-and-prose.md) for paragraph-level logic, interpretive movement, and language cleanup in discussion or conclusion sections.
- Load [contribution-and-implications.md](references/contribution-and-implications.md) when writing theory, methods, or practical implications.
- Load [limitations-and-future.md](references/limitations-and-future.md) when writing boundaries, caveats, or future research.
- Load [conclusion-closure.md](references/conclusion-closure.md) when writing the final paragraph or conclusion section.
- Load [back-end-qc.md](references/back-end-qc.md) when the discussion feels repetitive, scattered, shallow, or overclaimed.

## Assets

Load these templates when drafting to maintain stable output quality:

- Use [assets/discussion-block-shell.md](assets/discussion-block-shell.md) when drafting the main discussion paragraphs.
- Use [assets/implications-shell.md](assets/implications-shell.md) when writing theoretical or practical implications.
- Use [assets/limitations-shell.md](assets/limitations-shell.md) when writing limitations and future research.

## Execution

### Discussion Drafting

1. Restate the research question and main answer in compressed form.
2. Move immediately from what was found to what it changes in the conversation.
3. Interpret nulls, reversals, or surprising findings rather than hiding them.
4. Tie each major implication back to the paper's opening claims.
5. Keep the section moving; do not re-run the results table.

### Contribution And Implications

1. Identify the contribution promised in the introduction.
2. State how the findings address that promise.
3. Say whether the paper fills an incompleteness, exposes an inadequacy, or pushes against a prevailing assumption.
4. Separate theory implications from practical implications.
5. Keep claims bounded to what the findings actually support.

### Limitations And Future Research

1. State the limit clearly.
2. Explain what interpretive boundary it creates.
3. If possible, note why the limit does not invalidate the whole paper.
4. Derive future research from the actual limit or unexpected finding.
5. Avoid generic `future studies should...` filler.

### Conclusion

1. Return to the paper's question or larger problem.
2. Summarize the answer at a higher level than the results section.
3. Show how the conversation has moved.
4. End with a sentence that feels final, not administrative.

## Boundaries

- Do not merely summarize every result again.
- Do not inflate contribution because the author is tired or worried the paper feels small.
- Do not turn practical implications into vague management platitudes.
- Do not use limitations as a dumping ground for every imaginable weakness.
- Do not end with a generic call for more research if a stronger closing statement is available.

## Gotchas

> 这里记录实战中只有踩过坑才知道的经验。请在明天补充你遇到的真实案例。

<!-- TODO: 补充你在管理学期刊投稿中踩过的 discussion/conclusion 写作坑 -->
