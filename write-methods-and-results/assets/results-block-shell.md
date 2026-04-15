# Results Block Shell

Use this scaffold for each hypothesis test block in the results section. One block = one hypothesis. Do not compress multiple hypotheses into one paragraph.

---

## Shell

```
[PREDICTION RESTATEMENT — one compact sentence reminding the reader what was predicted.
 Pattern: "Hypothesis X predicted that [IV] is positively (negatively) related to [DV]."]

[POINTER — direct the reader to the relevant table or figure.
 Pattern: "Table X, Model Y presents the results." or "As shown in Figure X..."]

[RESULT — report the coefficient (or effect size), standard error or CI, and significance.
 Include enough numerical detail to be credible. For Stata reghdfe output: β, SE, p-value or t-stat.
 For survival models: hazard ratio and CI. For logit: log-odds and AME if available.]

[SUPPORT VERDICT — state clearly whether the hypothesis is supported.
 Use one of: "Hypothesis X is supported.", "Hypothesis X is not supported.",
 "Hypothesis X receives partial support."]

[INTERPRETATION — translate the coefficient into substantive language.
 Pattern: "A one-standard-deviation increase in [IV] is associated with a [magnitude]
 [increase/decrease] in [DV], equivalent to [contextualized comparison if available]."]
```

---

## Filled Example

> Hypothesis 2 predicted that prior alliance experience moderates the positive relationship between network centrality and innovation output, such that the relationship is stronger for firms with higher prior experience. Table 3, Model 4 presents the moderated regression results. The interaction term is positive and significant (β = .18, SE = .06, p < .01), supporting Hypothesis 2. Firms with one standard deviation above the mean in prior experience show a centrality–innovation slope that is approximately 40% steeper than firms at the mean.

---

## Interaction Results — Extra Requirements

When reporting moderation:

```
[PLOT REFERENCE — always reference or describe the interaction plot.
 "Figure X plots the interaction at ±1 SD of [Moderator]."]

[SLOPE INTERPRETATION — state the effect of IV on DV at high vs. low moderator values.
 Do NOT infer support from the sign of the interaction coefficient alone;
 plot the simple slopes.]

[SIGNIFICANCE OF SIMPLE SLOPES — if possible, report whether each simple slope
 is significantly different from zero.]
```

---

## Checklist

- [ ] Each hypothesis gets its own paragraph
- [ ] Prediction is restated (not just "as predicted")
- [ ] Table/figure pointer is specific (Table X, Model Y)
- [ ] Coefficient, SE, and p-value are all reported
- [ ] Support verdict is unambiguous
- [ ] Coefficient is translated into substantive units
- [ ] Interaction is plotted and simple slopes are interpreted, not inferred from sign
