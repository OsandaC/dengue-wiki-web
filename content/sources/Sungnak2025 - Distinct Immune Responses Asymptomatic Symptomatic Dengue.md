---
type: source
tags: [scRNA-seq, single-cell, immune-profiling, asymptomatic, CD8-T-cells, NK-cells, plasmablasts, ADE, type-I-interferon, IL-10, BCR-repertoire, TCR-repertoire, Thailand, immunopathogenesis]
authors: [Sungnak W, Jiravejchakul N, Poonpanichakul T, Trakoolsoontorn C, Srikor S, Opasawatchai A, Arora J, Jevapatarakul D, Thungsatianpun N, Nguantad S, Chantaraamporn J, Pakchotanon P, Punyadee N, Duangchinda T, Avirutnan P, Mongkolsapaya J, Meyer KB, Matangkasombut O, Charoensawan V, Teichmann SA, Matangkasombut P]
year: 2025
journal: Science Translational Medicine
doi: 10.1126/scitranslmed.ads5932
citations_semantic_scholar: 1
citations_crossref: 1
citations_retrieved: 2026-04-12
created: 2026-04-12
updated: 2026-04-12
---

# Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue

**Full citation:** Sungnak W, Jiravejchakul N, Poonpanichakul T, et al. Distinct systemic immune responses in asymptomatic and symptomatic dengue virus infection. *Science Translational Medicine*, 17(829), eads5932 (2025). https://doi.org/10.1126/scitranslmed.ads5932

**Raw file:** `[[raw/Sungnak2025.pdf]]`

## Summary

This study provides the first single-cell transcriptomic and immune receptor sequencing resource comparing peripheral blood mononuclear cell (PBMC) profiles across three dengue severity groups: asymptomatic dengue (AD), dengue fever (DF), and dengue hemorrhagic fever (DHF). The eight asymptomatic dengue samples were obtained through a systematic 5-year household surveillance programme (the DENFREE Thailand cohort), enabling collection from viremic individuals prior to and without development of any symptoms — a technically difficult and rarely achieved design. Sample groups were matched for viremia, age, sex, DENV serotype, and primary/secondary infection status to minimise confounding.

In asymptomatic dengue, the data suggest enhanced viral antigen processing for MHC class I presentation — mediated through differential ribosomal protein expression (RPL6↑, RPS28↑, RPL28↓ in memory B cells and CD16 monocytes) — correlating with expansion of clonally enriched CD8 effector T cells bearing functional (not exhausted) effector gene profiles. NK cells in asymptomatic donors showed an FcεRIγ-low, NKG2D-high phenotype associated with memory-like and activating functions. IGHA1-expressing plasmablasts were enriched in asymptomatic dengue, consistent with a protective IgA-mediated mechanism.

In symptomatic dengue, particularly DHF, gene expression patterns in multiple cell types indicated enrichment of receptor-mediated endocytosis and Fc receptor signalling pathways — transcriptomic evidence consistent with the antibody-dependent enhancement (ADE) model of viral entry. Elevated plasma IFN-α2 and a strong correlation between plasmablast abundance and IL-10 (Spearman ρ = 0.757, P = 1.13 × 10⁻⁴) pointed to a pro-pathogenic axis: IL-10 (from proliferating CD4 T cells) driving expansion of IGHG1+ plasmablasts with biased V(D)J gene usage and a public, shared BCR clonotype network across symptomatic donors.

## Study Design

- **Type:** Cross-sectional comparison + longitudinal cohort component
- **Sample size:** 24 individuals for scRNA-seq (8 AD, 8 DF, 8 DHF); 5 AD + 14 DF + 15 DHF for flow cytometry validation; 6 additional for longitudinal (3 DF + 3 DHF: acute febrile phase and 2-month convalescence)
- **Setting:** Three hospitals in Thailand (Vajira Hospital Bangkok, Faculty of Tropical Medicine Mahidol University Bangkok, Tasongyang Hospital Tak); part of the DENFREE Thailand cohort established 2012–2017
- **Population:** Adults and older children; predominantly Thai; viremic at time of sampling; symptomatic samples collected 24–48 hours before defervescence (most immunologically dynamic window); asymptomatic samples collected at time of enrollment during active viremia
- **Cells profiled:** 134,359 high-quality PBMCs; 30 cell types annotated via serial multimodal reference mapping to a CITE-seq reference of 162,000 PBMCs

## Key Findings

**Cell composition:**
- CD8 TEM cells (including CTLs) and NK cells significantly enriched in asymptomatic dengue vs. symptomatic (P < 0.05)
- Plasmablasts (including plasma cells) significantly enriched in symptomatic dengue (P < 0.05)
- CD4 TCM cells significantly higher in DF vs. DHF (P < 0.05)

**Asymptomatic dengue — potential protective mechanisms:**
- Ribosomal protein expression changes in memory B cells and CD16 monocytes suggest enhanced viral peptide generation for MHC class I: RPL6↑ (promotes viral peptide generation), RPS28↑ (inhibits cellular peptide generation), RPL28↓ (suppressor of viral peptide generation) — all in the direction of enhanced viral antigen presentation
- Cell-cell interaction analysis (CellChat) showed increased predicted MHC class I–mediated interactions of memory B cells and CD16 monocytes with CD8 TEM cells in AD vs. DHF
- IGHA1+ (IgA1) plasmablasts enriched in asymptomatic donors (P < 0.05); DENV-specific IgA can neutralise virus and antagonise IgG-mediated ADE
- CD8 TEM cells clonally expanded and expressed effector genes IFNG, TNF, GZMH, GNLY; less diverse TCR repertoire suggesting antigen-driven expansion
- NK cells: lower FCER1G expression (marker of memory-like, enhanced-function NK phenotype); higher KLRK1 (NKG2D) and NCR1 (NKp46); confirmed by flow cytometry (FcεRIγ+CD16+CD56dim/− enriched in AD; NKG2D+ NK cells enriched in AD, P < 0.05)

**Symptomatic dengue — potential pathogenic mechanisms:**
- DHF group: enrichment of receptor-mediated endocytosis (GO:0006898), Fc epsilon receptor signalling (GO:0038095), and Fc receptor signalling pathway (GO:0038093) gene sets — consistent with ADE via FcγR-mediated DENV entry
- Type I interferon (hallmark IFN-α response) enriched across multiple cell types in symptomatic dengue; plasma IFN-α2 protein significantly elevated in symptomatic vs. asymptomatic (P < 0.05)
- IGHG1+ (IgG1) plasmablasts enriched in symptomatic donors (P < 0.05); IgG1 has high FcγR affinity — implicated in ADE
- Plasmablast proportion strongly correlated with plasma IL-10 (Spearman ρ = 0.757, P = 1.13 × 10⁻⁴); IL-10 significantly higher in DHF vs. AD plasma; CD4 proliferating T cells are the highest expressers of IL10 in DHF
- Public BCR clonotype network: 79 plasmablasts from 8 symptomatic donors (3 DF + 5 DHF); 83.5% using IGHV4-39*01 and IGKV1-9*01; biased V(D)J gene usage in symptomatic plasmablasts but not total B cells
- CD8 TEM cells in symptomatic dengue: expressed PRF1, GZMB (different effector profile), plus FAS (cell death), PDCD1 (PD-1), LAG3, TIGIT (exhaustion/dysfunction markers); higher PD-1 and CD69 protein confirmed by flow cytometry in DHF
- MAIT and iNKT cells significantly expanded in DHF (P < 0.05)
- No significant difference in autoantibody levels (panel of 120 targets) across severity groups; anti-IFN autoantibodies not implicated

**Longitudinal (febrile → 2-month convalescence):**
- Plasmablasts, proliferating T cells, MAIT, iNKT all contracted at convalescence
- Most CD8 TEM cells from febrile phase remained as CD8 TEM at convalescence
- Some CD8-proliferating T cells (5/6 donors) transitioned to CD8 TEM at convalescence — suggesting the memory CD8 T cell pool is partly seeded by febrile-phase proliferating cells
- No matched BCR clones found between febrile and convalescent phases in plasmablasts

## Methods Used

- [[Single-Cell RNA Sequencing]] (scRNA-seq; 10x Genomics Chromium, 5′ gene expression; CellRanger v3.1.0; Seurat v4.2 with CITE-seq reference mapping; UMAP visualisation)
- [[V(D)J Sequencing]] (Chromium Single Cell V(D)J; BCR analysis via Dandelion + Scirpy; TCR analysis via Scirpy; CDR3 clonotype networks via BLOSUM62)
- [[qRT-PCR]] (for DENV viremia quantification in plasma; also used for primary/secondary infection classification via hemagglutination inhibition)
- [[PRNT]] (plaque reduction neutralisation test; used for asymptomatic donor primary/secondary classification)
- Flow cytometry (CytoFLEX; CD16, CD56, CD3, CD8, NKG2D, PD-1, CD69, FcεRI-γ antibody panel)
- Luminex bead array (MILLIPLEX; plasma IFN-α2 and IL-10 measurement)
- Antigen microarray (GeneCopoeia OmicsLink; 120 autoantibody targets in plasma)

## Entities Mentioned

- [[Aedes aegypti]] (vector; background)
- DENV-1, DENV-3, DENV-4 (serotypes present in cohort; DENV-2 absent — cited as limitation)

## Concepts Addressed

- [[Asymptomatic Dengue Infection]] (central subject; first single-cell characterisation)
- [[Antibody-Dependent Enhancement]] (transcriptomic evidence in DHF; IGHG1 plasmablast expansion)
- [[T Cell Responses in Dengue]] (CD8 TEM expansion, effector vs. exhausted phenotypes, MAIT/iNKT)
- [[NK Cell Responses in Dengue]] (FcεRIγ phenotype, NKG2D, NKp46, CD94 across severity groups)
- [[Type I Interferon Response in Dengue]] (IFN-α2 elevation in symptomatic; hallmark IFN-α enrichment)
- [[Autoimmunity in Dengue]] (autoantibody panel: no significant differences across severity groups)

## Relevance & Notes

This paper is one of the most methodologically sophisticated dengue immunology studies to date, combining single-cell transcriptomics with immune receptor sequencing at three disease severity levels including the rarely characterised asymptomatic state. The DENFREE Thailand cohort design (household surveillance of index case contacts) is the critical enabling factor — it is the only published approach to have successfully obtained viremic asymptomatic dengue PBMCs for deep immune profiling.

The key contribution is providing a mechanistic framework distinguishing protective from pathogenic immunity at single-cell resolution. The suggestion that MHC-I-driven CD8 T cell responses are a hallmark of protection — not pathology — has direct implications for vaccine design: vaccines that elicit robust, functional (non-exhausted) CD8 T cell responses against DENV nonstructural proteins (as TAK-003 and TV-003 do, contrasting with CYD-TDV) may be preferable.

The IL-10/IGHG1 plasmablast axis is a novel finding: IL-10 is classically anti-inflammatory, but here is proposed to drive pathogenic plasma cell expansion in severe dengue. The public BCR clonotype network (IGHV4-39*01 / IGKV1-9*01 bias in symptomatic plasmablasts) is potentially important for understanding convergent pathogenic humoral responses across individuals, but the antigen target of this public clonotype is unknown.

The study was limited by small n (particularly 8 AD, difficult to obtain), absence of DENV-2 (serotype most associated with severe secondary infection), adult predominance, PBMC focus (misses tissue-specific immunity), and lack of antigen-specificity data (cannot confirm which responses are DENV-specific vs. bystander-activated).

Regarding autoimmunity: the finding of no significant autoantibody differences across severity groups (including against IFN-α and IFN-ω, which are implicated in severe COVID-19) adds a useful negative result for the autoimmunity thread in this wiki.

## Questions Raised

1. What antigen does the public IGHV4-39*01 / IGKV1-9*01 BCR clonotype recognise — DENV structural protein, non-structural protein, or self-antigen?
2. Does the IL-10 → IGHG1 plasmablast axis produce antibodies that actually mediate ADE in subsequent infection, or is it an epiphenomenon of severe disease?
3. Are the MHC-I enhancement signals in asymptomatic dengue (memory B cells, CD16 monocytes) causal for protection, or correlates of lower viral burden?
4. Why do CD8 TEM cells show exhaustion markers in symptomatic dengue — is this driven by antigen load, cytokine environment (IL-10, IFN-α), or prior exposure (secondary infection effect)?
5. Would the IGHA1+ plasmablast enrichment in asymptomatic donors persist as long-lived IgA memory, and could this be recapitulated by vaccination?
6. What is the role of DENV-2 (absent from cohort) — does it produce a fundamentally different immune profile in secondary infection?
