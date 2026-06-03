---
type: analysis
tags: [methodology, study-design, case-control, matching, biomarker, workflow, conditional-logistic-regression, confounding]
created: 2026-05-25
updated: 2026-05-25
---

# Dengue vs. Healthy Controls — Analysis Methods Workflow

## Research Question

What is a defensible, step-by-step workflow for designing, matching, analysing, and reporting a case-control study comparing biomarker prevalence (e.g., ANA, autoantibodies, cytokines) between dengue patients and healthy controls?

This workflow synthesises the methodological prescriptions from [[Methodology Critique - ANA IIF Abstract Draft]] and the epidemiological frameworks of [[Pearce2016 - Analysis of Matched Case-Control Studies]] and [[Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies]], structured as an operational checklist. It is not a theory page — for the underlying rationale, see [[Age-Matched Case-Control Analysis]].

## Sources Used

- [[Pearce2016 - Analysis of Matched Case-Control Studies]]
- [[Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies]]
- [[Methodology Critique - ANA IIF Abstract Draft]]
- [[Tan1997 - ANA Range in Healthy Individuals]], [[Satoh2012 - ANA Prevalence in United States]], [[Dinse2022 - Increasing ANA Prevalence in United States]] — sex as confounder for ANA
- [[Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections]], [[Codes2002 - Autoantibodies in Acute Viral Hepatitis]] — febrile-control baselines
- [[Vo2020 - Autoantibody Profiling in Dengue]] — primary/secondary infection stratification
- [[Chatterjee2024 - ANA Detection in Dengue Kolkata]] — febrile-control comparator design

## Synthesis

### Phase 1 — Study Design

#### Step 1.1: Define the primary comparison and pre-specify the analysis plan

Before any data collection, state in writing:

- **Primary comparison:** Dengue cases vs. healthy controls on one named biomarker (e.g., ANA positivity at a specified dilution).
- **Primary statistical test:** Conditional logistic regression, treating each matched set as a stratum. This is the only analytical method endorsed by *both* Pearce2016 and Iwagami2022 for matched case-control data — it sidesteps their disagreement on unconditional approaches entirely.
- **All other comparisons** (subgroup by severity, subgroup by serotype, pattern distribution, secondary biomarkers) are declared **exploratory** at this stage. They will be reported as hypothesis-generating, not confirmatory.

**Failure mode prevented:** Overclaiming subgroup findings as primary results; dual-reporting of valid and invalid tests (Critique Issue 5, Issue 8).

#### Step 1.2: Choose the matching strategy

- **Match on age AND sex.** Sex is a mandatory matching variable for any biomarker with known sex-dependent prevalence — ANA prevalence is 2–3× higher in females across all population studies (see [[Tan1997 - ANA Range in Healthy Individuals]], n=15 labs; [[Satoh2012 - ANA Prevalence in United States]], n=4754 NHANES; [[Dinse2022 - Increasing ANA Prevalence in United States]], n=14,211 NHANES trend). Matching on age alone while sex is unmeasured or unbalanced is a fatal confound for any biomarker with known sex-dependent prevalence.
- **Do not over-match.** Matching on age + sex is sufficient for most dengue case-control designs. Adding hospital admission date, neighbourhood, or admission ward introduces over-matching risk — reducing informative discordant pairs without improving validity (see [[Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies]]).

**Failure mode prevented:** Sex confounding producing or masking the entire primary result (Critique Issue 1).

#### Step 1.3: Choose the matching ratio — target 1:2 or higher

- Use **1:2 or 1:3 matching** from the available control pool. Each additional control per case adds statistical power (with diminishing returns beyond 1:4 per [[Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies]]).
- 1:1 matching should only be used if the control pool is genuinely constrained to one control per case. Do not default to 1:1 when a larger pool is available.
- A higher matching ratio also makes the matching algorithm more forgiving in constrained age strata — if controls are sparse in a particular age range, having 2–3 match slots per case reduces the probability of unmatchable cases.
- **Variable matching ratios** (some cases matched 1:2, others 1:3) are analytically valid under conditional logistic regression. There is no requirement for uniform ratios.

**Failure mode prevented:** Discarding available controls unnecessarily; fragile matching in constrained age strata causing high case dropout (Critique Issues 3, 4).

#### Step 1.4: Plan a febrile-control arm (if the research question concerns dengue-specific effects)

If the study claims that dengue *specifically* drives biomarker elevation (rather than acute viral infection generically), a healthy-control arm alone is insufficient.

- **Minimum:** Healthy controls (establishes that dengue exceeds background).
- **Recommended:** Healthy controls + febrile non-dengue controls (establishes how much of the signal is dengue-specific vs. generic acute-viral).
- **Baseline reference:** ANA positivity during acute viral infections runs ~20% at ≥1:40 (see [[Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections]], n=88 infected; [[Codes2002 - Autoantibodies in Acute Viral Hepatitis]], 20.5% at ≥1:40, n=156). At ≥1:80 the hepatitis baseline drops to 4.5% (Codes2002). Dengue ANA rates must be benchmarked against these figures, not against zero.
- [[Chatterjee2024 - ANA Detection in Dengue Kolkata]] is an example of this design: 10.3% ANA in dengue-negative febrile controls, providing a disease-specific denominator.

**Failure mode prevented:** Attributing a generic acute-infection biomarker signal to dengue specifically (Critique Issue 6).

#### Step 1.5: Stratify by primary vs. secondary infection (if feasible)

If acute/convalescent paired sera or IgM/IgG ratio data are available for the dengue cases:

- Classify cases as primary or secondary infection.
- Include infection order as a covariate in the conditional logistic regression model (Step 3.1).
- **Rationale:** [[Vo2020 - Autoantibody Profiling in Dengue]] demonstrates that primary dengue infection produces broader IgG autoantibody repertoires than secondary — an inversion of severity-centric expectations. Failure to stratify means any DF > DHF biomarker trend could reflect infection order rather than severity.

If infection-order data are unavailable, acknowledge this explicitly as a confound in the methods section (not buried in limitations).

**Failure mode prevented:** Infection-order confounding of severity subgroup comparisons (Critique Issue 7).

---

### Phase 2 — Recruitment and Matching Execution

#### Step 2.1: Recruit controls to cover the full case age range

Before matching, verify that the control pool covers every age stratum represented in the cases. If the cases span ages 18–40, ensure controls are recruited across that full range — not concentrated in a narrower band.

- Sparse control coverage in any age stratum will cause case dropout during matching.
- Case dropout is not random: it systematically removes cases from the underserved stratum, creating a matched cohort that no longer represents the full case population.

#### Step 2.2: Execute matching and report dropout

- Match cases to controls using the pre-specified criteria (age ± tolerance, sex).
- **Report:**
  - Total cases available, total matched, total unmatched.
  - The demographic profile (age distribution, sex) of matched vs. unmatched cases.
  - Biomarker positivity in matched vs. unmatched cases — this comparison is mandatory, not optional.
- If >20% of cases cannot be matched, the matched cohort's generalisability to the full case population is compromised. State this in the methods section.

**Failure mode prevented:** Silent exclusion of a demographic stratum; matched cohort not representative of the source case population (Critique Issue 4).

---

### Phase 3 — Analysis

#### Step 3.1: Primary analysis — conditional logistic regression

- Run conditional logistic regression with each matched set as a stratum.
- Include age as a continuous covariate (to address mixed-precision matching, e.g., exact-age and ±1-year matches within the same dataset).
- If sex data were available but not used for matching, include sex as a covariate.
- Report: adjusted OR, 95% CI, p-value.

**Why conditional logistic regression, not McNemar's or Fisher's:**
- McNemar's exact test is valid for matched binary data but cannot incorporate covariates. For a study with a single binary outcome and no covariates, it is acceptable as a confirmatory secondary analysis.
- Fisher's exact test ignores the matched structure entirely. Per both [[Pearce2016 - Analysis of Matched Case-Control Studies]] and [[Iwagami2022 - Introduction to Matching in Case-Control and Cohort Studies]], applying Fisher's to matched data leaves matching-induced selection bias uncontrolled. **Do not report Fisher's on matched data.**
- Conditional logistic regression handles variable matching ratios, mixed matching precision, and additional covariates cleanly. Both Pearce2016 and Iwagami2022 agree it is always valid.

#### Step 3.2: Subgroup analyses (exploratory)

All subgroup comparisons (e.g., DF vs. controls, DHF vs. controls, DF vs. DHF) are pre-declared exploratory (Step 1.1).

- Run conditional logistic regression within each subgroup if matched sets can be preserved.
- If subgroup analyses break matched sets (e.g., analysing only DF cases and their matched controls), state the effective sample size.
- Report effect sizes and confidence intervals. Do not elevate a non-significant subgroup trend to a key finding.

#### Step 3.3: Multiple testing correction

- Pre-specify one primary comparison (Step 1.1). The primary comparison is tested at α = 0.05 without correction.
- For all exploratory comparisons, apply Benjamini-Hochberg FDR correction and report adjusted p-values alongside unadjusted values.
- Alternatively, declare a family of comparisons and apply Bonferroni correction. Either approach is acceptable; no correction at all is not.

**Failure mode prevented:** Primary result that would not survive any reasonable correction (Critique Issue 8).

#### Step 3.4: Sensitivity analyses

If there are design limitations that cannot be fully addressed (e.g., sex data partially missing, febrile controls not recruited), run sensitivity analyses:

- **Sex:** If sex is unknown for cases, compute the sex ratio among cases that would be required to nullify the primary result (a breakpoint analysis).
- **Matched vs. unmatched:** Compare biomarker prevalence in matched cases vs. unmatched cases. If rates differ significantly, qualify the primary result as applying to the matched subpopulation only.
- **Matching precision:** If a mixed matching scheme was used (exact age + ±1 year), run the analysis separately for exact matches only and compare.

---

### Phase 4 — Reporting

#### Step 4.1: Methods section must contain

- Matching criteria (which variables, what tolerance, what ratio).
- Number of cases matched and unmatched, with reasons for dropout.
- Sex distribution of both groups (if sex data are available for one group, state explicitly if they are unavailable for the other).
- Primary analytical method (conditional logistic regression), with justification for why it was chosen.
- Pre-specification statement: which comparison is primary and which are exploratory.

#### Step 4.2: Results section must contain

- Primary comparison: adjusted OR, 95% CI, p-value from conditional logistic regression.
- Subgroup comparisons: labelled as exploratory, with FDR-adjusted p-values.
- Matched vs. unmatched case biomarker comparison.
- If a biomarker pattern or subtype analysis is performed (e.g., ANA pattern distribution), report a statistical test for the observed distribution against a null model — not just a descriptive observation.

#### Step 4.3: Discussion section must address

- Whether the biomarker signal exceeds the acute-viral-infection baseline ([[Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections]], [[Codes2002 - Autoantibodies in Acute Viral Hepatitis]]), not just the healthy baseline.
- Any uncontrolled confounders (sex, infection order, unmeasured febrile-infection signal).
- The Pearce2016 caution: the matched OR is an estimate from the matched sample, not the source population. If substantial case dropout occurred, the reported OR may not generalise.

---

### ANA-Specific Addendum

For studies using ANA by indirect immunofluorescence (IIFA) as the biomarker:

1. **Screening dilution:** Use ≥1:80 per EULAR/ACR guidelines ([[Aringer2019 - 2019 EULAR ACR SLE Classification Criteria]]). This allows comparison with Dinse2022, Satoh2012, Chatterjee2024, and the Codes2002 hepatitis baseline (4.5% at ≥1:80).
2. **Substrate:** Specify the exact cell substrate (HEp-2, HEp-2000, HEp-20-10). Different substrates affect sensitivity and pattern recognition. If a non-standard substrate is used, state comparability with HEp-2 explicitly.
3. **Pattern classification:** Use ICAP nomenclature (AC-1 through AC-29). If a pattern such as AC-2 (anti-DFS70) is detected, discuss it separately from potentially pathological patterns — DFS70 is a clinical *exclusion* marker for systemic autoimmune disease, not evidence of pathological autoimmunity (see [[Chatterjee2024 - ANA Detection in Dengue Kolkata]]).
4. **Confirmatory testing:** IIFA-positive results should be confirmed with a second-line assay (LIA, ELISA, immunoblot). The IIFA-positive/LIA-negative fraction may represent polyreactive IgM amplification rather than antigen-specific autoimmunity (see [[Chatterjee2024 - ANA Detection in Dengue Kolkata]], ~66% non-confirmed; mechanistic framework in [[Zhou2007 - Polyreactive Antibodies Natural Antibody Function]]).
5. **Pattern non-overlap:** If claiming that case and control ANA patterns do not overlap, compute the probability of zero overlap under a null model (permutation test or multinomial simulation). With small samples drawing from a large pattern space (~27 ICAP designations), zero overlap by chance is non-trivial.

## Open Questions

- **Unconditional logistic regression validity:** Pearce2016 argues unconditional logistic regression adjusting for matching factors is valid when strata are not sparse; Iwagami2022 recommends against it. This workflow defaults to conditional logistic regression to sidestep the disagreement. Whether unconditional analysis would be acceptable for large dengue case-control studies with non-sparse strata remains an open question (see [[Age-Matched Case-Control Analysis]] Contradictions & Debates).
- **Severity as exposure vs. case definition:** This workflow assumes dengue status is the case definition and biomarker prevalence is the outcome. When severity (DF vs. DHF) is the exposure of interest *within* dengue cases, the matching and analytical strategy may need adaptation — particularly regarding whether matched healthy controls are even part of the relevant comparison.
- **Optimal matching tolerance for age:** The ±1-year tolerance used in the ANA IIF study is tight. Whether wider bands (±2 or ±3 years) with age as a continuous covariate in the regression would retain validity while reducing case dropout has not been formally evaluated for dengue biomarker studies.
- **Infection-order stratification sample size requirements:** Vo2020's primary group was n=6 — heavily confounded by sex and serotype. What minimum primary-infection subgroup size is needed for a reliable stratified analysis? Power calculations specific to dengue primary/secondary designs would inform this.

## Related Pages

- [[Age-Matched Case-Control Analysis]] — theory of matching and the Pearce/Iwagami debate
- [[Methodology Critique - ANA IIF Abstract Draft]] — the case study that generated this workflow
- [[ANA and Dengue - Review V2.0]] — the broader ANA-in-dengue synthesis
- [[Indirect Immunofluorescence ANA Test]] — ANA-specific methodology
- [[Polyreactive Antibodies]] — mechanistic basis for non-specific IIFA fraction
