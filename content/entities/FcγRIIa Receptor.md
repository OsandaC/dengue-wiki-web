---
type: entity
tags: [Fc-receptor, FcgRIIa, genetics, polymorphism, immune-complex, leukocyte, IgG-affinity, SPR, IgG2, inhibitory-receptor, FcgRIIB]
created: 2026-04-11
updated: 2026-04-13
sources: 4
---

# FcγRIIa Receptor

## Overview
FcγRIIa (Fc gamma receptor IIa; gene FcγRIIA) is a membrane-bound glycoprotein expressed on leukocytes including monocytes, macrophages, neutrophils, and dendritic cells. It binds the Fc region of IgG antibodies, mediating phagocytosis of immune complexes (IC) and modulating antibody-triggered inflammatory responses. A clinically important single nucleotide polymorphism (SNP) at codon 131 produces two alleles — Histidine (H131) and Arginine (R131) — yielding three genotypes: HH, HR, and RR. By SPR measurement, H131 binds IgG1 slightly more efficiently than R131 (KA ~52 vs ~35 ×10⁵ M⁻¹) and IgG3 essentially identically; the principal difference between the alleles is a 4.5-fold higher affinity for **IgG2** in H131 compared to R131 (KA 4.5 vs 1.0 ×10⁵ M⁻¹) (see [[Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses]]). Older literature characterised the H131 allele as higher-affinity for IgG2; Bruhns2009 confirms and precisely quantifies this, while clarifying that IgG1 and IgG3 affinities differ only modestly between alleles.

## Key Points from Literature
- The FcγRIIa-HH genotype was significantly associated with persistent clinical symptoms 2 years after dengue infection compared to HR+RR combined (p = 0.027; OR 2.83, 95% CI 1.01–8.11), particularly musculoskeletal pain (p = 0.036) and neurological complaints (p = 0.008) (see [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]]).
- HH genotype is a risk factor not only for sequelae but for symptomatic infection itself: HH frequency was 51.5% in DHF, 39.4% in DF, and only 9.1% in asymptomatic individuals from the same 2006 Cuban cohort (p = 0.008) (see [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]]).
- HH vs HR+RR: OR for DHF = 10.56 (95% CI 2.33–54.64, p = 0.00018); OR for DF = 4.33 (95% CI 1.08–20.10, p = 0.018) — both compared to asymptomatic group (see [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]]).
- RR genotype is protective against DHF development: OR = 0.09, p = 0.01; RR is also enriched in asymptomatic individuals, suggesting it confers protection against symptomatic disease (see [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]]).
- Proposed protective mechanism for RR: efficient IgG1/IgG3 binding → phagolysosome formation → immune complex elimination and control of viral dissemination.
- Proposed risk mechanism for HH: inefficient IgG1/IgG3 binding → failed lysosome fusion → proteolytic evasion → viral dissemination via ADE; also leads to IC accumulation, pro-inflammatory cytokine release (TNF-α, IL-1), and autoimmune tissue damage (see [[Autoimmunity in Dengue]]).
- Havana population baseline: 55% RR, 32% HR, 13% HH — markedly higher RR frequency than Asian populations (6–10% RR), potentially explaining geographic differences in DHF burden (see [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]]).

### FcγRIIa Affinity for IgG Subclasses — Quantitative Reference (Bruhns2009)

[[Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses]] provides the authoritative SPR-based affinity measurements for FcγRIIa variants across all four IgG subclasses:

| Receptor | IgG1 | IgG2 | IgG3 | IgG4 |
|---|---|---|---|---|
| FcγRIIA-H131 | 52±12 | **4.5±1.0** | 9.1±1.3 | 1.7±0.4 |
| FcγRIIA-R131 | 35±5 | **1.0±0.0** | 8.9±0.1 | 2.1±0.2 |
| FcγRIIB/C | 1.2±0.1 | 0.3±0.0 | 1.7±0.2 | 2.0±0.4 |

All values ×10⁵ M⁻¹. Values in **bold** mark the principal allele-dependent difference.

Key implications:
- The dominant allelic difference is **IgG2-specific**: H131 binds IgG2 4.5× more efficiently than R131. For IgG1 and IgG3, the alleles are functionally similar (~1.5× difference for IgG1; equivalent for IgG3).
- **FcγRIIB (inhibitory receptor) is ~43× weaker than FcγRIIA-H131 for IgG1.** FcγRIIB cannot independently intercept ICs — it requires co-engagement with activating FcγRs by the same IC to exert inhibitory signalling (ITIM). This means when activating FcγRIIA captures a dengue IC, there is no effective independent inhibitory checkpoint through FcγRIIB.
- IgG4 is the only subclass where R131 binds slightly *better* than H131 (2.1 vs 1.7 ×10⁵ M⁻¹) — a reversal of the IgG2 pattern.

**Dengue-specific implication:** The conventional model held that HH genotype was disadvantaged due to lower IgG1/IgG3 affinity. Bruhns2009 contradicts this: H131 has *higher* IgG1 affinity. The meaningful difference between HH and RR individuals in dengue is likely IgG2 handling, not IgG1/IgG3 handling. Whether anti-dengue IgG2 titres are clinically significant remains an open question (see Questions Raised in [[Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses]]).

### FCGR2A in the broader dengue host genetics landscape
Guzman2016 (Table 2) lists FCGR2A alongside multiple other host genetic loci associated with dengue susceptibility or severity (see [[Guzman2016 - Dengue Infection]]). FCGR2A is the most robustly replicated single-gene association in dengue genetics; confirmed associations across Cuban cohort (Garcia2010) and listed alongside:
- **HLA alleles** (multiple associations with DF/DHF susceptibility, varying by population)
- **IL-10 promoter variants** (higher IL-10 production → greater DHF risk in some studies)
- **TNF polymorphisms** (TNF-α production variants)
- **DC-SIGN (DCSIGN1/CD209)** variants — affect monocyte/DC DENV entry
- **Vitamin D receptor (VDR)** variants — immune regulation

The FCGR2A H131 allele (HH genotype) is listed under susceptibility DF/DHF; the R131 allele (RR genotype) is listed under resistance/better outcome — consistent with the Garcia2010 Cuban data.

## Contradictions & Debates
- **Mechanism revision required:** The prior standard explanation — HH genotype has *lower* IgG1/IgG3 affinity → poor IC clearance → IC accumulation → inflammation — is not supported by [[Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses]]. Bruhns shows H131 (HH allele) binds IgG1 slightly *more* efficiently than R131 (52 vs 35 ×10⁵ M⁻¹). The Overview of this page has been corrected accordingly. What makes HH worse in dengue remains mechanistically unclear. Three live hypotheses: (1) more efficient IgG1 binding in H131 → *over-activation* of inflammatory signalling via FcγRIIA-ITAM; (2) the key variable is IgG2 (where H131 has 4.5× advantage), not IgG1 — but anti-dengue IgG2 abundance in secondary infection is not well characterised; (3) the FcγRIIB inhibitory deficit (too weak to provide independent negative feedback) affects all individuals equally and is not the mechanism behind HH-specific risk.
- **Garcia2009/2010 proposed mechanism:** The Garcia papers propose that HH impairs IC clearance via failed phagolysosome fusion. This mechanism should be understood as a functional cell biology hypothesis that predates and is not consistent with the Bruhns affinity data. The appropriate revision is not yet available in the dengue literature.

## Related Pages
- [[Post-Dengue Syndrome]]
- [[Autoimmunity in Dengue]]
- [[Antibody-Dependent Enhancement]]
- [[Asymptomatic Dengue Infection]]
- [[FcγRIIa Genotyping]]
- [[Surface Plasmon Resonance]]
- [[Cuba]]

## Sources
- [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]]
- [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]]
- [[Guzman2016 - Dengue Infection]] (Table 2 host genetics; FCGR2A H131/R131 confirmed; broader genetic context)
- [[Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses]] (authoritative SPR affinity data; H131 4.5× higher IgG2 affinity than R131; IgG1/IgG3 affinities nearly equal; FcγRIIB ~43× weaker than FcγRIIA for IgG1)
