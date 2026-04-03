---
name: research-revision-preflight
description: Run preflight checks, desk-review diagnostics, discussion rewrites, and revision support for business-school research papers. Use when Codex needs to review a draft before submission, explain why a paper feels desk-rejectable, prepare a revision strategy, draft response-letter material, strengthen the discussion section, or triage reviewer comments into contribution, execution, and presentation issues.
---

# Research Revision Preflight

## Overview

Use this skill for late-stage draft assessment and revision work. It should identify the real bottlenecks in a draft and convert reviewer-style concerns into a concrete revision plan or revised prose.

## Core Files

Start with these files and load only what the task needs:

- `./references/playbooks/Desk_Reject_and_Review_Heuristics_Playbook.md`
- `./references/playbooks/Revision_Reviewer_Response_and_Editor_Communication_Playbook.md`

Load these when needed:

- `./references/playbooks/Discussion_Practical_Implications_and_Endgame_Playbook.md`
- `./references/playbooks/Empirical_Results_Interpretation_and_Robustness_Playbook.md`
- `./references/playbooks/Paper_Writing_and_Section_Design_Playbook.md`
- `./references/playbooks/Professor_One_Page_Research_Checklist_EN_Preflight.md`
- `./references/playbooks/Professor_One_Page_Research_Checklist.md`
- `./references/standard-input-template.md`

## Default Workflow

1. Read the local workspace guidance if one exists.
2. Read the two core files above.
3. Classify the draft's problems into:
   - contribution
   - execution
   - presentation
4. Load only the extra playbooks needed for that diagnosis.
5. Produce a prioritized review, revision plan, rewritten discussion text, or response-letter draft.

## Standard Input Template

If the request is underspecified, normalize it using:

- `./references/standard-input-template.md`

Infer missing fields when reasonable, but state the assumptions if they materially affect the review or revision diagnosis.

## Typical Outputs

- A desk-reject risk memo
- A preflight checklist pass
- A discussion rewrite
- A revision plan grouped by issue severity
- A response letter or reviewer-response skeleton
- A diagnosis of which comments are fatal, core-but-fixable, or surface-level

## Operating Heuristics

- Address contribution problems before polishing wording.
- Distinguish fatal issues from fixable execution issues.
- Treat the discussion as a place to recover the original theoretical motivation.
- When responding to reviewers, explain judgment plus revision action, not just the edit.
- Stay calibrated to what the data and design can actually support.

## Avoid

- Starting with line edits when the real problem is the paper's positioning
- Writing apologetic response letters instead of analytical ones
- Repeating results in the discussion without showing why they matter
- Treating every reviewer comment as equally important
- Assuming a rejected paper only needs cosmetic revision
