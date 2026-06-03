---
type: analysis
tags: [methodology, critique, ANA, IIFA, case-control, matching, study-design, autoimmunity, abstract-review]
created: 2026-05-25
updated: 2026-05-25
---

# Methodology Critique — ANA IIF Abstract Draft

## Research Question

Does the methodology section of the ANA IIF abstract draft (age-matched case-control study of ANA patterns in dengue fever vs. dengue hemorrhagic fever) withstand scrutiny against the epidemiological and immunological standards established in this wiki — with particular focus on the matched case-control design choices evaluated through Pearce2016 and Iwagami2022?

## Sources Used

- `raw/ANA_IIF_Abstract draft.pdf` (the abstract under review)
- [[Pearce2016 - Analysis of Matched Case-Control Studies]]
- [[Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies]]
- [[Age-Matched Case-Control Analysis]]
- [[Chatterjee2024 - ANA Detection in Dengue Kolkata]]
- [[Vo2020 - Autoantibody Profiling in Dengue]]
- [[Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections]]
- [[Codes2002 - Autoantibodies in Acute Viral Hepatitis]]
- [[Tan1997 - ANA Range in Healthy Individuals]]
- [[Satoh2012 - ANA Prevalence in United States]]
- [[Dinse2022 - Increasing ANA Prevalence in United States]]

## Synthesis

### Issue 1 — Sex confounding (FATAL FLAW)

The abstract states that **gender data were not available for the dengue cohort** and that **the control group was predominantly female**. This is not a minor limitation — it is a confounder that could produce the entire primary result.

ANA prevalence is 2–3× higher in females than males across all population studies in this wiki: Tan1997 (multicentre), Satoh2012 (NHANES), Dinse2022 (NHANES trend). If the dengue cohort is predominantly male (plausible — young adult males aged 18–34 have higher dengue exposure in many settings) while controls are predominantly female, then the observed 40.0% vs. 17.5% difference could reflect a *smaller* dengue-attributable signal than it appears — or, conversely, the true dengue signal could be *larger* if both groups were sex-balanced. The direction of the bias is unknown because the key variable is unmeasured.

**Path forward:** Recovering sex data for cases is essential. If available retrospectively, re-match on age + sex and re-analyse. If unavailable, this must be acknowledged not in the limitations paragraph but in the methods section itself, with a sensitivity analysis estimating the sex-distribution required to nullify the result (e.g., "the primary result would be confounded if >X% of cases were male").

### Issue 2 — Matching introduces confounding; analytical strategy does not adequately address it (MAJOR CONCERN)

The abstract's analytical strategy — Fisher's exact (p = 0.047) alongside McNemar's exact (p = 0.049) — is presented as dual corroboration. This framing has two problems, both grounded in the Pearce2016/Iwagami2022 framework.

**Problem 2a — Fisher's exact is invalid on matched data.** Per both [[Pearce2016 - Analysis of Matched Case-Control Studies]] and [[Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies]], matching in a case-control study introduces selection bias: controls are selected to resemble cases on age, which distorts the age–exposure relationship in the study sample. Fisher's exact test on the unpaired 2×2 table ignores the matched strata entirely and leaves this bias uncontrolled. McNemar's test accounts for the paired structure and is the appropriate 2×2 test. The two p-values are not independent corroboration — they are one valid test and one invalid test applied to the same 40-pair dataset. Presenting both inflates the impression of robustness.

**Problem 2b — Even McNemar's is suboptimal.** McNemar's test is valid but limited: it treats the matched pairs as binary strata and cannot incorporate covariates. The abstract uses a mixed matching scheme — 25 exact-age matches and 15 ±1-year matches — which is technically a mixed-precision design (see [[Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies]]). McNemar's handles this by treating all pairs as equivalent strata, but conditional logistic regression with age as a continuous covariate would be analytically cleaner. Critically, conditional logistic regression would also allow sex to be incorporated as a covariate if sex data are recovered (see Issue 1), and could accommodate severity (DF/DHF) as a covariate — eliminating the need for separate subgroup tests.

Pearce2016 demonstrates that matching can introduce confounding that did not exist in the source population: in his worked example, the crude OR in the source population was 0.86, but the crude matched OR was 1.68 — neither reflecting the true adjusted OR of 2.00. The abstract's reported ORs (3.14 unpaired, 3.25 paired) are estimates from the matched sample, not from the source population. Without conditional logistic regression or Mantel-Haenszel stratification adjusting for age at the precision used for matching, there is no guarantee these estimates are unbiased. Both Pearce2016 and Iwagami2022 agree — despite disagreeing on unconditional approaches — that conditional logistic regression is *always* valid for matched case-control data.

**Path forward:** Replace the dual Fisher/McNemar approach with conditional logistic regression as the sole primary analysis. This sidesteps the Pearce/Iwagami disagreement entirely (both endorse it), handles the mixed matching precision cleanly, and provides a natural framework for incorporating covariates (sex, severity, serotype) if data allow. Report McNemar's as a confirmatory paired analysis. Retire Fisher's from the matched comparison entirely.

### Issue 3 — 1:1 matching ratio discards statistical power unnecessarily (MAJOR CONCERN)

The study had 66 cases and 90 controls. A 1:1 matching design used only 40 of those 90 controls, leaving ~50 controls unused. Per [[Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies]], matching ratios up to 1:4 are standard practice, with each additional control adding statistical power (diminishing returns beyond 1:4). The 90-control pool could have supported 1:2 matching for most cases — and critically, a 1:2 or 1:3 design would have been more forgiving in the constrained 18–22 age range where the dropout occurred (see Issue 4). With two or three controls per case, fewer cases would have failed to find a match because the requirement is "find 2–3 controls near this age" rather than "find exactly 1 control at this exact age."

The choice of 1:1 matching simultaneously created two problems: (a) it discarded ~50 available controls, reducing the effective sample below what was available, and (b) it made the matching algorithm brittle in the youngest age stratum, causing the 39.4% case dropout described in Issue 4. A 1:2 design with the same ±1-year tolerance would likely have retained more of the 18–22-year-old cases and produced narrower confidence intervals — potentially resolving the DF-vs-controls comparison that currently sits at p = 0.055.

Per Pearce2016, one advantage of unconditional analysis is precisely that it can incorporate unmatched controls and mixed matching ratios. Even under Iwagami2022's stricter recommendation (conditional analysis only), conditional logistic regression handles variable matching ratios without difficulty. There was no analytical reason to constrain the design to 1:1.

**Path forward:** Re-match at 1:2 or 1:3 using the existing 90-control pool. If additional controls can be recruited to fill the 18–22 age gap, a 1:3 design with ≥60 matched sets would substantially improve power for the primary and subgroup analyses. Alternatively, use all 90 controls in an unconditional logistic regression adjusting for age as a continuous covariate (Pearce2016's preferred approach for non-sparse strata), though Iwagami2022 would dispute the validity of this approach for case-control data.

### Issue 4 — 39.4% case dropout from matching compromises representativeness (MAJOR CONCERN)

26 of 66 cases (39.4%) could not be matched, predominantly from the 18–22 age range. The matched cohort (mean age 26.1) is systematically older than the full case series (mean age 24.5). This is not a minor limitation — it is a direct consequence of the 1:1 ratio choice (Issue 3) interacting with a control pool that under-represents young adults.

Per Pearce2016's framework, the matched odds ratio estimates the effect *in the matched sample*, not in the source population. A matched sample that excludes 40% of cases — and those cases from a specific demographic stratum — cannot be assumed to generalise. The 18–22 age range is epidemiologically important: younger adults in dengue-endemic settings are more likely to be experiencing primary infection (see [[Vo2020 - Autoantibody Profiling in Dengue]] on primary > secondary IgG autoantibody inversion). If the unmatched younger cases have different ANA rates than the retained older cases, the primary result (40.0% vs. 17.5%) may not apply to the full dengue population the study purports to characterise.

This issue compounds with Issue 1 (sex confounding): the 18–22 age range is also the demographic most likely to be male in many dengue-endemic settings (occupational exposure, outdoor activity). If the dropped cases are disproportionately male and the retained controls are predominantly female, the matched cohort's sex imbalance may be *worse* than the full dataset's.

The abstract acknowledges the dropout in the limitations section but does not report the critical comparison: ANA positivity in matched vs. unmatched cases. This comparison is available from the existing data and requires no new recruitment.

**Path forward:** (1) Report ANA positivity in matched (n=40) vs. unmatched (n=26) cases — this is a mandatory disclosure, not an optional sensitivity analysis. (2) If rates differ, the primary result must be qualified as applying to the matched subpopulation only. (3) Re-match at 1:2 or 1:3 (see Issue 3) to recover some of the dropped cases. (4) If possible, recruit additional controls in the 18–22 age range to eliminate the structural gap in the control pool.

### Issue 5 — "DF drives the autoantibody signal" is overclaimed (MAJOR CONCERN)

The abstract elevates a non-significant result to a top-line finding. The three relevant tests:

| Comparison | Result | p-value | Significant? |
|---|---|---|---|
| DF vs. matched controls | 50.0% vs. 18.2%, OR 4.50 | 0.055 | No |
| DHF vs. matched controls | 27.8% vs. 16.7%, OR 1.92 | 0.691 | No |
| DF vs. DHF (full cohort) | 48.5% vs. 33.3%, OR 1.88 | 0.317 | No |

None of these comparisons reach significance. The abstract's third key finding — "DF drives the autoantibody signal" — and its Objective 3 ("exploring the counterintuitive possibility that milder disease may be associated with greater autoimmune activation") are not supported by the data at α = 0.05. The DF-vs-controls comparison at p = 0.055 is suggestive and may reflect insufficient power (acknowledged in the limitations), but framing it as a finding rather than a trend is overclaiming.

**Path forward:** Reframe the DF/DHF comparison as an exploratory observation: "ANA positivity was numerically higher in DF than DHF but the difference was not statistically significant. Power analysis suggests that a sample of ≥X per group would be required to detect this effect size at 80% power." Remove "DF drives the autoantibody signal" from Key Findings at a Glance.

### Issue 6 — Missing febrile-control comparator (MAJOR CONCERN)

The study compares dengue patients to *healthy* volunteers. The framing — "dengue infection itself drives autoantibody production" — assumes the relevant baseline is health. But two wiki sources establish that ANA positivity of ~20% is a generic feature of acute viral infections:

- [[Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections]]: 21.7% ANA during acute viral infections vs. 3.8% healthy controls (n=88 infected)
- [[Codes2002 - Autoantibodies in Acute Viral Hepatitis]]: 20.5% ANA in acute viral hepatitis at ≥1:40 (n=156 prospective)

The abstract's 40.0% dengue ANA rate at 1:80 exceeds these figures, but the appropriate question is *how much of the signal is dengue-specific vs. generic acute-viral*. Without a febrile non-dengue control arm, the study cannot distinguish these. Chatterjee2024 included dengue-negative febrile controls (10.3% ANA) — a better design for this question.

**Path forward:** Acknowledge the Berlin2007/Codes2002 baseline in the discussion. Frame the healthy-control comparison as establishing that dengue exceeds background autoimmunity, but note that a portion of the signal may be attributable to acute viral infection generically. Consider adding febrile non-dengue controls in the definitive study design (already mentioned in limitations).

### Issue 7 — No primary/secondary infection stratification (MODERATE CONCERN)

[[Vo2020 - Autoantibody Profiling in Dengue]] demonstrates that primary dengue infection produces *broader* IgG autoantibody repertoires than secondary infection — an inversion of severity-centric expectations. Without primary/secondary infection data on the 66 cases, the DF/DHF ANA comparison is confounded by infection order. If DF patients happen to be disproportionately primary infections (plausible — primary infections more often present as DF), the higher ANA rate in DF could reflect infection order rather than severity.

**Path forward:** If acute/convalescent paired sera or IgM/IgG ratio data exist, classify cases as primary vs. secondary and stratify. If unavailable, acknowledge this confound explicitly when interpreting the DF > DHF trend.

### Issue 8 — Multiple testing (MODERATE CONCERN)

The abstract reports one primary comparison (p = 0.047/0.049), two subgroup comparisons (DF vs. controls, DHF vs. controls), one within-dengue comparison (DF vs. DHF), pattern distribution analyses, and a DEN2/AC-10 association. No correction for multiple comparisons is applied. The primary result (p = 0.049 by McNemar) would not survive a Bonferroni correction at any reasonable family size. This does not invalidate the result, but it weakens the confidence level.

**Path forward:** Pre-specify the primary analysis (dengue vs. controls, McNemar) and declare all subgroup and pattern analyses as exploratory/hypothesis-generating. Alternatively, apply a Benjamini-Hochberg FDR correction and report adjusted p-values.

### Issue 9 — DFS70 (AC-2) interpretation (MODERATE CONCERN)

AC-2 (anti-DFS70) is listed as a "de novo autoantibody specificity" of dengue-induced autoimmunity. In clinical immunology, DFS70 is used as an *exclusion* marker for systemic autoimmune disease — its presence in isolation indicates the absence of pathological autoimmunity (see [[Chatterjee2024 - ANA Detection in Dengue Kolkata]], which uses DFS70 exactly this way). Listing AC-2 alongside AC-10 and AC-14 as evidence of "de novo autoantibody specificities" conflates a benign marker with potentially pathological ones.

**Path forward:** Discuss DFS70 separately from the other dengue-associated patterns. Frame it as evidence that dengue-associated ANA is at least partly non-pathological — consistent with the polyreactive IgM amplification model ([[Zhou2007 - Polyreactive Antibodies Natural Antibody Function]]) and the Chatterjee2024 IIFA→LIA confirmation gap. This would actually strengthen the paper's credibility by showing awareness of the clinical ANA interpretation literature.

### Issue 10 — "Complete non-overlap of repertoires" (MINOR LIMITATION)

The non-overlap finding is presented as the "most striking" result. However, 16 ANA-positive dengue patients spread across 7 ICAP patterns and 7 ANA-positive controls across 4 patterns — out of ~27 possible ICAP designations — is a very sparse multinomial distribution. The probability of zero overlap by chance alone, given two small independent samples drawing from a large pattern space, is non-trivial. Without a statistical test for the non-overlap (e.g., a permutation test or Fisher's exact on the pattern-level contingency table), this finding could be sampling noise rather than biological signal.

**Path forward:** Compute the probability of zero overlap under a null model (e.g., both groups drawing patterns independently from the same frequency distribution). If the non-overlap is significant against this null, it becomes a real finding. If not, reframe as "observed but not statistically confirmed."

### Issue 11 — HEp-20 substrate (MINOR — VERIFY)

The abstract specifies "HEp-20 cell substrate (Euroimmun AG)." The ICAP standard is HEp-2. Euroimmun's product line includes HEp-20-10 (a transfected cell line). If HEp-20 is used here, its comparability with the HEp-2 and HEp-2000 substrates used in Chatterjee2024, Tan1997, Satoh2012, and Dinse2022 should be stated explicitly, as substrate differences affect sensitivity and pattern recognition.

## What the methodology does well

These points are included for calibration — genuine strengths, not consolation:

- **Blinded single observer** with ICAP nomenclature is internally consistent and uses the current international standard for ANA pattern classification.
- **McNemar's exact test** is a valid primary analysis for matched binary data — the issue is not that it's missing, but that (a) the invalid Fisher's test is presented alongside it and (b) conditional logistic regression would be analytically stronger.
- **The 1:80 screening dilution** is appropriate per EULAR/ACR guidelines ([[Aringer2019 - 2019 EULAR ACR SLE Classification Criteria]]) and allows direct comparison with Dinse2022, Satoh2012, and Chatterjee2024.
- **The limitations section is unusually honest** — cross-sectional design, single reader, missing serotype, no longitudinal follow-up, and an explicit prescription for the definitive study are all stated. The issue is that several of these limitations (sex confounding, Fisher's validity) belong in the methods interpretation, not just the limitations.
- **The "definitive study" prescription** (≥70 controls, age+sex matching, primary/secondary stratification, 3+6 month follow-up, endpoint titration) is a reasonable design that would address most of the issues raised here.

## Summary table

| # | Issue | Severity | Fixable without new data? |
|---|---|---|---|
| 1 | Sex confounding | Fatal flaw | Possibly — if sex data can be recovered |
| 2 | Analytical strategy (Fisher's + McNemar vs. conditional logistic) | Major | Yes — replace with conditional logistic regression |
| 3 | 1:1 matching ratio discards power | Major | Yes — re-match at 1:2 or 1:3 from existing 90-control pool |
| 4 | 39.4% case dropout from matching | Major | Partially — report matched vs. unmatched ANA; re-match at higher ratio |
| 5 | DF>DHF overclaim | Major | Yes — reframe as exploratory trend |
| 6 | No febrile-control arm | Major | Partially — acknowledge Berlin2007/Codes2002 baseline |
| 7 | No primary/secondary stratification | Moderate | Possibly — if serology data allow classification |
| 8 | Multiple testing | Moderate | Yes — pre-specify and declare exploratory |
| 9 | DFS70 interpretation | Moderate | Yes — discuss separately from pathological patterns |
| 10 | Non-overlap statistics | Minor | Yes — add permutation test |
| 11 | HEp-20 substrate | Minor | Yes — clarify in methods |

## Open Questions

- If sex data are recovered and the primary result survives age+sex matching, what is the residual effect size? The current OR 3.14 may increase or decrease substantially.
- What is the ANA positivity rate in the 26 unmatched cases vs. the 40 matched cases? If these rates differ, the primary result applies only to the matched subpopulation — not the full dengue case series.
- Under 1:2 or 1:3 re-matching with the existing 90-control pool, how many of the 26 currently unmatched cases can be recovered? What is the resulting OR and p-value? This is computable from existing data.
- Does conditional logistic regression with age as a continuous covariate (rather than McNemar's pair stratification) change the OR estimate or its precision? Per Pearce2016, the matched crude OR may not equal the true adjusted OR — the current 3.14/3.25 are matched-sample estimates, not source-population estimates.
- Does the non-overlap of ANA patterns hold up under permutation testing, or is it an artefact of sparse sampling from a large pattern space?
- What proportion of the 40% dengue ANA signal is dengue-specific vs. generic acute-viral-infection signal? A febrile non-dengue control arm would answer this.
- Is the DF>DHF trend replicable in the Vo2020 framework — i.e., does DF show broader IIFA-pattern diversity than DHF, paralleling Vo2020's primary>secondary IgG autoantibody inversion?

## Related Pages

- [[Age-Matched Case-Control Analysis]]
- [[Dengue vs Healthy Controls - Analysis Methods Workflow]] — operational checklist derived from this critique
- [[Antinuclear Antibodies]]
- [[Autoimmunity in Dengue]]
- [[Indirect Immunofluorescence ANA Test]]
- [[Infection-Triggered Autoimmunity]]
- [[Polyreactive Antibodies]]
- [[ANA and Dengue - Review V2.0]]
