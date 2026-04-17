---
type: concept
tags: [original-antigenic-sin, cross-reactive-T-cells, secondary-infection, immunopathology, T-cell-memory, immunodominance, low-avidity, cytolytic-loss, TNF-alpha, IL-6]
created: 2026-04-12
updated: 2026-04-17
sources: 3
---

# Original Antigenic Sin

## Overview
Original antigenic sin (OAS) — also called the Hoskins effect in the context of influenza — describes the phenomenon whereby the immune memory established by a first antigen exposure dominates and shapes subsequent responses to related but distinct antigens. In dengue, the term is most commonly applied to T cell responses: upon secondary infection with a heterotypic DENV serotype, cross-reactive memory T cells from the primary serotype are preferentially re-expanded (because they have a lower activation threshold as memory cells), even if their affinity for the new serotype is lower than naive T cells specific for the new serotype would have. The resulting T cell response may be poorly tuned to the new infecting serotype and may contribute to immunopathology via excessive cytokine production and suboptimal viral clearance.

## Key Points from Literature

- OAS is listed as one of three hypotheses to explain dengue vascular permeability syndrome (alongside cytokine storm from overactive T cells, and immune complex-mediated complement activation), situating it within the context of the broader DHF pathogenesis debate (see [[Guzman2016 - Dengue Infection]])
- The original antigenic sin model predicts that cross-reactive T cell responses are directed preferentially against the original infecting serotype's NS protein epitopes, potentially producing lower-affinity responses against the secondary serotype while generating excessive cytokine production — contributing to cytokine storm without effective viral clearance
- Sungnak2025 offers single-cell evidence that CD8 TEM cells in symptomatic dengue (particularly DHF) show exhaustion markers (PD-1, LAG3, TIGIT) and a different effector profile (PRF1, GZMB) compared to the functional non-exhausted profile in asymptomatic dengue (IFNG, TNF, GZMH, GNLY) — which is consistent with, though not definitive evidence for, OAS-driven T cell dysfunction in severe disease (see [[T Cell Responses in Dengue]])

### OAS T cell mechanism — low-avidity CD8+ expansion and cytolytic loss (Bhatt2020)

[[Bhatt2020 - Dengue Pathogenesis Review]] provides the most mechanistically detailed account of OAS in this wiki, consolidating the cellular and functional basis for how the phenomenon drives DHF/DSS pathology:

- **Preferential expansion of low-avidity cross-reactive CD8+ T cells**: Memory CD8+ T cells from the primary serotype have a lower activation threshold than naive T cells and are re-expanded preferentially in secondary heterotypic infection. These cross-reactive cells bind heterologous epitopes on the new serotype but with lower affinity than de novo naive T cells would — they are not optimally matched to the secondary serotype.
- **Loss of cytolytic function**: Unlike high-avidity serotype-specific T cells that efficiently kill DENV-infected cells via perforin/granzyme, the low-avidity cross-reactive CD8+ T cells lose cytolytic activity against the secondary serotype while retaining cytokine-secreting function. The result is a decoupling of inflammation from killing.
- **High TNF-α and IL-6 without viral clearance**: The expanded cross-reactive pool produces elevated levels of TNF-α and IL-6 — both promoters of endothelial activation and vascular permeability — without effectively lysing DENV-infected target cells. Viral clearance is delayed.
- **Positive feedback loop**: Delayed viral clearance → higher and more prolonged viraemia → sustained T cell activation → further TNF-α/IL-6 production → amplification of vascular permeability → DHF/DSS. The OAS mechanism thus links impaired T cell quality (avidity mismatch with secondary serotype) to the canonical DHF/DSS phenotype via cytokine excess.

This mechanism is consistent with — and may partly explain — the CD8 TEM exhaustion profile (PRF1, GZMB, PD-1↑, LAG3↑, TIGIT↑) documented in DHF by Sungnak2025: the exhaustion markers may reflect a prolonged activation signal in the absence of efficient killing, precisely what the Bhatt2020 OAS model predicts.

## Contradictions & Debates
- OAS is a long-standing hypothesis but has not been definitively proven to drive DHF pathogenesis in humans; it is difficult to distinguish OAS-driven T cell dysfunction from exhaustion due to high antigen load or cytokine-mediated suppression in severe disease
- The implication that cross-reactive T cells are immunopathological in secondary dengue is in tension with evidence that T cells are also protective: effective CD8+ T cell immunity against NS protein epitopes is associated with protection, and Sungnak2025 found functional CD8 TEM enrichment in asymptomatic dengue

## Related Pages
- [[T Cell Responses in Dengue]]
- [[Antibody-Dependent Enhancement]]
- [[Dengue Pathophysiology]]
- [[Dengue Vaccine Candidates]]
- [[Asymptomatic Dengue Infection]]

## Sources
- [[Guzman2016 - Dengue Infection]]
- [[Bhatt2020 - Dengue Pathogenesis Review]] (OAS mechanism: low-avidity CD8+ T cells preferentially expanded; heterologous epitope recognition with reduced affinity; cytolytic loss combined with TNF-α/IL-6 excess; delayed viral clearance → DHF/DSS positive feedback loop; review article, India)
- [[Pang2017 - DHF Pathogenesis Review]] (OAS mechanism confirmed: cross-reactive low-affinity memory T cells expand preferentially in secondary infection; inefficient killing of new serotype; IFN-γ/IL-2/TNF-α cytokine excess → DHF; review, China)
