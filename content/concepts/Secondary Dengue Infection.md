---
type: concept
tags: [secondary-infection, ADE, DHF, DSS, heterotypic, cross-reactive-antibodies, disease-severity, thrombocytopenia, PAIgG, PAIgM, immune-complex, DHF-predictor, anti-prM, anti-endothelial, IgG, isotype-switch, Vietnam]
created: 2026-04-12
updated: 2026-04-19
sources: 15
---

# Secondary Dengue Infection

## Overview
Secondary dengue infection refers to infection with a DENV serotype different from a prior primary infection. It is the single most important risk factor for severe dengue (DHF/DSS). During secondary infection, pre-existing cross-reactive but non-neutralising antibodies from the primary infection can enhance viral uptake into Fc receptor-bearing cells (antibody-dependent enhancement, ADE), leading to higher viraemia, greater immune activation, and increased risk of vascular permeability and haemorrhagic complications.

## Key Points from Literature

### Epidemiological risk
- Severe dengue (DHF/DSS) occurs predominantly in secondary heterotypic infections — this is the core observation underlying the ADE hypothesis (see [[Antibody-Dependent Enhancement]])
- Third and fourth infections are typically mild or asymptomatic, suggesting that broad immunity develops after exposure to 2+ serotypes (see [[Guzman2016 - Dengue Infection]])
- A longer interval between primary and secondary infection increases DHF risk: in Cuba, a 20-year interval (DENV-2, 1981→2001) produced ~8× higher DHF rates than a 4-year interval; waning neutralising antibody levels may shift the balance toward enhancement (see [[Guzman2016 - Dengue Infection]])

### Immunological features
- **Anamnestic IgG response**: In secondary infection, IgG rises within 1–2 days of illness onset at high titres (≥1,280 by HI), unlike primary infection where IgG appears around day 7–10 (see [[IgM-IgG Serology ELISA]])
- **IgG:IgM ratio > 1.2** is used in research settings to classify secondary infection
- **Complement activation** proceeds via the classical pathway in secondary infection (immune complexes), vs. alternative pathway in primary (see [[Dengue Pathophysiology]])
- sNS1 blood levels correlate with disease severity specifically in secondary infection, not in primary (see [[Viraemia]])

### Serotype-specific patterns
- DENV-2 (Asian genotype) following primary DENV-1 is the best-documented sequence associated with severe secondary disease (see [[DENV-2]])
- The Sungnak2025 Thailand cohort notably lacked DENV-2, which the authors flag as a limitation given DENV-2's role in severe secondary infection (see [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]])

### Asymptomatic secondary infection
- Not all secondary infections are symptomatic: in the 2006 Cuban DENV-4 epidemic, among individuals with prior DENV-1 exposure (secondary dengue), the overt:subclinical ratio was approximately 1:1 (see [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]])
- FcγRIIa-RR131 genotype was significantly associated with asymptomatic outcome in secondary infection, suggesting host genetics modulate whether ADE leads to clinical disease (see [[FcγRIIa Receptor]])

### Anti-prM as dominant cross-reactive ADE-mediating antibody in secondary infection context

[[Dejnirattisai2010 - Anti-prM Antibodies Enhance Dengue ADE]] provides the mechanistic explanation for why cross-reactive antibodies from a prior primary infection are so effective at mediating ADE during secondary infection. Approximately 60% of anti-dengue structural antibodies in DENV-infected humans are directed against the prM protein — fully cross-reactive across all four serotypes — and cannot neutralise above a 10–60% ceiling regardless of titre. These antibodies mediate up to 10^5-fold enhancement in primary monocytes and DCs.

In the secondary infection context, the implication is that the dominant non-neutralising cross-reactive antibody pool that encounters a new heterotypic serotype is not primarily sub-threshold anti-E antibody (the classical model) but anti-prM antibody that is structurally incapable of neutralisation. See [[Antibody-Dependent Enhancement]] and [[prM Protein]] for the full mechanism.

### Antibody kinetics: primary vs secondary divergence (Bos2025)

[[Bos2025 - Longitudinal Antibody Dynamics After Dengue]] (PREPRINT) provides the most detailed comparison of antibody trajectories across primary and secondary infection currently in this wiki, in a Nicaraguan pediatric cohort (n=79, DENV-1/DENV-3, followed to 18M):

> **PREPRINT — not peer reviewed.**

- **Secondary infection kinetics are more compressed and attenuated at 18M** relative to primary — consistent with rapid memory recall and faster contraction in a primed host, rather than the sustained expansion seen after primary exposure
- **Cross-reactive E-IgG (XR E-IgG) rises 6–18M post-primary** (t½ = −2.13y), suggesting active accumulation of the cross-reactive pool in the inter-infection window — the pool most likely to mediate ADE upon secondary challenge (see [[Cross-Reactive Antibodies]])
- **NS1-IgG wanes post-primary** (t½ ≈ 2.1y), following the classical type-specific decay model; secondary kinetics show similar waning pattern
- The divergence between primary (rising XR E-IgG, waning NS1-IgG) and secondary (attenuated 18M responses overall) suggests that the immunological state entering a potential tertiary infection is qualitatively different from the state entering secondary infection, in ways the classical ADE model does not fully capture

### Thrombocytopenia mechanism in secondary infection — PAIgG and PAIgM

Two consecutive prospective studies from Manila (same research group, same institutions) establish a two-isotype immune complex model for thrombocytopenia in secondary dengue.

**[[Oishi2003 - PAIgG and Thrombocytopenia in Secondary Dengue]]** (n=53, Manila 2001):
- **Platelet-associated IgG (PAIgG) is the proximate driver**: a significant inverse correlation exists between PAIgG levels and platelet count (r = −0.570, P < 0.0001); absent in healthy volunteers.
- **Anti-dengue virus IgG — not anti-platelet autoantibody — is responsible**: anti-platelet IgG autoantibody was present in plasma in only 1/53 patients (1.9%). IgG eluted from platelets of all 8 tested patients was confirmed anti-dengue virus IgG by indirect ELISA.
- **Mechanism**: immune complexes of dengue antigen + anti-dengue IgG bind to platelets via **direct dengue-platelet interaction** — FcγRII is explicitly NOT required for this step (citing Wang 1995). PAIgG formation subsequently triggers platelet clearance by macrophages and/or complement-mediated platelet lysis.
- **Longitudinal confirmation**: platelet counts recovered (43 → 307 × 10³/μl, P = 0.0022) while PAIgG fell (1.49 → 0.31 ng/10⁷ platelets, P = 0.0037) together from acute to convalescent phase (4 days).
- **PAIgG level does not correlate with HI titre** (r = −0.130, P = 0.361), implying circulating antibody concentration alone is insufficient — viral antigen availability on platelets appears rate-limiting.

**[[Saito2004 - PAIgG and PAIgM in Secondary Dengue]]** (n=78, Manila 2002–2003) extends the Oishi2003 finding to include PAIgM:
- **PAIgM also inversely correlates with platelet count** in secondary infection: r = −0.231, P = 0.046; elevated in acute phase (17.5 ± 20.4 ng/10⁷) vs. healthy controls (4.2 ± 3.8 ng/10⁷, P < 0.001); falls at convalescence (P < 0.001).
- **Anti-dengue IgM activity confirmed in platelet eluates** from secondary-infection patients (OD 0.35 ± 0.20 vs. 0.09 ± 0.05 in controls) — PAIgM is also an immune complex carrying anti-dengue specificity, not anti-self.
- **PAIgM is quantitatively smaller**: 50.7% of patients had normal PAIgM vs. only 19.2% with normal PAIgG — PAIgG is the dominant contributor to thrombocytopenia.
- **PAIgM mechanism bypasses Fc receptors entirely**: IgM pentamer structure cannot engage FcγRs; clearance proceeds only via complement receptor- and complement-mediated lysis — completely FcγR-independent.
- **PAIgM independently predicts DHF** (logistic regression, P < 0.01): cut-off >20 ng/10⁷ platelets gives 92.1% specificity and 48.6% sensitivity for DHF; both PAIgG and PAIgM are significantly higher in DHF than DF.
- PAIgM >20 ng/10⁷ in virologically confirmed secondary infection is the highest-specificity clinical predictor of DHF severity in this data.

**Contrast with primary infection** (see [[Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients]]): primary DENV-3 infection drives thrombocytopenia via IgM anti-platelet *autoantibodies* (NS1 molecular mimicry), not immune complexes. Saito2004 and Oishi2003 show that the IgM elevated on platelets in secondary infection is anti-dengue virus IgM (not anti-self), mechanistically distinct from Lin2001's primary-infection IgM autoantibody. The bifurcation is now precisely defined:
- Primary: IgM anti-platelet autoantibody (NS1 mimicry; Lin2001)
- Secondary: PAIgG + PAIgM immune complexes, both carrying anti-dengue specificity (Oishi2003 + Saito2004)

### IgG Autoantibody Paradox: Primary > Secondary

A protein microarray screen of 123 autoantigens in Cambodian children found that **primary DENV infection was associated with significantly higher IgG autoantibody levels than secondary infection** (p < 0.01 for total IgG NFI; 70 individual IgG autoantibodies elevated in primary vs. secondary) (see [[Vo2020 - Autoantibody Profiling in Dengue]]). This is counterintuitive: secondary infection is the context of greater disease severity, higher viral loads, and the ADE mechanism — all of which might be expected to drive greater immunological dysregulation including more autoantibody production.

The Vo2020 interpretation attributes the primary-infection IgG autoantibody excess to impaired B cell tolerance checkpoints during first exposure, where naïve autoreactive B cells may escape deletion more readily in the absence of memory competition. In secondary infection, rapid memory recall responses dominate the B cell expansion, possibly outcompeting autoreactive clones that lack this established memory advantage.

This finding sits in tension with the severity-autoantibody correlation documented by Wan2012 (anti-endothelial cell Ab levels higher in DHF/DSS than DF by flow cytometry) — but the two studies measure different autoantibody populations by different methods (protein array NFI vs. anti-endothelial cell flow cytometry), and the Vo2020 comparison is primary vs. secondary infection order, not DF vs. DHF severity. They are compatible if: (a) secondary infection produces less *total* IgG autoantibody but the *specific* anti-endothelial autoantibodies tracked by Wan2012 are higher in DHF; or (b) in secondary DHF, autoantibodies are rapidly consumed through immune complex formation (consistent with the Vo2020 platelet-count correlation), leaving the measured total pool depleted even as pathogenic activity is high.

### Diagnostic classification
- Primary vs secondary infection classification relies on serology (IgG:IgM ratio, paired sera), PRNT, and HI assay (see [[IgM-IgG Serology ELISA]], [[PRNT]], [[Hemagglutination Inhibition Test]])
- HI titer ≥1:2,560 in a single plasma sample classifies secondary infection (WHO 1997 criterion; used in [[Oishi2003 - PAIgG and Thrombocytopenia in Secondary Dengue]])
- In the Sungnak2025 cohort, PRNT combined with HI assay was used for primary/secondary classification

## Contradictions & Debates
- **PAIgG vs. autoantibody thrombocytopenia**: Oishi2003 shows near-absent anti-platelet IgG autoantibody in secondary infection, while Lin2001 documents IgM anti-platelet autoantibody in primary infection. The two mechanisms are not mutually exclusive — secondary infection patients may harbour residual IgM autoantibody pathway alongside the dominant PAIgG pathway, but no study has directly measured both simultaneously across infection order.
- **FcγRIIa genotype and platelets**: Oishi2003/Wang 1995 state FcγRII is not required for dengue-platelet binding (and therefore for PAIgG formation). Yet Garcia2010 shows HH genotype dramatically increases DHF risk. FcγRIIa's role in severity must therefore operate through a mechanism other than direct platelet binding — most likely ADE-mediated viral uptake in monocytes/macrophages (see [[FcγRIIa Receptor]]).
- The relationship between secondary infection and severe disease is probabilistic, not deterministic — host genetics, infecting serotype sequence, inter-infection interval, and viral genotype all modulate outcome
- Whether ADE is the primary mechanism or whether T-cell original antigenic sin and cytokine-mediated pathology contribute independently remains debated (see [[Original Antigenic Sin]], [[T Cell Responses in Dengue]])
- CYD-TDV (Dengvaxia) vaccination of seronegatives created an ADE-like state mimicking secondary infection upon natural exposure — raising the question of whether vaccine-induced and naturally-acquired enhancing antibodies behave identically (see [[CYD-TDV]])

## Related Pages
- [[Antibody-Dependent Enhancement]]
- [[Cross-Reactive Antibodies]]
- [[Cytokine Storm]]
- [[Dengue Pathophysiology]]
- [[IgM-IgG Serology ELISA]]
- [[Hemagglutination Inhibition Test]]
- [[Viraemia]]
- [[FcγRIIa Receptor]]
- [[Original Antigenic Sin]]
- [[Asymptomatic Dengue Infection]]
- [[DENV-2]]
- [[CYD-TDV]]
- [[Philippines]]

## Sources
- [[Guzman2016 - Dengue Infection]] (inter-infection interval, ADE, 3rd/4th infection mildness, complement pathways)
- [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]] (asymptomatic secondary infection, FcγRIIa-RR genotype)
- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]] (primary/secondary classification, DENV-2 absence limitation)
- [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]] (autoantibodies in secondary dengue, molecular mimicry context)
- [[Wan2012 - Autoimmunity in Dengue Pathogenesis]] (DHF/DSS in secondary infection; autoantibody kinetics; intrinsic ADE in secondary infection context)
- [[Bos2025 - Longitudinal Antibody Dynamics After Dengue]] (primary vs. secondary kinetics comparison; secondary responses compressed and attenuated at 18M; XR E-IgG rising post-primary; NS1-IgG waning; PREPRINT)
- [[Oishi2003 - PAIgG and Thrombocytopenia in Secondary Dengue]] (PAIgG mechanism; anti-dengue IgG immune complexes on platelets; FcγRII not required; longitudinal acute-to-convalescent platelet recovery; absence of anti-platelet autoAbs in secondary infection)
- [[Saito2004 - PAIgG and PAIgM in Secondary Dengue]] (PAIgM extension of Oishi2003; both PAIgG and PAIgM inversely correlated with platelet count; anti-dengue IgM in platelet eluates confirmed; PAIgM independent DHF predictor 92.1% specificity; FcγR bypass for PAIgM)
- [[Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients]] (primary-infection contrast: anti-platelet IgM autoantibody mechanism arises independently of primary/secondary status; HI-confirmed majority primary in Taiwan 1998–99 DENV-3 cohort; challenges assumption that DHF/DSS requires secondary infection)
- [[Palacios2016 - Autoimmunity in Dengue Literature Review]] (Lai 2012 MAS+nephrotic syndrome case: confirmed reinfection by IgG+IgM seropositivity; literature context for secondary-infection autoimmune complications)
- [[Vo2020 - Autoantibody Profiling in Dengue]] (primary > secondary IgG autoantibody inversion: 70 IgG autoantibodies higher in primary infection; all 8 DHF patients were secondary infection; Cambodia cohort; IgG tolerance-escape model for primary-infection autoantibody excess)
- [[Dejnirattisai2010 - Anti-prM Antibodies Enhance Dengue ADE]] (anti-prM dominant structural antibody ~60%; full cross-reactivity across serotypes — the dominant non-neutralising pool available for ADE upon secondary challenge; 10^5-fold monocyte/DC enhancement; Thailand n=7 donors; secondary infection donors included)
- [[Pang2017 - DHF Pathogenesis Review]] (DHF risk quantified: secondary infection 118–208/1000 vs. 11–12/1000 primary — ≥10-fold; ADE mechanism overview; FcγR-mediated IFN suppression + IL-10 enhancement in secondary infection; review, China)
- [[Jardim2012 - Autoimmune Features DHF Case Report]] (secondary DENV-3 infection [IgM+/IgG+ dual positivity]; DHF with triple serositis, DIC, cryoglobulinemia, ANA 1/320 mitotic spindle — all resolved at follow-up; exemplifies broad autoimmune mimicry in secondary infection; Campinas Brazil; n=1 case report)
- [[Hung2008 - Anti-Platelet Anti-Endothelial Autoantibodies Vietnam]] (children [predominantly secondary]: anti-EC IgG elevated 25.1% vs 2.6% controls [p<0.001] alongside anti-EC IgM 46.0% vs 4.7% — isotype addition of IgG in secondary infection context; infection-order independence of anti-EC levels confirmed in children p=1.0/0.5; HCMC Vietnam; n=37 children)
