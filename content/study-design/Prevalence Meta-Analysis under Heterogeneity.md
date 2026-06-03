---
type: study-design
tags: [meta-analysis, prevalence, heterogeneity, prediction-interval, I-squared, random-effects, systematic-review, biostatistics, study-design, publication-bias, arcsine-transformation]
created: 2026-06-03
updated: 2026-06-03
sources: 1
---

# Prevalence Meta-Analysis under Heterogeneity

## Overview

A **prevalence meta-analysis** pools the proportion of a population with a condition (e.g., the fraction of dengue patients reporting fatigue) across multiple observational studies. Unlike a meta-analysis of treatment effects — where studies estimate a shared underlying contrast — prevalence estimates are exquisitely sensitive to *who was sampled, when, with what instrument, and under what case definition*. As a result, prevalence meta-analyses routinely exhibit **extreme between-study heterogeneity**, and the central pooled estimate can be a misleading summary of a distribution that is in fact extremely wide.

This page exists because reading such a meta-analysis correctly is a recurring need in this wiki: the curator's ANA↔fatigue thread leans on prevalence figures (acute fatigue ~59%, PIF ~20%) drawn from exactly this kind of synthesis. The single most important interpretive move is to **read the prediction interval, not just the confidence interval or I²**.

## Key Principles

### Confidence interval ≠ prediction interval

These answer different questions and are routinely confused:

- The **95% confidence interval (CI)** describes the precision of the *pooled mean* — how well we have estimated the average prevalence across the studies we have. It narrows as more studies (more total weight) are added, even when the studies disagree wildly.
- The **95% prediction interval (PI)** describes where the *true prevalence of a new, as-yet-unseen study* would plausibly fall. It incorporates the between-study variance (τ²) directly and does **not** shrink toward zero as studies accumulate; under high heterogeneity it can span almost the entire 0–1 range.

Under a random-effects model, when heterogeneity is large, the CI can look reassuringly tight while the PI reveals the pooled mean is almost uninformative about any individual setting. **Always report and reason from the PI when heterogeneity is high.**

### I² describes consistency, not magnitude

I² is the proportion of total variance attributable to between-study heterogeneity rather than sampling error. It is widely cited but widely over-interpreted:

- I² near 100% (common in prevalence syntheses with large samples) means studies are highly *inconsistent* — but I² alone says nothing about *how spread out* the prevalences are on the absolute scale. A high I² with clustered estimates and a high I² with estimates ranging 3–100% look identical in I² but mean very different things.
- I² mechanically inflates with study size: with large samples, sampling error shrinks, so almost all remaining variance is "between-study," pushing I² toward 100% even when the practical spread is modest. **Pair I² with τ² and the prediction interval** to recover the absolute scale.

### Random-effects pooling and variance-stabilising transformation

Prevalence data are bounded in [0,1] and non-normal, especially near 0 or 1. Standard practice (and the practice in the source paper below) is to apply a **variance-stabilising transformation** — typically the **arcsine (Freeman-Tukey double-arcsine or simple arcsine square-root)** — pool on the transformed scale with a random-effects model (DerSimonian-Laird or REML estimation of τ²), then back-transform. This avoids CIs that overshoot the [0,1] bounds and stabilises the contribution of studies with extreme proportions.

### Robustness of the mean ≠ narrowness of the prediction interval

Sensitivity analyses (leave-one-out, excluding high-risk-of-bias or small studies) test whether the *pooled mean* is driven by particular studies. A mean that survives these tests is "robust" — but this is a statement about the central estimate only. **It does not narrow the prediction interval and does not make the pooled rate transferable to a new setting.** A common error is to read "sensitivity analysis confirmed robustness" as licence to quote the point estimate without its heterogeneity caveat.

### Moderator / meta-regression analysis and its limits

When heterogeneity is high, subgroup and meta-regression analyses attempt to explain it via study-level covariates (continent, study design, mean age, case definition). Two cautions: (1) with few studies per covariate level, these analyses are underpowered and prone to false negatives ("no significant moderator" ≠ "no real moderator"); (2) study-level associations are vulnerable to **ecological bias** and must not be read as individual-level effects.

### Publication bias under heterogeneity

Funnel-plot asymmetry and Egger's test are standard, but in prevalence meta-analyses asymmetry often reflects genuine heterogeneity (true prevalence varying with study size/setting) rather than selective publication. Trim-and-fill "corrections" should be treated as sensitivity analyses, not definitive adjustments.

## Worked Example: Hertanti2024 (dengue fatigue / PIF)

[[Hertanti2024 - Fatigue and Post-Infectious Fatigue in Dengue]] is a clean illustration of every principle above:

| Quantity | Acute fatigue (37 studies) | PIF (9 studies) |
|---|---|---|
| Pooled prevalence (random-effects) | 59.0% | 20.0% |
| 95% **confidence** interval | 47–70% | 10–36% |
| 95% **prediction** interval | **[0.03; 1.00]** | **[0.02; 0.77]** |
| I² | 99.90% | 98.77% |
| τ² (arcsine scale) | 0.12 | 1.05 |

- The CIs (47–70%, 10–36%) look like ordinary, usable estimates. The **prediction intervals reveal the truth**: a new dengue cohort could report anywhere from ~3% to ~100% acute fatigue, or ~2% to ~77% PIF. The pooled means are therefore valid as the qualitative claims *"fatigue is common"* and *"PIF is frequent,"* but **not** as transferable rates for any specific clinic.
- The authors note "sensitivity analysis confirmed robustness" — true for the *mean* (leave-one-out PIF stayed 18–27%), but the PI is unaffected. The correct reading keeps the heterogeneity caveat attached to every citation of 59% / 20%.
- No moderator explained the fatigue heterogeneity; study design and mean age were significant for PIF — but on only 9 studies, both the null (fatigue) and the positive (PIF) moderator findings are fragile.
- Measurement heterogeneity is partly mechanistic, not noise: clinical-symptom checklists found PIF in 12.6% vs 29.5% by validated questionnaire — a case-ascertainment difference that *should* be modelled as a moderator rather than buried in τ².

**Practical takeaway for this wiki:** when the ANA↔fatigue thread cites "59% of dengue patients experience fatigue," it must do so as "common, but with a prevalence so heterogeneous (PI 3–100%) that it cannot be pinned to a rate" — and the same discipline applies to any future prevalence figure ingested into the fatigue or ANA banks.

## Relationship to Other Study-Design Pages

This page covers **synthesis-level** design (how to pool and read prevalence across studies); [[Age-Matched Case-Control Analysis]] covers **primary-study** design (how to match and analyse a single case-control study). They are complementary lenses on the same epistemic problem — making a number mean what it appears to mean. Both feed the curator's methodological scrutiny of the ANA IIF abstract (see [[Methodology Critique - ANA IIF Abstract Draft]], [[Dengue vs Healthy Controls - Analysis Methods Workflow]]).

## Related Pages
- [[Age-Matched Case-Control Analysis]]
- [[Hertanti2024 - Fatigue and Post-Infectious Fatigue in Dengue]]
- [[Post-Dengue Syndrome]]
- [[Methodology Critique - ANA IIF Abstract Draft]]

## Sources
- [[Hertanti2024 - Fatigue and Post-Infectious Fatigue in Dengue]] (worked example: dengue fatigue 59% [PI 0.03–1.00] and PIF 20% [PI 0.02–0.77] under I²≈99%; arcsine transformation; random-effects pooling; moderator and sensitivity analyses)
