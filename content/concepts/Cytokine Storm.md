---
type: concept
tags: [cytokines, immunopathogenesis, IL-10, TNF-alpha, IFN-alpha, vascular-permeability, plasma-leakage, DHF, DSS, TLR4, NS1, bystander-activation, MAS, macrophage-activation-syndrome, HLH, hyperferritinemia, MIF, autophagy, Th2-skewing, Treg, cytotoxic-factor, hCF]
created: 2026-04-13
updated: 2026-04-18
sources: 12
---

# Cytokine Storm

## Overview
Cytokine storm in dengue refers to the excessive and dysregulated release of pro-inflammatory and immunomodulatory cytokines during acute infection, particularly in severe dengue (DHF/DSS). It is one of several converging mechanisms — alongside ADE, autoantibody-mediated damage, and direct NS1 effects — that drive vascular permeability, thrombocytopenia, and coagulopathy. The term encompasses a complex network of mediators including IL-10, TNF-alpha, IFN-alpha, IL-6, IL-8, MCP-1, MIF, and MMP-9, each with distinct cellular sources and downstream effects.

Importantly, cytokine storm is not a single mechanism but a downstream consequence of multiple upstream triggers: ADE-enhanced viral replication in FcR-bearing cells, T cell overactivation via original antigenic sin, NS1-TLR4 signalling, and bystander innate immune activation. These pathways feed into each other, making the relative contribution of each difficult to dissect.

## Key Points from Literature

### Key cytokines and their roles

#### IL-10
IL-10 is the cytokine most consistently associated with dengue severity in this wiki's sources:
- Plasma IL-10 is significantly elevated in DHF versus asymptomatic dengue (P < 0.05); correlates strongly with plasmablast abundance (Spearman rho = 0.757, P = 1.13 x 10^-4) (see [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]])
- **Cellular source:** CD4 proliferating T cells are the highest expressers of IL10 in DHF; CellChat analysis predicts IL-10/IL-10R signalling from these T cells to plasmablasts, driving IgG1+ plasmablast expansion (see [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]])
- IL-10 correlates with platelet loss in dengue patients (see [[Wan2012 - Autoimmunity in Dengue Pathogenesis]])
- IL-10 ACC/ATA haplotype combined with TNF-308A is associated with susceptibility to DSS in the Cuban population (see [[Guzman2016 - Dengue Infection]])
- In the intrinsic ADE model, FcgammaR-mediated viral entry enhances IL-10 production, which suppresses IFN-gamma signalling and promotes Th2 skewing — a positive feedback loop favouring antibody production over viral clearance (see [[Wan2012 - Autoimmunity in Dengue Pathogenesis]], [[Antibody-Dependent Enhancement]])
- **IL-10 directly induces T cell apoptosis** in acute dengue: IL-10 blockade significantly reduces T cell apoptosis; reduced T cell numbers have been documented in DHF vs. DF patients (Green 1999; Mathew & Rothman 2008, as reviewed in [[Pang2017 - DHF Pathogenesis Review]]). This adds a cytotoxic arm to IL-10's role beyond immunosuppression: not only does IL-10 suppress Th1 killing, it actively eliminates T cells — compounding the viral clearance deficit (see [[T Cell Responses in Dengue]])

#### IFN-alpha (Type I Interferon)
- Plasma IFN-alpha2 is significantly elevated in symptomatic dengue (DF and DHF) versus asymptomatic infection (P < 0.05, Kruskal-Wallis + Dunn's test) (see [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]])
- The hallmark IFN-alpha response gene set is enriched across multiple PBMC populations in symptomatic dengue
- ADE-mediated viral entry may amplify IFN signalling: FcgammaR-mediated endocytosis delivers DENV RNA to endosomal TLRs (TLR2, TLR4, TLR6, TLR8), triggering innate sensing cascades (see [[Type I Interferon Response in Dengue]])
- IFN-beta (distinct from IFN-alpha) is proposed to mediate bone marrow suppression during the early febrile phase, contributing to thrombocytopenia by suppressing megakaryocyte differentiation (see [[Guzman2016 - Dengue Infection]])
- Anti-IFN autoantibodies (implicated in severe COVID-19) were not significantly different across dengue severity groups in a 120-antigen autoantibody panel (see [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]])

#### TNF-alpha
- TNF-alpha triggers endothelial activation and increases vascular permeability (see [[Wan2012 - Autoimmunity in Dengue Pathogenesis]])
- ADE enhances TNF-alpha-mediated endothelial activation as part of the intrinsic ADE pathway (see [[Wan2012 - Autoimmunity in Dengue Pathogenesis]])
- TNF-308A polymorphism is a genetic risk factor for DSS in the Cuban population (see [[Guzman2016 - Dengue Infection]])

#### Other mediators
- **MIF, MMP-9, MCP-1:** all promote vascular permeability (see [[Wan2012 - Autoimmunity in Dengue Pathogenesis]])
- **IL-6, IL-8:** upregulated by anti-NS1 autoantibody-mediated NF-kappaB activation in endothelial cells — linking the autoimmune pathway to cytokine release (see [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]], [[NS1 Molecular Mimicry in Dengue]])
- **ICAM-1:** upregulated on endothelium by anti-NS1-driven NF-kappaB activation; promotes PBMC adhesion and further inflammation (see [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]])

### NS1-TLR4 as a direct cytokine trigger
Soluble NS1 (sNS1) activates TLR4 on macrophages and PBMCs — analogous to LPS/endotoxin recognition — triggering pro-inflammatory cytokine release independently of antibodies. This mechanism can operate in primary infection before anti-NS1 Abs are generated and may be the earliest trigger of the cytokine cascade (see [[Guzman2016 - Dengue Infection]], [[NS1 Protein]], [[Dengue Pathophysiology]]).

### Bystander activation and polyclonal immune stimulation
Cytokine storm can drive non-specific polyclonal B and T cell activation (bystander activation): IFN-alpha/gamma, IL-1, IL-6, and TNF released during infection activate plasmacytoid dendritic cells, which in turn drive polyclonal B cell activation and transient autoantibody production (see [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]], [[Infection-Triggered Autoimmunity]]). However, the COVID-19 comparison (Trahtemberg et al., cited in Johnson2022) found no significant ANA difference between COVID-19-positive and -negative ICU patients — suggesting bystander activation from severe cytokine storm alone is insufficient to consistently elevate ANA.

### Original antigenic sin amplifies cytokine production
In secondary heterotypic infection, low-affinity memory T cells from the primary infection expand selectively (original antigenic sin). These cross-reactive T cells produce inflammatory cytokines (TNF-alpha, IFN-gamma) that drive plasma leakage, but clear the new serotype inefficiently — a proposed mechanism for why secondary infection is more severe (see [[Wan2012 - Autoimmunity in Dengue Pathogenesis]], [[Original Antigenic Sin]], [[T Cell Responses in Dengue]]).

Bhatt2020 specifies the functional correlate: **low-avidity CD8+ T cells produce elevated TNF-α and IL-6** specifically while losing cytolytic activity — meaning the cytokine excess is not merely a by-product of vigorous killing but occurs in the absence of adequate viral clearance. This decoupling of inflammation from viral control is the mechanistic basis for why OAS amplifies the cytokine storm rather than resolving it (see [[Bhatt2020 - Dengue Pathogenesis Review]]).

### MIF-autophagy: a viral amplifier of cytokine-linked pathology (Bhatt2020)

Macrophage migration inhibitory factor (MIF), a pro-inflammatory cytokine elevated during dengue, induces **autophagy** in DENV-infected cells (see [[Bhatt2020 - Dengue Pathogenesis Review]]). DENV hijacks the autophagic flux — using lipid droplets and amino acids from autophagosomes as nutrient substrates for replication on ER-derived membranes. The implication is that MIF, despite being an inflammatory cytokine, paradoxically promotes viral replication by triggering a nutrient-mobilisation pathway the virus exploits:

- MIF elevation (part of the cytokine storm) → autophagy induction → increased viral replication → more virus → more antigen → amplified immune response → more MIF
- This positive feedback may partly explain why MIF elevation correlates with disease severity

### Th2 skewing and Treg IL-10 in secondary infection (Bhatt2020)

[[Bhatt2020 - Dengue Pathogenesis Review]] consolidates the Th1→Th2 shift mechanism in secondary DENV infection:

- ADE-mediated FcγR viral entry into monocytes/macrophages suppresses IFN-γ (Th1 cytokine) production while enhancing IL-10 output
- **IL-10 is produced by T regulatory cells (Tregs) as well as CD4+ T cells** — consistent with Sungnak2025's finding that CD4 proliferating T cells are the highest IL10 expressers in DHF, and extending the cellular source to include Tregs
- IL-10-driven Th2 skewing: inhibits virus clearance (Th1/CD8+ cytolytic killing dependent) while sustaining high antibody production → creates conditions for ADE amplification in a positive feedback loop
- This mechanism is the molecular link between intrinsic ADE and the high IL-10 levels consistently documented in severe dengue (see [[Antibody-Dependent Enhancement]])

### Temporal dynamics
The cytokine cascade follows a characteristic time course:
- Cytokine accumulation occurs throughout the febrile phase
- Vascular permeability peaks at **defervescence**, not during peak viraemia — suggesting threshold-dependent cytokine-mediated effects rather than direct viral cytopathology (see [[Dengue Pathophysiology]])
- Resolution is typically rapid (24-36 hours in non-fatal cases), consistent with a reversible soluble-mediator mechanism rather than structural endothelial damage

### Cytotoxic Factor (hCF) — a dengue-specific CD4-T-cell cytokine (Chaturvedi2001)

> **⚠ Caveat:** hCF is characterised exclusively by the Chaturvedi group; no independent replication exists. The following should be treated as hypothesis-generating.

[[Chaturvedi2001 - Cytotoxic Factor Autoantibodies DHF]] describes a dengue-specific cytokine produced by CD4+ T cells during DENV infection (see also [[Cytotoxic Factor in Dengue]]):

- hCF is produced rapidly by CD4+ T cells once DENV replicates in macrophages; its amino-terminal sequence has no homology with any known protein or cytokine
- **hCF cascade:** hCF → macrophages produce free radicals, nitrite, reactive oxygen species, peroxynitrite → (a) target cell apoptosis; (b) upregulation of IL-1α, TNF-α, IL-8, H₂O₂ in macrophages
- Change in IL-12/TGF-β balance shifts Th1 → Th2-biased response → disease exacerbation; vascular permeability increased via combined histamine, free radicals, pro-inflammatory cytokines, and complement products
- hCF levels are **highest in DHF grade IV** (companion paper, ref [9] of Chaturvedi2001), the mirror image of the anti-hCF autoantibody pattern
- **Anti-hCF autoantibodies** are present in 96% of DF patients but only 8% of DHF grade IV patients (P ≤ 0.001) — suggesting that patients who mount this anti-cytokine response are protected from severe disease (see [[Autoimmunity in Dengue]])

If confirmed, this represents an additional upstream driver of the cytokine cascade that is distinct from NS1-TLR4, ADE-mediated entry, and OAS T cell overactivation — all operating earlier in the infection before the known cytokine storm triggers become dominant.

### Macrophage Activation Syndrome — Extreme End of the Cytokine Spectrum

[[Morel2014 - Autoimmune Response in Children With Dengue]] documents dengue-triggered Macrophage Activation Syndrome (MAS/secondary HLH) in two Paraguayan paediatric patients. MAS represents the most extreme form of dengue-associated cytokine dysregulation and is characterised by macrophage/CD8+ T cell hyperactivation rather than by autoantibody production. Key cytokine correlates in MAS include IL-18, IFN-gamma, and IL-6 (not directly measured in Morel2014, but established in HLH pathophysiology literature).

The dengue-specific triggers of macrophage hyperactivation in these cases likely include NS1-TLR4 activation (sNS1 acting as a macrophage-activating signal), ADE-mediated FcγR entry amplifying intracellular viral replication in macrophages, and possibly direct DENV infection of macrophages. The result is a positive feedback loop: macrophage activation → cytokine release → further macrophage recruitment → spiralling hyperferritinemia (Case 3: 3828 mg/dl) and cytopenias.

Critically, these MAS cases were **ANA and anti-dsDNA negative** — confirming that macrophage-driven cytokine storm in dengue does not require or produce nuclear autoantibodies. This distinguishes the MAS mechanism from the NS1 molecular mimicry → anti-platelet/anti-endothelial antibody pathway (see [[NS1 Molecular Mimicry in Dengue]]).

[[Palacios2016 - Autoimmunity in Dengue Literature Review]] adds a MAS case with nephrotic syndrome (Lai et al. 2012), extending the dengue-MAS spectrum to adults and documenting renal involvement. See [[Macrophage Activation Syndrome in Dengue]] for the full clinical characterisation.

## Contradictions & Debates
- **Cause vs. consequence:** Elevated cytokines in severe dengue may be driving pathology or may be markers of a more vigorous but ultimately appropriate immune response to higher intracellular viral loads (from ADE). Sungnak2025 matched viremia across severity groups, partially addressing this — but intracellular viral burden in tissue-resident macrophages is not captured by plasma viremia measurement.
- **IFN-alpha paradox:** IFN-alpha is essential for antiviral defence, yet elevated in severe disease. Whether the problem is too much IFN-alpha, the wrong timing, or an ADE-amplified IFN response to endosomally delivered viral RNA remains unresolved (see [[Type I Interferon Response in Dengue]]).
- **IL-10: pathogenic or regulatory?** IL-10 is conventionally anti-inflammatory, yet consistently elevated in severe dengue. In the intrinsic ADE model, IL-10 suppresses Th1 clearance while driving antibody (and potentially ADE-capable Ab) production — a context-dependent pathogenic role.
- **Multiple competing models:** NS1-TLR4, T cell-mediated cytokine release, ADE-amplified innate sensing, and anti-NS1 autoantibody-mediated NF-kappaB activation all converge on cytokine production. No single pathway accounts for all observations, and their relative contributions likely vary by infection sequence, host genetics, and viral genotype.

## Related Pages
- [[Dengue Pathophysiology]]
- [[Antibody-Dependent Enhancement]]
- [[NS1 Protein]]
- [[NS1 Molecular Mimicry in Dengue]]
- [[Macrophage Activation Syndrome in Dengue]]
- [[Type I Interferon Response in Dengue]]
- [[T Cell Responses in Dengue]]
- [[Original Antigenic Sin]]
- [[Infection-Triggered Autoimmunity]]
- [[Secondary Dengue Infection]]

## Sources
- [[Chaturvedi2001 - Cytotoxic Factor Autoantibodies DHF]] (hCF — dengue-specific CD4 T cell cytokine; macrophage free radical + IL-1α/TNF-α/IL-8 cascade; Th1→Th2 shift; anti-hCF autoantibody inverse correlation with DHF severity 96% DF → 8% DHF-IV; n=136, 1996 North India epidemic; ⚠ group-specific concept)
- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]] (IL-10/plasmablast axis; IFN-alpha2 elevation; CD4 T cell IL10 expression; anti-IFN autoantibody negative finding)
- [[Wan2012 - Autoimmunity in Dengue Pathogenesis]] (intrinsic ADE cytokine amplification; IL-10/platelet correlation; TNF-alpha endothelial activation; MIF/MMP-9/MCP-1; OAS cytokine production)
- [[Guzman2016 - Dengue Infection]] (NS1-TLR4 cytokine trigger; IFN-beta bone marrow suppression; IL-10/TNF haplotype genetics; vascular permeability onset at defervescence)
- [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]] (bystander activation via cytokines; IFN-alpha/pDC/polyclonal B cell pathway; COVID-19 ANA comparator)
- [[Morel2014 - Autoimmune Response in Children With Dengue]] (dengue-triggered MAS as extreme cytokine storm; ANA-negative; responded to methylprednisolone; hyperferritinemia 3828 mg/dl in most severe case)
- [[Palacios2016 - Autoimmunity in Dengue Literature Review]] (additional MAS + nephrotic syndrome case; literature context for dengue-MAS as cytokine-driven complication)
- [[Oishi2003 - PAIgG and Thrombocytopenia in Secondary Dengue]] (complement activation invoked in secondary-infection platelet clearance; immune-complex-driven macrophage engagement)
- [[Vo2020 - Autoantibody Profiling in Dengue]] (cytokine storm cited as background pathogenesis mechanism; deregulated T cell compartment and elevated cytokines invoked to explain autoreactive antibody production during acute DENV infection)
- [[Bhatt2020 - Dengue Pathogenesis Review]] (MIF-autophagy viral amplification loop; OAS CD8+ T cell TNF-α/IL-6 excess without cytolytic clearance; Th1→Th2 shift mechanism; IL-10 from Tregs + CD4 T cells; review, India)
- [[Pang2017 - DHF Pathogenesis Review]] (IL-10 → T cell apoptosis mechanism reviewed; reduced T cell numbers in DHF vs DF; IL-10 blockade reduces apoptosis; anti-NS1 NF-κB → IL-6/IL-8/MCP-1 pathway confirmed; review, China)
- [[Farias2024 - Dengue Mimickers]] (cytokine storm cited as background mechanism driving dengue severity; COVID-19 parallel noted — both SARS-CoV-2 and DENV trigger cytokine storm with shared clinical features; Brazil narrative review — secondary source)
