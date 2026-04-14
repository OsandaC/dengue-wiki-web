---
type: method
tags: [SPR, BIAcore, affinity, binding-kinetics, FcR, IgG, in-vitro]
created: 2026-04-13
updated: 2026-04-13
sources: 1
---

# Surface Plasmon Resonance

## Overview
Surface plasmon resonance (SPR) is a label-free optical biosensor technique that measures molecular binding interactions in real time by detecting changes in the refractive index near a sensor chip surface. One binding partner (the ligand) is immobilised on the chip; the other (the analyte) is flowed over it. The change in resonance units (RU; 1 RU ≈ 1 pg/mm²) as analyte binds and dissociates reflects the kinetics and equilibrium affinity of the interaction. SPR is the gold-standard method for determining binding affinity constants (KA, KD) and kinetic rate constants (kon, koff) for protein–protein interactions, including antibody–receptor binding.

In the context of Fc receptor biology, SPR is used to measure the affinity of soluble FcγR ectodomains (immobilised on the chip) for IgG subclasses (analyte in solution). For polyclonal IgG preparations — where kinetic constants cannot be reliably extracted due to heterogeneity — affinity is determined from the concentration-dependence of the steady-state signal (Req) at the end of injection.

## Key Points from Literature
- [[Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses]] used SPR (BIAcore 2000 biosensor; CM5 sensor chip; immobilised soluble FcγR ectodomains at ~1500–2650 RU; analyte injected at 20 µL/min; contact time 300 s, dissociation 900 s) to measure affinity of all 6 human FcγRs and all known polymorphic variants for polyclonal IgG1, IgG2, IgG3, and IgG4. This is the primary SPR-based reference for hFcγR–IgG affinity constants in the dengue wiki.
- Varying immobilised FcγR density (1200–2700 RU) did not significantly affect steady-state affinities — confirming that surface crowding effects were not confounding the measurements.
- FcγR ectodomains were N-glycosylated (verified by PNGase F treatment), which is required for correct IgG binding; unglycosylated IgG does not bind FcγRs.
- The high-/low-affinity threshold for FcγRs is operationally defined at KA ~9×10⁶ M⁻¹: receptors with KA above this threshold can bind monomeric IgG; below it, they only bind immune complexes or aggregated IgG with high avidity.

## Contradictions & Debates
- SPR measures affinity in a cell-free system using soluble ectodomains immobilised on a chip surface. In vivo, receptors are embedded in cell membranes, often clustered, and subject to lateral diffusion and co-receptor interactions. Two-dimensional cell-surface affinities (measured by fluorescence cytometry) can differ from three-dimensional solution-phase SPR affinities. Bruhns2009 addresses this by combining SPR with cell-based immunofluorescence, finding generally concordant results.
- For polyclonal IgG preparations, kinetic constants (kon, koff) cannot be determined because the mixture contains antibodies with heterogeneous affinities; only the equilibrium affinity constant KA is reported.

## Related Pages
- [[FcγRIIa Receptor]]
- [[Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses]]
- [[Antibody-Dependent Enhancement]]

## Sources
- [[Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses]] (BIAcore 2000 SPR; all hFcγR–IgG subclass affinity constants; primary SPR reference in this wiki)
