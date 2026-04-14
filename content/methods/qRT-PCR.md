---
type: method
tags: [diagnostics, viremia, PCR, molecular-detection, acute-phase]
created: 2026-04-12
updated: 2026-04-12
sources: 1
---

# qRT-PCR

## Overview

Quantitative reverse transcription polymerase chain reaction (qRT-PCR) is the gold-standard method for detecting and quantifying DENV RNA in clinical samples during the acute phase of infection. The method converts viral RNA to cDNA (reverse transcription), then amplifies a target sequence with fluorescent detection to generate a quantitative readout (viral load in copies/mL or genome equivalents/mL).

In dengue, qRT-PCR is most sensitive during the first 5 days of illness (viraemia window), before viremia declines and antibodies rise. It can detect all four DENV serotypes and, with serotype-specific primers, can distinguish between them. It is the primary method used for:
- Confirming DENV infection in research and clinical settings
- Quantifying viremia (viral load) as a study matching/stratification variable
- Defining asymptomatic infections by presence of DENV RNA without symptoms
- Identifying the serotype of infecting strain

## Key Points from Literature

**Role in asymptomatic dengue identification:** Sungnak2025 (see [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]) used qRT-PCR of plasma samples to detect DENV RNA in household members of symptomatic cases, taken every 2–3 days. Asymptomatic dengue was defined as detectable DENV RNA without any dengue-related symptoms over a 2-week follow-up. This approach identified 8 viremic asymptomatic individuals from 179 household members — illustrating the challenge of acquiring such samples (4.5% capture rate from a carefully monitored prospective cohort).

**Viremia matching:** In Sungnak2025, viremia measured by qRT-PCR on the day of enrollment was used as a key matching variable across the three severity groups (AD, DF, DHF), ensuring that observed immune differences were not attributable to differences in viral burden. No significant difference in viremia between groups was found (Kruskal-Wallis test).

**Limitations for viremia characterisation in asymptomatic infections:** Because asymptomatic individuals have no symptoms to anchor the timing of sampling, the relationship between sample collection day and peak viremia is unknown — a confound acknowledged in Sungnak2025. Asymptomatic dengue also tends to have lower viremia and different infection kinetics than symptomatic dengue.

**NS1 rapid test comparison:** The lower sensitivity of the NS1 antigen rapid test (relative to qRT-PCR) in detecting asymptomatic dengue is noted in Sungnak2025 as a barrier to population-level surveillance of asymptomatic infections. qRT-PCR remains the reference standard.

## Contradictions & Debates

None currently in this wiki. Note that DENV RNA cannot be detected by standard scRNA-seq library preparation (oligo(dT) primed) because DENV genomic RNA lacks a polyadenylate tail — making qRT-PCR of plasma the necessary parallel assay for viremia quantification in single-cell studies (see [[Single-Cell RNA Sequencing]]).

## Related Pages

- [[Single-Cell RNA Sequencing]]
- [[PRNT]] (used alongside qRT-PCR for primary/secondary infection classification)
- [[Asymptomatic Dengue Infection]]

## Sources

- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]
