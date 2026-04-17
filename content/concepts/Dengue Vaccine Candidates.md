---
type: concept
tags: [vaccines, CYD-TDV, DENVax, TAK-003, TV003, tetravalent, live-attenuated, subunit, ADE, seronegative, phase-III, correlates-of-protection, anti-prM, prM-design, ADE-risk, ADE-window, enhancement-titer, Katzelnick]
created: 2026-04-12
updated: 2026-04-17
sources: 6
---

# Dengue Vaccine Candidates

## Overview
Dengue vaccine development is complicated by the need to simultaneously protect against all four serotypes and to do so without inducing partial immunity that could predispose vaccinees to antibody-dependent enhancement (ADE) upon breakthrough infection. As of 2016, one vaccine (CYD-TDV/Dengvaxia) had been approved in multiple countries; others were in phase II/III trials. The key challenge is that the correlates of dengue protection are incompletely understood — high-titre neutralising antibodies do not always predict protection, and the role of T cell immunity is increasingly recognised as important.

## Key Points from Literature

### The fundamental challenge
- A dengue vaccine must provide **balanced tetravalent immunity** — unbalanced responses leave individuals partially immune and potentially at ADE risk for the under-protected serotype
- Waning immunity is itself a risk: the longer the interval between sensitisation (whether by natural infection or vaccine) and a subsequent heterotypic exposure, the greater the DHF risk (DENV2 secondary infection after 20-year vs 4-year interval → 8× higher DHF rate)
- No validated animal model for human dengue disease; no single established correlate of protection
(see [[Guzman2016 - Dengue Infection]])

### CYD-TDV (Dengvaxia; Sanofi Pasteur) — approved
- Live attenuated chimeric vaccine: prM and E genes of each DENV serotype inserted into 17D yellow fever vaccine backbone (ChimeriVax platform)
- Phase III in >30,000 children across 10 countries; efficacy 56.5% (Asia) / 60.8% (Americas); >80% against DHF
- **Critical safety signal**: seronegative children ≤5 years at vaccination had 5× the hospitalised breakthrough disease rate of controls; mechanism is ADE — vaccine primes naïve individuals with cross-reactive non-neutralising antibodies, enhancing viral entry during subsequent natural infection
- Approved for ages 9–45 years in five countries; recommended only where >70% of target population is seropositive
- See dedicated page: [[CYD-TDV]]
(see [[Guzman2016 - Dengue Infection]])

### DENVax / TAK-003 (Takeda) — phase II at publication
- Live attenuated chimeric vaccine: DENV-2 PDK-53 attenuated backbone with prM/E genes of wild-type DENV-1, -3, -4 substituted in (three chimeric serotypes + attenuated DENV-2)
- Well-tolerated in children and adults 1.5–45 years; neutralising antibody seroconversion to all four serotypes; T cell-mediated cross-reactive responses
- Phase III trials initiated in Asian countries (note: TAK-003 subsequently completed phase III and received approval in multiple countries after the Guzman2016 publication date)
(see [[Guzman2016 - Dengue Infection]])

### TV003 / TV005 (US NIAID / Instituto Butantan) — phase II at publication
- Live attenuated vaccine using 3′ UTR deletion (Δ30 mutation) to attenuate DENV-1 and DENV-4; recombinant chimeric DENV-2 and DENV-3
- Human challenge study: **single dose of TV003 fully protected all 21 vaccinated volunteers** against virologically confirmed dengue infection; all 20 unvaccinated controls became infected
- TV005 is a higher-titre formulation
- Does not use yellow fever backbone — different immune priming profile than CYD-TDV
(see [[Guzman2016 - Dengue Infection]])

### Subunit vaccines
- **DEN-80E (Hawaii Biotech / Merck)**: truncated recombinant E protein subunit (80% of E, lacking transmembrane domain); induces neutralising antibodies in mice and non-human primates; phase I of DENV-1-80E completed; tetravalent phase I began 2012
- **DIII-C (IPK Cuba / CIGB)**: domain III of E protein fused to capsid protein; induces serotype-specific antibody and cellular immunity in Balb/c mice and Vervet monkeys; advanced preclinical stage; developed by the same IPK group as the Garcia2009/2010 cohort studies
- Advantages: no ADE risk from viral replication; balanced tetravalent responses feasible; accelerated immunisation schedule
- Disadvantages: require adjuvants and multiple doses; may not induce as durable immunity as live attenuated vaccines
(see [[Guzman2016 - Dengue Infection]])

### Inactivated vaccines
- DPIV (purified formalin-inactivated; WRAIR/GSK): immunogenic in rhesus macaques; phase I completed 2011; no replication risk; multiple doses required; adjuvants needed
(see [[Guzman2016 - Dengue Infection]])

### Implications for protective immunity (relevant to Sungnak2025)
- Sungnak2025 suggests that CD8 T cell effector responses (non-exhausted, functional, directed against NS protein epitopes) are the hallmark of protective asymptomatic dengue, while IGHG1+ plasmablast expansion is a marker of pathogenic DHF
- This aligns with the expectation that vaccines including NS protein antigens (TV003's live attenuated design; some DNA vaccine approaches) may induce more protective T cell responses than vaccines relying solely on E protein (subunit 80E, inactivated virus)
- CYD-TDV, which uses only prM/E in the yellow fever backbone without NS proteins, may therefore be structurally less capable of inducing the NS-epitope CD8 T cell responses that appear protective in natural infection
(see [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]])

### NS1-based vaccine: protective AND pathogenic (Wan2012)
- Anti-NS1 Abs fix complement and trigger **complement-mediated lysis** of DENV-infected cells — a protective mechanism distinct from neutralisation
- Active immunisation with NS1 protein or passive transfer of anti-NS1 Abs protects mice against lethal DENV challenge
- However, anti-NS1 Abs also cross-react with platelets, endothelial cells, and coagulation factors via molecular mimicry — pathogenic
- Resolution requires **epitope engineering**: remove or modify the C-terminal aa 277–352 pathogenic epitopes while preserving the protective complement-fixing epitopes
- A successful dengue vaccine must therefore address three constraints: tetravalent efficacy, no ADE, AND no autoimmune cross-reactivity
(see [[Wan2012 - Autoimmunity in Dengue Pathogenesis]])

### Anti-prM ADE risk from native prM sequences (Dejnirattisai2010)

All three leading vaccine platforms — CYD-TDV, TAK-003, and TV003/TV005 — incorporate **native prM sequences** alongside E protein genes. Dejnirattisai2010 demonstrates that natural DENV infection primes anti-prM antibodies as the **dominant structural antibody class (~60%)**, and that these antibodies are:
- Fully cross-reactive across all four serotypes
- Unable to neutralise above a 10–60% ceiling (structural limit from incomplete prM cleavage)
- Capable of up to 10^5-fold ADE enhancement in primary monocytes and DCs

Any vaccine using native prM sequences will likely prime an anti-prM response with the same profile. The authors call for **heterologous prM sequences** or **prM deletion** in future vaccine constructs to avoid priming this ADE-prone antibody class. This is an unresolved challenge: as of the sources in this wiki, no approved dengue vaccine has adopted a modified or deleted prM approach.

See [[prM Protein]] and [[Antibody-Dependent Enhancement]] for full mechanistic context. This adds a specific structural-antibody-level constraint to the ADE concern documented for CYD-TDV seronegatives (see [[CYD-TDV]]).
(see [[Dejnirattisai2010 - Anti-prM Antibodies Enhance Dengue ADE]])

### Quantitative ADE window — a rational safety benchmark for vaccine titre monitoring (Bhatt2020)

[[Bhatt2020 - Dengue Pathogenesis Review]] introduces the **Katzelnick 2017 quantitative ADE window** (1:21–1:80 as peak enhancement titer; n=6,684 Nicaraguan children) as a benchmark for evaluating vaccine safety over time. This converts the qualitative "waning immunity = ADE risk" concern into a testable quantitative criterion:

- Vaccines that induce neutralising titres well above 1:1,280 initially may provide protection, but as titres wane (which occurs at different rates for different vaccines and recipients), **any period spent in the 1:21–1:80 range represents a potential ADE vulnerability window**
- For **seronegative CYD-TDV vaccinees** specifically: the vaccine induced titres that, as they waned, passed through the enhancement range — consistent with the observed 5× hospitalisation risk in this group
- For **TAK-003 (Qdenga)** and **TV003**: post-vaccination waning kinetics have not been benchmarked against the Katzelnick window in available wiki sources; whether their titres track through 1:21–1:80 as they wane is unknown
- The window also contextualises the Bos2025 (PREPRINT) observation that XR E-IgG *rises* post-primary — if rising cross-reactive antibody titres are in the enhancement range, duration of risk may differ from the simple waning model

(see [[Antibody-Dependent Enhancement]], [[CYD-TDV]])

## Contradictions & Debates
- **CYD-TDV seronegative risk**: The ADE interpretation of the CYD-TDV safety signal is widely accepted but mechanistic proof in vaccinees (e.g., FcR pathway enrichment, IGHG1 plasmablast expansion as in DHF Sungnak2025 data) has not been directly demonstrated.
- **Neutralising antibody vs. T cell correlates**: High neutralising antibody titres in vaccinees do not always predict protection (observed for DENV-2 in some CYD-TDV vaccinees); T cell immunity is increasingly recognised as important but is not yet a validated regulatory correlate.
- **Anti-prM vs. anti-E as dominant ADE mechanism**: Standard vaccine immunogenicity readouts measure anti-E neutralising titres. If anti-prM is the more potent and numerically dominant ADE pathway (Dejnirattisai2010), current vaccine evaluation frameworks may be missing the most important enhancing antibody class. Whether anti-prM titres post-vaccination track with breakthrough DHF risk has not been tested.

## Related Pages
- [[CYD-TDV]]
- [[Antibody-Dependent Enhancement]]
- [[prM Protein]]
- [[E Protein]]
- [[T Cell Responses in Dengue]]
- [[NS1 Protein]]
- [[Asymptomatic Dengue Infection]]
- [[DENV-1]]
- [[DENV-2]]
- [[DENV-3]]
- [[DENV-4]]

## Sources
- [[Guzman2016 - Dengue Infection]] (vaccine landscape as of 2016)
- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]] (vaccine implications from protective immune correlates)
- [[Wan2012 - Autoimmunity in Dengue Pathogenesis]] (NS1 vaccine paradox: complement-mediated protection vs. autoimmune cross-reactivity)
- [[Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients]] (foundational anti-platelet IgM finding; discussion section explicitly notes need to avoid pathogenic cross-reactive epitopes in NS1-based vaccine design)
- [[Dejnirattisai2010 - Anti-prM Antibodies Enhance Dengue ADE]] (all current vaccines use native prM; will prime ADE-potent anti-prM response; heterologous prM design needed; Thailand experimental n=7 donors)
- [[Bhatt2020 - Dengue Pathogenesis Review]] (Katzelnick 2017 peak ADE window 1:21–1:80 titer; n=6684 Nicaraguan children; quantitative safety benchmark for post-vaccination titre monitoring; review, India)
