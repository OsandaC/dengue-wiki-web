---
type: method
tags: [flow-cytometry, autoantibody-detection, anti-platelet, anti-endothelial, FITC, FACScan, IgM, IgG, dengue, DHF, Taiwan, Vietnam, Thailand, autoimmunity]
created: 2026-04-19
updated: 2026-04-19
sources: 3
---

# Flow Cytometry

## Overview

Flow cytometry is a laser-based technique that simultaneously measures multiple physical and fluorescent characteristics of cells or particles in suspension. In dengue research, it has been used primarily for detecting and quantifying autoantibodies in patient sera that bind to the surface of fixed platelets or endothelial cells — the key experimental approach for characterising anti-platelet and anti-endothelial autoantibodies in DHF/DSS. The method offers the advantage of measuring antibody binding activity on intact, physiologically relevant cell surfaces rather than on coated plate antigens, making it sensitive to conformational epitopes that ELISA may miss.

## Key Points from Literature

### Anti-platelet autoantibody detection in dengue (Lin2001, Hung2008)

The core protocol established by [[Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients]] (Taiwan) and applied by [[Hung2008 - Anti-Platelet Anti-Endothelial Autoantibodies Vietnam]] (Vietnam):

1. Platelet-rich plasma (PRP) isolated from normal healthy donors by differential centrifugation; washed and fixed in 1% formaldehyde in PBS
2. 2.5×10⁶ fixed platelets incubated with diluted patient or control serum (1:25) for 1 h on ice
3. FITC-conjugated goat anti-human IgG or anti-human IgM secondary antibody added (10 µL; Sigma C.); incubated 40 min on ice
4. Analysis by FACScan (Becton Dickinson, Mountain View, CA); excitation 488 nm; percentage of platelets in the reactive gate reported as the output metric

Key quantitative outputs from this protocol:
- Lin2001 (Taiwan, DENV-3, n=9 DHF/DSS + controls): anti-platelet IgM 34.6 ± 4.1% reactive in DHF/DSS vs 28.0 ± 2.4% in DF; MFI divergence (276 vs 140) larger than percentage divergence
- Hung2008 (Vietnam, DENV-2/3/4, n=50 infants + 37 children): anti-platelet IgM infants 16.5 ± 8.6% vs controls 1.5 ± 1.2% (p<0.001); children 11.0 ± 8.2% vs controls 3.2 ± 1.0% (p<0.001)

### Anti-endothelial cell autoantibody detection (Lin2006 principle, Hung2008)

Same NCKU group protocol using HUMEC-1 (human microvascular endothelial cell line, CDC Atlanta) in place of platelets:

1. HUMEC-1 cells suspended at 5×10⁵ per assay; fixed in 1% formaldehyde 10 min; washed
2. Patient sera incubated with cells at 4°C for 1 h; washed three times
3. FITC-conjugated goat anti-human IgG or IgM secondary antibody (5 µL) added; incubated 1 h at 4°C
4. FACScan analysis; excitation 488 nm; percentage of HUMEC-1 cells reactive reported

Key quantitative outputs from Hung2008:
- Infants (predominantly primary): anti-EC IgM 17.6 ± 10.5% vs controls 4.0 ± 1.9% (p=0.003); anti-EC IgG not significantly elevated
- Children (predominantly secondary): anti-EC IgM 46.0 ± 15.3% vs controls 4.7 ± 0.5% (p<0.001); anti-EC IgG 25.1 ± 8.5% vs controls 2.6 ± 0.5% (p<0.001)

### Asymptomatic vs. symptomatic dengue — single-cell transcriptomics (Sungnak2025)

[[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]] (Thailand DENFREE cohort) used flow cytometry in combination with single-cell RNA sequencing (scRNA-seq) for immune cell phenotyping rather than autoantibody detection:
- NK cell surface phenotyping: FcεRIγ expression on NK cells as an asymptomatic-enriched phenotype
- Plasmablast sorting by flow cytometry prior to V(D)J sequencing
- T cell immunophenotyping (CD8 TEM effector vs. exhausted)

This application differs fundamentally from the Lin/Hung autoantibody protocols above — using flow cytometry as a cell-sorting and phenotyping tool rather than a plate-binding assay for antibody detection.

## Contradictions & Debates

- Percentage of reactive cells as the output metric in the NCKU anti-platelet/anti-EC protocol depends on gate settings and platelet/cell preparation variability. Mean fluorescence intensity (MFI) may be a more sensitive readout for comparing autoantibody levels across groups — Lin2001 showed MFI divergence between DF and DHF/DSS was proportionally larger than percentage divergence.
- The Lin2001/Hung2008 protocols use fixed cells; fixation may denature some conformational epitopes. Whether native surface epitopes are fully preserved after 1% formaldehyde fixation has not been systematically validated for dengue autoantibody applications.

## Related Pages

- [[NS1 Molecular Mimicry in Dengue]]
- [[Autoimmunity in Dengue]]
- [[NS1 Protein]]
- [[Platelet-Associated Immunoglobulin ELISA]]
- [[Single-Cell RNA Sequencing]]

## Sources

- [[Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients]] (original application of flow cytometry for anti-platelet IgM detection in dengue; DENV-3 Taiwan 1998–99; FACScan protocol established; MFI and % reactive platelets reported; absorption with NS1 confirms cross-reactivity)
- [[Hung2008 - Anti-Platelet Anti-Endothelial Autoantibodies Vietnam]] (same NCKU flow cytometry protocol applied to Vietnamese paediatric cohort; both anti-platelet and anti-EC IgM/IgG; first application to infants with primary dengue in endemic setting; Vietnam/NCKU collaboration)
- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]] (flow cytometry for immune cell phenotyping and plasmablast sorting; NK FcεRIγ surface phenotype; Thailand DENFREE cohort; different application from autoantibody detection protocols)
