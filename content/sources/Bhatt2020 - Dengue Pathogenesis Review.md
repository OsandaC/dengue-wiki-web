---
type: source
tags: [pathogenesis, sfRNA, RIG-I, TRIM25, interferon-evasion, ADE, OAS, original-antigenic-sin, T-cells, glycocalyx, cathepsin-L, heparanase, MIF, autophagy, cytokine-storm, Th2-skewing, NS1, review, India]
authors: [Bhatt P, Sabeena SP, Varma M, Arunkumar G]
year: 2021
journal: Current Microbiology
doi: 10.1007/s00284-020-02284-w
citations_semantic_scholar: 300
citations_crossref: 294
citations_retrieved: 2026-04-17
created: 2026-04-17
updated: 2026-04-17
---

# Bhatt2020 - Dengue Pathogenesis Review

**Full citation:** Bhatt P, Sabeena SP, Varma M, Arunkumar G. Current Understanding of the Pathogenesis of Dengue Virus Infection. *Current Microbiology* 2021; 78(1):17–32. https://doi.org/10.1007/s00284-020-02284-w

**Raw file:** `[[raw/Bhatt2020.pdf]]`

## Summary

This narrative review from Kasturba Medical College, Manipal Academy of Higher Education (Karnataka, India) synthesises pathogenesis mechanisms across dengue virus infection with emphasis on molecular immune evasion, cellular tropism, and the basis of severe dengue. The review incorporates mechanistic data from experimental and clinical studies published through approximately 2019.

The review covers three principal mechanistic axes: (1) viral immune evasion via non-coding RNA species and protein-mediated interferon antagonism; (2) immunopathogenesis driven by antibody-dependent enhancement and original antigenic sin; and (3) the downstream effector pathways — glycocalyx degradation, cytokine-mediated vascular permeability, and viral-autophagy interactions — that translate immune dysregulation into the haemorrhagic phenotype.

The Manipal group contextualises the review within an Indian/Southeast Asian epidemiological perspective, noting the dominance of the virulent Asian genotype of DENV-2 in the region. As a review article, the paper does not report original data but draws on key primary sources — including Manokaran 2015 (*Science*) for sfRNA/TRIM25/RIG-I, and Katzelnick et al. 2017 (*Science*) for quantitative ADE titres — that represent important mechanistic milestones not captured in the wiki's earlier sources.

## Study Design

- **Type:** Narrative review
- **Sample size:** Not applicable
- **Setting:** Kasturba Medical College, Manipal Academy of Higher Education, Manipal, Karnataka, India
- **Population:** Review of dengue pathogenesis literature; no primary patient cohort

## Key Findings

### sfRNA-mediated IFN evasion (via Manokaran 2015)
- DENV genomic RNA (11 kb positive-strand) is not fully degraded by the host 5′→3′ exoribonuclease XRN1; degradation stalls at secondary structures in the 3′ UTR, generating subgenomic flavivirus RNA (sfRNA) species of 0.3–0.5 kb
- Three sfRNA species are generated (sfRNA1, sfRNA2, sfRNA3); sfRNA1 is the most abundant
- **sfRNA1 binds TRIM25** (tripartite motif containing 25), a ubiquitin E3 ligase required for RIG-I activation: TRIM25 ubiquitinates RIG-I at K172, licensing downstream MAVS/IRF3 signalling and type I IFN production; sfRNA binding to TRIM25 blocks this ubiquitination step → RIG-I remains inactive → type I IFN production is suppressed (Manokaran et al. 2015, *Science* 350:217–221)
- sfRNA also inhibits Dicer, the endonuclease that generates small interfering RNAs (siRNAs) for RNAi-mediated antiviral defence — suppressing the siRNA antiviral pathway in parallel
- Implication: DENV uses its own non-coding degradation product as a dedicated IFN-suppression tool, enabling replication in cells where innate sensing would otherwise be rapidly triggered

### Quantitative ADE window (Katzelnick 2017)
- Using a prospective cohort of 6,684 Nicaraguan children aged 2–14 years followed from 2004 to 2013, Katzelnick et al. (2017) identified a **peak antibody-dependent enhancement window** for DENV: pre-existing anti-dengue antibody titres of **1:21–1:80** were associated with increased dengue hospitalisation risk (enhancement range)
- Below this window (<1:21): insufficient antibody to mediate FcR-mediated viral uptake → no enhancement
- Above this window (>1:1280): sufficient high-avidity neutralising antibody → protection (neutralisation dominates)
- The ADE window thus defines a quantitative immunological "danger zone" that individuals pass through as neutralising Ab titres wane after primary infection — or as vaccine-induced titres wane

### Original antigenic sin — T cell mechanism
- In secondary heterotypic DENV infection, pre-existing memory CD8+ T cells specific for the primary serotype have a lower activation threshold than naive T cells and are preferentially expanded
- These cross-reactive, **low-avidity** CD8+ T cells recognise heterologous epitopes on the secondary serotype with reduced affinity
- Their functional profile diverges from high-avidity serotype-specific T cells: they produce high levels of **TNF-α and IL-6** but lose cytolytic activity (reduced perforin/granzyme killing)
- The result is delayed viral clearance (cytolysis is impaired) combined with excessive pro-inflammatory cytokine release — prolonged T cell activation feeds the cytokine storm while the virus replicates longer, contributing to vascular permeability and DHF/DSS

### NS1 as ER replication complex cofactor
- Intracellular NS1 (ER-membrane form) functions as an **essential cofactor for the viral RNA replication complex**, associating with NS2A, NS2B, NS3, NS4A, and NS4B at the ER membrane to form the replicase complex
- This replication complex role is distinct from the secreted sNS1 pathogenic mechanisms; the intracellular NS1 pool is critical for viral genome amplification and has been proposed as a target for antivirals that would disrupt replication without triggering anti-NS1 autoantibodies

### Glycocalyx disruption via cathepsin L and heparanase
- NS1 activates **heparanase** (an endo-β-glucuronidase that degrades heparan sulfate proteoglycans, the major glycocalyx component) — promoting glycocalyx shedding from the endothelial surface
- NS1 also activates **cathepsin L** (a lysosomal cysteine protease that cleaves the heparan sulfate proteoglycan core proteins), providing a second enzymatic route to glycocalyx degradation
- Glycocalyx loss: (1) reduces the barrier function of the endothelial surface; (2) releases anticoagulant heparan sulfate chains into circulation, contributing to coagulopathy; (3) may expose integrin attachment sites, facilitating platelet-endothelial interactions

### MIF-autophagy pathway
- Macrophage migration inhibitory factor (MIF), a pro-inflammatory cytokine elevated during dengue infection, induces **autophagy** in DENV-infected cells
- Autophagy provides lipid droplets and amino acids as nutrient substrates for DENV replication on ER-derived autophagosomes — a "viral hijacking" of the autophagy pathway
- MIF-induced autophagy is therefore paradoxically beneficial to the virus despite being an innate immune response signal, and may explain why MIF elevation correlates with disease severity rather than protection

### Th1→Th2 shift and Treg IL-10
- In secondary infection, ADE-mediated FcγR viral entry into monocytes/macrophages suppresses IFN-γ (Th1 cytokine) while enhancing IL-10 production from T regulatory cells (Tregs) and CD4+ T cells
- This IL-10-driven Th1→Th2 shift inhibits virus clearance (Th1-dependent) while sustaining high antibody production — creating conditions for enhanced viral replication and ADE amplification
- IL-10 elevation in severe dengue is confirmed by multiple independent cohorts and is consistent with this regulatory feedback model

### DENV serotype-specific virulence
- **DENV-1 primary infection** produces higher circulating NS1 levels than DENV-2 primary infection; DENV-1 primary viraemia is also higher
- **DENV-2 secondary infection** produces the highest overall viraemia across infection orders
- The **Southeast Asian genotype** of DENV-2 replicates more efficiently in *Ae. aegypti* salivary glands and in human dendritic cells than the American DENV-2 genotype, with amino acid differences in NS proteins (particularly NS3) underlying the difference in replication fitness and epidemic potential

## Methods Used
- No primary methods; review synthesises published experimental and clinical data

## Entities Mentioned
- [[NS1 Protein]]
- [[prM Protein]]
- [[DENV-1]]
- [[DENV-2]]
- [[Aedes aegypti]]

## Concepts Addressed
- [[Antibody-Dependent Enhancement]]
- [[Original Antigenic Sin]]
- [[T Cell Responses in Dengue]]
- [[Type I Interferon Response in Dengue]]
- [[Cytokine Storm]]
- [[Dengue Pathophysiology]]
- [[NS1 Molecular Mimicry in Dengue]]
- [[Dengue Vaccine Candidates]]
- [[Cross-Reactive Antibodies]]

## Relevance & Notes
Bhatt2020 serves three primary functions in the wiki:

1. **sfRNA/TRIM25/RIG-I mechanism** — this is the first source in the wiki to provide molecular detail on how DENV suppresses type I IFN at the level of a specific viral RNA species and its target ubiquitin ligase. Prior sources (Sungnak2025, Guzman2016) documented IFN elevation in severe dengue and IFN-β-mediated bone marrow suppression but did not explain how the virus modulates innate sensing to survive. The sfRNA mechanism accounts for why innate sensing may be inadequate despite RIG-I expression.

2. **Katzelnick 2017 quantitative ADE window** — prior wiki sources (Guzman2016, Wan2012, Dejnirattisai2010) established the ADE mechanism qualitatively. Bhatt2020 brings in the Katzelnick titer data that converts the conceptual model into a quantitative prediction: 1:21–1:80 is the zone where partial immunity is actively harmful. This has direct implications for vaccine design — a vaccine whose titre wanes into this range post-immunisation may temporarily increase risk.

3. **OAS T cell mechanism** — the Original Antigenic Sin page previously had only one source (Guzman2016, a review-level summary). Bhatt2020 provides a mechanistic description of the low-avidity CD8+ expansion, cytolytic loss, and cytokine excess that is distinct from the existing content.

The glycocalyx/cathepsin L/heparanase and MIF-autophagy content fills mechanism-level gaps in Dengue Pathophysiology and Cytokine Storm pages.

Limitation: as a narrative review, the paper does not provide systematic evidence quality assessment; some cited mechanisms (e.g., MIF-autophagy) rest on limited in vitro data.

## Questions Raised
- The sfRNA/TRIM25 mechanism (Manokaran 2015) was shown in cell lines — has it been confirmed in primary human monocytes/DCs, which are the primary DENV target cells in vivo?
- If the quantitative ADE window is 1:21–1:80, what are the post-vaccination antibody titre trajectories for CYD-TDV, TAK-003, and TV003 in seronegative and seropositive recipients? Are waning vaccinee titres predicted to pass through the enhancement window?
- Does sfRNA suppress innate immunity in all target cell types equally, or is there differential TRIM25 expression between monocytes/DCs (where DENV replicates) and hepatocytes/endothelial cells (where secondary pathology occurs)?
- What is the half-life of anti-DENV titres after primary infection in the context of the Katzelnick enhancement window — how long does the average individual spend in the 1:21–1:80 range?
- The MIF-autophagy pathway promotes viral replication — would MIF antagonists (currently in trials for other conditions) reduce DENV severity, and at what cost to immunological control?
