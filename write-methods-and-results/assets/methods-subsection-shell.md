# Methods Subsection Shell

Use this scaffold when drafting any methods subsection. Identify the subsection type first (Sample, DV, IV/Controls, Analysis Strategy), then fill in the appropriate slots.

---

## Sample and Context

```
[SETTING — one or two sentences on the empirical context. Why this setting?
 What makes it appropriate for testing the research question?]

[SAMPLE FRAME — what is the population? What time window?]

[CONSTRUCTION FUNNEL — walk through each inclusion/exclusion step with N at each stage.
 Pattern: "We began with X observations. We excluded Y observations due to [reason],
 leaving Z observations. We further required [condition], resulting in a final sample of N."]

[FINAL N — restate final N, unit of analysis, and panel dimensions if applicable.
 E.g., "The final sample includes N firm-year observations from X unique firms."]
```

---

## Dependent Variable(s)

```
[CONSTRUCT NAME — restate the DV construct from the theory section.]

[OPERATIONALIZATION — how exactly is it measured? Source, variable, formula if needed.
 Be specific enough that a reader could replicate it.]

[JUSTIFICATION — why is this operationalization appropriate for the construct?
 Cite prior use if available. Note any limitations proactively.]
```

---

## Independent Variables and Controls

```
[FOCAL IV — same structure as DV above.]

[MODERATOR(S) — if applicable.]

[CONTROLS — list each control, its source, and a brief rationale.
 Do not include a control without a rationale. Reviewers will ask why it is there.]

[ORDER NOTE — ensure this matches the order in your regression tables.]
```

---

## Analysis Strategy

```
[MODEL CHOICE — state the estimator and why it fits the data structure.
 E.g., "We estimate OLS models with firm and year fixed effects using reghdfe (Correia, 2017),
 which removes time-invariant unobserved heterogeneity at the firm level."]

[CLUSTERING — state the level at which standard errors are clustered and why.]

[IDENTIFICATION LOGIC — if the design supports a causal interpretation, explain why.
 If not, state explicitly what the study can and cannot establish.]

[DIAGNOSTICS — note key checks run: multicollinearity (VIF), heteroscedasticity,
 functional form tests, missing data strategy, etc.]
```

---

## Checklist before submitting a methods section

- [ ] Sample funnel shows N at each step
- [ ] DV operationalization cites prior use or justifies novelty
- [ ] Every control has a one-line rationale
- [ ] Estimator choice is justified, not just stated
- [ ] SE clustering level is stated
- [ ] Causal language does not exceed what the design supports
