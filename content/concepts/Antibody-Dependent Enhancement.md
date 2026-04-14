---
type: concept
tags: [ADE, immunopathogenesis, FcR, secondary-infection, severe-dengue, IGHG1, plasmablast, scRNA-seq, IgG-affinity, FcgRIIIA, SPR]
created: 2026-04-11
updated: 2026-04-13
sources: 6
---

# Antibody-Dependent Enhancement

## Overview
Antibody-dependent enhancement (ADE) is a mechanism by which cross-reactive, non-neutralising antibodies from a prior dengue infection bind a new infecting serotype and enhance viral uptake into Fc receptor-bearing cells (monocytes, macrophages, dendritic cells) via the FcR, increasing intracellular viral replication. ADE has long been considered a central mechanism in the pathogenesis of severe dengue (DHF/DSS) in secondary infections.

## Key Points from Literature
- ADE is cited as background context for the role of FcγRIIa in dengue pathogenesis (see [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]]).
- The same FcγRIIa receptor that mediates ADE-based viral entry also regulates immune complex clearance; its polymorphism may therefore contribute to both acute severity and long-term autoimmune sequelae (see [[FcγRIIa Receptor]]).
- Proposed mechanism linking FcγRIIa genotype to ADE: in HH individuals, inefficient binding of DENV/IgG1/3 immune complexes to FcγRIIa leads to failed phagolysosome fusion, evasion of the proteolytic system, and intracellular viral dissemination via ADE. In RR individuals, efficient binding promotes lysosomal destruction of the complex and control of viral spread (see [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]]).

## ADE as the mechanism of "conditional virulence" (Guzman2016)

Guzman2016 advances the framing that dengue viruses are not inherently virulent — they require prior sensitisation (partial immunity) to cause severe disease (see [[Guzman2016 - Dengue Infection]]). Key epidemiological observations supporting this model:

- **3rd and 4th infections are typically mild or asymptomatic**: severe dengue peaks at secondary infection when cross-reactive non-neutralising antibodies from the primary serotype enhance the new infecting serotype; by 3rd/4th infection, broader immunity is established
- **Maternal antibody ADE in infants**: primary dengue infections can cause DHF in infants 6–12 months of age because maternally transferred IgG antibodies from a previously-infected mother act as ADE mediators — analogous to secondary infection without prior personal exposure
- **Inter-infection interval predicts severity**: in secondary infection, a longer interval between first and second infection correlates with greater DHF risk; in the Cuban epidemiological record, a 20-year interval (1981→2001) produced ~8× higher DHF rates than a shorter interval; waning immunity may shift the balance from neutralising to enhancing antibody concentrations
- **CYD-TDV (Dengvaxia) seronegative ADE validation**: CYD-TDV in seronegative children acted like a priming infection with cross-reactive non-neutralising antibodies; subsequent natural DENV infection produced 5× hospitalised breakthrough disease vs controls — the clearest clinical proof-of-concept for vaccine-primed ADE in humans (see [[CYD-TDV]])
- **Broadly neutralising antibodies at DI-DII hinge**: some cross-reactive antibodies that bind the DI-DII domain hinge of the E protein broadly neutralise all four serotypes and are unlikely to mediate ADE; these represent a potential target for vaccines capable of eliciting protective rather than enhancing cross-serotype immunity (see [[E Protein]])

## Intrinsic ADE — IFN suppression and Th2 skewing

Wan2012 describes the "intrinsic ADE" hypothesis, which postulates that FcγR-mediated DENV internalisation does more than increase viral uptake — it actively suppresses antiviral immunity (see [[Wan2012 - Autoimmunity in Dengue Pathogenesis]]):
- FcγR-mediated entry inhibits type I IFN-mediated antiviral gene expression
- Simultaneously enhances IL-10 production, which suppresses IFN-γ signalling and promotes Th2 responses
- Th2 skewing limits virus clearance (Th1-dependent) while enhancing antibody production — creating a positive feedback loop of high viral loads AND high antibody titres
- This may link ADE mechanistically to autoimmunity: by driving Th2/antibody-dominant responses, intrinsic ADE creates conditions for enhanced autoantibody production alongside cross-reactive anti-DENV antibodies

## Transcriptomic evidence for ADE in DHF

Sungnak2025 provides the first single-cell transcriptomic evidence consistent with ADE-mediated viral entry during natural DENV infection (see [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]). In DHF patients specifically, scRNA-seq identified enrichment of gene sets for:
- Receptor-mediated endocytosis (GO:0006898)
- Fc epsilon receptor signalling pathway (GO:0038095)
- Fc receptor signalling pathway (GO:0038093)

These enrichments were observed across multiple cell types in DHF versus asymptomatic dengue. The authors propose this represents FcγR-mediated internalisation of DENV/antibody immune complexes, consistent with classical ADE. In the same dataset, IGHG1+ (IgG1) plasmablasts — producing antibodies with high FcγR affinity — were significantly enriched in symptomatic dengue (P < 0.05), while IGHA1+ (IgA1) plasmablasts were enriched in asymptomatic dengue. DENV-specific IgA has been separately shown to antagonise IgG-mediated ADE.

A public BCR clonotype network (IGHV4-39*01/IGKV1-9*01 bias) was identified exclusively in symptomatic plasmablasts, raising the possibility that shared antigen-driven clonal expansion contributes to the pool of potentially ADE-mediating IgG1 antibodies — though the antigen target of this clonotype is unknown.

The proposed IL-10 → IGHG1+ plasmablast axis may represent a mechanism for in vivo amplification of ADE-capable antibody: IL-10 (produced by CD4 proliferating T cells in DHF) promotes plasma cell differentiation and class switching, driving IgG1+ plasmablast expansion via IL-10/IL-10R signalling.

## FcγR Affinity Hierarchy — Quantitative Substrate for ADE (Bruhns2009)

[[Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses]] provides the systematic SPR-based affinity measurements that underlie the FcγR-mediated mechanisms invoked in ADE and IC-driven autoimmunity. Key values relevant to dengue:

- **FcγRIIA-H131 vs. R131 for IgG1**: KA 52 vs. 35 ×10⁵ M⁻¹ (~1.5× difference only — not the large gap assumed in older models)
- **FcγRIIA-H131 vs. R131 for IgG2**: KA 4.5 vs. 1.0 ×10⁵ M⁻¹ (4.5× difference — the dominant allele-dependent effect)
- **FcγRIIIA-V158 for IgG3**: KA ~9.8×10⁶ M⁻¹ — crosses the high-/low-affinity threshold, enabling monomeric IgG3 binding; FcγRIIIA preferentially engages IgG3 (~5× higher affinity than IgG1)
- **FcγRIIB (inhibitory)**: KA ~1.2×10⁵ M⁻¹ for IgG1 — ~43× weaker than FcγRIIA-H131; can only function by co-engagement with activating receptors on the same IC

For ADE specifically: the predominant anti-dengue antibody isotype mediating ADE entry in secondary infection is IgG1 (IGHG1+ plasmablasts expanded in DHF per Sungnak2025). Both FcγRIIA variants bind IgG1 IC with similar efficiency (~52 vs ~35 ×10⁵ M⁻¹), suggesting the H131/R131 difference may not be the primary determinant of ADE efficiency for IgG1-mediated enhancement. FcγRIIIA-V158 vs. F158, by contrast, shows a larger fold-difference for IgG1 (~1.7×) and is the receptor implicated in ADE-related transcriptomic signatures (Sungnak2025).

## Rising XR E-IgG — Complication for the Classical Waning Model (Bos2025)

[[Bos2025 - Longitudinal Antibody Dynamics After Dengue]] introduces a finding that directly complicates the classical "waning immunity creates the ADE window" framework:

> **PREPRINT — not peer reviewed.**

- **XR E-IgG rises 6–18M post-primary** (t½ = −2.13 years). The standard model predicts that cross-reactive antibodies wane from an early post-infection peak, eventually dropping below the neutralisation threshold and converting from protective to enhancing. Bos2025 shows the opposite trajectory for cross-reactive E protein IgG: it is actively increasing in the 6–18M period.
- **Domain specificity:** The rising antibodies target **EDI/II** (the fusion/dimerisation interface; cross-reactive epitopes); **EDIII** antibodies (receptor-binding; more serotype-specific and neutralising) are flat. The expanding pool is thus enriched for non-neutralising cross-reactive antibodies — the class most likely to mediate ADE.
- **Implication:** The ADE risk window may not be created by passive waning of neutralising antibodies, but by active accumulation of a non-neutralising cross-reactive EDI/II-targeting IgG population. If correct, the ADE risk is not simply a function of time elapsed and concentration decay — it is driven by a parallel immunological process of cross-reactive antibody expansion that coincides with declining type-specific neutralising titres.
- **IgG3 persistence at 18M** adds kinetic evidence for sustained FcγRIIIA engagement (IgG3 has ~5× higher FcγRIIIA affinity than IgG1 per Bruhns2009) — relevant to ADE-related transcriptomic signatures seen in DHF (FcR/endocytosis pathway enrichment, Sungnak2025).

## Contradictions & Debates
- **Mechanism revision required for FcγRIIa-HH model:** The prior standard model held that HH genotype (H131) binds IgG1 poorly → ADE via failed clearance → IC accumulation. [[Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses]] contradicts this: H131 binds IgG1 slightly *more* efficiently than R131, not less. The FcγRIIa-H131/R131 difference is primarily for IgG2 (4.5× advantage for H131). The mechanism linking HH genotype to worse dengue outcomes therefore requires revision — it is not simply "impaired IgG1/IgG3 clearance." See [[FcγRIIa Receptor]] for the full discussion.
- **Transcriptomic ADE evidence is correlational:** The FcR/endocytosis pathway enrichment in Sungnak2025 is based on gene expression, not direct measurement of ADE. Whether these transcriptional signatures represent active ADE-mediated viral entry or a secondary consequence of severe inflammation requires experimental validation.
- **IgA as ADE antagonist vs. IgG as ADE mediator:** The contrasting isotype enrichment (IGHA1 in asymptomatic, IGHG1 in symptomatic) aligns well with the ADE model, but the specific target antigens of each isotype — and whether the IGHG1+ antibodies are actually non-neutralising cross-reactive ADE mediators — have not been established in this study.
- **Rising XR E-IgG vs. classical waning model (Bos2025, PREPRINT):** The standard model that ADE risk arises from waning cross-reactive antibodies dropping below the neutralisation threshold is complicated by Bos2025's finding that XR E-IgG (targeting EDI/II) *rises* 6–18M post-primary. Whether the rising pool is functionally enhancing (non-neutralising), and whether it contributes to ADE in a subsequent infection, is not established from kinetics data alone.

## Related Pages
- [[FcγRIIa Receptor]]
- [[Cross-Reactive Antibodies]]
- [[Cytokine Storm]]
- [[Asymptomatic Dengue Infection]]
- [[Autoimmunity in Dengue]]
- [[Infection-Triggered Autoimmunity]]
- [[Post-Dengue Syndrome]]
- [[Type I Interferon Response in Dengue]]
- [[T Cell Responses in Dengue]]
- [[V(D)J Sequencing]]
- [[Surface Plasmon Resonance]]

## Sources
- [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]] (background mention)
- [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]] (mechanistic framework)
- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]] (transcriptomic ADE evidence; IGHG1/IGHA1 isotype bias; public BCR clonotype)
- [[Guzman2016 - Dengue Infection]] (conditional virulence model; maternal antibody ADE; inter-infection interval; CYD-TDV clinical validation; DI-DII broadly neutralising Abs)
- [[Wan2012 - Autoimmunity in Dengue Pathogenesis]] (intrinsic ADE: IFN-I suppression, IL-10/Th2 skewing, autoimmunity link)
- [[Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses]] (SPR affinity hierarchy; FcγRIIA H131/R131 IgG2 asymmetry; FcγRIIIA-V158 monomeric IgG3 binding; FcγRIIB inhibitory weakness)
- [[Bos2025 - Longitudinal Antibody Dynamics After Dengue]] (rising XR E-IgG EDI/II 6–18M post-primary; IgG3 persistence at 18M; challenge to classical waning model; PREPRINT)
