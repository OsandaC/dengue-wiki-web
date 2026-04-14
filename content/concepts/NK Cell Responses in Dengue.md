---
type: concept
tags: [NK-cells, FcεRIγ, NKG2D, NKp46, CD94, innate-immunity, immunopathogenesis]
created: 2026-04-12
updated: 2026-04-12
sources: 1
---

# NK Cell Responses in Dengue

## Overview

Natural killer (NK) cells are innate lymphocytes that provide rapid antiviral responses without prior antigen sensitisation. They recognise and kill virus-infected cells through germline-encoded activating and inhibitory receptors, and produce cytokines (IFN-γ, TNF) that shape the adaptive immune response. In dengue, NK cell populations and phenotypes differ across disease severity, with asymptomatic infection and severe disease associated with distinct NK cell states.

NK cells can be broadly divided by surface marker expression:
- **CD56bright NK cells:** tissue-homing, cytokine-producing, less cytotoxic
- **CD56dim/CD16+ NK cells:** peripheral blood-dominant, highly cytotoxic, ADCC-capable (antibody-dependent cellular cytotoxicity via FcγRIII/CD16)

An adaptive or memory-like NK cell phenotype is characterised by low expression of the Fc receptor common γ subunit (FcεRIγ, encoded by FCER1G); these NK cells display enhanced recall responses and have been described following CMV infection.

## Key Points from Literature

**NK cell depletion in symptomatic dengue:**
Sungnak2025 (see [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]) confirmed that CD16+CD56dim/− NK cells are significantly reduced in the PBMCs of symptomatic dengue patients (DF and DHF) compared with asymptomatic dengue donors (P < 0.05 by flow cytometry). The mechanism of this depletion is not established — possible explanations include redistribution to tissues, activation-induced apoptosis, or NK cell exhaustion.

**FcεRIγ phenotype distinguishes asymptomatic from symptomatic dengue:**
NK cells from asymptomatic donors showed significantly lower FCER1G gene expression (scRNA-seq) and were enriched for FcεRIγ+ cells in flow cytometry of asymptomatic dengue PBMCs (P < 0.05). This means that asymptomatic dengue donors have proportionally more FcεRIγ+/high NK cells (canonical phenotype), while symptomatic donors have accumulation of FcεRIγ−/low NK cells (adaptive/memory-like phenotype).

The functional interpretation is complex: FcεRIγ−/low NK cells have been associated with memory-like functions and enhanced cytotoxicity in some viral settings (CMV, COVID-19), but also with greater disease severity in COVID-19 and accumulation in chronic infections. In chronic viral infection, FcεRIγ expression in NK cells limits CD8 T cell expansion — raising the possibility that the FcεRIγ−/low NK phenotype in symptomatic dengue may suppress protective CD8 T cell responses.

**Activating receptors higher in asymptomatic dengue:**
NK cells from asymptomatic donors expressed significantly higher levels of KLRK1 (encoding NKG2D — an activating receptor recognising stress ligands on infected/transformed cells) and NCR1 (encoding NKp46 — a natural cytotoxicity receptor) than symptomatic donors (P < 0.05, Wilcoxon). NKG2D protein expression was confirmed by flow cytometry (P < 0.05). NKG2D recognises MICB (encoded by a gene at a known dengue susceptibility GWAS locus), connecting genetics to NK cell function in dengue pathogenesis.

**Inhibitory receptors higher in symptomatic dengue:**
KLRD1 (encoding CD94, a subunit of the inhibitory NKG2A/CD94 receptor complex) was higher in NK cells from symptomatic donors, particularly DHF. CD94/NKG2A engagement with HLA-E suppresses NK cell cytotoxicity — elevated CD94 in severe dengue may represent NK cell inhibition or exhaustion.

**RNA/protein discrepancy in FCER1G:**
FCER1G RNA was higher in DHF NK cells by scRNA-seq, but FcεRIγ protein was lower in DHF NK cells by intracellular flow cytometry. The authors suggest post-transcriptional regulation, translation efficiency, or protein stability may decouple RNA and protein. This discrepancy is flagged as needing further investigation.

## Contradictions & Debates

The significance of FcεRIγ−/low NK cells in dengue remains unresolved. Some studies associate them with protective memory-like function (CMV literature), while Sungnak2025's context — accumulation in symptomatic disease — suggests the opposite. The paper proposes that FcεRIγ−/low NK cells may limit CD8 T cell expansion (as demonstrated in chronic viral infection models), potentially impairing protective immunity in symptomatic dengue and contrasting with the FcεRIγ+/high phenotype in asymptomatic donors where CD8 T cell expansion is robust.

Furthermore, the FCER1G RNA/protein discrepancy (higher RNA in DHF, lower protein in DHF) makes straightforward interpretation of scRNA-seq data alone insufficient for NK cell biology.

Genetic polymorphisms in KLRK1 (NKG2D) have been associated with vascular leakage and more severe dengue forms, and MICB (NKG2D ligand) harbours a susceptibility locus for dengue shock syndrome (Khor et al., 2011 GWAS). This suggests a genetic basis for differential NK cell activation between individuals.

## Related Pages

- [[T Cell Responses in Dengue]]
- [[Antibody-Dependent Enhancement]]
- [[Asymptomatic Dengue Infection]]
- [[Single-Cell RNA Sequencing]]

## Sources

- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]
