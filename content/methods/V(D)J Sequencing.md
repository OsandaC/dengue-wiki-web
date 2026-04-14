---
type: method
tags: [BCR, TCR, immune-repertoire, V(D)J, clonotype, CDR3, plasmablast]
created: 2026-04-12
updated: 2026-04-12
sources: 1
---

# V(D)J Sequencing

## Overview

V(D)J sequencing (also called immune receptor sequencing or adaptive immune receptor repertoire sequencing, AIRR-seq) profiles the variable (V), diversity (D), and joining (J) gene segments that are rearranged during B and T lymphocyte development to generate diverse antigen receptor sequences. The complementarity-determining region 3 (CDR3), encoded at the V(D)J junction, is the primary determinant of antigen specificity.

When performed at single-cell resolution (scV(D)J-seq), it enables pairing of B cell receptor (BCR) heavy and light chains (or T cell receptor α and β chains) from the same cell, providing far more specific clonotype information than bulk repertoire sequencing. In the 10x Genomics Chromium platform, single-cell 5′ gene expression and V(D)J libraries are prepared from the same cDNA and can be directly integrated: each cell's transcriptional identity (from scRNA-seq) can be linked to its BCR or TCR sequence.

**BCR analysis** enables: immunoglobulin isotype identification (IGHG, IGHA, IGHM, etc.), somatic hypermutation frequency estimation (indicating affinity maturation), clonotype network construction (identifying cells sharing related receptor sequences, suggesting recognition of common epitopes), and V gene usage bias detection.

**TCR analysis** enables: clonal expansion quantification, identification of canonical T cell subtypes (MAIT cells: TRAV1-2+; iNKT cells: TRAV10+TRAJ18+), and tracking of T cell clones across time points.

## Key Points from Literature

**Application to dengue (Sungnak2025):** Sungnak et al. used 10x Chromium Single Cell V(D)J Enriched libraries prepared alongside 5′ gene expression libraries (see [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]). BCR data were analysed using Dandelion + Scirpy; TCR data using Scirpy. Key findings enabled by V(D)J sequencing:

- **Public BCR clonotype network in symptomatic dengue:** 79 plasmablasts from 8 symptomatic donors (3 DF, 5 DHF) formed a shared clonotype cluster based on CDR3 amino acid similarity (BLOSUM62 distance matrix). 83.5% used IGHV4-39*01 heavy chain and IGKV1-9*01 light chain — a striking V gene bias not seen in total B cells, suggesting antigen-driven selection.
- **Immunoglobulin isotype bias:** IGHG1+ (IgG1) plasmablasts enriched in symptomatic dengue; IGHA1+ (IgA1) plasmablasts enriched in asymptomatic dengue (both P < 0.05). Isotype assignment is only possible with V(D)J sequencing or RNA-level isotype identification.
- **T cell clonotype expansion:** CD8 TEM cells showed the highest clonal expansion overall; expanded clones were enriched in asymptomatic donors. Absence of overlapping clonotypes between donors confirmed donor-specificity (no public TCR clonotype).
- **Canonical innate-like T cells:** MAIT cells (TRAV1-2+ with TRAJ33/TRAJ12/TRAJ20) and iNKT cells (TRAV10+TRAJ18+ / TRBV25-1+) identified and quantified; both expanded in DHF.
- **Longitudinal clonal tracking:** CD8-proliferating T cells from febrile phase were traced to CD8 TEM identity at convalescence in 5/6 donors, suggesting this transition seeds long-term memory.

**BCR clonotype definition used:** identical V and J gene usage + identical CDR3 amino acid length + ≥85% CDR3 amino acid similarity (Hamming distance), applied to both heavy and light chains.

**TCR clonotype definition used:** exact CDR3 nucleotide sequence match + identical V(D)J gene usage in both α and β chains.

## Contradictions & Debates

The public BCR clonotype network identified in symptomatic donors (IGHV4-39*01/IGKV1-9*01) has an unknown antigen target. Whether this represents DENV-specific, cross-reactive, or autoreactive antibodies remains unresolved. Sungnak2025 found no elevated autoantibodies on a 120-antigen panel, arguing against the autoreactive hypothesis, but the panel may not include the relevant antigen.

## Related Pages

- [[Single-Cell RNA Sequencing]] (performed from same library prep)
- [[Antibody-Dependent Enhancement]] (IGHG1 isotype bias and ADE relevance)
- [[T Cell Responses in Dengue]]
- [[Asymptomatic Dengue Infection]]

## Sources

- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]
