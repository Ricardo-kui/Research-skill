# Research Revision Preflight Standard Input Template

Use this template when the user wants review, preflight, or revision support but the request is underspecified.

## Minimum fields

- Project or paper title:
- Target journal or review context:
- Current stage:
  - pre-submission
  - under review
  - revise and resubmit
  - rejected and reframe
- Artifact under review:
  - abstract
  - introduction
  - theory section
  - full draft
  - reviewer letter
- Current text or comments:
- Main claim of the paper:
- Main method or empirical design:
- Biggest concern already suspected by the user:
- What must be preserved:
- What the user wants now:
  - desk-reject diagnosis
  - preflight checklist
  - discussion rewrite
  - revision plan
  - response letter draft

## Fast normalization rule

When the user does not provide these fields explicitly:

1. Infer the review stage.
2. Infer whether the main problem is contribution, execution, or presentation.
3. Identify the most likely fatal issue before discussing cosmetic ones.
4. Extract must-preserve claims and non-negotiables from the draft.
5. State assumptions before delivering the diagnosis if they materially affect the outcome.

## Output modes

- `Desk-reject memo`: Short risk memo prioritized by severity.
- `Preflight pass`: Checklist-style review before submission.
- `Revision plan`: Group issues into fatal, core-but-fixable, and surface.
- `Response draft`: Draft reviewer-response prose or a response-letter skeleton.
- `Discussion repair`: Rewrite the discussion or implications section.
