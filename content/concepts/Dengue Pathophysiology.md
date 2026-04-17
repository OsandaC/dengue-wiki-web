---
type: concept
tags: [pathophysiology, vascular-permeability, thrombocytopenia, coagulopathy, complement, liver, NS1, TLR4, plasma-leakage, DHF, DSS, PAIgM, PAIgG, secondary-infection, immune-complex, FcR-bypass, glycocalyx, cathepsin-L, heparanase, MIF, autophagy]
created: 2026-04-12
updated: 2026-04-17
sources: 8
---

# Dengue Pathophysiology

## Overview
Dengue haemorrhagic fever (DHF) and dengue shock syndrome (DSS) are defined by three interacting pathological phenomena: (1) increased vascular permeability causing plasma leakage, (2) thrombocytopaenia with impaired platelet function, and (3) coagulopathy with altered haemostasis. These occur in a coordinated, time-locked pattern — emerging during the febrile phase, peaking at defervescence, and typically resolving within 24–36 hours in non-fatal cases. Understanding the molecular drivers of each phenomenon is essential to developing targeted therapies, vaccines, and prognostic tools.

## Key Points from Literature

### Vascular Permeability
- The cardinal feature of DHF/DSS; defined by plasma leakage into serous cavities (pleural effusion, ascites) and into the interstitial space
- Endothelial cell death and direct viral infection of endothelium **do not** appear to be the primary mechanism: patients recovering from DHF regain normal endothelial function rapidly, implying a reversible soluble mediator rather than structural damage (see [[Guzman2016 - Dengue Infection]])
- **Onset at defervescence**, not during peak viraemia — suggesting vascular permeability results from factors that accumulate throughout the febrile phase and surpass a threshold at fever resolution
- **NS1 as a direct trigger**: sNS1 activates TLR4 on myeloid cells → pro-inflammatory cytokines; separately, sNS1 disrupts endothelial monolayer integrity in vitro and in vivo; DENV NS1-induced TLR4 signalling is a proposed central mechanism for barrier dysfunction (see [[Guzman2016 - Dengue Infection]], [[NS1 Protein]])
- **APTT as strongest vascular permeability correlate**: APTT values (measuring coagulation activation time) are the strongest laboratory correlate of vascular permeability in dengue patients — linking coagulopathy and plasma leakage mechanistically (see [[Guzman2016 - Dengue Infection]])
- Anti-NS1 autoantibodies additionally induce endothelial apoptosis (NO→p53/Bax/caspase-3 pathway) and NF-κB inflammatory activation (IL-6, IL-8, MCP-1; ICAM-1 upregulation) — a distinct antibody-mediated vascular damage pathway (see [[NS1 Molecular Mimicry in Dengue]])

### Thrombocytopaenia
- Two concurrent mechanisms:
  1. **Bone marrow suppression**: early febrile phase; suppression of all blood cell lineages; proposed to be mediated by IFN-β (by analogy with lymphocytic choriomeningitis virus in animal models); megakaryocyte arrest persists until near the end of the febrile period
  2. **Peripheral platelet destruction**: immune-mediated; mechanism depends on infection order:
     - *Primary infection*: IgM anti-platelet autoantibodies (NS1 molecular mimicry) cause complement-mediated platelet lysis; anti-NS1 antibodies inhibit ADP-induced platelet aggregation via PDI inhibition (see [[NS1 Molecular Mimicry in Dengue]], [[NS1 Protein]], [[Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients]])
     - *Secondary infection*: **PAIgG** (anti-dengue IgG immune complexes deposited on platelets via direct dengue-platelet binding, FcγRII-independent) triggers platelet clearance via macrophage Fc receptor- and complement receptor-mediated phagocytosis; **PAIgM** (anti-dengue IgM immune complexes) also elevated and triggers clearance exclusively via complement receptor — completely FcγR-independent (IgM pentamer structure). PAIgM >20 ng/10⁷ platelets is an independent predictor of DHF with 92.1% specificity (see [[Oishi2003 - PAIgG and Thrombocytopenia in Secondary Dengue]], [[Saito2004 - PAIgG and PAIgM in Secondary Dengue]])
- Platelet counts can fall to 5,000/ml (normal ~200,000/ml) at nadir
- Thrombocytopaenia is common across infectious diseases generally; it is the combination of thrombocytopaenia with vascular permeability that is distinctive of DHF/DSS
- **Platelet count is NOT a reliable predictor of bleeding severity** in dengue; risk factors for severe haemorrhage are duration of shock and low-to-normal haematocrit at shock onset (see [[Guzman2016 - Dengue Infection]])
(see also [[Guzman2016 - Dengue Infection]])

### Glycocalyx Degradation — Cathepsin L and Heparanase Pathways (Bhatt2020)

[[Bhatt2020 - Dengue Pathogenesis Review]] adds two specific enzymatic mechanisms for NS1-driven glycocalyx degradation that complement the Guzman2016 description of glycocalyx shedding:

- **Heparanase activation**: NS1 activates endothelial heparanase (endo-β-glucuronidase), which cleaves heparan sulfate chains within the glycocalyx — removing the core anticoagulant/antiadhesive surface layer and releasing heparan sulfate fragments into circulation
- **Cathepsin L activation**: NS1 also activates cathepsin L (a lysosomal cysteine protease), which degrades the protein core of heparan sulfate proteoglycans — providing a parallel structural route to glycocalyx loss that is independent of heparanase

Together, these mechanisms offer two enzymatic routes to glycocalyx depletion: enzymatic cleavage of the sugar chains (heparanase) and proteolytic cleavage of the protein cores (cathepsin L). The downstream consequences are: (1) increased vascular permeability from loss of the endothelial surface barrier; (2) release of anticoagulant heparan sulfate into the bloodstream contributing to the coagulopathic picture; (3) exposure of integrin binding sites facilitating platelet-endothelial adhesion.

This fills a mechanistic gap in the existing glycocalyx-shedding model: Guzman2016 established that glycocalyx loss occurs in dengue but did not specify the enzymatic mediators beyond NS1's general disruptive role on the endothelial barrier.

### Coagulopathy
- Characterised by prolonged APTT (activated partial thromboplastin time), reduced fibrinogen, and reduced anticoagulant protein concentrations
- Classic disseminated intravascular coagulation (DIC) is **debated**: procoagulant marker elevation is present but usually mild; anticoagulant protein reduction is more prominent
- **NS1-thrombin binding**: sNS1 binds thrombin in vivo forming NS1-thrombin complexes; rNS1 inhibits prothrombin activation and prolongs APTT in human platelet-deficient plasma (see [[Guzman2016 - Dengue Infection]])
- **E protein WGNGCG motif**: E protein aa 101–106 homologous to coagulation factors (XI, X, IX, VII, thrombin, plasminogen, tPA); anti-E antibodies inhibit plasmin activity (see [[NS1 Molecular Mimicry in Dengue]], [[E Protein]])
- **Glycocalyx shedding**: NS1 may shed heparan sulfate/chondroitin sulfate from the endothelial glycocalyx → anticoagulant molecules enter circulation → contributes to coagulopathy (see [[Guzman2016 - Dengue Infection]])
- Most coagulopathy is minor and self-limiting; major haemorrhage is usually a complication of prolonged shock, not a primary dengue effect
- The APTT-vascular permeability correlation raises the possibility that coagulation interference is proximal to, not merely co-incident with, plasma leakage

### Complement Activation
- Complement system activated to control DENV infection but its activation contributes to pathogenesis
- **Secondary infection**: classical complement pathway activation via circulating immune complexes; levels of C3a/C5a elevated; temporal correlation with fibrinogen and thrombocytopaenia changes
- **Primary infant infection**: alternative complement pathway activated; NS1 may directly activate complement by the alternative pathway
- Activated complement interacts with the coagulation system, amplifying both coagulopathy and vascular inflammation
(see [[Guzman2016 - Dengue Infection]])

### Autoantibodies Against Complement and Coagulation Components
A protein microarray screen in Cambodian pediatric dengue patients revealed that **IgG autoantibodies against complement components and coagulation proteins are produced during DENV infection and correlate with platelet counts in DHF** (see [[Vo2020 - Autoantibody Profiling in Dengue]]):
- IgM autoantibodies against complement proteins C5, C8, C9, Factor B, Factor H, and Factor P were elevated in DENV-infected patients vs. healthy donors
- In DHF patients specifically, **low levels of anti-Factor P IgG and anti-complement C4 IgG** correlated with low platelet counts (both p < 0.05), as did anti-prothrombin IgG
- The correlation is positive (higher Ab = higher platelets), implying these autoantibodies are *consumed* through immune complex formation as DHF worsens, rather than being directly pathogenic
- Factor P (properdin) stabilises the alternative C3 convertase (C3bBb); Factor H inhibits it. Prior reports showed DHF patients have lower Factor H expression, promoting the alternative complement cascade. The Vo2020 data adds that IgG against both proteins is depleted in severe disease — consistent with immune complex formation sequestering these proteins and further imbalancing the complement system toward activation
- Anti-heparan-sulfate and anti-proteoglycan IgG autoantibodies were decreased in DF/DHF vs. asymptomatic patients, raising the speculative hypothesis that anti-heparan sulfate Abs may block DENV attachment to cell membranes (heparan sulfate proteoglycans are a putative DENV receptor) and that their depletion could facilitate infection

### Liver Involvement
- Hepatomegaly in **55% of DHF cases vs. 18% of DF cases** (P<0.01); significantly more common in severe disease
- Mechanisms: (1) generalised oedema from vascular permeability; (2) inflammatory response to hepatocyte infection by DENVs
- Histopathology: **Councilman bodies** (apoptotic DENV-infected hepatocytes engulfed by Kupffer cells) — the same histological finding as in yellow fever (another flavivirus); almost no cellular inflammatory infiltrate in fatal cases, suggesting apoptosis rather than inflammatory hepatocyte death
- AST/ALT elevated in 60–90% of children with DHF; 7–10% have levels >10× upper limit of normal
- Jaundice is rare despite hepatomegaly; gamma-glutamyl transpeptidase elevated in 83% of cases
- Post-dengue liver enzyme elevation may persist for months; anti-NS1 hepatitis-like effects in mouse models (see [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]])
(see [[Guzman2016 - Dengue Infection]])

## Contradictions & Debates
- **Cause of vascular permeability**: Multiple competing models exist — NS1-TLR4, cytokine storm (T cell-mediated), immune complex complement activation, anti-NS1 autoantibody endothelial damage — none fully accounts for all observations. The paper itself notes that none of the existing explanations can account for why infants with no prior infection develop severe dengue.
- **DIC vs non-DIC**: The haemostatic profile of DHF resembles but does not fully meet diagnostic criteria for classic DIC; some researchers distinguish dengue coagulopathy as mechanistically distinct.
- **NS1 as mediator vs. marker**: sNS1 levels correlate with severity, NS1 can cause endothelial disruption in vitro, and NS1-thrombin binding has been demonstrated in vivo — but whether NS1 is the primary driver of vascular permeability or a secondary marker of disease severity remains debated.

## Related Pages
- [[NS1 Protein]]
- [[NS1 Molecular Mimicry in Dengue]]
- [[E Protein]]
- [[Antibody-Dependent Enhancement]]
- [[Cytokine Storm]]
- [[Cross-Reactive Antibodies]]
- [[Viraemia]]
- [[Dengue Clinical Classification]]
- [[Type I Interferon Response in Dengue]]
- [[Autoimmunity in Dengue]]

## Sources
- [[Guzman2016 - Dengue Infection]]
- [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]] (anti-NS1 hepatitis-like effects in mouse models)
- [[Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients]] (primary-infection platelet pathology: anti-platelet IgM, complement-mediated lysis severity-correlated, aggregation inhibition not; NS1-platelet cross-reactivity as mechanistic origin)
- [[Morel2014 - Autoimmune Response in Children With Dengue]] (MAS/HLH as severe dengue immunopathology; hyperferritinemia, triglyceridemia, organomegaly; macrophage hyperactivation as distinct pathophysiological axis from autoantibody-mediated mechanisms)
- [[Oishi2003 - PAIgG and Thrombocytopenia in Secondary Dengue]] (secondary-infection thrombocytopenia mechanism: PAIgG–platelet count inverse correlation r=−0.570; immune complex macrophage/complement platelet clearance; FcγRII-independent dengue-platelet binding)
- [[Saito2004 - PAIgG and PAIgM in Secondary Dengue]] (PAIgM extension: both isotypes inversely correlated with platelet count; anti-dengue IgM confirmed in platelet eluates; PAIgM >20 ng/10⁷ predicts DHF with 92.1% specificity; FcγR bypass for PAIgM via IgM pentamer structure)
- [[Vo2020 - Autoantibody Profiling in Dengue]] (protein microarray; IgM autoantibodies against complement C5, C8, C9, Factor B, H, P elevated vs. HD; anti-Factor P IgG + anti-C4 IgG + anti-prothrombin IgG positively correlated with platelet counts in DHF [consumption model]; anti-heparan sulfate/proteoglycan IgG decreased in DF/DHF vs. ASD; Cambodia pediatric cohort)
- [[Bhatt2020 - Dengue Pathogenesis Review]] (glycocalyx degradation: NS1 activates heparanase → heparan sulfate chain cleavage; NS1 activates cathepsin L → proteoglycan core cleavage; dual enzymatic glycocalyx loss mechanism; MIF-autophagy viral amplification; review, India)
