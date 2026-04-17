---
type: concept
tags: [asymptomatic, subclinical, silent-infection, seroprevalence, FcgRIIa, protection, scRNA-seq, immune-profiling, CD8-T-cells, NK-cells, plasmablasts]
created: 2026-04-11
updated: 2026-04-12
sources: 5
---

# Asymptomatic Dengue Infection

## Overview
Asymptomatic (subclinical) dengue infection occurs when a person is infected with dengue virus but does not develop clinical symptoms. Such individuals are seropositive for dengue antibodies (IgM and/or high-titre IgG) despite no recorded fever or illness. The proportion of infections that are subclinical varies by setting and serotype but is substantial, meaning the true burden of dengue infection is considerably larger than reported case counts suggest. Asymptomatic infection is diagnostically important as a comparator group for understanding what determines disease outcome.

## Key Points from Literature
- In the 2006 Cuban DENV-4 epidemic, 42 asymptomatic individuals were identified from a seroepidemiological survey (relatives/neighbours of confirmed cases); all had IgG titres ≥1,280 suggestive of secondary infection without any recorded symptoms (see [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]]).
- None of the 42 asymptomatic patients reported any persistent clinical symptoms at 2-year follow-up, in contrast to 56.7% of symptomatic patients — asymptomatic infection conferred no apparent long-term sequelae (see [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]]).
- The FcγRIIa-RR genotype was significantly enriched in asymptomatic individuals (RR: 38.1%) compared to DF (26.5%) and DHF (20.7%) groups, and the HH genotype was dramatically less frequent in the asymptomatic group (9.1%) vs DF (39.4%) and DHF (51.5%) — suggesting FcγRIIa polymorphism is a genetic determinant of whether infection is symptomatic or not (see [[FcγRIIa Receptor]]).

## Single-cell immune profiling of asymptomatic dengue

Sungnak et al. (2025) produced the first single-cell RNA sequencing characterisation of the systemic immune response in viremic asymptomatic dengue, drawing from the DENFREE Thailand cohort (see [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]). Eight asymptomatic donors were identified from 179 household contacts of symptomatic index cases over 5 years — illustrating the extreme difficulty of capturing viremic asymptomatic individuals even within a purpose-designed surveillance programme (4.5% yield). Key findings:

**Cell composition:** CD8 TEM (effector memory) cells and NK cells were significantly enriched in asymptomatic donors compared with dengue fever and DHF (P < 0.05); plasmablasts were significantly enriched in symptomatic donors (P < 0.05).

**Potential protective mechanisms unique to asymptomatic dengue:**
- Enhanced MHC class I antigen presentation signals: memory B cells and CD16 monocytes show ribosomal protein changes (RPL6↑, RPS28↑, RPL28↓) predicted to favour viral peptide generation for CD8 T cell priming
- CD8 TEM cells clonally expanded (antigen-driven) and express effector molecules IFNG, TNF, GZMH, GNLY — a functional, non-exhausted profile
- IGHA1+ (IgA1) plasmablasts enriched (P < 0.05); DENV-specific IgA can neutralise virus and antagonise IgG-mediated ADE
- NK cells: FcεRIγ+/high phenotype; elevated NKG2D and NKp46 activating receptors — suggesting activated innate NK function
- No type I interferon response enrichment, no elevated plasma IFN-α2

**Comparison with symptomatic dengue:** In contrast, symptomatic donors showed FcγR/endocytosis pathway enrichment (ADE evidence), elevated IFN-α2, IL-10–driven IGHG1+ plasmablast expansion, and CD8 TEM exhaustion markers (PD-1, LAG3, TIGIT).

**Autoimmunity thread:** No significant differences in autoantibody levels (120-antigen panel) were found between asymptomatic dengue, DF, and DHF groups (see [[Autoimmunity in Dengue]]).

## Asymptomatic infection and infection parity (Guzman2016)

Guzman2016 provides epidemiological data contextualising the frequency and determinants of asymptomatic dengue at a population level (see [[Guzman2016 - Dengue Infection]]):

- **Primary infections are predominantly subclinical** in immunologically naive individuals: in the 1981 Cuban DENV-2 epidemic, among individuals with no prior dengue infection, the overt:subclinical ratio was nearly 0 (nearly all primary infections were clinically silent)
- **Secondary infections determine disease**: in the same epidemic, among individuals with prior DENV-1 exposure (secondary dengue), the overt:subclinical ratio was close to 1:1 — roughly half became symptomatic; symptomatic cases included both DF and DHF
- **3rd and 4th infections are again typically mild or asymptomatic**: after broad multi-serotype immunity develops, the balance shifts back toward subclinical infection; clinical severity peaks at 2nd infection
- This "inverted U" pattern (subclinical → clinical → subclinical as infection number rises) is a central feature of the ADE model: peak severity at 2nd infection coincides with peak cross-reactive non-neutralising antibody concentration

The implication for seroprevalence studies: measured dengue seroprevalence substantially underestimates the true number of infections (especially 1st infections, which are clinically invisible). Estimates of 390 million infections/year (of which only 96 million are symptomatic) are consistent with this pattern.

## Contradictions & Debates
- The asymptomatic group in the Cuban studies (Garcia2009, Garcia2010) was identified retrospectively by serology, not by PCR during active viremia — some truly asymptomatic pre-seroconversion infections may have been missed. Sungnak2025 confirmed viremia by qRT-PCR, providing a stricter asymptomatic definition.
- Asymptomatic individuals in Garcia2009/2010 were not tested for autoimmune markers; Sungnak2025 found no autoantibody differences across severity groups.
- The age distribution differed between the DF and DHF groups in Sungnak2025 (a limitation acknowledged by the authors). Pediatric populations — more common in dengue globally — were underrepresented.
- The exact timing of sampling relative to infection onset is unknown for asymptomatic donors in Sungnak2025 (no symptom onset to anchor to), introducing uncertainty about where in the infection course the immune snapshot was captured.

## Related Pages
- [[FcγRIIa Receptor]]
- [[Post-Dengue Syndrome]]
- [[Antibody-Dependent Enhancement]]
- [[DENV-4]]
- [[Cuba]]
- [[Thailand]]
- [[T Cell Responses in Dengue]]
- [[NK Cell Responses in Dengue]]
- [[Type I Interferon Response in Dengue]]
- [[Single-Cell RNA Sequencing]]
- [[qRT-PCR]]

## Sources
- [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]]
- [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]]
- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]
- [[Guzman2016 - Dengue Infection]] (primary infections predominantly subclinical; 3rd/4th infections mild/asymptomatic; Cuban epidemic overt:subclinical ratios)
- [[Vo2020 - Autoantibody Profiling in Dengue]] (ASD as primary comparator group; no significant difference in total IgM or IgG autoantibody load between ASD and DF/DHF patients; asymptomatic individuals identified via household cluster investigation; Cambodia 2012–2013)
