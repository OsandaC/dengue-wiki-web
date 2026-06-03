---
type: source
tags: [epidemiology, case-control, cohort, matching, study-design, biostatistics, propensity-score]
authors: [Iwagami M, Shinozaki T]
year: 2022
journal: Annals of Clinical Epidemiology
doi: 10.37737/ace.22005
citations_semantic_scholar: 115
citations_crossref: 122
citations_retrieved: 2026-05-24
created: 2026-05-24
updated: 2026-05-24
---

# Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies

**Full citation:** Iwagami M, Shinozaki T. Introduction to matching in case-control and cohort studies. *Annals of Clinical Epidemiology* 2022;4(2):33–40. doi:10.37737/ace.22005

**Raw file:** `[[raw/Iwagami2022.pdf]]`

## Summary

This seminar paper provides a practical tutorial on matching techniques in both case-control and cohort study designs. It covers the rationale for matching, the mechanics of selecting matched controls, the distinction between individual and frequency matching, and the analytical requirements that follow from each. The paper explicitly addresses common choices such as matching ratios, matching with versus without replacement, and the problem of over-matching.

A central point is the distinction between matching in case-control studies (which introduces selection bias that must be removed analytically) and matching in cohort studies (which directly removes or reduces confounding without introducing selection bias). The paper covers propensity score matching as a modern extension of cohort matching, including marginal matching and the difference between propensity score matching and propensity score adjustment.

The paper cites Pearce2016 (reference [12]) and agrees with the general framework that matching in case-control studies does not eliminate confounding. However, Iwagami2022 and Pearce2016 diverge on the validity of unconditional logistic regression for matched case-control data — a disagreement documented in [[Age-Matched Case-Control Analysis]].

## Study Design
- **Type:** Methodological tutorial (Seminar series)
- **Sample size:** N/A — conceptual worked examples
- **Setting:** N/A — general epidemiological methods guidance
- **Population:** N/A

## Key Findings

- **Matching in case-control studies** introduces selection bias: controls are selected to resemble cases on the matching factors, which distorts the exposure–matching-factor relationship. This bias must be removed by adjusting for matching factors in the analysis (Mantel-Haenszel stratification or conditional logistic regression).
- **Unconditional logistic regression** with matching factors as covariates is described as "not recommended" for matched case-control data, even with non-sparse strata — Iwagami2022 cites Greenland (1986) on model misspecification due to selection bias. This directly contradicts Pearce2016's position that unconditional analysis is valid and may be preferable when strata are not sparse.
- **Matching ratios:** 1:1 is most common; ratios up to 1:4 or 1:5 are standard practice. Beyond 1:4, each additional control adds diminishing statistical power. Mixed matching ratios (e.g., some cases matched 1:2, others 1:3) are valid if matching factors are adjusted for in the analysis.
- **Matching with vs. without replacement:** Matching with replacement allows the same control to be selected for multiple cases, which can increase precision when the control pool is limited but requires analytical adjustment for the non-independence.
- **Over-matching** occurs when too many variables are used for matching or when matching is performed on variables that lie on the causal pathway between exposure and outcome. Over-matching reduces the number of informative (discordant) matched sets and thus reduces statistical efficiency without improving validity.
- **Matching in cohort studies** differs fundamentally from case-control matching: it removes or reduces confounding directly (by balancing confounder distributions at baseline) and does not introduce selection bias. Standard (unconditional) regression can be used for analysis.
- **Propensity score matching** in cohorts creates comparison groups balanced on multiple measured confounders simultaneously. Marginal matching (matching on propensity score without regard to individual covariate values) is distinguished from exact matching on specific covariates.
- **Risk set sampling** (concurrent sampling, incidence density sampling): controls are sampled from the risk set at the time each case occurs. The resulting odds ratio estimates the rate ratio (hazard ratio) rather than the odds ratio. This is a design feature, not an analytical correction.

## Methods Used

- [[Age-Matched Case-Control Analysis]]

## Entities Mentioned

None (general epidemiological methods paper — no disease-specific entities).

## Concepts Addressed

- [[Age-Matched Case-Control Analysis]]

## Relevance & Notes

This is not a dengue paper. It is ingested as a methodological reference — the second study-design paper alongside [[Pearce2016 - Analysis of Matched Case-Control Studies]]. Together these two papers provide the framework for evaluating matched study designs used in dengue research, particularly age-matched case-control designs in the curator's own ANA IIF abstract and in published dengue studies (e.g., [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]]).

The paper is published in Annals of Clinical Epidemiology (a Japanese clinical epidemiology journal) and is part of a seminar series on epidemiological methods. Iwagami is affiliated with the London School of Hygiene and Tropical Medicine and the University of Tsukuba; Shinozaki is at the Tokyo University of Science.

**Limitations:** The paper is a tutorial, not original research. The worked examples are conceptual, not data-driven. The discussion of propensity score matching and risk set sampling is introductory — these topics each have extensive dedicated literatures. The claim that unconditional logistic regression is "not recommended" for matched case-control data is stated without worked demonstration (unlike Pearce2016, which provides a numerical example showing unconditional analysis works).

## Questions Raised

- The Pearce2016/Iwagami2022 disagreement on unconditional logistic regression for matched case-control data is unresolved. Which position is adopted in practice in dengue epidemiology? A survey of analytical methods in dengue case-control studies would clarify whether this debate is practically consequential.
- Over-matching is described conceptually but not illustrated with dengue examples. In dengue case-control studies matching on age + sex + hospital admission date + neighborhood, is over-matching a plausible concern?
- Risk set sampling (incidence density sampling) is mentioned as producing rate ratios rather than odds ratios. Are any dengue case-control studies using this design, and are they correctly interpreting their effect measures?
