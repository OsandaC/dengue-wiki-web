---
type: study-design
tags: [epidemiology, case-control, matching, study-design, biostatistics, age-matching]
created: 2026-05-24
updated: 2026-05-24
sources: 2
---

# Age-Matched Case-Control Analysis

## Overview

Age-matched case-control analysis is a study design in which controls are selected to match cases on age (and often sex), followed by an analytical strategy that accounts for the matching. Age matching is one of the most common matching strategies in case-control studies, used to improve study efficiency by ensuring roughly equal numbers of cases and controls in each age stratum. However, matching on age introduces methodological complexities that are frequently misunderstood in practice.

The critical distinction is between the **design** (how controls are selected) and the **analysis** (how confounding is handled). Matching is a design strategy; it does not substitute for analytical control of confounding. A matched design almost always requires controlling for the matching factors in the analysis, but does not necessarily require a matched (conditional) analytical method — though the two major methodological references disagree on this point (see Contradictions & Debates below).

## Key Principles

### Matching does not eliminate confounding

Matching makes controls more similar to cases on the matching factor (age) but also — because the matching factor is associated with the exposure — on the exposure itself. This can introduce confounding by the matching factor that did not exist in the source population (see [[Pearce2016 - Analysis of Matched Case-Control Studies]], hypothetical example: crude OR shifts from 0.86 in the total population to 1.68 in the matched sample, neither reflecting the true adjusted OR of 2.00). More precisely, matching introduces **selection bias** — controls are selected conditional on the matching factor, which distorts the matching-factor–exposure relationship in the study sample (see [[Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies]]).

### Unconditional vs. conditional analysis

- **Conditional (matched) analysis:** Conditional logistic regression treating each matched set as a stratum, or Mantel-Haenszel stratification. Both sources agree this is always valid for matched case-control data.
- **Unconditional (standard) analysis:** Logistic regression adjusting for matching factors as covariates. The validity of this approach is disputed — see Contradictions & Debates.

### Matching ratios

The most common ratio is 1:1 (one control per case). Ratios up to 1:4 or 1:5 are standard practice; beyond 1:4, each additional control adds diminishing statistical power. Mixed matching ratios (e.g., some cases matched 1:2, others 1:3) are valid if matching factors are adjusted for in the analysis (see [[Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies]]).

### Over-matching

Over-matching occurs when too many variables are used for matching or when matching is performed on variables that lie on the causal pathway between exposure and outcome. Over-matching reduces the number of informative (discordant) matched sets, reducing statistical efficiency without improving validity (see [[Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies]]).

### When is conditional analysis necessary?

Sparse strata arise when:
- Controls are individually matched (siblings, neighbours)
- Matching is performed on many factors simultaneously
- Each stratum has just one case and one control

Both sources agree that conditional analysis is required when strata are sparse. When matching is on a small number of standard factors (age group, sex) and strata contain multiple cases and controls, Pearce2016 argues unconditional analysis is valid and may be preferable; Iwagami2022 disagrees.

### Case-control vs. cohort matching

Matching in cohort studies differs fundamentally from case-control matching: it removes or reduces confounding directly (by balancing confounder distributions at baseline) and does not introduce selection bias. Standard (unconditional) regression can be used for cohort analysis without the concerns that apply to case-control data (see [[Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies]]).

## Application in Dengue Research

Age matching is relevant to dengue case-control studies comparing:
- Symptomatic vs. asymptomatic dengue (e.g., [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]])
- DHF/DSS vs. DF severity outcomes
- Dengue vs. non-dengue febrile controls in diagnostic studies
- Post-dengue autoimmune outcomes vs. matched population controls (e.g., [[Li2018 - Increased Risk of Autoimmune Diseases in Dengue]], [[Shih2023 - Autoimmune Disease Risk After Dengue]] — cohort designs, but with age-matched comparison groups)

When evaluating these studies, the key questions are:
1. Was the matching factor (age) controlled for in the analysis?
2. Was the analytical method (unconditional vs. conditional) appropriate for the stratum size?
3. If multiple matching factors were used, were strata sparse enough to require conditional analysis?
4. Is the matching ratio adequate (1:4 or greater for reasonable power)?
5. Could over-matching be reducing statistical efficiency (e.g., matching on hospital admission date in addition to age and sex)?

## Contradictions & Debates

### Validity of unconditional logistic regression for matched case-control data

**Pearce2016** argues that unconditional logistic regression adjusting for matching factors as covariates is valid when strata are not sparse (i.e., when multiple cases and controls share matching-factor values). Using a worked numerical example, Pearce demonstrates that unconditional analysis yields the correct adjusted OR (2.00) with slightly narrower confidence intervals than conditional analysis (1.42–2.81 vs. 1.40–2.89). Pearce recommends unconditional analysis as the default for population-based studies with standard matching on age and sex.

**Iwagami2022** describes unconditional logistic regression with matching factors as covariates as "not recommended" for matched case-control data, citing Greenland (1986) on the argument that the selection bias introduced by matching causes model misspecification in unconditional regression, regardless of stratum sparseness. Iwagami2022 recommends Mantel-Haenszel stratification or conditional logistic regression as the default analytical approach.

**Status:** This is a genuine methodological disagreement in the epidemiological literature. Both positions have adherents. Pearce's argument is supported by a numerical demonstration; Iwagami's invokes a theoretical concern (model misspecification from selection bias) without a worked counterexample. Neither source cites simulation studies that would settle the question empirically. When evaluating dengue case-control studies, the choice of analytical method should be noted and assessed in light of both positions.

### Matched design requires matched analysis (common misconception)

Both Pearce2016 and Iwagami2022 agree that matching in the design does not automatically require a "matched" (conditional) analysis — the key requirement is that matching factors are controlled for analytically. However, they disagree on *how* that control should be implemented (see above). The misconception that conditional analysis is the only option is widespread, with practical consequences: unnecessarily discarding unmatched controls reduces sample size and precision.

## Related Pages

- [[Dengue vs Healthy Controls - Analysis Methods Workflow]] — operational checklist applying these principles to dengue case-control biomarker studies
- [[Indirect Immunofluorescence ANA Test]] — dengue ANA studies where age-matching is relevant to case-control comparisons
- [[FcγRIIa Genotyping]] — genetic association studies frequently use age-matched case-control designs

## Sources

- [[Pearce2016 - Analysis of Matched Case-Control Studies]]
- [[Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies]]
