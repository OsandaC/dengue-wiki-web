---
type: concept
tags: [autoimmunity, molecular-mimicry, bystander-activation, epitope-spreading, viral-infection, ANA, autoantibodies, post-infectious, NS1, dengue-specific, ADEM, epidemiology]
created: 2026-04-12
updated: 2026-04-12
sources: 6
---

# Infection-Triggered Autoimmunity

## Overview
Infectious agents — viruses, bacteria, fungi, and parasites — can induce autoantibody production and, in some cases, overt autoimmune disease in individuals without prior autoimmune history. This occurs through distinct but non-mutually exclusive mechanisms: molecular mimicry, bystander activation, and epitope spreading (see [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]]). The resulting autoantibodies may be transient (resolving after pathogen clearance) or persistent (potentially progressing to clinical autoimmune disease), depending on the mechanism and host factors.

This concept is directly relevant to interpreting autoimmune markers — including ANA positivity — detected in patients recovering from dengue (see [[Autoimmunity in Dengue]]).

## Key Points from Literature

### Three Core Mechanisms

#### Molecular Mimicry
A pathogen-derived antigen shares sufficient sequence or structural similarity with a host self-antigen that anti-pathogen immune responses cross-react with host tissue (see [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]]). Both T cells and B cells may be involved:
- **B cell cross-reactivity**: Pathogen antigen activates self-reactive B cells when pathogen epitope resembles a self-epitope, bypassing tolerance
- **T cell cross-reactivity**: Viral peptide-MHC complexes activate self-reactive T cells that escaped central tolerance
- **Canonical example**: *Campylobacter jejuni* → anti-ganglioside antibodies (anti-GM1, anti-GD1a, anti-GQ1b) → Guillain-Barré syndrome; ~30–40% of GBS follows C. jejuni infection
- **Relevance to dengue**: Dengue NS1 protein shares structural homology with endothelial and platelet proteins — the same mimicry mechanism could, in principle, produce cross-reactive antinuclear antibodies

#### Bystander Activation
Non-specific polyclonal T and B cell activation driven by cytokines (IFN-α/γ, IL-1, IL-6, TNF) released during infection, without antigen-specific stimulation (see [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]]):
- IFN-α activates plasmacytoid dendritic cells → polyclonal B cell activation → transient autoantibodies, typically without affinity maturation
- **Critical caveat**: Trahtemberg et al. (cited in Johnson2022) found **no significant difference in ANA prevalence** between COVID-19-positive and COVID-19-negative ICU patients — suggesting that bystander polyclonal activation from severe infection alone is insufficient to consistently elevate ANA
- Autoantibodies from bystander activation tend to be low-affinity and transient

#### Epitope Spreading
Initial immune response to a pathogen damages host tissue → releases cryptic self-antigens that were not presented during thymic selection → immune response expands to target additional self-epitopes (see [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]]):
- May explain diversity of autoantibody specificities after acute infection, including detection of multiple ANA specificities simultaneously (as seen in HAV patients in [[Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections]])
- Most consistent with *persistent* post-infectious autoimmunity: if cryptic nuclear antigens are released, secondary ANA responses may continue beyond the acute phase even after pathogen clearance

### ANA Prevalence During Acute Infections
[[Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections]] provides the key empirical data:

| Infection Type | ANA Prevalence | Significance vs. Controls |
|---|---|---|
| Viral (HAV, HBV, HCV; n=23) | 21.7% | P<0.013 |
| Bacterial (n=41) | 20.0% | P<0.006 |
| Parasitic (n=17) | 17.6% | NS |
| Rickettsial (n=7) | 0% | — |
| Healthy controls (n=80) | 3.8% | — |

Method: ELISA (ANA 8 Pro, Euroimmun; 8 nuclear antigens; 1:100 dilution). The 3.8% control rate is lower than population IIF-based estimates (13.8–16.1%), reflecting the narrower antigen coverage of the ELISA panel; the fold-change (21.7% vs. 3.8%, ~5.7×) is more meaningful than the absolute rates.

### Transience vs. Persistence
A central question is whether infection-triggered autoantibodies are transient or persistent:
- **Evidence for transience**: One study (cited in Berlin2007) found ANA in 20.5% during acute viral hepatitis, dropping to 6.4% in convalescence — a rapid resolution with pathogen clearance
- **Evidence for persistence**: [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]] found 23.1% ANA positivity at 2 years post-dengue — if genuine, this is not transient; it may reflect a different mechanism (epitope spreading, or genetically mediated impaired clearance)
- The FcγRIIa-HH genotype (impaired IC clearance) may predispose certain individuals to persistent rather than transient infection-triggered autoimmunity (see [[FcγRIIa Receptor]])

### Host Risk Factors
From [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]]:
- **Female sex**: TLR7 on X chromosome (double dose), estrogen-driven immune activation; ~20% of healthy women are ANA-positive
- **Genetics**: HLA-DR alleles, complement gene deficiencies (C1q/C2/C4 → impaired IC clearance → SLE risk), BANK1 polymorphisms, TLR2/4/7/9 variants
- **Innate immunity**: TLR pathway variants modulate both pathogen clearance and autoimmune activation threshold

### Specific Pathogen-Autoimmunity Associations
Key examples from [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]]:
- **EBV**: Molecular mimicry and epitope spreading → Sjögren's syndrome, SLE, multiple sclerosis
- **Influenza**: Anti-phospholipid antibodies → type 1 diabetes, GBS, anti-phospholipid syndrome
- **SARS-CoV-2**: Bystander polyclonal activation → broad but non-specific autoantibodies; ANA not significantly increased vs. non-COVID ICU patients
- **HBV**: CNS demyelination via molecular mimicry
- ***C. jejuni***: Anti-ganglioside → GBS (canonical molecular mimicry example)

The Lin/Lei group at NCKU provides the most mechanistically detailed dengue-specific example, spanning two reviews (see [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]] Table 1, which also catalogues Coxsackievirus B/Type I DM, HCV/cryoglobulinemia, Rubella/Type I DM, HCMV/SLE, HSV/stromal keratitis, Parvovirus B19/SLE+RA).

### Population-Level Constraint on Post-Dengue Autoimmune Disease
[[Shih2023 - Autoimmune Disease Risk After Dengue]] provides the largest epidemiological test of whether dengue-triggered autoimmunity leads to clinical autoimmune disease. Key findings relevant to the transience/persistence debate:

- Over a mean 4.57-year follow-up, 14 autoimmune disease categories were examined in 63,814 lab-confirmed dengue patients. After Bonferroni correction, only **autoimmune encephalomyelitis (ADEM)** was significantly elevated (aHR 2.72; P < 0.0001), and only in the **first month** after infection.
- Diseases with strong prior case-report support (SLE, GBS, post-infectious arthritis) were statistically non-significant at the population level.
- This finding constrains the interpretation of dengue-associated autoimmunity: even if molecular mimicry or bystander activation produce transient autoantibodies, these do not commonly result in sustained clinical autoimmune disease. The Shih2023 data supports the "transient autoimmunity" interpretation of the mechanistic literature.
- ADEM after dengue fits the classical post-infectious autoimmunity model: transient molecular mimicry or autoreactive T-cell activation targeting CNS myelin, confined to the acute/post-acute period (days 3–19 after symptom onset, consistent with the first-month risk window). See [[Dengue Neurological Complications]].

### Dengue NS1 — A Detailed Molecular Mimicry Case

Dengue provides one of the best-characterised examples of acute-phase molecular mimicry leading to direct tissue damage (see [[NS1 Molecular Mimicry in Dengue]]):
- Anti-NS1 Abs cross-react with PDI, vimentin, ATP synthase β-chain, and HSP60 on platelets and endothelial cells; responsible domain mapped to C-terminal NS1 aa 311–352 (see [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]])
- Anti-NS1 causes complement-mediated platelet lysis (IgM), inhibits platelet aggregation via PDI, and induces endothelial apoptosis and NF-κB inflammatory activation (see [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]])
- A WGNGCG motif on the E protein is homologous to coagulation factors; present in haemorrhagic flaviviruses (JEV, WNV, YFV) but not HCV — a molecular basis for flavivirus-specific haemorrhagic phenotype
- **Critically distinctive**: dengue autoimmunity manifests during the acute infection phase, not post-infectious — this contrasts with the *C. jejuni*/GBS paradigm and most EBV-associated autoimmune diseases, which develop after pathogen clearance; it makes dengue uniquely suited to study the initiation of autoimmunity in real time

## Contradictions & Debates
- **Biomarker elevation vs. clinical disease**: Garcia2009 found elevated ANA, IC, and CRP at 2 years post-dengue in symptomatic patients. Yet Shih2023 found no elevated incidence of clinical autoimmune diseases over 4.57 years in 63,814 dengue patients. These are not necessarily contradictory — ANA positivity and clinical autoimmune disease are distinct endpoints, and most ANA-positive individuals do not develop clinical disease — but the discrepancy highlights that biological autoimmune activation does not reliably translate into clinical outcome.
- **Bystander activation vs. ANA**: The COVID-19 data (Johnson2022) suggests bystander activation alone does not explain ANA elevation, yet severe dengue involves a similar cytokine storm. This leaves the mechanism of dengue-associated ANA (Garcia2009) unclear — molecular mimicry or epitope spreading may be more relevant than bystander activation.
- **ELISA vs. IIF**: Berlin2007's 3.8% control rate (ELISA, 8 antigens) vs. 13.8–16.1% (IIF, all antigens; Satoh2012/Dinse2022) highlights that infection-triggered ANA detected by ELISA may represent a narrow, disease-associated subset, while IIF captures a broader range including non-pathogenic nuclear reactivities.
- **Transience timeline**: The evidence for transience (Berlin2007, acute hepatitis) and persistence (Garcia2009, 2 years post-dengue) may reflect genuinely different mechanisms or simply different time points; longitudinal data specifically for dengue ANA is absent.

## Related Pages
- [[Autoimmunity in Dengue]]
- [[Dengue Neurological Complications]]
- [[NS1 Molecular Mimicry in Dengue]]
- [[NS1 Protein]]
- [[Antinuclear Antibodies]]
- [[FcγRIIa Receptor]]
- [[Antibody-Dependent Enhancement]]
- [[Post-Dengue Syndrome]]

## Sources
- [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]] (mechanistic review)
- [[Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections]] (empirical ANA rates during acute infections)
- [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]] (dengue-specific ANA persistence)
- [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]] (dengue NS1 molecular mimicry; experimental evidence)
- [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]] (molecular targets; C-terminal NS1 domain; flavivirus coagulation homology; broader virus-autoimmunity catalogue)
- [[Shih2023 - Autoimmune Disease Risk After Dengue]] (population-level constraint: only ADEM elevated after dengue; supports transient autoimmunity interpretation; large misclassification problem in prior literature)
