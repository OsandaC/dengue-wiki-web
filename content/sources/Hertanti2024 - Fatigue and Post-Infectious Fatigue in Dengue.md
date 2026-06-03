---
type: source
tags: [fatigue, post-infectious-fatigue, PIF, post-dengue-syndrome, meta-analysis, systematic-review, prevalence, risk-factors, female-sex, DHF, comorbidities, heterogeneity, prediction-interval, autoimmunity, Sri-Lanka, host-factors, sex-bias, convalescence]
authors: [Hertanti NS, Nguyen TV, Chuang YH]
year: 2024
journal: eClinicalMedicine
doi: 10.1016/j.eclinm.2024.103041
citations_semantic_scholar: 7
citations_crossref: 9
citations_retrieved: 2026-06-03
created: 2026-06-03
updated: 2026-06-03
---

# Hertanti2024 - Fatigue and Post-Infectious Fatigue in Dengue

**Full citation:** Hertanti NS, Nguyen TV, Chuang Y-H. Global prevalence and risk factors of fatigue and post-infectious fatigue among patients with dengue: a systematic review and meta-analysis. *eClinicalMedicine.* 2025;80:103041. (Published online 31 December 2024.) doi:10.1016/j.eclinm.2024.103041. PROSPERO CRD42024543058. Open access (CC BY-NC-ND).

**Raw file:** `[[raw/Hertanti2024.pdf]]`

## Summary

This is the first systematic review and meta-analysis to quantify the global prevalence and risk factors of **fatigue** (acute phase) and **post-infectious fatigue** (PIF; persisting beyond the acute phase, defined here as 2 weeks to ≥6 months) among dengue patients. From 715 records across five databases (inception to 22 June 2024), 40 observational studies were included: 37 contributed to the fatigue prevalence pool (37,790 patients) and 9 to the PIF prevalence pool (5045 patients). A random-effects model (arcsine square-root transformation for fatigue, owing to non-normality) yielded a pooled **acute-fatigue prevalence of 59.0% (95% CI 47–70%)** and **PIF prevalence of 20.0% (95% CI 10–36%)**.

Both pooled estimates carry **extreme heterogeneity** (fatigue I²=99.90%, Q=32026.88; PIF I²=98.77%, Q=649.05) and — critically — **prediction intervals that span almost the entire possible range** (fatigue PI [0.03; 1.00]; PIF PI [0.02; 0.77]). The point estimates are therefore best read as "fatigue is common and PIF is frequent," not as precise rates: the next dengue cohort could plausibly report anywhere from near-zero to near-universal fatigue. No moderator explained the fatigue heterogeneity; for PIF, study design and mean age were significant moderators (older age → higher PIF).

For PIF, three risk factors reached pooled significance: **female sex (OR 1.65), dengue haemorrhagic fever (DHF) (OR 1.80), and pre-existing comorbidities (OR 2.14)**. The authors list four *hypothesized* mechanisms for post-viral fatigue carried over from the broader literature — viral persistence, **autoimmunity**, immune dysfunction, and autonomic dysregulation — and sketch an estrogen→B-cell-activation→autoantibody→fatigue chain to explain the female-sex association, but explicitly state this "requires further confirmation." **The study measures no antinuclear antibodies and no autoantibodies of any kind.** Its value to this wiki's primary thread is precisely that: it is the largest synthesis of the *fatigue bank* and it names the ANA↔fatigue link as a hypothesis, leaving it untested — it defines the gap rather than filling it.

## Study Design
- **Type:** Systematic review and meta-analysis of observational studies (PRISMA 2020; PROSPERO-registered). Pooled prevalence (random-effects, DerSimonian-Laird via R `meta`/`metafor` v4.3.3); risk-factor pooling (ORs, ≥2 studies required); meta-regression; sensitivity, subgroup, and publication-bias analyses.
- **Sample size:** 40 studies / 38,406 dengue patients overall; fatigue pool 37 studies (37,790 patients); PIF pool 9 studies (5045 patients). Risk-factor pools: 2–3 studies each.
- **Setting:** Global. Included studies predominantly Asian (n=25, 62.5%), then South America (n=7, 17.5%), Africa (n=4, 10.0%), Europe (n=3, 7.5%), North America (n=1, 2.5%). PIF pool heavily Sri Lanka– and Singapore-dominated.
- **Population:** Dengue patients across all phases; 48.2% female, mean age 40.9 (SD 18.5) overall; PIF subset younger (mean 29.5, SD 13.7) and 50.8% female. Fatigue measured by clinical symptoms in 35/40 (87.5%) studies and by a validated fatigue questionnaire in only 5/40 (12.5%).
- **Risk of bias:** Hoy's tool — 3 studies low (7.5%), 28 moderate (70.0%), 9 high (22.5%).

## Key Findings

- **Acute fatigue is common but the rate is imprecise:** pooled prevalence **59.0% (95% CI 47–70%)**, but I²=99.90% and the **prediction interval is [0.03; 1.00]** (Fig 2). The 95% CI describes the precision of the *mean*; the prediction interval describes where a *new study* would fall — and here it is essentially uninformative (≈3–100%). Every downstream use of "59%" must carry this caveat.
- **PIF is frequent but equally heterogeneous:** pooled **20.0% (95% CI 10–36%)**, I²=98.77%, **prediction interval [0.02; 0.77]** (Fig 3). Sensitivity analyses (excluding 9 high-risk-of-bias studies → 58.0%; excluding small studies → 61.0%; PIF leave-one-out 18.0–27.0%) confirm the point estimate is robust *to study removal* — but robustness of a central estimate does not narrow the prediction interval.
- **Significant PIF risk factors (pooled):**
  - **Female sex — OR 1.65 (95% CI 1.27–2.14), p=0.0002, I²=0.00** (3 studies: Seet2007, Perera2023, Abeysena2019). Zero heterogeneity; a *modest* effect.
  - **DHF — OR 1.80 (95% CI 1.02–3.16), p=0.042, I²=18%** (2 studies). Borderline; carried by Perera2023 (1.58, 1.04–2.40, significant); Sigera2021 (3.43, 0.92–12.76) is individually non-significant.
  - **Pre-existing comorbidities — OR 2.14 (95% CI 1.36–3.38), p=0.001, I²=0.00** (2 studies).
- **Non-significant PIF risk factors (pooled):** older age (2.03, 0.58–7.14; I²=92.5%), post-discharge myalgia (1.82, 0.66–5.05; I²=81%), post-discharge headache (1.16, 0.41–3.31; I²=82%). Individual studies are sometimes significant in opposite directions; the pools are null.
- **Acute-fatigue × DHF is null and contradictory:** pooled OR 1.29 (0.43–3.88), p=0.65, I²=93.5% — driven by **Ferreira2018 (2.31, harmful) vs Recker2024 (0.75, protective)**, two large studies pointing opposite ways. This is the single sharpest illustration that **dengue severity has no consistent relationship to fatigue** in the current literature.
- **⚠ Table 2 internal error (verified against the PDF):** the female-sex row prints **Seet2007's OR as "9.69" but with CI "0.78–4.01"** — a point estimate that cannot lie inside its own interval, and incompatible with the pool's I²=0.00 across {Seet, Perera 1.82, Abeysena 1.50}. The reliable figure is the **pooled 1.65**; Seet's unadjusted contribution is ≈1.7 (95% CI 0.78–4.01, non-significant alone). The "9.69" is a transcription of Seet2007's own *adjusted multivariate* OR (9.687, CI 1.546–60.684), a sparse-data artifact — see [[Seet2007 - Post-Infectious Fatigue Syndrome in Dengue]]. **This corrects the prior wiki framing** of 9.687 as a robust "outsized" female effect.
- **PIF measurement depends on the instrument:** clinical-symptom checklists detected PIF in only 12.6% of cases vs 29.5% with validated fatigue questionnaires (subgroup difference not statistically significant, but directionally large) — mirroring post-COVID data (47.5% by questionnaire vs 43.2% by checklist). Fatigue prevalence is plausibly *underestimated* in the 87.5% of studies relying on clinical symptoms.
- **Benchmarking:** PIF 20.0% is similar to post-Q-fever chronic fatigue, and lower than post-COVID fatigue in the first 6 months (41.0–46.6%).

## Methods Used
- [[Prevalence Meta-Analysis under Heterogeneity]] — random-effects pooling of prevalence under extreme between-study heterogeneity; this paper is the worked example for why the prediction interval, not I² alone, governs interpretation.

## Entities Mentioned
*(None at the entity level. The meta-analysis is serotype-agnostic — it pools across all DENV serotypes and reports no serotype-specific fatigue data, so no serotype entity pages are updated.)*

## Concepts Addressed
- [[Post-Dengue Syndrome]] — quantifies the fatigue/PIF bank of post-dengue sequelae and its risk factors.
- [[Autoimmunity in Dengue]] — names autoimmunity as one of four *hypothesized* PIF mechanisms; supplies the meta-analytic correction to the Seet2007 female-sex OR.
- [[Antinuclear Antibodies]] — gap marker: the largest fatigue synthesis in dengue measures **no** ANA.

## Relevance & Notes

This paper is pivotal for the wiki's primary thread — *is there a correlation between ANA and chronic fatigue in dengue?* — but its contribution is to **define the gap, not close it**:

1. **It quantifies the fatigue bank.** Before this, the fatigue side of the bridge rested on single cohorts (Seet2007 24.4% at 2 months; Garcia2009 asthenia 23.0% at 2 years). Hertanti2024 establishes that acute fatigue (~59%) and PIF (~20%) are common across 40 studies — but with prediction intervals so wide that the *rate* is almost uninformative; what is solid is the *qualitative* claim that fatigue is a major post-dengue burden.
2. **It corrects the "shared confounder" framing.** The wiki's ANA↔fatigue logic leans on female sex being a strong driver of *both* outcomes (the "shared signal = shared confounder" argument). Hertanti2024 deflates the fatigue half: the cross-study female→PIF effect is a **modest, precise 1.65 (I²=0.00)** — not the dramatic 9.687 that the single Seet2007 multivariate model produced. Sex remains a confounder to control, but it is a smaller lever than the prior framing implied. The mandatory-control-for-sex lesson from the methodology thread (see [[Methodology Critique - ANA IIF Abstract Draft]]) still holds, but the expected effect size is recalibrated downward.
3. **It names autoimmunity but tests nothing.** Autoimmunity is 1 of 4 mechanisms the authors list, and the estrogen→B-cell→autoantibody→fatigue chain is flagged "requires further confirmation." Zero ANA, zero autoantibodies are measured. So even the field's largest fatigue synthesis leaves the ANA↔fatigue correlation untested — confirming this is genuinely open territory rather than a settled negative.
4. **It reinforces severity-independence.** The null/contradictory DHF×acute-fatigue result (Ferreira 2.31 vs Recker 0.75, pooled NS) is consistent with the wiki's existing cross-cohort finding that DF-vs-DHF severity does not predict post-dengue sequelae (see [[Post-Dengue Syndrome]], [[Seet2007 - Post-Infectious Fatigue Syndrome in Dengue]], [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]]). The borderline DHF→*PIF* signal (1.80) is a tension to hold, not a reversal — it rests on 2 studies, one non-significant.

**Limitations (author-stated and curator-noted):** (1) extreme, largely unexplained heterogeneity; (2) 87.5% of studies used non-standardised clinical-symptom assessment, likely under-detecting fatigue; (3) most studies moderate risk of bias; (4) risk-factor pools are tiny (2–3 studies) and dominated by a small set of Sri Lankan cohorts (Abeysena2019, Sigera2021, Perera2023, Umakanth2018), limiting generalisability and raising a single-setting-cluster concern; (5) no inverse-probability weighting for population differences; (6) the Table 2 transcription error noted above.

## Questions Raised
- Does ANA-positivity track PIF at the *individual* level once sex and age are controlled? Hertanti2024 cannot say — it pools study-level prevalences and measures no ANA.
- Which fatigue instrument should the wiki privilege? The 12.6% (clinical symptoms) vs 29.5% (validated questionnaire) gap means cross-study fatigue rates are not comparable without harmonising the measure — directly relevant to aligning Seet2007 (FQ), Gawali2021, and Garcia2009.
- Is the borderline DHF→PIF signal (1.80, 2 studies) real, given that DHF→*acute*-fatigue is null and contradictory? A cohort co-measuring acute severity and PIF trajectory would resolve whether severity acts only on the persistent phase.
- The PIF risk-factor evidence is geographically narrow (Sri Lanka–heavy). Do the female/DHF/comorbidity associations replicate outside South Asia?
