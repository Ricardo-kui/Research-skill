# Research Intro Builder Standard Input Template

Use this template when the user wants introduction work but the request is underspecified.

## Minimum fields

- Project or paper title:
- Target journal or reader:
- Current stage:
  - idea
  - draft
  - revise and resubmit
- Current introduction text:
  - first paragraph only
  - full introduction
  - none yet
- Core research question:
- Why this topic matters:
- What the literature already knows:
- What is still missing or unresolved:
- Main theoretical lens:
- Data, method, or empirical context:
- Intended contribution claim:
- What the user wants now:
  - opening paragraph
  - full introduction rewrite
  - diagnosis only
  - outline plus prose

## Fast normalization rule

When the user does not provide these fields explicitly:

1. Infer the paper topic and current stage.
2. Infer the likely audience from the context.
3. Extract the current puzzle, gap, or contradiction.
4. Extract or infer the method and empirical context.
5. State assumptions before rewriting if they materially affect the output.

## Output modes

- `Opening-only`: Rewrite just the first paragraph.
- `Structure-first`: Give a paragraph-by-paragraph introduction plan before prose.
- `Full rewrite`: Rewrite the full introduction in polished prose.
- `Diagnostic`: Explain why the current introduction is weak and what must change.
