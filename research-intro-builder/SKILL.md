---
name: research-intro-builder
description: Build and rewrite introductions for business-school research papers inside D:\Codex\Business_Research_Vault. Use when Codex needs to sharpen an opening hook, improve the first paragraph, structure a full introduction, turn a weak gap into a stronger puzzle, frame what-do-we-learn claims, or rewrite an introduction so it works as a focused mini-summary for a journal-facing paper.
---

# Research Intro Builder

## Overview

Use this skill for introduction-specific work. It should turn vague front-end framing into a sharper opening, a clearer problem setup, and a more convincing contribution preview.

## Core Files

Start with these files and load only what the task needs:

- `D:\Codex\Business_Research_Vault\4_Learning\Research_Playbook_Methods\Introduction_Hooks_Openings_and_First_Paragraph_Playbook.md`
- `D:\Codex\Business_Research_Vault\4_Learning\Research_Playbook_Methods\Introduction_Architecture_and_Mini_Summary_Playbook.md`

Load these when needed:

- `Research_Puzzle_and_Problematization_Playbook.md`
- `Literature_Review_Synthesis_and_Intertextual_Coherence_Playbook.md`
- `Theoretical_Contribution_Framing_and_Claim_Strategy_Playbook.md`
- `Argument_Structure_and_Key_Line_Playbook.md`
- `Paper_Writing_and_Section_Design_Playbook.md`
- `D:\Codex\Business_Research_Vault\.agents\skills\research-intro-builder\references\standard-input-template.md`

## Default Workflow

1. Read `D:\Codex\Business_Research_Vault\AGENTS.md`.
2. Read the two core files above.
3. Diagnose whether the main problem is:
   - weak opening
   - weak puzzle
   - weak introduction structure
   - weak contribution preview
4. Read only the extra playbooks needed for that diagnosis.
5. Produce revised prose, not just commentary, unless the user explicitly asks for diagnosis only.

## Standard Input Template

If the request is underspecified, normalize it using:

- `D:\Codex\Business_Research_Vault\.agents\skills\research-intro-builder\references\standard-input-template.md`

Infer missing fields when reasonable, but state the assumptions if they materially affect the rewrite.

## Typical Outputs

- A new first paragraph
- A rewritten full introduction
- A paragraph-by-paragraph introduction outline
- A diagnosis of why the current introduction feels weak
- A stronger "what do we know / do not know / so what" sequence
- A sharper "what will we learn" contribution preview

## Operating Heuristics

- Keep the opening concrete and specific.
- Make the introduction function as a stand-alone mini-summary.
- State the research question clearly rather than only naming a broad topic.
- Preview the contribution in a calibrated way; do not overclaim.
- If the problem is really a literature or puzzle problem, fix that first rather than polishing sentences.

## Avoid

- Starting with broad, generic background that could fit any paper
- Treating "there is a gap" as sufficient motivation
- Letting the opening story drift away from the research question
- Using the introduction to summarize chapter order instead of making the case
- Promising a contribution that the paper does not actually deliver
