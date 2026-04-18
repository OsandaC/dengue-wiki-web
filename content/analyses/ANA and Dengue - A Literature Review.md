---
type: analysis
tags: [ANA, antinuclear-antibody, dengue, autoimmunity, molecular-mimicry, bystander-activation, epitope-spreading, post-dengue, IIF, HEp-2, LIA, prevalence, healthy-population, acute-phase, IIFA, FcγRIIa, NS1, MAS, HLH, macrophage-activation, NS1-IgG-kinetics, primary-infection, PAIgG, PAIgM, ANA-negative, Talib2013, literature-review, autoantigen-microarray, nuclear-antigen-consumption, thrombocytopenia-bifurcation, immune-complex]
created: 2026-04-13
updated: 2026-04-19
sources: 31
---

# ANA and Dengue — A Literature Review

*Synthesised from 33 source papers and 9 concept/method pages. Last updated 2026-04-19.*

> **Revision note (2026-04-17, first pass):** Added five sources ingested 2026-04-14 through 2026-04-15 — Bos2025 (longitudinal antibody kinetics), Lin2001 (foundational IgM anti-platelet autoantibody with attribution correction), Oishi2003 (PAIgG/immune-complex thrombocytopenia in secondary infection), Morel2014 (ANA-negative MAS case series), and Palacios2016 (letter adding the Talib 2013 ANA-positive SLE case and Lai 2012 MAS+nephrotic case). New §5.5 on macrophage-driven autoimmunity without ANA; new §6.3 on NS1-IgG waning kinetics; updated §8 on progression with the Morel/Talib case contrast; additional open questions in §10 and hypothesis-generating claims in §11.

> **Revision note (2026-04-17, second pass):** Added Vo2020 (Cambodian pediatric autoantigen microarray, n=40) and Saito2004 (PAIgM in secondary dengue, n=78). Key additions: §4.4 on the nuclear antigen IgG consumption model — 19 DHF-correlated IgGs including canonical ANA targets positively correlate with platelet count, suggesting ANA levels may be paradoxically *lower* in severe dengue due to immune complex sequestration; §5.4 extended with Saito2004 PAIgM characterisation (anti-viral, not autoimmune; completely FcγR-independent; 92.1% DHF specificity); §7 paragraph on the primary>secondary IgG autoantibody inversion (Vo2020, counterintuitive); §9 infection-order host factor; two new open questions (Q12–Q13); §11 established-claim update (three-pathway thrombocytopenia) and new hypothesis-generating entries.

> **Revision note (2026-04-17, third pass):** Added four sources — Zhou2007 (polyreactive IgM), Gawali2021 (6-month ANA), Velazqueza2017 (pediatric SLE+dengue case series, Mexico), and Rajadhyaksha2012 (biopsy-confirmed lupus nephritis, Mumbai). Key additions: new §4.5 on polyreactive IgM as the mechanism for the non-specific IIFA fraction (resolves the Watch Item from state.md); §6.2 trajectory table now includes the Gawali2021 6-month data point; §8 case contrast expanded with Velazqueza2017 (n=2 pediatric SLE+dengue) and Rajadhyaksha2012 (Class IV LN, anti-cardiolipin, primary DENV-1); new open question Q14 on anti-cardiolipin persistence; §11 updated with polyreactive IgM as an established framework for the non-specific fraction.

> **Revision note (2026-04-18, fifth pass):** Added [[Cheng2015 - NS1 P311-330 Anti-PDI Autoantibodies in DHF]] and [[Chaturvedi2001 - Cytotoxic Factor Autoantibodies DHF]]. Key additions: §5.1 updated with P311-330 as the precisely mapped PDI cross-reactive epitope and primary/secondary independence of anti-endothelial autoantibodies confirmed across three independent studies (Lin2001, Saito2004, Cheng2015); anti-vimentin anomaly flagged (no NS1 correlation); new §5.6 on anti-hCF as a tentative third ANA-invisible protective autoimmune axis (⚠ heavily caveated — unvalidated group-specific concept); §11 updated with P311-330 and infection-order independence under Established, and anti-hCF protective axis under Hypothesis-generating.

> **Revision note (2026-04-19, sixth pass):** Added [[Hung2008 - Anti-Platelet Anti-Endothelial Autoantibodies Vietnam]] and [[Santosa2012 - Delayed SLE Diagnosis Dengue Serology]]. Hung2008 is the Vietnamese endemic-setting replication confirming anti-platelet IgM in primary dengue (infants, n=50, DENV-3/4) and introduces the anti-EC isotype shift: IgM only in infants/primary, IgM+IgG in children/predominantly secondary (§5.1 extended; §11 Established bullet on infection-order independence updated). Santosa2012 completes the reverse direction: SLE-associated polyclonal IgM causes false-positive dengue serology (§5.1 brief note). Also: Berlin2007 HAV specificity data corrected — Results section shows 3/10 HAV patients positive for all 8 ANA antigens (not "all patients with HAV" as the Discussion erroneously states); source count corrected from 31 to 33.

> **Revision note (2026-04-18, fourth pass):** Added [[Jardim2012 - Autoimmune Features DHF Case Report]] (secondary DENV-3 DHF; n=1; Campinas Brazil) — missed from the ingest propagation to this analysis page. Key additions: Jardim2012 row added to §8 case table ("transient multi-autoantibody" pole: ANA 1/320 mitotic spindle pattern, full resolution at follow-up, anti-dsDNA negative, cryoglobulinemia, selective C3 depression); new discussion point 5 on Jardim2012's unique contribution; sources list updated (28→29).

---

## 1. Why ANA and Dengue?

Antinuclear antibodies ([[Antinuclear Antibodies]]) — immunoglobulins directed against nuclear and cytoplasmic components of eukaryotic cells — are the canonical biomarker of systemic autoimmune rheumatic disease (SARD). Yet they are not specific to autoimmune disease: they appear transiently in healthy individuals, rise with age, and are elevated during acute infections. The question this literature review addresses is: **does dengue virus infection produce ANA in a pattern that is clinically meaningful, mechanistically distinct, or prognostically significant — and if so, for whom, through what mechanism, and for how long?**

Dengue is an unusual candidate for this question because it is the most prevalent mosquito-borne viral disease globally (~390 million infections per year; see [[Guzman2016 - Dengue Infection]]) and because its immunopathogenesis — dominated by the NS1 protein's cross-reactivity with host proteins — involves molecular mimicry operating during the *acute phase* of infection rather than post-infectious. This creates a tight, observable window for studying the initiation of autoimmunity in a real-world setting.

---

## 2. Establishing the Healthy-Population Baseline

Before interpreting ANA rates in dengue patients, a robust baseline is essential. Four studies in this wiki characterise healthy-population ANA prevalence:

| Study                                                       | Population                              | Dilution/Method | ANA Prevalence |
| ----------------------------------------------------------- | --------------------------------------- | --------------- | -------------- |
| [[Tan1997 - ANA Range in Healthy Individuals]]              | Multicentre international; adults 21–60 | 1:40, IIF       | 31.7%          |
| [[Tan1997 - ANA Range in Healthy Individuals]]              | As above                                | 1:80, IIF       | 13.3%          |
| [[Tan1997 - ANA Range in Healthy Individuals]]              | As above                                | 1:160, IIF      | 5.0%           |
| [[Satoh2012 - ANA Prevalence in United States]]             | US NHANES 1999–2004; ≥12 yrs            | 1:80, IIF       | 13.8%          |
| [[Li2019 - ANA Epidemiology in Chinese Healthy Population]] | Chinese health-checkup; all ages        | >1:100, IIF     | 14.01%         |
| [[Dinse2022 - Increasing ANA Prevalence in United States]]  | US NHANES 2011–2012; ≥12 yrs            | 1:80, IIF       | 16.1%          |

Several features of this baseline are directly relevant to interpreting dengue data:

**Dilution dependence.** Prevalence drops sharply with increasing dilution — from ~32% at 1:40 to ~5% at 1:160 in Tan1997. The clinical standard established by [[Aringer2019 - 2019 EULAR ACR SLE Classification Criteria]] is ≥1:80 on HEp-2 cells as the mandatory entry criterion for SLE classification (sensitivity 96.1%, meta-regression of 13,080 patients across 64 studies). Studies not specifying their dilution threshold cannot be meaningfully interpreted against this baseline.

**Rising temporal trend.** US ANA prevalence increased from 11.0% (1988–91) to 16.1% (2011–12) by NHANES, with the most dramatic rise in adolescents 12–19 (OR 2.77 for 2011–12 vs. 1988–91) and in men (see [[Dinse2022 - Increasing ANA Prevalence in United States]]). This trend is not explained by BMI, smoking, or alcohol changes, and was documented using identical methodology in a single laboratory — making methodological drift an unlikely explanation. **The implication for dengue research:** a study reporting 23.1% ANA positivity in 2009 Cuban adults must be evaluated against contemporary baselines (likely ~11–14%), not against 2022 figures.

**Consistent floor at high dilutions.** The ~5–6% rate at ≥1:160–1:320 is strikingly consistent across populations and decades (Tan1997, Li2019). This floor likely represents a genuine background rate of autoimmune activation in the general population, independent of dengue.

**Sociodemographic correlates.** Female sex (~2× higher), age >50 years, and — in older data — non-Hispanic Black race are consistently associated with higher ANA prevalence. Any dengue cohort that is disproportionately female or older will show an inflated ANA rate relative to a mixed baseline (see [[Antinuclear Antibodies]]).

---

## 3. ANA During Acute Infections — The Non-Dengue Comparator

Before addressing dengue specifically, it is worth establishing how much any acute infection elevates ANA. [[Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections]] provides the key data:

| Infection Type | n | ANA Prevalence | P vs. controls |
|---|---|---|---|
| Viral (HAV, HBV, HCV) | 23 | **21.7%** | P<0.013 |
| Bacterial | 41 | 20.0% | P<0.006 |
| Parasitic | 17 | 17.6% | NS |
| Rickettsial | 7 | 0% | — |
| Healthy blood donor controls | 80 | 3.8% | — |

Method: ELISA (ANA 8 Pro; 8 nuclear antigens; 1:100). The control rate of 3.8% is lower than IIF-based estimates (13.8–16.1%), because the ELISA covers only 8 specific antigens while IIF detects all antinuclear reactivities. The **fold-change (~5.7×)** is more interpretable than the absolute infection-group rate.

Two additional findings from Berlin2007 are noteworthy for mechanistic context:

- **Anti-annexin V** and **anti-prothrombin** are the most commonly elevated autoantibodies during acute infections — both coagulation-pathway targets. Anti-prothrombin was detected in 69.6% of viral infections, which converges strikingly with Lin2011's finding that the dengue E protein WGNGCG motif shares homology with prothrombin (see [[NS1 Molecular Mimicry in Dengue]] and [[Notable Findings]]).
- ANA detected during acute viral hepatitis fell from 20.5% in the acute phase to 6.4% in convalescence (see [[Codes2002 - Autoantibodies in Acute Viral Hepatitis]], n=156 prospective cohort, IIF homogeneous ≥1:40, Salvador Brazil; also 14.8% ASMA → 3.9%; no severity or chronification association) — establishing that *transience* is a genuine feature of infection-triggered ANA. This is important context for interpreting both dengue-specific acute ANA measurements and claims about post-dengue persistence.

The ~21.7% ANA rate in acute viral infections (Berlin2007) sets the baseline expectation: *any viral infection appears to produce ANA in roughly one-fifth of patients by a narrow ELISA panel*. Dengue must be evaluated against this generic benchmark, not just against the healthy-population baseline.

---

## 4. ANA in Acute Dengue — Direct HEp-2 Measurement

[[Chatterjee2024 - ANA Detection in Dengue Kolkata]] is the key contribution to this question, providing the first measurement of ANA in *acute* dengue using HEp-2 cells — the gold-standard, most sensitive IIF substrate. The study design: Kolkata, India; 135 dengue-confirmed patients (94% IgM ELISA, 6% RT-PCR) presenting to fever clinics; 126 dengue-negative febrile controls; February 2021–February 2024.

### 4.1 The headline numbers

- **HEp-2 IIFA: 54.8%** ANA positive in dengue patients vs. **10.3%** in dengue-negative controls (p < 0.001)
- **LIA (18 specific autoantibodies): 18.5%** positive in dengue patients vs. **7.1%** in controls (p = 0.009)

The 54.8% IIFA rate is the highest ANA rate reported in any dengue context in this wiki. It substantially exceeds the generic acute viral infection rate of ~21.7% documented by Berlin2007 — though the comparison is imperfect because Berlin2007 used a narrower 8-antigen ELISA while Chatterjee2024 used HEp-2 IIFA, which detects all antinuclear reactivities (see [[Indirect Immunofluorescence ANA Test]]).

### 4.2 The critical IIFA:LIA gap

The 54.8% IIFA rate vs. 18.5% LIA rate creates a ~3:1 ratio: **approximately two-thirds of IIFA-positive dengue patients had no confirmed disease-specific autoantibody by LIA**. This is mechanistically decisive. Among dengue-negative febrile controls, the IIFA:LIA ratio is much tighter (10.3% vs. 7.1%), confirming that the non-specific IIFA positivity is a dengue-specific phenomenon, not a feature of febrile illness in general.

The interpretation: dengue acutely perturbs nuclear antigen reactivity on a massive scale, but almost none of this corresponds to the specific autoantibody targets of named autoimmune diseases (Sm, dsDNA, Ro, La, Scl-70, U1-RNP, Jo-1, etc.). The pattern is consistent with broad, low-affinity polyclonal activation — the immunological equivalent of collateral fire. This is the most direct evidence yet that the acute-phase autoimmune activation in dengue is largely non-specific (see [[Autoimmunity in Dengue]], [[Notable Findings]]).

### 4.3 Disease-category signals in the LIA data

Of 7 autoimmune disease categories tested, only **MCTD** (multivariate p = 0.041; OR 14.01, 95% CI 2.197–89.215) and **autoimmune myositis** (multivariate p = 0.018; OR 18.37, 95% CI 2.746–122.944) were significantly elevated in dengue patients. Caution is warranted: these ORs have very wide confidence intervals, the sample is small (n=135), and these findings are hypothesis-generating rather than confirmed. Whether the elevated MCTD and myositis-specific autoantibodies represent genuine disease risk or serological noise at low-frequency targets requires larger prospective studies.

### 4.4 The Nuclear Antigen IgG Consumption Model — Why Severe Dengue May Show *Lower* ANA

[[Vo2020 - Autoantibody Profiling in Dengue]] provides a mechanistic reinterpretation of the ANA–severity relationship in DHF that runs counter to the conventional severity-centric expectation. Using a 123-antigen protein microarray in Cambodian children (n=40; 8 HD, 11 ASD, 13 DF, 8 DHF), Vo2020 found that in DHF patients, **19 IgG autoantibodies — including those targeting canonical nuclear antigens (KU/P70/P80, SmD, SmD1, Sm/RNP, histone H3, histone H4, nucleosome antigen, U1-snRNP-C) — were positively correlated with platelet count** (Spearman r = 0.74–0.83; all p < 0.05). The directionality is counterintuitive: more severe disease (lower platelet count) correlates with *lower* free-serum autoantibody levels, not higher.

The proposed mechanism is **consumption**: as DHF progresses, nuclear antigen IgGs are sequestered into immune complexes circulating and depositing in tissues, reducing their detectable free-serum fraction. The positive correlation with platelet count mirrors a depletion model — both the platelets and the autoantibodies are consumed as disease severity rises. Low anti-Factor P IgG and low anti-complement C4 IgG alongside the low anti-nuclear IgGs are proposed to contribute to complement cascade dysregulation (Factor P normally inhibits complement amplification; its depletion into ICs would remove a brake on complement activation).

**The implication for the ANA thread is direct.** If nuclear antigen IgGs are consumed during severe dengue, a clinical ANA test performed at peak disease severity — the usual study design — would *underestimate* the total dengue ANA burden specifically in DHF patients. Chatterjee2024's 54.8% IIFA rate was measured in a fever-clinic cohort (predominantly DF); DHF patients presenting at nadir platelet counts would be expected, by the Vo2020 model, to show a paradoxically lower free-serum ANA titre at that moment. This provides a mechanistic explanation for why Morel2014's most severe MAS cases tested ANA-negative: maximum autoimmune activation may correspond to minimum detectable free ANA, not minimum autoimmune burden.

This interpretation is constrained by the size of Vo2020's DHF cohort (n=8), cross-sectional sampling at one timepoint, and the absence of multiple comparison correction on the 19 correlated autoantibodies. The consumption model requires prospective testing with serial paired measurements of free-serum ANA, complement activation markers (C3d, sC5b-9), immune complex levels, and platelet count across the DHF severity spectrum.

### 4.5 The Polyreactive IgM Interpretation — A Mechanism for the Non-Specific Fraction

[[Zhou2007 - Polyreactive Antibodies Natural Antibody Function]] provides the most mechanistically precise account of what the non-specific IIFA fraction actually *is*.

Germline-encoded **polyreactive IgM** antibodies — present constitutively in all healthy individuals from birth — bind structurally unrelated self and non-self antigens with low affinity, without antigen-driven selection or somatic hypermutation. They constitute ~15–20% of adult peripheral blood B cells at rest, have a serum half-life of ~8 hours, and are *normal* immune components rather than disease indicators. Their defining property is multi-specificity: the same antibody molecule, encoded by germline V-gene segments without V(D)J recombination junctional diversity, binds disparate antigen structures — including nuclear components such as dsDNA, histones, and nucleosomal antigens — as a constitutive feature of its germline-encoded combining site.

In the context of acute dengue, the inflammatory milieu (polyclonal B cell stimulation by dengue structural proteins and NS1, cytokine amplification, antigen release from damaged tissue) may expand or unmask the polyreactive IgM pool beyond its resting baseline. This would generate a transient, IgM-dominated, broadly self-reactive signal with exactly the fingerprint of the Chatterjee2024 non-specific fraction: detectable by HEp-2 IIFA (polyreactive IgM binds nuclear antigens non-specifically), negative on LIA (LIA tests for defined disease-specific autoantibodies against selected targets, not for low-affinity germline binding), and expected to resolve rapidly given the ~8-hour half-life once the inflammatory stimulus subsides.

This framework directly interprets three otherwise-puzzling features of the dengue ANA data:
1. **The 3:1 IIFA:LIA ratio** (54.8% IIFA vs. 18.5% LIA in Chatterjee2024): the non-specific excess is polyreactive IgM noise, not antigen-induced autoimmunity
2. **The 80 elevated IgM autoantibodies** in Vo2020's microarray: consistent with broad, low-affinity polyreactive IgM binding across structurally diverse self-antigen targets
3. **Expected transience**: the polyreactive IgM half-life (~8h) predicts rapid resolution of the non-specific IIFA component once dengue-driven inflammatory amplification subsides — consistent with the acute viral hepatitis ANA transience documented in Berlin2007

**A critical distinction.** The polyreactive IgM framework does not explain — and is not meant to explain — the 18.5% LIA-positive fraction. The LIA-confirmed autoantibodies (anti-Sm, anti-dsDNA, anti-Ro/La, anti-MCTD specificities) require antigen-driven selection and represent genuinely induced autoimmunity — through molecular mimicry, bystander activation, or epitope spreading. The two fractions are separable: LIA positivity is the operationally cleaner measure of dengue-induced pathological autoimmunity; IIFA positivity captures both the disease-relevant LIA-confirmed fraction and a superimposed polyreactive IgM background that is immunologically normal.

**Practical implication for clinical ANA testing:** In the acute dengue setting, a positive HEp-2 IIFA alone is not evidence of pathological autoimmune induction. The critical second step — LIA confirmation — determines whether the positivity is polyreactive IgM background or genuine disease-specific autoantibody. This distinction matters prognostically: the polyreactive IgM signal is self-limiting; the LIA-positive signal may not be. (See also [[Polyreactive Antibodies]], [[Notable Findings]])

---

## 5. Mechanisms Producing ANA in Dengue

The [[Infection-Triggered Autoimmunity]] literature identifies three canonical mechanisms. All three are potentially relevant to dengue, but their relative contributions differ:

### 5.1 Molecular Mimicry — The Primary Dengue-Specific Mechanism

The NCKU group (Lin, Lei et al.) has provided the most experimentally detailed evidence. Anti-dengue NS1 antibodies, generated during normal antiviral immunity, cross-react with platelet and endothelial cell surface proteins due to structural/sequence similarity between NS1 and those host proteins.

**Attribution note:** The foundational identification of an IgM anti-platelet autoantibody in dengue (i.e. the *autoreactive* — not just immune-complex — component of dengue thrombocytopenia) was made by [[Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients]], reporting elevated platelet-bindable IgM (but not IgG) in 8/10 acute DHF patients with no detectable circulating immune complexes. Lin2006 extends and re-uses this finding; the substantive molecular-mimicry programme that follows (Lin2006, Lin2011, Wan2012) builds on the 2001 case identification.

**Established cross-reactive targets** (see [[NS1 Molecular Mimicry in Dengue]], [[Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients]], [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]], [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]]):

| Host Protein | Location | Functional Consequence |
|---|---|---|
| PDI (protein disulfide isomerase) | Platelet surface | Anti-NS1 inhibits PDI → platelet aggregation inhibition; cross-reactive epitope mapped to **P311–330** (see [[Cheng2015 - NS1 P311-330 Anti-PDI Autoantibodies in DHF]]) |
| Vimentin | Platelet + endothelial | Surface binding; consequences under investigation |
| ATP synthase β-chain | Platelet + endothelial | Surface binding; consequences under investigation |
| HSP60 | Platelet + endothelial | Cross-targeted also by anti-prM Abs |
| LYRIC protein | Endothelial | NS1 aa 116–119 shares sequence similarity with human LYRIC aa 334–337 |

The responsible NS1 domain is the **C-terminal region (amino acids 311–352)**. Within this region, [[Cheng2015 - NS1 P311-330 Anti-PDI Autoantibodies in DHF]] has narrowed the **PDI-cross-reactive epitope to P311–330** using a synthetic 20-mer blocking assay: anti-P311–330 serum suppresses anti-PDI IgM binding by ~80%. HSP60 cross-reactivity uses a distinct, as-yet-unidentified NS1 epitope — not P311–330 — confirmed by the same assay. Deletion of aa 277–352 abolishes anti-NS1-mediated platelet aggregation and bleeding tendency. The vaccine design implication is direct: NS1-based constructs retaining P311–330 will generate anti-PDI cross-reactive antibodies; constructs with this peptide deleted or mutated may avoid the platelet-aggregation arm of NS1 mimicry.

**Infection-order independence** of anti-endothelial autoantibodies was confirmed by Cheng2015 in a Vietnamese/Taiwanese DHF cohort: anti-PDI IgM, anti-HSP60 IgM, and anti-endothelial cell IgM were comparably elevated in primary DHF (n=2) and secondary DHF (n=15), with no significant difference by infection order. This is convergent with Lin2001's primary-infection IgM anti-platelet autoantibody (primary DENV-3) and with the Saito2004 dataset.

[[Hung2008 - Anti-Platelet Anti-Endothelial Autoantibodies Vietnam]] provides the largest independent replication in an endemic setting. In 50 Vietnamese infants (<12 months) with predominantly primary DENV-3/4 infections, anti-platelet IgM was elevated in 49/50 cases (16.5 ± 8.6% vs controls 1.5 ± 1.2%, p<0.001). This extends Lin2001's Taiwan primary-infection finding to Vietnam and to two additional serotypes. Hung2008 additionally introduces an **anti-EC isotype shift by infection order**: infants (primary) produce IgM anti-EC only (elevated vs controls; IgG not significant), while older children (89.2% secondary) produce both IgM and IgG anti-EC, with markedly higher overall levels (IgM 46.0 ± 15.3% vs 4.7%; IgG 25.1 ± 8.5% vs 2.6%; both p<0.001). This IgM→IgM+IgG shift is consistent with immune memory class switching upon re-exposure and provides the first age/infection-order-stratified data for anti-EC autoantibodies. In vivo endothelial structural damage was confirmed by elevated serum thrombomodulin (TM) in both age groups. Critically, neither autoantibody levels nor TM correlated with DHF severity grade, platelet count, or haematocrit increase — reinforcing the multi-mechanism model of DHF.

Together, **four independent studies** (Lin2001, Saito2004, Cheng2015, Hung2008) establish that **NS1 molecular mimicry anti-platelet and anti-endothelial autoantibodies are constitutive to NS1 immunity and are not ADE-escalated secondary-infection phenomena**. The implication for the ANA thread: the 54.8% IIFA rate in Chatterjee2024's predominantly secondary-infection fever-clinic cohort likely *underestimates* the contribution from first-time DENV-exposed individuals, not overestimates it.

**An anomaly:** Anti-vimentin IgM is elevated in DHF vs. controls in Cheng2015 but does **not** correlate with anti-NS1 IgM or anti-EC IgM — inconsistent with a simple NS1-mimicry origin. Whether a different dengue protein (capsid, prM, E protein) drives anti-vimentin elevation, or whether vimentin cross-reactivity operates through bystander activation or direct viral binding to surface vimentin, is unknown. This is a mechanistic gap not addressed by any other source in this wiki.

**Two endothelial pathology pathways** are mediated by anti-NS1:
1. **Apoptosis**: anti-NS1 → NO production → p53/Bax/caspase-3 pathway → endothelial cell death
2. **Inflammatory activation**: anti-NS1 → NF-κB → IL-6, IL-8, MCP-1↑; ICAM-1↑ → PBMC adhesion → monolayer permeability↑

Beyond NS1: [[Wan2012 - Autoimmunity in Dengue Pathogenesis]] extends the target repertoire to include the dengue capsid (C) protein and RGD structural mimicry, and [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]] identifies that the E protein's WGNGCG motif shares homology with coagulation factors XI, X, IX, VII, II (thrombin), plasminogen, and tPA — providing a second molecular basis for coagulopathy via anti-E antibodies inhibiting plasmin activity.

**A critical caveat for the ANA question**: the established dengue molecular mimicry targets (platelet surface proteins, endothelial proteins) are *not* canonical nuclear antigens. They are surface-accessible cytoplasmic and transmembrane proteins. It remains unclear whether dengue NS1 shares structural homology with nuclear antigens (Sm, dsDNA, Ro/La, Scl-70) in addition to these established targets. If it does not, then the dengue-associated IIFA-positive ANA (54.8%) must be explained by a second mechanism.

### 5.2 Bystander Activation — Likely Insufficient

Bystander activation — non-specific polyclonal B and T cell activation driven by cytokines (IFN-α/γ, IL-1, IL-6, TNF) released during infection — is the intuitive explanation for why any severe viral illness might produce ANA. Dengue involves a cytokine storm comparable to that seen in severe COVID-19.

However, [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]] (citing Trahtemberg et al.) found **no significant difference in ANA prevalence between COVID-19-positive and COVID-19-negative ICU patients**. If bystander polyclonal activation were sufficient to explain infection-triggered ANA, it should elevate ANA in severe COVID-19 relative to matched ICU controls — and it doesn't.

This is the most direct available evidence that cytokine storm *alone* is insufficient to drive ANA elevation. It sharply narrows the explanation for dengue-associated ANA: the mechanism must involve something dengue-specific — either molecular mimicry with nuclear antigens, or epitope spreading from dengue-induced tissue damage releasing cryptic nuclear antigens (see [[Notable Findings]]).

### 5.3 Epitope Spreading

Epitope spreading — initial immune response damages host tissue → cryptic self-antigens are released → immune response expands to new self-epitopes — is most consistent with *persistent* post-infectious autoimmunity. If dengue-induced tissue damage (endothelial apoptosis, platelet lysis) releases nuclear antigens that were not presented during thymic selection, a secondary ANA response could sustain itself after viral clearance. This is the most plausible mechanism for Garcia2009's 2-year ANA persistence (see §6 below), and it is consistent with the breadth and non-specificity of the IIFA-positive fraction in Chatterjee2024.

### 5.4 FcγRIIa-Driven Immune Complex Persistence

A fourth, dengue-specific amplifying mechanism involves the FcγRIIa receptor. The FcγRIIa-HH genotype impairs immune complex (IC) clearance, causing IC accumulation in tissues and circulation. [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]] found that FcγRIIa-HH is significantly associated with post-dengue sequelae (OR 2.83) and that elevated IC correlated with higher anti-dengue IgG titers (p = 0.042). This FcγRIIa mechanism does not directly produce ANA — but by prolonging antigen stimulation, it may sustain polyclonal B cell activation beyond the expected resolution window, providing one explanation for why ANA persists at 2 years in the Garcia2009 cohort (see [[FcγRIIa Receptor]]).

[[Oishi2003 - PAIgG and Thrombocytopenia in Secondary Dengue]] provides direct *acute-phase* evidence that the IC pathway operates independently of FcγRII binding: platelet-associated IgG (PAIgG) levels were significantly elevated in DHF and DF patients vs. other febrile illness controls (P < 0.0001), and PAIgG was inversely correlated with platelet count (r = −0.50, P < 0.001). Critically, eluted PAIgG bound recombinant DENV-2 NS1 by immunoblot — establishing that the platelet-bound IgG is dengue-antigen-specific (NS1 immune complex deposited on platelets), *not* an autoantibody to platelet antigens. Anti-platelet integrin GPIIb/IIIa receptor blockade did **not** reduce PAIgG binding, indicating a non-FcγRII-mediated route of attachment. This positions the Oishi2003 mechanism as orthogonal to (rather than redundant with) the Lin2001/Lin2006 IgM autoantibody pathway: dengue thrombocytopenia involves at least two distinct immunological processes converging on the same end-organ.

**Saito2004 extends the secondary-infection picture** by adding a second platelet-associated isotype. [[Saito2004 - PAIgG and PAIgM in Secondary Dengue]] demonstrates that IgM-class platelet-associated immunoglobulin (PAIgM) is also significantly elevated in secondary dengue (17.5 ± 20.4 vs. 4.2 ± 3.8 ng/10⁷ in healthy controls, P < 0.001), inversely correlates with platelet count (r = −0.231, P = 0.046), and — critically — **carries anti-dengue virus IgM specificity** confirmed by platelet eluate ELISA. This establishes that PAIgM in secondary infection is **not an anti-platelet autoantibody** but an anti-dengue immune complex. It is mechanistically opposite to Lin2001's primary-infection IgM anti-platelet autoantibody despite being the same isotype. PAIgM is **completely FcγR-independent**: the IgM pentamer precludes Fc receptor engagement, so platelet clearance proceeds entirely via complement receptor- and complement-mediated pathways. PAIgM independently predicts DHF by multivariate logistic regression; a cut-off >20 ng/10⁷ platelets yields 92.1% specificity and 48.6% sensitivity (n=78 secondary-infection patients, DHF grades I–II).

The full secondary-infection thrombocytopenia picture is now: PAIgG (anti-dengue IgG IC; Oishi2003) + PAIgM (anti-dengue IgM IC; Saito2004), both bypassing FcγRII at the platelet-docking step, and PAIgM additionally bypassing FcγR at every downstream step. The FcγRIIa paradox sharpens accordingly: if both major secondary-infection thrombocytopenia pathways bypass FcγR at platelet engagement, the Garcia2010 FcγRIIa-HH DHF risk (OR 10.56) must operate through an entirely non-platelet route — ADE-driven monocyte/macrophage activation remains the leading hypothesis, but no study in this wiki tests this directly.

### 5.5 Macrophage-Driven Autoimmunity Without ANA

[[Morel2014 - Autoimmune Response in Children With Dengue]] reports three pediatric cases at a Paraguayan referral hospital. Two of the three (a 3-year-old and a 3-month-old) met HLH-2004 criteria for macrophage activation syndrome (MAS) / secondary haemophagocytic lymphohistiocytosis: fever, hepatosplenomegaly, leukopenia with neutropenia, anaemia (Hgb 8.0–8.2 g/dl), hypertriglyceridaemia (383–470 mg/dl), and hyperferritinaemia (1150 mg/dl in the 3-year-old; 3828 mg/dl in the 3-month-old). Both responded clinically to methylprednisolone bolus therapy. The mildest case — a self-limiting 8-year-old — was the only one with detectable autoimmune markers (IgM anticardiolipin positive, hypocomplementaemia, proteinuria).

The decisive finding is that **ANA and anti-dsDNA were negative in all three cases**, including the two most severe MAS presentations. This is the first paper in this wiki to document a clinically severe dengue-autoimmune complication operating through a mechanism that is *invisible* to the standard ANA screen. [[Palacios2016 - Autoimmunity in Dengue Literature Review]], a letter to the editor responding to Morel2014, adds an additional MAS+nephrotic syndrome case (Lai et al. 2012) consistent with this pattern.

The mechanistic implication for the dengue-ANA literature is significant. The dominant frame of the wiki — built from Lin2006, Lin2011, Wan2012, Chatterjee2024, Garcia2009 — places dengue autoimmunity along a B-cell axis (NS1 mimicry → autoreactive antibodies → ANA-detectable phenomena). Morel2014 adds a parallel **macrophage hyperactivation axis**: cytokine-driven (likely IFN-γ, IL-18, IL-6), CD163-marked, with end-organ damage from histiocyte/macrophage infiltration rather than autoantibody-mediated targeting. ANA and anti-dsDNA are insensitive to this axis by design — they probe nuclear-antigen B-cell reactivity, not innate-cell hyperactivation.

This does not reverse the Wan2012 autoantibody-severity correlation in the strict sense, because Wan2012 measured anti-endothelial and anti-platelet antibodies by flow cytometry, not standard ANA/anti-dsDNA. But it does establish that *severity-by-autoimmune-complication* is not adequately captured by ANA testing alone — the most severe complications in Morel2014 are entirely ANA-negative. The implication for any future ANA-prevalence study in dengue is that ANA-positive patients and ANA-negative-MAS patients may both be mislabelled when only one screen is applied: the former as "subclinical autoimmune", the latter as "non-autoimmune severe dengue" when in fact they sit on a parallel autoimmune axis.

### 5.6 Anti-Cytokine Autoantibody — A Tentative Third Axis Invisible to ANA Testing

[[Chaturvedi2001 - Cytotoxic Factor Autoantibodies DHF]] introduces a conceptually distinct autoimmune axis: autoantibodies directed *against* a dengue-produced cytokine (hCF, "human cytotoxic factor"), proposed to be **protective** rather than pathogenic. In a 1996 Lucknow epidemic cohort, anti-hCF IgG was detected in 96% of DF patients vs. 8% of grade IV DHF patients (P ≤ 0.001) — an inverse association with severity that no other dengue autoantibody in this wiki shares. The proposed mechanism: hCF is a dengue-specific CD4+ T cell cytotoxin produced by monocytes; anti-hCF autoantibodies neutralise hCF activity, reducing cytotoxic damage and correlating with milder disease.

**⚠ Critical epistemic caveat:** hCF is the Chaturvedi group's proprietary, uncharacterised construct — partially purified by HPLC from dengue-infected monocyte supernatants but never sequenced, deposited, or independently replicated. No external group has published on hCF; CrossRef citation count is 1. It may map to a known cytokine or dengue structural protein fragment, or may be an artefact of the purification protocol. All claims about hCF must be treated as hypothesis-generating pending independent validation; none should be cited as established dengue immunobiology.

The conceptual contribution to the ANA framework is indirect but structurally important. If anti-hCF exists and is protective, dengue's autoimmune response is at minimum three-branched:
1. **ANA-positive B-cell axis** — NS1 molecular mimicry → anti-PDI/HSP60/endothelial autoantibodies → platelet lysis, vascular leakage (pathogenic; ANA detectable via IIF)
2. **ANA-negative macrophage axis** — cytokine-driven MAS/HLH → histiocyte hyperactivation → ANA-negative, ferritin-elevated severe complication (Morel2014)
3. **ANA-negative anti-cytokine axis** — anti-hCF protective autoantibody → severity-inverse, cytotoxin-neutralising (Chaturvedi2001 — ⚠ unvalidated)

Standard ANA testing is blind to both ANA-negative axes. Whether axes 2 and 3 co-occur or dissociate in individual patients has not been tested.

---

## 6. Post-Dengue ANA — The Persistence Question

### 6.1 Garcia2009: 23.1% ANA at 2 Years

[[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]] remains the principal source on post-dengue ANA. In a Cuban cohort followed 2 years after the 2006 DENV-4 epidemic, 23.1% (6/26) of symptomatic patients who returned for autoimmune testing were ANA-positive. Comparisons:

| Reference | Rate | Dilution/Substrate | Excess vs. Garcia2009 |
|---|---|---|---|
| [[Tan1997 - ANA Range in Healthy Individuals]] | 5.0% | 1:160, IIF | ~4.6× elevated |
| [[Satoh2012 - ANA Prevalence in United States]] | 13.8% | 1:80, US 1999–2004 | ~1.7× elevated |
| [[Dinse2022 - Increasing ANA Prevalence in United States]] | 16.1% | 1:80, US 2011–12 | ~1.4× elevated |
| [[Li2019 - ANA Epidemiology in Chinese Healthy Population]] | 14.01% | >1:100, Chinese | ~1.6× elevated |

Garcia2009 used **rat liver tissue** as the IIF substrate — an older, less sensitive substrate than HEp-2 cells, which detects fewer ANA specificities and systematically underestimates ANA prevalence. This means the 23.1% figure is a *conservative lower bound*; HEp-2 testing would likely yield a higher rate. All comparisons above therefore underestimate the true elevation.

**Critical methodological limitations of Garcia2009's ANA data:**
- Testing dilution not clearly stated
- No contemporaneous healthy control group tested for ANA
- Subset selection: only 26 of the original 97 symptomatic patients returned for autoimmune testing (potential selection bias toward sicker individuals)
- Rat liver substrate incompatible with all modern healthy-population reference studies

Despite these limitations, the consistent elevation above all reference values — even when conservatively assessed — provides reasonable evidence that ANA positivity is genuinely increased in post-dengue symptomatic patients.

### 6.2 The Acute-to-Chronic Trajectory — An Unresolved Gap

A coherent timeline of dengue ANA now exists in this wiki, with a new intermediate time point from [[Gawali2021 - ANA Prevalence in Seroconverted Dengue Patients]]:

| Study | Timing | Substrate | Rate | Setting |
|---|---|---|---|---|
| [[Chatterjee2024 - ANA Detection in Dengue Kolkata]] | Acute (fever clinic) | HEp-2 IIFA | 54.8% | Kolkata, India (hospital-based) |
| [[Chatterjee2024 - ANA Detection in Dengue Kolkata]] | Acute | LIA (18 specificities) | 18.5% | Kolkata, India |
| [[Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections]] | Acute viral (non-dengue) | ELISA (8 antigens) | 21.7% | Europe (HAV/HBV/HCV) |
| [[Gawali2021 - ANA Prevalence in Seroconverted Dengue Patients]] | **6 months post-dengue** | HEp-2 IIFA (1:100) | **18.33%** | Gwalior, India (IgG+ follow-up) |
| [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]] | 2 years post-dengue | Rat liver IIF | 23.1% | Cuba (symptomatic subset) |

Gawali2021 fills the most critical gap in the trajectory: 120 dengue patients confirmed IgG-seroconverted at 6 months were tested by HEp-2 IIFA at a single 1:100 dilution; 22/120 (18.33%) were positive, with AC-1 (nuclear homogeneous) as the dominant pattern (81.81%). This is consistent with a declining trajectory from the acute 54.8% peak, though the comparison is imperfect because Gawali2021 tested only IgG-seroconverted patients (not all dengue patients), used a single dilution without titre information, and had **no control group** — making it impossible to determine the background ANA rate for Central India. The closest available proxy (Li2019: 14.01% at >1:100 in a Chinese health-checkup population) leaves only ~4 percentage points of excess attributable to dengue, within the range of sampling variability for n=120.

Even with this limitation, the trajectory hint is suggestive: 54.8% (acute, HEp-2) → ~18% (6 months, HEp-2) → 23.1% (2 years, rat liver, which likely underestimates what HEp-2 would find). The apparent stabilisation or slight rise from 6 months to 2 years — if real across substrate differences — would be more consistent with an epitope-spreading or IC-persistence component than with simple passive decay of the acute spike. The dominant ANA pattern at 6 months (AC-1 nuclear homogeneous) points to dsDNA/histone/nucleosome targets — the same nuclear antigen class that Vo2020 finds positively correlated with platelet count in DHF, consistent with IgG class autoantibodies in those specificities persisting into the sub-acute period.

The outstanding gap remains the **1–3 month window**: the trajectory from peak (acute) to 6 months is still not directly observed. A single prospective study with HEp-2 IIFA at baseline (acute), 1M, 3M, 6M, 12M, and 24M with a concurrent dengue-negative febrile control arm would resolve the trajectory definitively.

### 6.3 What the NS1-IgG Kinetics Tell Us About the Trajectory

[[Bos2025 - Longitudinal Antibody Dynamics After Dengue]] supplies the first quantitative kinetic constraint relevant to this trajectory. In a Nicaraguan pediatric cohort followed at <1, 3, 6, and 18 months post-dengue, **NS1-IgG wanes with a calculated half-life of ≈ 2.1 years** in primary infection (similar trajectory in secondary infection). NS1 antibodies in this dataset are predominantly type-specific and follow a classical decay model.

If anti-NS1 antibodies are the substrate for NS1-driven molecular mimicry (as Lin2006, Lin2011, Wan2012 establish), then the NS1-mimicry *component* of dengue ANA should decline on a similar timescale — i.e., the share of acute IIFA positivity attributable to NS1 cross-reactivity should be roughly halved every ~2 years. This partially answers the trajectory question: at 2 years post-dengue, NS1-IgG is at approximately 50% of its acute peak, so the NS1-mimicry component of ANA should be at approximately 50% of its acute contribution — *if* the cross-reactive sub-fraction wanes with the same kinetics as NS1-IgG overall (an assumption that has not been directly measured).

This does not resolve the substrate-incompatibility problem between Chatterjee2024 (HEp-2) and Garcia2009 (rat liver). It does, however, add a constraint: the persistence of post-dengue ANA at 2 years cannot be entirely attributed to ongoing NS1-mimicry — a substantial fraction of the acute NS1-driven reactivity should have decayed by then. The persistence Garcia2009 documents is therefore more likely to reflect **epitope-spreading components** (cryptic-self exposure during acute tissue damage; see §5.3), **FcγRIIa-driven IC persistence** (§5.4), or **IgG3 persistence** (Bos2025 documents substantial IgG3 seropositivity at 18M, with IgG3 having ~5× higher FcγRIIIA affinity than IgG1 per [[Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses]]) — rather than continued NS1-driven mimicry. Bos2025 reframes Garcia2009's persistence as the *residual* of an actively decaying NS1-mimicry signal plus a more durable substrate-spreading and IC-driven component.

A separate observation from Bos2025 has the opposite implication: **cross-reactive E protein IgG (XR E-IgG) does not wane in the 6–18 month window — it rises** (calculated t½ = −2.13 years, indicating active growth). The dengue E protein WGNGCG motif shares homology with prothrombin and coagulation factors XI, X, IX, VII, II (Lin2011; see §5.1). If anti-E cross-reactive IgG is *actively rising* between 6 and 18 months while anti-NS1 IgG wanes, then the anti-E component of dengue autoreactivity may follow a different — and longer — trajectory than the anti-NS1 component. This complicates the simple "single-decay" model and is consistent with Garcia2009's finding of *persistent* (not just residual) ANA at 2 years.

---

## 7. Temporal Signature — Dengue Autoimmunity During the Acute Phase

A defining and underappreciated feature of dengue-associated autoimmunity is its **acute-phase timing**. Unlike most other infection-triggered autoimmune diseases — Campylobacter/GBS appearing weeks after diarrhea, EBV/SLE or EBV/multiple sclerosis appearing months to years after infection — dengue anti-NS1 autoimmune damage occurs *simultaneously* with active viral infection (see [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]], [[NS1 Molecular Mimicry in Dengue]]).

The implication is mechanistically important: the anti-NS1 antibodies responsible for platelet lysis and endothelial damage are generated within the first 5–7 days of infection, before adaptive immune maturation is complete. This raises the question of whether these early autoantibodies are predominantly IgM (rapid, low-affinity, complement-activating — consistent with Lin2006's characterisation of anti-platelet IgM) or whether rapid secondary infection anamnestic responses (IgG) contribute. Lin2006 identifies the anti-platelet autoantibodies as predominantly IgM; IgG contribution is referenced as unpublished in the same paper.

The "intrinsic ADE" hypothesis from [[Wan2012 - Autoimmunity in Dengue Pathogenesis]] adds a mechanistic link between ADE and autoantibody production: FcγR-mediated DENV entry suppresses type I IFN while promoting IL-10 and Th2 skewing, creating conditions for enhanced antibody production alongside high viral loads. If correct, ADE doesn't merely increase viral replication — it actively tilts the immune response toward the antibody-producing phenotype that generates cross-reactive autoantibodies via NS1 molecular mimicry. This would explain why DHF/DSS patients (where ADE is most active) show the highest anti-platelet and anti-endothelial autoantibody levels (Lin2006), and may explain why the IL-10-driven IGHG1+ plasmablast expansion documented in DHF by [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]] is so pronounced.

**Vo2020's primary>secondary IgG inversion complicates this model.** The intrinsic ADE hypothesis predicts that secondary infection — the context of ADE, higher viral loads, and greater clinical severity — should generate more autoantibody dysregulation. [[Vo2020 - Autoantibody Profiling in Dengue]] finds the opposite: Cambodian children with primary DENV infection showed significantly higher IgG autoantibody levels than those with secondary infection by microarray profiling (70 of 123 IgG autoantibodies elevated in primary vs. secondary, p < 0.01), while IgM did not differ. The Vo2020 interpretation — B cell tolerance checkpoint leakiness preferentially in primary infection, where naïve B cells may escape deletion without memory-dominated competition — is mechanistically plausible but untested. This inversion applies to breadth (number and range of IgG autoantibody reactivities), not necessarily to the specific pathogenic anti-endothelial and anti-platelet autoantibodies that Lin2006 and Wan2012 correlate with DHF severity in secondary infection; those two datasets are therefore not directly contradictory. The most parsimonious reconciliation is that primary infection generates a broader but mostly non-pathogenic polyclonal IgG autoantibody repertoire, while secondary infection generates a narrower but more pathogenically targeted anti-platelet/anti-endothelial response. This interpretation requires replication: the Vo2020 primary group was n=6, all male, all DENV-1 — too small and too confounded to treat as established.

---

## 8. Does Dengue-Associated ANA Progress to Clinical Autoimmune Disease?

The most rigorous evidence on this question comes from [[Shih2023 - Autoimmune Disease Risk After Dengue]] — a population-based cohort of 63,814 laboratory-confirmed dengue patients in Taiwan, 255,256 matched controls, followed for a mean of 4.57 years:

- **Overall autoimmune disease risk: aHR 1.16** (P = 0.0002) — statistically significant but clinically modest.
- After Bonferroni correction across 14 specific autoimmune outcomes: **only ADEM (autoimmune encephalomyelitis) is significantly elevated** (aHR 2.72; P < 0.0001).
- The ADEM risk is **entirely confined to the first month** post-infection (HR >9999 in month 1; non-significant thereafter); 16 dengue patients vs. 0 controls developed ADEM in month 1.
- All other outcomes — SLE, Sjögren's, rheumatoid arthritis, GBS, myasthenia gravis, post-infectious arthritis — are non-significant after correction.

This directly refutes [[Li2019 - ANA Epidemiology in Chinese Healthy Population]]'s predecessor Li et al. (2018), which reported dengue associated with >20 autoimmune diseases (aHR 1.88), on the basis that 51.4% of hospitalised "dengue" diagnoses in the pre-NS1 RDT era were not laboratory-confirmed — likely including patients with early autoimmune presentations misdiagnosed as dengue (fever, rash, thrombocytopenia are shared features). This is a methodological lesson with wide applicability: non-lab-confirmed cohorts in outbreak settings may be enriched with autoimmune disease misdiagnoses, producing spurious risk estimates.

**Reconciling Garcia2009 with Shih2023:** Garcia2009 found elevated ANA, IC, and CRP in symptomatic post-dengue patients at 2 years; Shih2023 finds no elevated clinical autoimmune disease incidence over 4.57 years. These are compatible:
1. ANA positivity is not equivalent to autoimmune disease. Most individuals who test ANA-positive — even at clinically relevant dilutions — never develop clinical SARD.
2. Garcia2009's cohort was a highly selected symptomatic subset (multiple prior infections, FcγRIIa-HH enriched), not representative of all dengue patients. Shih2023 covers all confirmed dengue, including asymptomatic and mild.
3. Elevated IC and CRP may reflect post-infectious inflammation rather than true autoimmunity; the autoimmune marker elevations may be biologically real but fall below the threshold for clinical disease in the vast majority.

ADEM as the exception is instructive: it is a transient, acute autoimmune demyelinating response confined to the first month — consistent with a post-infectious molecular mimicry mechanism targeting CNS myelin that resolves once acute immune stimulation subsides. It is not a chronic autoimmune disease, and its restriction to the first month supports the broader interpretation that dengue-triggered autoimmunity is transient and self-limiting.

**The ANA-negative vs. ANA-positive dengue autoimmune spectrum.** The case-report literature sharpens the question of when, if ever, dengue progresses to clinical SARD. Four primary sources now document five cases spanning the full spectrum from transient autoimmune syndrome to persistent SLE:

| Case / Source | ANA / anti-dsDNA | Renal involvement | Clinical syndrome | Evidence weight |
|---|---|---|---|---|
| Morel2014 Cases 2 & 3 | Both **negative** | Absent | MAS / secondary HLH; most severe in the series | n=2 within n=3 case series |
| Talib 2013 (cited in [[Palacios2016 - Autoimmunity in Dengue Literature Review]]) | ANA homogeneous **positive**; anti-dsDNA **positive** | Lupus nephritis | SLE + lupus nephritis; 4 of 11 ACR criteria | Single case via secondary source; no primary data |
| [[Rajadhyaksha2012 - Dengue Evolving into SLE and Lupus Nephritis]] | ANA 1:320 4+; anti-dsDNA 1:80 4+ | **Biopsy-confirmed Class IV GN** | SLE + lupus nephritis; anti-cardiolipin IgM+IgG+; 4-week post-dengue interval | n=1 case report; primary data; Mumbai India |
| [[Velazqueza2017 - SLE vs Dengue Case Series]] Cases 1 & 2 | ANA 1:1280 4+; anti-dsDNA+; antinucleosome+ in both | Not documented | SLE (concurrent or diagnosed 2 months after dengue) | n=2 case series; Guadalajara Mexico |
| [[Jardim2012 - Autoimmune Features DHF Case Report]] | ANA 1/320 **mitotic spindle**; anti-dsDNA **negative** throughout | Proteinuria only (0.55 g/day); no biopsy | Transient DHF autoimmune syndrome — **full ANA resolution at follow-up**; cryoglobulinemia; selective C3↓ with C4-normal | n=1 case report; primary data; Campinas Brazil; secondary DENV-3 |

Several features of this case series are now clear:

1. **Rajadhyaksha2012 is the primary-source case for biopsy-confirmed dengue→lupus nephritis.** The Talib 2013 case is known only via Palacios2016's citation — the original source was not directly ingested. Rajadhyaksha2012, the primary source published in *Lupus* 2012, independently documents Class IV diffuse proliferative GN confirmed by renal biopsy, providing the most objective histological evidence in this wiki for dengue-associated lupus renal disease.

2. **Anti-cardiolipin is an additional autoantibody axis.** Rajadhyaksha2012 documents combined IgM (44 MPLU/mL) and IgG (12 GPLU/mL) anti-cardiolipin, both persistently elevated at 4-month follow-up. No other dengue-SLE case in this wiki documents durable combined-isotype antiphospholipid antibodies; Morel2014 Case 1 (the *milder* case) showed transient IgM aCL only. The 4-month persistence in Rajadhyaksha2012 is consistent with SLE-driven antiphospholipid production rather than dengue-induced transient antiphospholipid response.

3. **The primary DENV-1 context across two independent case sources.** Rajadhyaksha2012 documents primary infection (IgM+/IgG-). Velazqueza2017's serotype data are not reported. The Vo2020 finding that primary DENV-1 infection generates broader IgG autoantibody repertoires than secondary now raises the question of whether first-time infection in genetically susceptible individuals is a higher-risk window for dengue-triggered SLE than reinfection — an interpretation opposite to severity-centric ADE-based thinking.

4. **The shared causal ambiguity.** In both Rajadhyaksha2012 and Velazqueza2017 Case 2 (the cases with the clearest post-dengue SLE timelines), no autoantibody testing was performed at the time of initial dengue — making it impossible to determine whether dengue triggered de novo autoimmunity or amplified pre-existing subclinical disease to clinical threshold. The very high ANA titres (1:1280 in Velazqueza2017; 1:320 in Rajadhyaksha2012 at presentation) are, if anything, more consistent with pre-existing tolerance breakdown than with a 4–8-week de novo induction kinetic.

5. **Jardim2012 establishes the "transient multi-autoantibody" pole.** This case is the only source in this wiki documenting complete ANA resolution at follow-up alongside the most complex single-case autoimmune picture: ANA 1/320 (mitotic spindle pattern), cryoglobulinemia, LE cells in pleural fluid, selective C3 depression with C4-normal, triple serositis, and DIC — all co-present and all fully resolved. The **mitotic spindle ANA pattern** targets centromere/spindle apparatus proteins (pericentrin, NuMA) rather than nuclear DNA/histones, expanding the autoantigen repertoire beyond what NS1-nuclear mimicry alone predicts and beyond all other dengue ANA patterns in this wiki (AC-1 homogeneous in Gawali2021; homogeneous+cytoplasmic in Velazqueza2017; homogeneous 4+ in Rajadhyaksha2012). Anti-dsDNA was negative throughout, unambiguously distinguishing this from SLE. The **selective C3 depression with C4-normal** (0.39 g/L vs. normal; C4 0.33 g/L — normal) contrasts with Rajadhyaksha2012's bilateral C3+C4 depression, suggesting a different complement activation route (alternative or MBL pathway rather than classical) — potentially useful as a differential distinguishing point in endemic settings. Together, this case is the strongest available evidence that dengue can produce an immunologically rich, multi-autoantibody syndrome that is completely self-limiting, supporting transience as the default outcome and persistence/SLE as the exception in susceptible individuals.

These cases do not challenge Shih2023's headline null finding (no broad SARD elevation at population level). What they document — individually — is that the rare individual who sits at the intersection of dengue infection and genetic SLE susceptibility may experience a clinically severe, biopsy-confirmed autoimmune flare within weeks of dengue exposure, spanning both renal (Class IV GN) and antiphospholipid axes, detectable by conventional ANA screen. Whether this represents 1-in-10,000 dengue patients or 1-in-100,000 cannot be determined from case reports alone; it lies below the detection threshold of any population-based cohort study yet published.

---

## 9. Host Factors Modifying the ANA Response

Several host factors modulate who develops ANA after dengue and whether it persists:

**FcγRIIa genotype.** The FcγRIIa-HH genotype impairs IC clearance and is associated with post-dengue sequelae (OR 2.83, Garcia2009) and, by extension, with the immune complex accumulation that sustains inflammatory stimulation. Critically, FcγRIIa acts primarily as a binary gate — controlling *symptomatic vs. asymptomatic* infection — rather than a severity dial within symptomatic disease (see [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]], [[Notable Findings]]). This means FcγRIIa genotype is relevant to whether autoimmune markers are elevated at all, not to how severe they become.

**Sex.** Post-dengue symptomatic sequelae in Garcia2009 were strongly female-predominant (65.7% of women vs. 36.7% of men, p = 0.008). This mirrors the well-established female predominance of ANA positivity in general (roughly 2× higher, driven partly by X-linked TLR7 double dosing and estrogen-driven immune activation — see [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]]). Whether sex interacts specifically with dengue-driven ANA production (beyond the baseline demographic effect) is unknown from available data.

**Prior infection history.** 21/26 patients with autoimmune marker elevations in Garcia2009 had ≥1 prior dengue infection; 12/26 had tetravalent infection history. Multiple prior infections likely increase cumulative NS1-antigen exposure and may shift from IgM-dominant to IgG-dominant autoantibody profiles — potentially sustaining autoimmune stimulation through longer-lived plasma cells.

**Severity.** Counterintuitively, acute illness severity (DF vs. DHF/DSS) did not predict development of post-dengue sequelae in Garcia2009 (p = 0.086). However, anti-platelet and anti-endothelial autoantibody levels *during* the acute phase are higher in DHF/DSS than DF (Lin2006). These may resolve at similar rates regardless of peak severity, or the relationship may be non-linear.

**Infection order (primary vs. secondary).** [[Vo2020 - Autoantibody Profiling in Dengue]] introduces infection order — first vs. subsequent exposure — as a factor not previously tracked in IIFA-based ANA studies. Vo2020 found that primary infection generated broader IgG autoantibody repertoires than secondary (70 of 123 microarray antigens elevated in primary vs. secondary, p < 0.01; n=6 primary, n=26 secondary). If this extends to HEp-2 IIFA positivity, clinical ANA cohorts enriched for secondary infection — typical of hyperendemic populations such as those in Garcia2009 and Chatterjee2024 — may systematically underestimate the IgG-autoantibody burden associated with first-time DENV exposure. The practical implication: populations newly encountering a serotype for the first time (e.g., naïve adults in an outbreak of an emerging serotype) may carry higher individual-level autoimmune activation risk than secondary-infection-dominant literature predicts. This finding requires replication in a powered and better-matched cohort before it can be incorporated into any clinical framework.

---

## 10. Key Open Questions

The following gaps emerge directly from the synthesis above:

1. **The intermediate trajectory.** What happens to the acute HEp-2 IIFA rate (54.8%) at 1, 3, and 6 months post-dengue? Without this, it is impossible to determine whether Garcia2009's 2-year finding represents persistence of the acute spike or near-complete resolution. A single longitudinal study using HEp-2 IIFA at multiple time points in a lab-confirmed dengue cohort would resolve this.

2. **Titer distribution of the IIFA-positive fraction.** Are the IIFA-positive, LIA-negative dengue ANAs predominantly low-titer (1:40–1:80) or do some reach ≥1:160? Titer data would distinguish polyclonal noise from genuinely elevated self-reactive antibodies and allow meaningful comparison with the SLE classification threshold.

3. **NS1 homology with nuclear antigens.** The established dengue molecular mimicry targets are surface-accessible cytoplasmic and transmembrane proteins (PDI, vimentin, ATP synthase β). Do dengue NS1 or other viral proteins share structural homology with canonical nuclear antigens (Sm, dsDNA, Ro, La)? If they do, this would recast dengue as capable of directly generating disease-relevant ANA through molecular mimicry rather than only through non-specific bystander or epitope-spreading mechanisms.

4. **ANA-FcγRIIa genotype interaction.** Does ANA rate and persistence correlate with FcγRIIa genotype (HH > RR > HR) in dengue patients? If the IC-persistence model is correct — impaired clearance → prolonged antigen stimulation → sustained ANA production — this would be the expected finding and would provide a mechanistic explanation for why Garcia2009's post-dengue ANA persists.

5. **The Chatterjee2024 MCTD and myositis signals.** Do the 18.5% LIA-positive dengue patients go on to develop clinical MCTD or autoimmune myositis at higher rates? The 6–7 month follow-up in Chatterjee2024 is insufficient to determine progression to clinical disease. A 2–5 year longitudinal follow-up of this LIA-positive subgroup is needed.

6. **Whether Shih2023's null SARD findings have adequate statistical power for rare outcomes.** MCTD and autoimmune myositis would be very rare even in a 63,814-patient cohort. The absence of a significant signal for these specific diseases in Shih2023 does not rule out a clinically meaningful risk — it may simply reflect insufficient power. Sample size calculations for MCTD-incidence studies in post-dengue cohorts have not been published.

7. **Does dengue-triggered MAS represent a separate autoimmune axis invisible to ANA testing?** Morel2014's two MAS cases were ANA- and anti-dsDNA-negative despite being the most severe presentations in the series. If MAS is a parallel macrophage-hyperactivation axis (rather than a B-cell autoantibody axis), then ANA-prevalence studies in dengue will systematically miss the MAS-prone subset. Prospective measurement of soluble CD163, IL-18, and ferritin in ANA-stratified dengue cohorts would test whether these axes co-occur or dissociate.

8. **Is the Talib 2013 SLE case de novo or flare?** Palacios2016 catalogues the only documented ANA-positive (homogeneous pattern, anti-dsDNA-positive) clinical SLE case in this wiki's dengue literature, but the original authors note the diagnosis could represent pre-existing subclinical SLE pushed into flare by acute dengue. Distinguishing de novo induction from flare requires pre-infection ANA serology, which is almost never available in endemic-population dengue cohorts.

9. **Does NS1-IgG waning kinetically predict anti-platelet / anti-endothelial autoantibody decay?** Bos2025 establishes NS1-IgG t½ ≈ 2.1 years. If the cross-reactive (anti-host) sub-fraction wanes with the same kinetics as bulk NS1-IgG, then post-dengue autoreactivity attributable to NS1-mimicry should halve every ~2 years. This is testable by paired longitudinal measurement of (a) NS1-binding IgG titre and (b) anti-PDI / anti-vimentin titre in the same patients across the 0–24 month window.

10. **Does the rising XR E-IgG trajectory after primary infection produce *increasing* anti-coagulation-factor reactivity?** If E protein's WGNGCG motif (Lin2011) cross-reacts with prothrombin and other coagulation factors, and if XR E-IgG actively rises between 6 and 18 months (Bos2025), then anti-coagulation-factor autoreactivity may *grow* in the inter-infection window — the opposite trajectory from anti-NS1 reactivity. This would imply two opposing temporal vectors within the same patient's autoreactive repertoire.

11. **What is the relative contribution of the Lin2001/Lin2006 IgM autoantibody pathway versus the Oishi2003/Saito2004 IC deposition pathways to dengue thrombocytopenia?** Primary infection: IgM anti-platelet autoantibody (true autoreactivity; Lin2001). Secondary infection: PAIgG and PAIgM anti-dengue immune complexes (Oishi2003, Saito2004). Only the Lin2001 pathway is amenable to autoimmune-directed therapy (steroids, IVIG); the secondary-infection pathways require virus-clearance or complement inhibition strategies. Knowing the dominant pathway in a given patient would directly inform therapeutic choice.

12. **Does nuclear antigen IgG consumption explain ANA-negative severe dengue?** Vo2020 found that canonical ANA-target IgGs (KU, Smith, histone, Sm/RNP, nucleosome) positively correlate with platelet counts in DHF (r = 0.74–0.83; n=8 DHF), implying these antibodies are consumed into immune complexes at peak disease severity. If correct, clinical ANA testing at nadir platelet count underestimates the total autoimmune burden in DHF, and "ANA-negative" severe dengue cases (including Morel2014's MAS) may reflect consumption rather than absence of autoimmune activation. Prospective testing requires serial paired measurement of free-serum ANA, complement activation markers (C3d, sC5b-9), IC levels, and platelet count across the DHF severity spectrum.

14. **Is the anti-cardiolipin response in dengue-associated SLE dengue-induced or SLE-driven?** [[Rajadhyaksha2012 - Dengue Evolving into SLE and Lupus Nephritis]] documents combined IgM + IgG anti-cardiolipin at SLE diagnosis, persisting at 4 months. Morel2014 Case 1 (mild, self-limiting dengue without SLE) showed transient IgM aCL only. The combined-isotype persistence in Rajadhyaksha2012 is more consistent with SLE-driven antiphospholipid antibody production than with the transient single-isotype IgM aCL documented in dengue without SLE. However, no pre-dengue aCL measurement exists for the Rajadhyaksha2012 patient. A prospective study measuring anti-cardiolipin at acute dengue, 3 months, and 12 months in a cohort stratified by ANA positivity would determine whether durable combined-isotype aCL is specific to dengue patients with underlying SLE susceptibility or whether it occurs in dengue without SLE.

13. **Does PAIgM's complete FcγR independence explain its superiority over PAIgG as a DHF predictor?** Saito2004 shows PAIgM independently predicts DHF (92.1% specificity) while PAIgG does not survive multivariate regression. If FcγRIIa genotype modulates PAIgG-mediated platelet clearance — the magnitude of PAIgG accumulation varying by HH/HR/RR status — then PAIgM, bypassing all FcγR steps via IgM pentamer structure, would be a purer measure of dengue IC severity unconfounded by FcγRIIa polymorphism. A study measuring PAIgG, PAIgM, and FcγRIIa genotype concurrently in secondary dengue would directly test whether the PAIgM predictive advantage dissolves after genotype stratification.

---

## 11. Summary and Synthesising Framework

A coherent picture emerges from this wiki's 28 sources on ANA and dengue, best captured in three claims of different epistemic weight:

**Established (convergent evidence across ≥3 sources):**
- Dengue massively upregulates ANA during acute infection: ~55% by HEp-2 IIFA (Chatterjee2024), far exceeding the healthy-population baseline (13–16% at 1:80) and the generic viral-infection rate (~22% by narrower ELISA, Berlin2007).
- The vast majority (~66%) of this acute IIFA positivity is non-specific. **The mechanistic basis is now named:** germline-encoded polyreactive IgM, constitutively present in all healthy individuals with a serum half-life of ~8 hours, binds nuclear antigens non-specifically as a normal property of the immune repertoire. Dengue's inflammatory milieu amplifies this pool, producing a transient, IgM-dominated IIFA signal that does not correspond to antigen-driven autoimmunity. The LIA-confirmed fraction (~18.5%) is the operationally relevant measure of pathologically induced dengue autoimmunity (Zhou2007, Chatterjee2024, Vo2020).
- Dengue-associated autoimmunity manifests during the *acute phase* of infection, not post-infectious — an unusual and mechanistically distinctive timing relative to other infection-triggered autoimmunities.
- At the population level, dengue does not broadly elevate clinical autoimmune disease incidence; only ADEM is robustly elevated, and only in the first month (Shih2023).
- Dengue can produce a clinically severe autoimmune complication (MAS / secondary HLH) that is **ANA- and anti-dsDNA-negative** (Morel2014, with supporting MAS+nephrotic case in Lai 2012 cited by Palacios2016) — establishing a parallel macrophage-driven autoimmune axis distinct from the NS1-mimicry → autoantibody pathway.
- Dengue thrombocytopenia involves at least three immunologically distinct platelet-bound immunoglobulin populations: (1) a true autoreactive IgM anti-platelet antibody in primary infection (Lin2001, Lin2006); (2) an NS1-specific anti-dengue IgG immune complex in secondary infection (Oishi2003) without FcγRII binding; and (3) an anti-dengue IgM immune complex in secondary infection (Saito2004) that is completely FcγR-independent and independently predicts DHF with 92.1% specificity. The secondary-infection IgM immune complex is mechanistically opposite to the primary-infection IgM autoantibody despite being the same isotype.
- **NS1 molecular mimicry anti-platelet and anti-endothelial autoantibodies are infection-order independent.** Anti-PDI IgM, anti-HSP60 IgM, and anti-EC IgM are comparably elevated in primary and secondary DHF (Cheng2015, n=17 DHF), convergent with Lin2001 (primary DENV-3), Saito2004, and Hung2008 (primary-infection infants, n=50, Vietnam). The PDI-cross-reactive epitope has been narrowed to **P311–330** within the NS1 C-terminal region (Cheng2015). These are constitutive NS1 immunity features, not ADE-escalated secondary-infection phenomena. Hung2008 additionally documents an anti-EC **isotype shift** by infection order: IgM only in primary/infants; IgM+IgG in predominantly secondary/children — with the IgG component reflecting immune memory class switching, not a different mechanistic pathway.

**Probable (supported by ≥2 sources with methodological limitations):**
- ANA positivity remains elevated at 2 years post-dengue in symptomatic patients (Garcia2009), consistent with the molecular mimicry + FcγRIIa IC-persistence model, but constrained by rat-liver substrate and lack of a contemporaneous control group.
- NS1 molecular mimicry — producing anti-PDI, anti-vimentin, anti-HSP60 autoantibodies — is the primary dengue-specific mechanism for the autoimmune component of thrombocytopenia and vascular leakage (Lin2001, Lin2006, Lin2011, Wan2012, Guzman2016).
- Bystander activation is likely insufficient on its own to explain dengue-associated ANA (inference from Johnson2022's COVID-19 ICU finding).
- Anti-NS1 IgG wanes with t½ ≈ 2.1 years post-primary dengue (Bos2025), implying the NS1-mimicry component of post-dengue ANA decays on a similar timescale and that Garcia2009's 2-year ANA persistence is more attributable to epitope-spreading and IC-persistence components than to ongoing NS1 mimicry.

**Hypothesis-generating (single source or indirect inference):**
- MCTD and autoimmune myositis may be specifically elevated in dengue-associated ANA (Chatterjee2024 — wide CIs, small n).
- The "intrinsic ADE" mechanism may create a positive feedback loop between viral enhancement and autoantibody production (Wan2012).
- The acute plasmablast clonotype expanded in symptomatic dengue disappears at convalescence (Sungnak2025), raising the possibility that autoreactive clones may be among those cleared — or alternatively, that they leave no persistent memory precisely because they target self-antigens and tolerance is re-established.
- Dengue is associated with ANA-positive clinical SLE in multiple independent case reports across different countries: Rajadhyaksha2012 (Mumbai India, biopsy-confirmed Class IV LN, anti-cardiolipin IgM+IgG+, primary DENV-1), Velazqueza2017 Cases 1&2 (Guadalajara Mexico, ANA 1:1280, antinucleosome, n=2 pediatric), and Talib 2013 (Singapore, via Palacios2016). These are consistent across geographically and demographically diverse settings. Whether they represent dengue triggering de novo SLE or amplifying subclinical pre-existing disease is unresolved in every case — no pre-dengue autoantibody baseline exists for any of them. Combined-isotype anti-cardiolipin (IgM+IgG) persisting to 4 months adds an antiphospholipid dimension not previously characterised in the dengue-SLE literature (Rajadhyaksha2012).
- Cross-reactive E protein IgG actively *rises* between 6 and 18 months post-primary infection (Bos2025, t½ = −2.13 y); given the E-protein WGNGCG motif's homology with coagulation factors (Lin2011), the anti-coagulation-factor component of dengue autoreactivity may follow an opposite (rising) temporal vector to the anti-NS1 component within the same patient.
- Nuclear antigen IgGs (KU, Smith, histone, Sm/RNP, nucleosome) are positively correlated with platelet counts in DHF (Vo2020, n=8 DHF; no multiple comparison correction) — interpreted as immune complex consumption, implying that ANA testing at peak disease severity may underestimate the autoimmune burden in the most severe patients and that some "ANA-negative severe dengue" cases may reflect antibody consumption rather than absence of nuclear antigen reactivity.
- Primary DENV infection generates broader IgG autoantibody repertoires than secondary infection on microarray profiling (Vo2020, n=6 primary — heavily confounded by sex and serotype), implying that first-exposure dengue may represent the window of maximal polyclonal IgG autoantibody activation — a reversal of severity-centric expectations.
- **Anti-hCF as a protective anti-cytokine autoantibody axis (Chaturvedi2001 — ⚠ unvalidated):** Anti-hCF IgG was present in 96% of DF vs. 8% of grade IV DHF patients in a 1996 Lucknow cohort — an inverse severity association unique among dengue autoantibodies in this wiki. If real, this represents a third ANA-invisible autoimmune axis (anti-cytokine, protective) alongside the established pathogenic B-cell axis and the ANA-negative MAS macrophage axis. However, hCF itself has never been sequenced or independently replicated — all downstream claims are contingent on that validation.

---

## Related Pages

- [[Antinuclear Antibodies]]
- [[Autoimmunity in Dengue]]
- [[NS1 Molecular Mimicry in Dengue]]
- [[Infection-Triggered Autoimmunity]]
- [[Post-Dengue Syndrome]]
- [[FcγRIIa Receptor]]
- [[Indirect Immunofluorescence ANA Test]]
- [[Line Immunoassay ANA]]
- [[Antibody-Dependent Enhancement]]
- [[Dengue Neurological Complications]]
- [[Notable Findings]]

---

## Sources

- [[Tan1997 - ANA Range in Healthy Individuals]]
- [[Satoh2012 - ANA Prevalence in United States]]
- [[Li2019 - ANA Epidemiology in Chinese Healthy Population]]
- [[Aringer2019 - 2019 EULAR ACR SLE Classification Criteria]]
- [[Dinse2022 - Increasing ANA Prevalence in United States]]
- [[Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections]]
- [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]]
- [[Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients]]
- [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]]
- [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]]
- [[Oishi2003 - PAIgG and Thrombocytopenia in Secondary Dengue]]
- [[Wan2012 - Autoimmunity in Dengue Pathogenesis]]
- [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]]
- [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]]
- [[Chatterjee2024 - ANA Detection in Dengue Kolkata]]
- [[Shih2023 - Autoimmune Disease Risk After Dengue]]
- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]
- [[Guzman2016 - Dengue Infection]]
- [[Bos2025 - Longitudinal Antibody Dynamics After Dengue]]
- [[Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses]]
- [[Morel2014 - Autoimmune Response in Children With Dengue]]
- [[Palacios2016 - Autoimmunity in Dengue Literature Review]]
- [[Vo2020 - Autoantibody Profiling in Dengue]]
- [[Saito2004 - PAIgG and PAIgM in Secondary Dengue]]
- [[Zhou2007 - Polyreactive Antibodies Natural Antibody Function]] (polyreactive IgM as mechanistic basis for non-specific IIFA fraction; germline-encoded low-affinity IgM binding nuclear antigens constitutively; PAB cell biology; half-life ~8h; distinction from antigen-induced pathological autoantibodies)
- [[Gawali2021 - ANA Prevalence in Seroconverted Dengue Patients]] (6-month post-dengue ANA: 18.33% HEp-2 IIFA positive in dengue IgG+ patients at 1:100; AC-1 dominant; no control group; Gwalior Central India; n=120; intermediate time point in the acute→2-year trajectory)
- [[Velazqueza2017 - SLE vs Dengue Case Series]] (n=2 pediatric SLE+dengue; ANA 1:1280 + antinucleosome + anti-dsDNA in both; Case 2 SLE diagnosed 2 months post-dengue; Guadalajara Mexico; extends ANA-positive dengue-SLE cluster to a second geographic setting)
- [[Rajadhyaksha2012 - Dengue Evolving into SLE and Lupus Nephritis]] (n=1 adult, primary DENV-1; ANA 1:320 + anti-dsDNA 1:80 + anti-cardiolipin IgM+IgG+ + biopsy-confirmed Class IV LN; 4-week post-dengue interval; Mumbai India; first primary-source documentation of dengue→lupus nephritis with renal biopsy; anti-cardiolipin IgM+IgG persistent at 4 months)
- [[Jardim2012 - Autoimmune Features DHF Case Report]] (n=1, secondary DENV-3 DHF; ANA 1/320 mitotic spindle pattern; cryoglobulinemia; selective C3 depression C4-normal; LE cells in pleural fluid; triple serositis; DIC; full ANA resolution at follow-up; anti-dsDNA negative throughout; Campinas Brazil; clearest example of transient multi-autoantibody syndrome in the wiki)
- [[Codes2002 - Autoantibodies in Acute Viral Hepatitis]] (primary source for 20.5% acute / 6.4% convalescent ANA in viral hepatitis; IIF homogeneous ≥1:40; n=156 prospective; Salvador Brazil; also 14.8% → 3.9% ASMA; not a dengue paper — viral-infection transience comparator baseline cited via Berlin2007)
- [[Cheng2015 - NS1 P311-330 Anti-PDI Autoantibodies in DHF]] (PDI cross-reactive epitope narrowed to P311–330 by synthetic peptide blocking assay; HSP60 uses distinct unidentified NS1 epitope; anti-vimentin anomalous — no NS1 correlation; primary/secondary DHF equivalence for anti-endothelial autoantibodies confirmed; n=17 DHF (2 primary + 15 secondary) + 2 DF; Ho Chi Minh City/NCKU Taiwan)
- [[Chaturvedi2001 - Cytotoxic Factor Autoantibodies DHF]] (⚠ unvalidated group-specific concept; anti-hCF IgG 96% DF → 8% DHF-IV, P ≤ 0.001; hCF = dengue-specific CD4+ T cell cytotoxin unsequenced and unreplicated; if real, represents a third ANA-invisible protective autoimmune axis; Lucknow AIIMS 1996 epidemic, n=74)
- [[Hung2008 - Anti-Platelet Anti-Endothelial Autoantibodies Vietnam]] (anti-platelet IgM in primary-infection infants, n=50, DENV-3/4, Ho Chi Minh City — replication of Lin2001 in endemic Vietnam; anti-EC isotype shift: IgM only in primary/infants, IgM+IgG in predominantly secondary/children; TM elevated as in vivo endothelial damage evidence; no autoantibody–severity or –platelet count correlation)
- [[Santosa2012 - Delayed SLE Diagnosis Dengue Serology]] (reverse direction: SLE-associated polyclonal IgM false-positives dengue IgM serology; mechanistically links the low-affinity IgM pool in SLE to dengue test cross-reactivity; Singapore NUHS)
