---
type: concept
tags: [CD8-T-cells, CD4-T-cells, MAIT, iNKT, exhaustion, effector, TCR, immunopathogenesis, low-avidity, OAS, cytolytic-loss, TNF-alpha, IL-6]
created: 2026-04-12
updated: 2026-04-17
sources: 4
---

# T Cell Responses in Dengue

## Overview

T cell responses — particularly from CD8+ cytotoxic T lymphocytes (CTLs) — are central to both protective immunity and immunopathology in dengue. The quality, magnitude, and phenotype of T cell responses differ markedly between individuals who develop asymptomatic infection versus dengue fever or dengue hemorrhagic fever. A key unresolved question in dengue immunology is whether pre-existing T cell memory from prior heterologous DENV infection helps or harms during secondary infection (the "original antigenic sin" model predicts cross-reactive T cells may be inefficient against the new serotype yet generate excessive cytokines).

**Key T cell populations in dengue:**
- **CD8 TEM (effector memory):** Primary cytotoxic effectors; can be DENV-specific; marker of clonal expansion
- **CD4 TCM (central memory):** Helper coordination; may also acquire cytotoxic function (CD4 CTL)
- **MAIT cells (mucosal-associated invariant T cells):** Innate-like; TRAV1-2+ with TRAJ33/TRAJ12/TRAJ20; activated during many viral infections
- **iNKT cells (invariant NKT cells):** Innate-like; TRAV10+TRAJ18+ / TRBV25-1+; associated with severe dengue

## Key Points from Literature

**Asymptomatic dengue — functional CD8 effector response:**
In asymptomatic dengue, CD8 TEM cells and NK cells are significantly enriched in PBMCs relative to symptomatic cases (P < 0.05), and CD8 TEM cells show the highest degree of clonal expansion (see [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]). The TCR repertoire of expanded CD8 TEM cells is less diverse in asymptomatic donors (higher antigen-driven clonal focus), and expanded clones are predominantly from asymptomatic donors rather than symptomatic ones.

Gene expression profiles of CD8 TEM in asymptomatic dengue are consistent with effective cytotoxic function: high IFNG (IFN-γ), TNF, GZMH (granzyme H), and GNLY (granulysin). This effector profile is proposed to result from enhanced viral antigen presentation via MHC class I — driven by changes in ribosomal protein expression in memory B cells and CD16 monocytes that favour viral peptide generation (RPL6↑, RPS28↑, RPL28↓).

**Symptomatic dengue — markers of exhaustion and overactivation:**
CD8 TEM cells in symptomatic dengue (particularly DHF) express a different profile: PRF1 (perforin) and GZMB (granzyme B) as effector genes, but also markers of dysfunction — FAS (apoptosis), PDCD1 (PD-1), LAG3, and TIGIT (all inhibitory receptors associated with T cell exhaustion and overactivation). Flow cytometry confirmed significantly elevated PD-1 and CD69 surface protein on CD8 T cells in symptomatic dengue, especially DHF.

**MAIT and iNKT expansion in severe dengue:**
MAIT cells (TRAV1-2+) and iNKT cells (TRAV10+TRAJ18+) show significantly higher clonal expansion in DHF compared with DF and AD (P < 0.05). This is consistent with prior literature associating these innate-like T cell subsets with severe dengue. The mechanism may involve bystander activation by dengue-induced cytokines rather than DENV-specific TCR recognition.

**CD4 CTLs:** Also observed to be clonally expanded (consistent with prior reports of dengue-specific CD4 cytotoxic T lymphocytes). CD4 proliferating T cells in DHF show the highest IL10 expression and are proposed (via CellChat analysis) to signal to plasmablasts through IL-10/IL-10R — potentially driving pathogenic plasma cell expansion.

**Longitudinal dynamics:** From febrile phase to 2-month convalescence, proliferating T cells contract. However, CD8-proliferating T cells from the febrile phase were found to transition to CD8 TEM identity at convalescence in 5/6 donors, suggesting the effector-to-memory transition occurs partly from this proliferating pool rather than exclusively from pre-existing CD8 TEM.

### IL-10-driven T cell apoptosis — a mechanism for impaired viral clearance (Pang2017)

[[Pang2017 - DHF Pathogenesis Review]] synthesises evidence for a specific IL-10 → T cell apoptosis pathway in severe dengue (citing Mathew & Rothman 2008; Green 1999):

- **IL-10 is elevated in severe dengue** (consistent with Sungnak2025 and Bhatt2020 in this wiki, where IL-10 is the cytokine most consistently associated with DHF)
- **IL-10 directly induces T cell apoptosis** in patients with acute dengue infection; IL-10 blockade is significantly associated with *reduced* T cell apoptosis in acute DENV infection
- **Consequence: reduced T cell numbers in DHF vs. DF** — documented by Green et al. (1999) in the original source cited; fewer T cells → impaired viral clearance → prolonged viraemia → more severe clinical dengue
- **Mechanism implication:** IL-10's role in dengue severity thus operates through at least two parallel arms: (1) Th2 skewing / IFN-γ suppression → impaired antiviral killing (Bhatt2020, Wan2012); and (2) T cell apoptosis → quantitative depletion of the effector pool → reduced clearance capacity

This provides a quantitative cellular basis for the Bhatt2020 OAS model: not only are the expanded cross-reactive T cells functionally inferior (low avidity, cytolytic loss), but IL-10 produced in the same severe dengue context actively eliminates T cells — compounding the clearance deficit via a second, independent mechanism.

Note: the IL-10 → T cell apoptosis connection is reviewed here from secondary sources (Pang2017 citing Mathew & Rothman 2008) and has not been directly measured in this wiki's primary data sources.

### OAS-driven CD8+ dysfunction mechanism — Bhatt2020

[[Bhatt2020 - Dengue Pathogenesis Review]] provides mechanistic detail for how original antigenic sin translates into T cell dysfunction and downstream pathology in secondary dengue (see [[Original Antigenic Sin]]):

- **Low-avidity CD8+ T cells are expanded preferentially**: memory CD8+ T cells from the primary serotype have a lower activation threshold than naive T cells; in secondary infection they expand before naive T cells can establish adequate primary responses. These cross-reactive cells bind heterologous epitopes with sub-optimal avidity.
- **Cytolytic activity is lost**: the low-avidity cross-reactive CD8+ T cells produce high TNF-α and IL-6 (cytokine-producing function retained) but lose cytolytic capacity (perforin/granzyme killing impaired). This mirrors the PRF1/GZMB expression in DHF-associated CD8 TEM from Sungnak2025 — perforin and granzyme B are expressed, but killing efficiency against the heterologous serotype may be reduced by low TCR avidity.
- **Delayed clearance → amplification**: viral replication continues longer than in a well-matched primary response → sustained antigen stimulation → prolonged T cell activation → cytokine amplification → vascular permeability.

The Bhatt2020 OAS mechanism and the Sungnak2025 single-cell exhaustion data are complementary: Sungnak2025 identifies the end-state (exhaustion markers, PRF1/GZMB bias, PD-1↑/LAG3↑/TIGIT↑); Bhatt2020 provides the upstream cause (avidity mismatch from preferential cross-reactive memory expansion).

## T cell biology from Guzman2016

Guzman2016 provides a review-level summary of T cell knowledge as of 2016 (see [[Guzman2016 - Dengue Infection]]):

- The relative contribution of antibody-mediated vs T cell–mediated immunity to dengue protection is **not well understood** — both are recognised as important
- **CD8+ T cells**: effective CD8+ CTL immunity is largely directed against NS protein epitopes (not E protein, which is the predominant vaccine antigen in live attenuated vaccines using only prM/E); NS-specific CD8 T cells contribute to viral clearance but may also produce immunopathological cytokines in secondary heterotypic infection (original antigenic sin model; see [[Original Antigenic Sin]])
- **CD4+ T cells** contribute to protection through multiple mechanisms:
  1. Antiviral cytokine production (IFN-γ, TNF-α)
  2. Cytotoxic killing of DENV-infected cells (CD4 CTL)
  3. Enhancement of CD8 T cell responses (T helper function)
  4. Enhancement of B cell and antibody responses (follicular helper T cell function)
  5. Promotion of immune memory formation
- Cross-reactive T cells from a prior heterologous infection are re-expanded preferentially in secondary dengue — the mechanistic basis for OAS; whether this is net protective or pathological remains debated
- Vaccine implication: vaccines that include NS protein antigens (TV003/TV005 live attenuated; some DNA vaccines) may induce more protective CD8 T cell responses than vaccines relying solely on E protein (CYD-TDV, subunit DEN-80E, inactivated DPIV) — a prediction now supported by Sungnak2025's finding that NS-epitope CD8 TEM functional profiles characterise asymptomatic/protective immunity

## Contradictions & Debates

The relative importance of antibody-mediated (ADE) versus T cell–mediated immunopathology in severe dengue remains debated. Sungnak2025 identifies transcriptomic evidence for both, but the two mechanisms may cooperate: ADE-mediated entry could increase intracellular viral antigen load, driving excessive T cell activation. The "original antigenic sin" model predicts that cross-reactive, low-avidity T cells from prior heterologous infection dominate the response and produce excessive cytokines (e.g., TNF, IFN-γ) without efficiently killing infected cells — but Sungnak2025's data show the highest effector gene expression (including IFNG, TNF) in asymptomatic donors, which complicates the simple model that high cytokine production = pathology.

## Related Pages

- [[Antibody-Dependent Enhancement]]
- [[NK Cell Responses in Dengue]]
- [[Asymptomatic Dengue Infection]]
- [[Type I Interferon Response in Dengue]]
- [[V(D)J Sequencing]]
- [[Single-Cell RNA Sequencing]]

## Sources

- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]
- [[Guzman2016 - Dengue Infection]] (NS protein epitope CD8 immunity; CD4 T cell multifunctionality; cross-reactive T cells and OAS; vaccine implications)
- [[Bhatt2020 - Dengue Pathogenesis Review]] (OAS mechanism: low-avidity CD8+ preferentially expanded; cytolytic loss + TNF-α/IL-6 excess; delayed clearance; positive feedback to DHF/DSS; review article, India)
- [[Pang2017 - DHF Pathogenesis Review]] (IL-10-driven T cell apoptosis: IL-10 blockade reduces T cell apoptosis; reduced T cell numbers in DHF vs DF; impaired clearance from apoptotic T cell loss; cross-reactive T cell OAS mechanism confirmed; Tsinghua University China; review)
