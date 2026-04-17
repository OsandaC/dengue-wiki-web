---
type: concept
tags: [interferon, IFN-alpha, innate-immunity, immunopathogenesis, TLR, RIG-I, sfRNA, TRIM25, XRN1, Dicer, siRNA, immune-evasion]
created: 2026-04-12
updated: 2026-04-17
sources: 3
---

# Type I Interferon Response in Dengue

## Overview

Type I interferons (primarily IFN-α and IFN-β) are central antiviral cytokines induced by innate immune sensing of viral RNA. They signal through the IFNAR receptor to upregulate hundreds of interferon-stimulated genes (ISGs), restrict viral replication, and activate immune effectors. In dengue, the type I IFN response is paradoxical: while essential for antiviral defence, it is also associated with disease severity, potentially contributing to immunopathology when sustained or excessive.

DENV is sensed by multiple pattern recognition receptors including TLR2, TLR4, TLR6, TLR8 (endosomal), and the cytosolic RNA sensors DDX58 (RIG-I) and IFIH1 (MDA5). DENV also encodes NS2B/NS3 and NS4B proteins that antagonise the interferon response, allowing it to replicate despite innate immune activation.

## Key Points from Literature

**IFN-α2 elevation in symptomatic dengue:**
Sungnak2025 (see [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]) measured plasma IFN-α2 protein by Luminex in an expanded dataset. IFN-α2 was significantly elevated in symptomatic dengue (DF and DHF) compared with asymptomatic dengue (P < 0.05, Kruskal-Wallis + Dunn's test). This systemic IFN-α elevation corresponded to transcriptional enrichment of the hallmark IFN-α response gene set in multiple PBMC populations in symptomatic dengue cases.

**Transcriptomic evidence for IFN-driven pathology:**
In symptomatic dengue (particularly DHF), scRNA-seq identified enrichment of innate immunity-related genes including TLR2, TLR4, TLR6, TLR8, DDX58 (RIG-I), IFIH1 (MDA5), and EIF2AK2 (encoding PKR/protein kinase R — an ISG that inhibits translation). The enrichment of receptor-mediated endocytosis and Fc receptor signalling pathways in DHF suggests antibody-mediated DENV entry (ADE) as a trigger for this amplified IFN response: FcγR-mediated endocytosis delivers DENV RNA to endosomal TLRs, enhancing innate sensing.

**Proposed mechanism:** ADE-mediated viral entry → endosomal TLR activation → type I IFN → ISG upregulation → PKR activation → translation inhibition → and a systemic inflammatory amplification loop. This is analogous to the pathological IFN-α response described in severe COVID-19.

**Comparison to COVID-19:** Sungnak2025 draws an explicit parallel to COVID-19, where excessive type I IFN response contributes to disease pathology (Stephenson et al. 2021; Yoshida et al. 2022). The authors note the association with dengue severity appears at least as pronounced. Anti-IFN autoantibodies (anti-IFN-α, anti-IFN-ω) implicated in severe COVID-19 were not found to differ across dengue severity groups in Sungnak2025's 120-antigen autoantibody panel — arguing against this particular mechanism in the studied (primarily young, Thai adult) population.

**Pattern recognition receptor genes as disease markers:** The enrichment of TLR and RIG-I/MDA5 pathway genes across severity groups suggests these could serve as transcriptomic biomarkers of DENV disease progression, though the study was not designed to validate clinical utility.

## IFN-β and bone marrow suppression (Guzman2016)

Guzman2016 introduces IFN-β (type I interferon) as the proposed mediator of bone marrow suppression in the early febrile phase of dengue, with the evidence based on analogy with an animal model (see [[Guzman2016 - Dengue Infection]]):

- During the febrile phase of dengue, all haematopoietic lineages are suppressed — red cells, platelets, and white cells
- In animal models of lymphocytic choriomeningitis virus (LCMV), IFN-β has been shown to suppress haematopoiesis
- By analogy, DENV-induced IFN-β is proposed to suppress megakaryocyte differentiation in the bone marrow during the early febrile phase, contributing to the thrombocytopaenia that peaks at defervescence
- Bone marrow megakaryocyte arrest resolves near the end of the febrile period — platelet count recovery typically begins after the nadir at defervescence

**Relationship to Sungnak2025**: Sungnak2025 documents elevated plasma IFN-α2 (not IFN-β specifically) in symptomatic dengue associated with a transcriptional IFN-α response gene set enrichment. The two IFN subtypes may serve distinct roles: IFN-β in bone marrow suppression (via DENV-infected haematopoietic progenitors or stromal cells), and IFN-α in peripheral immune cell activation and immunopathology in severe disease.

## sfRNA-mediated IFN suppression — viral immune evasion mechanism (Bhatt2020)

[[Bhatt2020 - Dengue Pathogenesis Review]] introduces a key molecular mechanism by which DENV actively suppresses type I IFN production that is absent from the other sources in this wiki.

**Generation of sfRNA:** The host 5′→3′ exoribonuclease XRN1 degrades DENV genomic RNA but stalls at secondary structures in the 3′ UTR, generating **subgenomic flavivirus RNA (sfRNA)** fragments of approximately 0.3–0.5 kb. Three sfRNA species are produced (sfRNA1, sfRNA2, sfRNA3); sfRNA1 is most abundant.

**Mechanism of RIG-I inhibition:** sfRNA1 binds **TRIM25** (tripartite motif-containing 25), the ubiquitin E3 ligase required for RIG-I activation. Normally, TRIM25 ubiquitinates RIG-I at K172 → licensed RIG-I signals through MAVS → IRF3 phosphorylation → IFN-β transcription. By sequestering TRIM25, sfRNA blocks this ubiquitination step, leaving RIG-I inactive → type I IFN production is suppressed despite cytosolic double-stranded RNA being present (primary evidence in Manokaran et al. 2015, *Science* 350:217–221, as cited in Bhatt2020).

**Parallel siRNA pathway suppression:** sfRNA also inhibits **Dicer**, the endonuclease that generates siRNAs from dsRNA. This suppresses the RNAi-mediated antiviral pathway in parallel with the IFN pathway, providing dual coverage of innate RNA sensing.

**Relationship to existing wiki content on IFN-α2 elevation (Sungnak2025):** Sungnak2025 documents elevated plasma IFN-α2 in symptomatic dengue — which may appear paradoxical given the sfRNA mechanism. The two are not contradictory: (1) sfRNA suppresses IFN in the primary infected cells (monocytes/DCs — where DENV needs to replicate), but neighbouring uninfected cells that receive paracrine IFN signals are not subject to sfRNA-mediated suppression; (2) the elevated systemic IFN-α2 in severe dengue may represent a second-wave response from non-infected innate cells (pDCs, NK cells) reacting to danger signals and viral products circulating at high titre during secondary infection. The sfRNA mechanism explains an early escape window at the level of the infected cell; the eventual systemic IFN-α2 elevation reflects a response that overwhelms this evasion.

## Contradictions & Debates

The relationship between type I IFN and dengue severity is not fully resolved. In some experimental models, IFN-α/β are protective; in severe clinical disease, they appear pathological. Whether the elevated IFN-α2 in symptomatic dengue is causally driving immunopathology, or is merely a marker of higher viral burden, cannot be determined from Sungnak2025's design alone. Viremia was matched across severity groups, which argues against a simple "more virus → more IFN" interpretation, but the matched groups had overlapping viremia ranges.

The asymptomatic dengue group in Sungnak2025 did not show IFN-α enrichment despite having detectable viremia, suggesting that the IFN response amplitude is not simply proportional to viral load but may be shaped by the mode of viral entry (ADE vs. direct infection) or by pre-existing immune state.

## Related Pages

- [[Antibody-Dependent Enhancement]]
- [[T Cell Responses in Dengue]]
- [[NK Cell Responses in Dengue]]
- [[Asymptomatic Dengue Infection]]
- [[NS1 Protein]]

## Sources

- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]
- [[Guzman2016 - Dengue Infection]] (IFN-β and bone marrow suppression in early febrile phase; LCMV analogy)
- [[Bhatt2020 - Dengue Pathogenesis Review]] (sfRNA1 biogenesis from XRN1 stalling; TRIM25 sequestration → RIG-I K172 ubiquitination block → IFN-β suppression; Dicer inhibition → siRNA pathway suppression; three sfRNA species; review of Manokaran 2015 mechanism; India review)
