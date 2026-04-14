---
type: source
tags: [autoimmunity, NHIRD, Taiwan, population-cohort, adrenocortical-insufficiency, SLE, ADEM, vasculitis, myasthenia-gravis, TLR, NS1, aHR, retrospective-cohort, ICD-coded]
authors: [Li HM, Huang YK, Su YC, Kao CH]
year: 2018
journal: Journal of Infection
doi: 10.1016/j.jinf.2018.03.014
citations_semantic_scholar: 38
citations_crossref: 40
citations_retrieved: 2026-04-13
created: 2026-04-13
updated: 2026-04-13
---

# Li2018 - Increased Risk of Autoimmune Diseases in Dengue

**Full citation:** Li, H.M., Huang, Y.K., Su, Y.C., & Kao, C.H. (2018). Increased risk of autoimmune diseases in dengue patients: a population-based cohort study. *Journal of Infection*, 77(1), 10–17. https://doi.org/10.1016/j.jinf.2018.03.014

**Raw file:** `[[raw/li2018.pdf]]`

## Summary

Li et al. used the Taiwan National Health Insurance Research Database (NHIRD) to investigate whether dengue patients have an elevated incidence of autoimmune diseases in the 3 years following acute infection. Using a retrospective cohort design, dengue patients were identified by ICD-9 discharge diagnosis codes from hospital admissions between 2000 and 2010 and matched 1:9 to non-dengue controls. The study reported that dengue patients had an overall 1.88× elevated risk of developing autoimmune diseases (aHR 1.88; 95% CI 1.49–2.37; p<0.001), with significant associations for primary adrenocortical insufficiency, SLE, ADEM, systemic vasculitis, myasthenia gravis, and several rarer conditions.

The mechanistic explanation proposed centres on dengue NS1 protein activating TLR2/6 and TLR4 signalling. Because TLRs are expressed on adrenocortical cells, endothelial cells, and chondrocytes, the authors argue that NS1-mediated tissue-specific TLR activation could explain the broad spectrum of autoimmune targets observed — with primary adrenocortical insufficiency the most common outcome by absolute case count.

**Critical methodological context:** This paper has been directly and extensively critiqued by [[Shih2023 - Autoimmune Disease Risk After Dengue]], which used the same NHIRD but restricted to *laboratory-confirmed* dengue (63,814 cases — 5× larger) and applied Bonferroni correction for multiple comparisons. Shih2023 identified three methodological problems: (1) only 51.4% of hospitalised dengue patients in Taiwan between 2000–2010 were lab-confirmed, meaning approximately half the Li2018 "dengue" cohort may not have had dengue; (2) Li2018 did not correct for multiple comparisons when testing 20+ diseases; (3) restriction to hospitalised patients introduces selection bias. After these corrections, Shih2023 found only ADEM significantly elevated — the one disease where both papers converge.

## Study Design
- **Type:** Retrospective population-based cohort
- **Sample size:** 12,506 dengue patients; 112,554 matched controls (1:9 ratio)
- **Setting:** Taiwan NHIRD 2000–2010; 3-year follow-up period, starting 1 month after dengue diagnosis
- **Population:** Hospitalized adults and children with ICD-9 dengue discharge diagnosis codes (061, 065.4, 066.3); patients with any autoimmune disease in the 3 years prior to index date were excluded
- **Matching variables:** Age, sex, index date, Charlson comorbidity index, urbanization level
- **Outcome ascertainment:** Registry for Catastrophic Illness (specialist-validated diagnoses) or ≥3 outpatient visits with the same ICD-9 code within 1 year

## Key Findings

### Overall Risk
- **Overall autoimmune disease incidence significantly elevated in dengue cohort: aHR 1.88 (95% CI 1.49–2.37; p < 0.001)**

### Disease-Specific Risks (without multiple comparison correction)
| Autoimmune Disease | aHR | 95% CI | Dengue cases (n) |
|---|---|---|---|
| Reiter's syndrome | 14.03 | 1.84–106.89 | 1 |
| Multiple sclerosis | 11.57 | 1.40–95.69 | 1 |
| Myasthenia gravis | 5.35 | 1.55–18.50 | 4 |
| ADEM | 3.80 | 1.65–8.75 | 9 |
| Systemic vasculitis | 3.70 | 1.02–13.44 | 4 |
| SLE | 3.50 | 1.67–7.33 | 13 |
| Primary adrenocortical insufficiency | 2.05 | 1.08–3.88 | 19 |

- **Primary adrenocortical insufficiency** was the most frequent outcome by absolute case count (n=19; IR 60.8/100,000 person-years in dengue vs. 29.3/100,000 in controls)
- **ADEM** had the highest relative risk among conditions with >5 cases (aHR 3.80) — and is the one disease also significant in Shih2023 (aHR 2.72), making it the most robust cross-study finding
- **GBS was NOT significant** (aHR 0.97; 95% CI 0.41–2.30) — also non-significant in Shih2023; this null finding converges across two methodologically opposite studies

### Residual Baseline Imbalances
Despite matching, substantial group differences persisted:
- Age: dengue group mean 45.1 years vs. controls 51.1 years (dengue substantially younger)
- Sex: dengue 50.5% male vs. controls 44.5% male
- Urbanization: standardised mean differences (SMD) 0.30–0.38 across urbanization strata (SMD >0.1 is conventionally imbalanced)

These residual imbalances were acknowledged but not resolved; younger, more urban patients in the dengue group may have higher healthcare-seeking rates and therefore higher rates of incidental autoimmune diagnosis — a systematic bias toward overestimating relative risk.

### Proposed Mechanism
The authors propose a TLR-centred explanation for the broad autoimmune disease spectrum:
- Dengue **NS1 activates TLR2/6 and TLR4** → downstream cytokines (IL-6, TNF-α, IL-12, IL-1β)
- **TLRs expressed on adrenocortical cells** → NS1-mediated adrenal inflammation → primary adrenocortical insufficiency
- **TLRs on endothelial cells** → systemic vasculitis
- **TLRs on chondrocytes** → reactive arthritis (Reiter's syndrome)
- Molecular mimicry (from [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]] and [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]]) cited as an additional contributing mechanism

## Methods Used
- Administrative database linkage (Taiwan NHIRD + Registry for Catastrophic Illness + NDDCC) — not a clinical study; no laboratory data available
- Cox proportional hazards regression (adjusted HR with 95% CI and p-values)
- ICD-9-CM diagnosis code–based cohort definition
- Note: [[NS1 Antigen Detection]] was not used to confirm dengue in this study — the critical limitation identified by Shih2023

## Entities Mentioned
- [[NS1 Protein]] (TLR2/6 and TLR4 activation; proposed adrenocortical mechanism)

## Concepts Addressed
- [[Autoimmunity in Dengue]] (primary topic: population-level post-dengue autoimmune disease risk across 20 conditions)
- [[Infection-Triggered Autoimmunity]] (TLR-mediated mechanism proposed; molecular mimicry cited)
- [[Dengue Neurological Complications]] (ADEM aHR 3.80; MS aHR 11.57)
- [[Post-Dengue Syndrome]] (3-year follow-up for autoimmune sequelae)

## Relevance & Notes

Li2018 holds an important but methodologically contested place in the dengue autoimmunity literature. Its broad risk claim was widely cited and is now directly assessable from primary source data in this wiki.

**Cross-paper convergences:** The one finding that holds across Li2018 and Shih2023 is ADEM risk — relative risk estimates of 3.80 and 2.72 respectively from two completely different study designs. The one null finding that also holds across both papers is GBS (aHR 0.97 in Li2018; non-significant in Shih2023). These convergences are more methodologically robust than any finding that appears in only one study.

**What Li2018 adds beyond Shih2023:** The primary adrenocortical insufficiency finding (the most frequent outcome by case count) and the TLR/adrenocortical mechanism hypothesis are not directly addressed by Shih2023, which may have had insufficient power to detect this rarer outcome even at n=63,814. The mechanism — NS1-mediated TLR4 activation on adrenocortical cells — is plausible given established NS1-TLR4 biology (see [[Guzman2016 - Dengue Infection]]), though it remains unvalidated in any controlled experimental or larger epidemiological study.

**What this paper cannot do:** Without laboratory confirmation of dengue diagnosis, without serotype data, and without individual-level confounder adjustment beyond matching variables, Li2018 cannot establish causal links for any individual autoimmune disease.

## Questions Raised
- Does the TLR/adrenocortical mechanism hold in a properly powered, lab-confirmed cohort? Shih2023 may have been too rare-event–limited to test adrenocortical insufficiency specifically.
- If NS1-TLR4 activation causes adrenal inflammation, would serum cortisol or ACTH levels be depressed in acute dengue patients? This is a directly testable biomarker hypothesis.
- Is the ADEM convergence across Li2018 and Shih2023 the single most methodologically robust disease-specific finding in the dengue–autoimmunity literature?
- Can the null GBS finding (consistent across two studies) finally settle the GBS-dengue debate, or are case reports capturing a real but rare association below population-level detection thresholds?
