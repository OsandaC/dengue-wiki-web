---
type: method
tags: [autoantibody, microarray, protein-array, high-throughput, IgM, IgG, NFI, fluorescence, autoimmunity, dengue, SLE]
created: 2026-04-17
updated: 2026-04-17
sources: 1
---

# Autoantigen Microarray

## Overview
Autoantigen microarray (also called autoantibody microarray or antigen protein array) is a high-throughput method for simultaneously profiling autoantibody reactivity against hundreds of self-antigens from a single plasma or serum sample. Purified self-antigens are spotted in duplicate onto a nitrocellulose-coated slide; patient plasma is incubated with the array; bound IgG and IgM autoantibodies are detected with fluorescently labelled anti-human secondary antibodies and quantified using a laser scanner. The result is a normalized fluorescence intensity (NFI) value for each antigen–isotype combination, allowing direct comparison across patients and groups.

## Key Points from Literature

### Platform and workflow
- The platform used in dengue research (see [[Vo2020 - Autoantibody Profiling in Dengue]]) is the autoantigen microarray developed at the University of Texas Southwestern Medical Center (Zhu et al. 2015, originally validated in SLE), carrying 123 self-antigens covering nuclear proteins, basement membrane proteins, coagulation factors, complement components, and cell stress-related proteins, plus 4 control proteins — 127 spots total, printed in duplicate
- Plasma is pre-treated with DNase-I to remove free circulating DNA (which can bind nuclear antigen spots non-specifically) and diluted 1:50 in PBST buffer before incubation
- Detection: cy3-conjugated anti-human IgG (1:2000) and cy5-conjugated anti-human IgM (1:2000) simultaneously, using a Genepix 4200A scanner at 532 and 635 nm; images analysed in Genepix Pro 7.0
- NFI calculation: median spot signal minus local background, averaged across duplicates, normalised to the mean intensity of IgG/IgM internal controls spotted on the array, then PBS-blank-subtracted
- Signal-to-noise ratio (SNR) ≥ 3 is the positivity threshold

### Analytic strengths
- Simultaneous profiling of IgM and IgG across the full antigen panel without prior knowledge of target specificity — an unbiased screen
- Enables identification of novel autoantibody targets not captured by targeted single-analyte assays (ELISA, IIFA, LIA)
- Can detect subtle quantitative differences across patient groups even when the absolute signal is below the SNR positivity threshold (using continuous NFI values and group-level statistics)

### Analytic limitations
- **Low throughput per experiment**: slide-based format; each sample consumes a full slide; not suitable for very large cohorts without significant resources
- **Cross-validation not feasible with limited sample volume**: small plasma volumes preclude repeat or orthogonal validation
- **No confirmatory isotype specificity**: reports total IgG or IgM signal; cannot distinguish specific IgG subclasses (IgG1–IgG4) or free vs. immune-complex-bound antibodies
- **Multiple comparisons burden**: 123 antigens × 2 isotypes = 246 possible comparisons; Bonferroni correction would require p < 0.0002 for each individual test — thresholds rarely applied in exploratory studies, limiting interpretation of individual positive findings

### Application in dengue
In [[Vo2020 - Autoantibody Profiling in Dengue]], the platform was used to characterise the autoantibody repertoire in Cambodian pediatric dengue patients (ASD, DF, DHF) vs. healthy donors. Key findings enabled by the breadth of the array:
- Identification of 80 IgM and 6 IgG autoantibodies elevated across DENV-infected vs. HD
- Discovery of the primary > secondary IgG autoantibody finding — a relationship not testable by single-target assays
- Identification of 19 IgG autoantibodies correlating with platelet counts in DHF, spanning complement, coagulation, and nuclear antigens — a cross-domain pattern only visible with an untargeted screen

## Contradictions & Debates
- NFI-based array results require independent validation by orthogonal methods (ELISA, IIFA, flow cytometry) before clinical utility can be claimed; array findings are hypothesis-generating
- Bystander polyclonal activation during infection inflates the number of "positive" signals; interpretation of individual elevated antibodies as specifically relevant to pathogenesis requires absorption or functional follow-up experiments

## Related Pages
- [[Indirect Immunofluorescence ANA Test]] (clinical-grade ANA method; measures nuclear-pattern autoantibodies by HEp-2)
- [[IgM-IgG Serology ELISA]] (targeted dengue-specific serology)
- [[NS1 Antigen Detection]]
- [[Autoimmunity in Dengue]]
- [[Line Immunoassay ANA]]

## Sources
- [[Vo2020 - Autoantibody Profiling in Dengue]]
