---
type: method
tags: [single-cell, transcriptomics, scRNA-seq, PBMC, immune-profiling]
created: 2026-04-12
updated: 2026-04-12
sources: 1
---

# Single-Cell RNA Sequencing

## Overview

Single-cell RNA sequencing (scRNA-seq) profiles gene expression in individual cells rather than bulk populations, enabling identification of rare cell types, cell-state heterogeneity, and differential gene expression at cell-type resolution. In dengue research, scRNA-seq of peripheral blood mononuclear cells (PBMCs) allows comparison of immune cell composition and transcriptional programs across disease severity groups and over time.

The most common commercial platform for PBMC scRNA-seq is 10x Genomics Chromium, which uses droplet microfluidics to capture single cells alongside oligonucleotide-barcoded beads. Library types include 3′ gene expression (most common), 5′ gene expression (enables paired V(D)J immune receptor sequencing), and CITE-seq (adds protein-level surface marker quantification via antibody-derived tags).

Key analytical steps typically include: ambient RNA removal (SoupX), doublet identification (Scrublet), dimensionality reduction (PCA, UMAP), cell clustering, reference-based cell-type annotation, differential gene expression (DGE) analysis, and gene set enrichment analysis (GSEA).

## Key Points from Literature

**Application to dengue:** Sungnak et al. (2025) performed 5′ scRNA-seq of PBMCs from 24 DENV-infected individuals (8 asymptomatic, 8 dengue fever, 8 dengue hemorrhagic fever), profiling 134,359 cells and identifying 30 cell types (see [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]). Cell-type annotation was performed by serial multimodal reference mapping to a CITE-seq reference of 162,000 PBMCs (Hao et al., 2021), addressing batch effects. This design enabled detection of significant differences in CD8 TEM, NK cell, and plasmablast proportions across severity groups that would be invisible to bulk transcriptomics.

**Advantages over bulk methods:** scRNA-seq resolves which specific cell types drive gene expression changes. For example, enrichment of Fc receptor signalling pathway genes in DHF was identified in specific cell types (B cells, monocytes), not distributed evenly — this cell-type specificity is critical for mechanistic interpretation.

**Limitations in dengue:**
- DENV genomic RNA lacks a polyadenylate tail, so viral transcripts are not captured by standard oligo(dT)-primed scRNA-seq (see [[qRT-PCR]] for viremia quantification). Virus-inclusive scRNA-seq (viscRNA-seq) requires targeted viral amplification.
- PBMC-based profiling misses tissue-resident immune responses (lymph nodes, spleen, endothelium, skin).
- Cost and technical complexity limit sample sizes; Sungnak2025's n=8 per group, though matched for confounders, is acknowledged as a limitation for power.

**Reference mapping:** Sungnak2025 used Seurat v4.2 with a precomputed CITE-seq reference to annotate cells at level 2 granularity (30 cell types). This approach reduces batch effects and enables standardised annotation across samples and studies.

## Contradictions & Debates

Prior scRNA-seq studies of dengue focused exclusively on symptomatic cases, experimental infection, or vaccine responses (Waickman et al. 2021, 2019, 2020; Zanini et al. 2018; Ghita et al. 2023; Robinson et al. 2023). Sungnak2025 is the first to include viremic asymptomatic individuals, making direct comparison to prior datasets difficult due to differing study designs, sampling time points, and annotation frameworks.

## Related Pages

- [[V(D)J Sequencing]] (commonly performed from the same 5′ scRNA-seq library)
- [[T Cell Responses in Dengue]]
- [[NK Cell Responses in Dengue]]
- [[Asymptomatic Dengue Infection]]

## Sources

- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]
