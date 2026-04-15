# Robustness and Post Hoc Writeup Shell

Use this scaffold to keep robustness checks and post hoc analyses conceptually separate. Mixing them invites reviewer criticism about what the paper actually claims.

---

## The Key Distinction

| Type | Question it answers | Typical position |
|---|---|---|
| **Robustness check** | "Does the main result still hold under alternative design choices?" | Immediately after main hypothesis tests |
| **Post hoc analysis** | "What else does this data reveal that was not predicted?" | After robustness, clearly labeled exploratory |

---

## Robustness Check Block Shell

```
[THREAT — state the specific alternative explanation or design concern being addressed.
 Pattern: "One concern is that [X] may confound the relationship between [IV] and [DV]."]

[TEST — describe what was done to address the threat.
 Pattern: "To address this, we [re-estimated the model using / replaced [DV] with /
 restricted the sample to / added a control for] [description]."]

[RESULT — report the finding compactly.
 Pattern: "The coefficient on [IV] remains positive and significant
 (β = [X], p < [Y]; see Appendix Table [Z])."]

[IMPLICATION — one sentence on what this establishes.
 Pattern: "This result suggests that [main finding] is not an artifact of [threat]."]
```

---

## Post Hoc Analysis Block Shell

```
[MOTIVATION — explain what observation or unexpected pattern prompted this analysis.
 Be honest that it is exploratory. Pattern: "An unexpected finding in the main results
 prompted us to explore whether [X]. Although not hypothesized, this analysis..."]

[TEST — describe the analysis.]

[RESULT — report compactly.]

[BOUNDARY — state clearly what the post hoc analysis does and does not establish.
 Post hoc ≠ confirmation. Pattern: "While this pattern is consistent with [X],
 we treat this as exploratory and encourage future research to test it directly."]
```

---

## Organizational Options

**Option A** — subsection within Results:
- 4.1 Descriptive Statistics
- 4.2 Hypothesis Tests
- 4.3 Robustness Checks
- 4.4 Additional Analyses (post hoc, clearly labeled)

**Option B** — Robustness in supplementary appendix, referenced in text.
Use Option B when the robustness battery is long and would disrupt the main results narrative.

---

## Checklist

- [ ] Each robustness check names the specific threat it addresses
- [ ] Robustness results are reported with enough detail to verify (table reference + key coefficient)
- [ ] Post hoc analyses are labeled as exploratory
- [ ] Post hoc boundary statement prevents overclaiming
- [ ] Robustness and post hoc sections have distinct headings or are clearly separated
