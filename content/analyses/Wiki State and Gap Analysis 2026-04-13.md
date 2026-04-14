---
type: analysis
tags: [gap-analysis, wiki-state, research-priorities, ANA, autoimmunity, NS1, molecular-mimicry, FcγRIIa, diagnostics, geography, post-dengue]
created: 2026-04-13
updated: 2026-04-13
sources: 16
---

# Wiki State and Gap Analysis — 2026-04-13

*Curator-directed synthesis of current wiki coverage and research priorities. Supersedes [[Wiki State and Gap Analysis 2026-04-12]].*

---

## Current Wiki State

**16 sources | 64 pages total** as of 2026-04-13.

### Page Inventory

| Category | Count | Pages |
|---|---|---|
| Sources | 16 | See index |
| Entities | 11 | DENV-1/2/3/4, FcγRIIa Receptor, Aedes aegypti, Aedes albopictus, NS1 Protein, E Protein, CYD-TDV, Wolbachia |
| Concepts | 17 | Post-Dengue Syndrome, Autoimmunity in Dengue, ADE, Asymptomatic Dengue Infection, Antinuclear Antibodies, Infection-Triggered Autoimmunity, NS1 Molecular Mimicry in Dengue, T Cell Responses in Dengue, NK Cell Responses in Dengue, Type I Interferon Response in Dengue, Viraemia, Dengue Pathophysiology, Dengue Clinical Classification, Dengue Vaccine Candidates, Original Antigenic Sin, Dengue Neurological Complications, Secondary Dengue Infection |
| Methods | 11 | PRNT, ELISA Inhibition Method, FcγRIIa Genotyping, Indirect Immunofluorescence ANA Test, Single-Cell RNA Sequencing, V(D)J Sequencing, qRT-PCR, RT-PCR, NS1 Antigen Detection, IgM-IgG Serology ELISA, Line Immunoassay ANA |
| Geography | 4 | Cuba, Thailand, Taiwan, India |
| Analyses | 4 | This page, Wiki State 2026-04-12, Reading Plan, Notable Findings, ANA and Dengue — A Literature Review |
| Meta | 1 | state.md |

---

## What Changed Since 2026-04-12

The wiki grew from 9 sources / 27 pages to 16 sources / 64 pages — more than doubling — through seven ingests:

| Source | Key Contribution |
|---|---|
| [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]] | NS1 molecular mimicry mechanism; anti-platelet IgM; endothelial apoptosis + NF-κB pathways |
| [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]] | NS1 C-terminal domain (aa 311–352); PDI/vimentin/HSP60/ATP synthase β targets; WGNGCG coagulation motif; anti-prM |
| [[Guzman2016 - Dengue Infection]] | Comprehensive review; global burden; direct sNS1 TLR4/endothelial/thrombin/glycocalyx mechanisms; vaccine pipeline; vector biology |
| [[Shih2023 - Autoimmune Disease Risk After Dengue]] | Large population-based refutation of broad autoimmune risk claim; ADEM only; 51.4% misclassification rate identified |
| [[Wan2012 - Autoimmunity in Dengue Pathogenesis]] | Capstone NCKU review; autoantibody kinetics; LYRIC/RGD/capsid mimicry; intrinsic ADE–autoimmunity link |
| [[Chatterjee2024 - ANA Detection in Dengue Kolkata]] | First HEp-2 IIFA measurement in acute dengue: 54.8% IIFA, 18.5% LIA; non-specific majority; MCTD/myositis signals |
| [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]] | scRNA-seq + V(D)J in Thailand DENFREE cohort; CD8 TEM exhaustion in DHF; public BCR clonotype absent at convalescence; 120-target autoantibody panel negative |

The two top priorities from the 2026-04-12 analysis have been addressed:
- ✅ **NS1 molecular mimicry papers** — three sources (Lin2006, Lin2011, Wan2012) plus Guzman2016 now fully evidence this mechanism
- ✅ **ANA specificity in dengue** — Chatterjee2024 provides HEp-2 IIFA + LIA data, answering which specificities are elevated and how many are non-specific

One priority from 2026-04-12 remains unresolved:
- ⬜ **Bruhns et al. FcγRIIa binding affinity contradiction** — the IgG3/RR vs. HH paradox identified in [[FcγRIIa Receptor]] and [[Antibody-Dependent Enhancement]] is still unresolved; the Bruhns 2009 paper has not been ingested

Today, a comprehensive ANA literature review was completed:
- ✅ **[[ANA and Dengue - A Literature Review]]** — 15-source synthesis covering baselines, acute ANA, mechanisms, persistence, clinical outcomes, host modifiers, and 6 open questions

---

## Research Thread Summary

### Primary Thread: Autoimmunity in Dengue / ANA Dynamics

**Status: Substantially developed.** The ANA literature review now provides a complete synthesis. The central narrative is stable:

1. Dengue produces a **massive acute ANA spike** (~55% by HEp-2 IIFA), far exceeding healthy-population baselines (~13–16% at 1:80) and the generic viral-infection rate (~21.7% by narrower ELISA)
2. **~66% of this spike is non-specific** — not corresponding to disease-associated autoantibody specificities on LIA
3. **NS1 molecular mimicry** is the dengue-specific mechanism for immune-mediated platelet lysis and endothelial damage, but its established targets (PDI, vimentin, HSP60, ATP synthase β) are surface proteins, not nuclear antigens — leaving the mechanism of the HEp-2-positive nuclear ANA unexplained by mimicry alone; epitope spreading is the leading candidate
4. **Bystander activation is insufficient** to explain the ANA elevation (COVID-19 ICU null finding, Johnson2022)
5. **At the population level, dengue does not broadly elevate clinical SARD incidence** (Shih2023); only ADEM is robustly elevated, and only in the first month
6. **ANA persists at 2 years post-dengue** in symptomatic patients (Garcia2009), but the substrate incompatibility (rat liver vs. HEp-2) makes the acute-to-chronic trajectory unresolvable from current data

**What remains open:**
- The acute-to-chronic trajectory of ANA (1, 3, 6-month time points on HEp-2 not yet measured in any dengue source)
- Whether NS1 shares structural homology with nuclear antigens (not yet tested in the literature covered)
- Whether the MCTD and myositis signals in Chatterjee2024 represent genuine disease risk or LIA noise
- Whether FcγRIIa genotype predicts ANA rate/persistence, as the IC-persistence model predicts

### Secondary Thread: Asymptomatic vs. Symptomatic Dengue

**Status: Begun but thin.** Sungnak2025 is the strongest entry — scRNA-seq in the Thailand DENFREE cohort identifies CD8 TEM effector (asymptomatic) vs. exhausted (DHF) phenotypes, NK FcεRIγ signature, and a public BCR clonotype present only in symptomatic disease and absent at convalescence. Garcia2010 from Cuba provides the FcγRIIa genotype data. Only 2 dedicated sources; the thread needs population-level incidence data and broader immunological coverage.

---

## Coverage Gaps and Thin Areas

### 1. Post-Dengue Syndrome — Still Only 1 Dedicated Source

Garcia2009 remains the sole paper in this wiki directly measuring post-dengue sequelae in a follow-up cohort. Guzman2016 provides secondary coverage from a review. The core claim that autoimmune markers persist at 2 years rests on n=26 symptomatic Cuban adults, single epidemic, no contemporaneous control group for the ANA measurement.

**What to look for:**
- Any **prospective longitudinal cohort** following dengue patients ≥6 months post-recovery with standardised symptom assessment — PubMed: "post-dengue sequelae longitudinal" OR "dengue convalescence symptoms"
- **Seet et al. 2007** (*Emerg Infect Dis*) — Singapore post-dengue cohort; cognitive and fatigue sequelae; frequently cited in this area
- Any cohort with **ANA measurement at multiple time points** (acute + convalescence + 6 months) — this is the single most important methodological gap in the ANA thread

### 2. ANA Trajectory — The Core Unresolvable Gap

The most clinically significant open question is: does the acute HEp-2 IIFA spike (~55%) persist or resolve, and at what rate? No source in this wiki measures dengue ANA at more than one time point using HEp-2. Garcia2009 uses rat liver (incompatible substrate; 2-year time point only). This is structurally a single missing experiment.

**What to look for:**
- Any study measuring **serial ANA by HEp-2 IIFA in dengue patients** at acute, convalescent, and post-convalescent time points — may be in Asian rheumatology journals
- Studies examining **autoantibody persistence after arboviral infections** as a proxy (chikungunya has a better-documented post-acute arthropathy literature)

### 3. FcγRIIa — Contradiction Still Unresolved

The paradox flagged in the 2026-04-12 analysis remains: Garcia2010 identifies FcγRIIa-HH as a risk genotype for symptomatic dengue, on the rationale that HH has higher IgG1 binding affinity enabling more efficient ADE. But Bruhns et al. 2009 (*Blood*) — not yet in this wiki — shows FcγRIIa-RR has higher binding affinity for IgG3, which would predict the opposite. The [[FcγRIIa Receptor]] and [[Antibody-Dependent Enhancement]] pages flag this contradiction but cannot resolve it without Bruhns.

**Priority: medium.** The contradiction does not affect the ANA narrative but matters for the ADE mechanism and for the asymptomatic/symptomatic thread.

### 4. Geography — Four Countries, No Regional Overview Pages

Coverage: Cuba (3 sources), Taiwan (2), Thailand (1), India (1). No regional overview pages for Southeast Asia, Latin America/Caribbean, or South Asia. No coverage of the largest dengue-burden countries: Indonesia, Philippines, Brazil, Vietnam, Bangladesh.

**What to look for:**
- **Bhatt et al. 2013** (*Nature*) — the canonical global burden paper; would anchor a global geography overview and populate an Americas/Southeast Asia page simultaneously
- Any country-specific seroprevalence or epidemiology paper for a high-burden country not yet in the wiki
- **Southeast Asia** regional page could be created using Guzman2016's epidemiology section as a starting point (currently cited but no dedicated page)

### 5. Thin Entity Pages (Single Source)

| Entity | Source Count | Suggestion |
|---|---|---|
| DENV-1 | 1 | Any serotype-comparative paper would add both DENV-1 and other serotypes simultaneously |
| DENV-3 | 1 | As above |
| E Protein | 2 | Lin2011 + Guzman2016 cover the WGNGCG motif — a flavivirus E protein review would expand this substantially |
| Aedes albopictus | 1 | A vector biology / range expansion paper (albopictus is globalising) |
| CYD-TDV | 1 | Sridhar et al. 2018 (*NEJM*) — the serostatus-stratified efficacy paper; critical for the vaccine thread |
| Wolbachia | 1 | Any Wolbachia field trial paper (Moreira et al. or WMP data) |

### 6. Missing Concept Pages (Referenced But Absent)

| Concept | Referenced In | Priority |
|---|---|---|
| Cytokine Storm | Guzman2016, multiple | Medium — relevant to both pathophysiology and ADE |
| Cross-Reactive Antibodies | Johnson2022, Lin2006 | Medium — distinct from NS1 mimicry in scope |
| Herd Immunity | Guzman2016 | Low — not central to current research threads |
| Dengue Haemorrhagic Fever | Guzman2016, Lin2006 | Medium — the clinical endpoint for most mechanism work; currently covered in Dengue Clinical Classification but deserves its own page |

### 7. Diagnostics — Better Than Before, but Uneven

The method pages are now less sparse than in the 2026-04-12 state. NS1 Antigen Detection has 3 sources; IIFA and LIA are documented. However:
- **RT-PCR** has only 1 source; no paper covering the **viraemia window / PCR sensitivity timeline**
- **IgM-IgG serology** has only 1 source; no coverage of the primary vs. secondary infection serology distinction (which affects ADE interpretation)
- No paper on the **WHO Dengue Diagnostic Guidelines** or head-to-head diagnostic comparisons

### 8. Vaccine and Vector Biology — Almost Empty

The Dengue Vaccine Candidates concept page has 3 sources, but all coverage comes from Guzman2016's comprehensive review — no dedicated vaccine efficacy papers. Vector biology coverage (Aedes aegypti with 5 sources) is better, but relies on Guzman2016 for most content.

**Priority: Low** relative to the autoimmunity thread, unless the curator's focus shifts.

---

## What the ANA Thread Has and Has Not Answered

| Question | Status | Notes |
|---|---|---|
| Is dengue ANA elevated above healthy-population baseline? | ✅ Established | Both acutely (54.8% IIFA, Chatterjee2024) and at 2 years (23.1% rat liver, Garcia2009) — both exceed reference ranges |
| What proportion of dengue ANA is disease-specific? | ✅ Established | ~34% of IIFA-positives confirmed by LIA; ~66% non-specific (Chatterjee2024) |
| Which specific autoantibodies are elevated? | ⚠️ Partial | LIA shows MCTD and myositis-associated antibodies (Chatterjee2024); but wide CIs and small n; no dengue-specific HEp-2 pattern characterised |
| What mechanism drives nuclear ANA in dengue? | ⚠️ Inferred | NS1 mimicry targets surface proteins, not nuclear antigens → epitope spreading is the leading candidate; not directly demonstrated |
| Does dengue-associated ANA resolve or persist? | ❌ Open | The acute-to-chronic trajectory on HEp-2 is absent; only Garcia2009's 2-year rat liver data exists; substrate gap makes the question unresolvable from current data |
| Does dengue ANA lead to clinical autoimmune disease? | ✅ Established (population level) | Shih2023 (n=63,814): no broad SARD elevation; only ADEM in month 1 |
| Do host factors (FcγRIIa, sex) predict ANA? | ⚠️ Indirect | FcγRIIa-HH associated with post-dengue sequelae (Garcia2009); sex effect on ANA is established in healthy populations; no study directly links FcγRIIa genotype to ANA rate |

---

## Priority Order for Next Ingests

| Priority | Paper / Topic | Gap Addressed |
|---|---|---|
| 1 | Longitudinal dengue cohort with serial ANA (HEp-2, multiple time points) | The single most important missing experiment — resolves the acute-to-chronic trajectory |
| 2 | Second post-dengue sequelae cohort (e.g. Seet 2007, Singapore) | Replicates Garcia2009 in a different country/serotype; makes the post-dengue syndrome claim generalisable |
| 3 | Bhatt et al. 2013 (*Nature*) — global dengue burden | Anchors global geography; fills the largest geographic gap |
| 4 | Sridhar et al. 2018 (*NEJM*) — CYD-TDV serostatus and efficacy | The most important vaccine paper; the CYD-TDV entity page is a stub |
| 5 | Bruhns et al. 2009 (*Blood*) — FcγRIIa binding affinities | Resolves the IgG3/RR paradox flagged in FcγRIIa Receptor and ADE pages |
| 6 | Serotype-comparative dengue paper (incidence or severity by DENV-1/2/3/4) | Strengthens thin DENV-1 and DENV-3 entity pages simultaneously |

---

## Related Pages

- [[Notable Findings]]
- [[ANA and Dengue - A Literature Review]]
- [[Wiki State and Gap Analysis 2026-04-12]] *(superseded)*
- [[Autoimmunity in Dengue]]
- [[Antinuclear Antibodies]]
- [[Post-Dengue Syndrome]]
- [[NS1 Molecular Mimicry in Dengue]]
- [[FcγRIIa Receptor]]

## Sources

All 16 sources in the wiki inform this analysis. Key sources for gap assessment:
- [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]]
- [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]]
- [[Chatterjee2024 - ANA Detection in Dengue Kolkata]]
- [[Shih2023 - Autoimmune Disease Risk After Dengue]]
- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]
- [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]]
- [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]]
- [[Wan2012 - Autoimmunity in Dengue Pathogenesis]]
- [[Guzman2016 - Dengue Infection]]
- [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]]
- [[Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections]]
- [[Tan1997 - ANA Range in Healthy Individuals]], [[Satoh2012 - ANA Prevalence in United States]], [[Li2019 - ANA Epidemiology in Chinese Healthy Population]], [[Dinse2022 - Increasing ANA Prevalence in United States]], [[Aringer2019 - 2019 EULAR ACR SLE Classification Criteria]]
