---
type: analysis
tags: [ANA, antinuclear-antibody, dengue, autoimmunity, molecular-mimicry, bystander-activation, epitope-spreading, post-dengue, IIF, HEp-2, LIA, prevalence, healthy-population, acute-phase, IIFA, FcγRIIa, NS1, literature-review]
created: 2026-04-13
updated: 2026-04-13
sources: 12
---

# ANA and Dengue — A Literature Review

*Synthesised from 12 source papers and 8 concept/method pages. Last updated 2026-04-13.*

---

## 1. Why ANA and Dengue?

Antinuclear antibodies ([[Antinuclear Antibodies]]) — immunoglobulins directed against nuclear and cytoplasmic components of eukaryotic cells — are the canonical biomarker of systemic autoimmune rheumatic disease (SARD). Yet they are not specific to autoimmune disease: they appear transiently in healthy individuals, rise with age, and are elevated during acute infections. The question this literature review addresses is: **does dengue virus infection produce ANA in a pattern that is clinically meaningful, mechanistically distinct, or prognostically significant — and if so, for whom, through what mechanism, and for how long?**

Dengue is an unusual candidate for this question because it is the most prevalent mosquito-borne viral disease globally (~390 million infections per year; see [[Guzman2016 - Dengue Infection]]) and because its immunopathogenesis — dominated by the NS1 protein's cross-reactivity with host proteins — involves molecular mimicry operating during the *acute phase* of infection rather than post-infectious. This creates a tight, observable window for studying the initiation of autoimmunity in a real-world setting.

---

## 2. Establishing the Healthy-Population Baseline

Before interpreting ANA rates in dengue patients, a robust baseline is essential. Four studies in this wiki characterise healthy-population ANA prevalence:

| Study | Population | Dilution/Method | ANA Prevalence |
|---|---|---|---|
| [[Tan1997 - ANA Range in Healthy Individuals]] | Multicentre international; adults 21–60 | 1:40, IIF | 31.7% |
| [[Tan1997 - ANA Range in Healthy Individuals]] | As above | 1:80, IIF | 13.3% |
| [[Tan1997 - ANA Range in Healthy Individuals]] | As above | 1:160, IIF | 5.0% |
| [[Satoh2012 - ANA Prevalence in United States]] | US NHANES 1999–2004; ≥12 yrs | 1:80, IIF | 13.8% |
| [[Li2019 - ANA Epidemiology in Chinese Healthy Population]] | Chinese health-checkup; all ages | >1:100, IIF | 14.01% |
| [[Dinse2022 - Increasing ANA Prevalence in United States]] | US NHANES 2011–2012; ≥12 yrs | 1:80, IIF | 16.1% |

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
- ANA detected during acute viral hepatitis fell from 20.5% in the acute phase to 6.4% in convalescence in a cited study — establishing that *transience* is a genuine feature of infection-triggered ANA. This is important context for interpreting both dengue-specific acute ANA measurements and claims about post-dengue persistence.

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

---

## 5. Mechanisms Producing ANA in Dengue

The [[Infection-Triggered Autoimmunity]] literature identifies three canonical mechanisms. All three are potentially relevant to dengue, but their relative contributions differ:

### 5.1 Molecular Mimicry — The Primary Dengue-Specific Mechanism

The NCKU group (Lin, Lei et al.) has provided the most experimentally detailed evidence. Anti-dengue NS1 antibodies, generated during normal antiviral immunity, cross-react with platelet and endothelial cell surface proteins due to structural/sequence similarity between NS1 and those host proteins.

**Established cross-reactive targets** (see [[NS1 Molecular Mimicry in Dengue]], [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]], [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]]):

| Host Protein | Location | Functional Consequence |
|---|---|---|
| PDI (protein disulfide isomerase) | Platelet surface | Anti-NS1 inhibits PDI → platelet aggregation inhibition |
| Vimentin | Platelet + endothelial | Surface binding; consequences under investigation |
| ATP synthase β-chain | Platelet + endothelial | Surface binding; consequences under investigation |
| HSP60 | Platelet + endothelial | Cross-targeted also by anti-prM Abs |
| LYRIC protein | Endothelial | NS1 aa 116–119 shares sequence similarity with human LYRIC aa 334–337 |

The responsible NS1 domain is the **C-terminal region (amino acids 311–352)**: deletion of aa 277–352 abolishes anti-NS1-mediated platelet aggregation and bleeding tendency. This is the same domain relevant to the autoimmune risk of NS1-based vaccines — retaining the C-terminal domain carries autoimmune risk.

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

A coherent timeline of dengue ANA now exists in this wiki:

| Study | Timing | Substrate | Rate |
|---|---|---|---|
| [[Chatterjee2024 - ANA Detection in Dengue Kolkata]] | Acute (fever clinic) | HEp-2 IIFA | 54.8% |
| [[Chatterjee2024 - ANA Detection in Dengue Kolkata]] | Acute | LIA (18 specificities) | 18.5% |
| [[Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections]] | Acute viral (non-dengue) | ELISA (8 antigens) | 21.7% |
| [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]] | 2 years post-dengue | Rat liver IIF | 23.1% |

The missing data are the **intermediate time points** — 1, 3, and 6 months post-dengue. Wan2012 describes dengue autoantibody titres peaking in the acute phase, declining during convalescence, and persisting for "several months" — but provides no IIFA-based ANA quantification. What happens to the acute 54.8% IIFA rate over time? If it follows the acute viral hepatitis pattern (20.5% → 6.4% in convalescence), the trajectory would converge toward the healthy-population baseline. If it follows the Garcia2009 pattern (still elevated at 2 years), the substrate incompatibility makes the comparison unclear.

The substrate gap makes this calculation impossible from current data: a rat-liver-measured 23% at 2 years may correspond to a HEp-2-measured rate anywhere from ~30–50%, which would represent substantial persistence of the acute spike — or it may represent near-complete resolution. Without a longitudinal HEp-2 IIFA study at multiple time points post-dengue, this trajectory is unresolvable.

---

## 7. Temporal Signature — Dengue Autoimmunity During the Acute Phase

A defining and underappreciated feature of dengue-associated autoimmunity is its **acute-phase timing**. Unlike most other infection-triggered autoimmune diseases — Campylobacter/GBS appearing weeks after diarrhea, EBV/SLE or EBV/multiple sclerosis appearing months to years after infection — dengue anti-NS1 autoimmune damage occurs *simultaneously* with active viral infection (see [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]], [[NS1 Molecular Mimicry in Dengue]]).

The implication is mechanistically important: the anti-NS1 antibodies responsible for platelet lysis and endothelial damage are generated within the first 5–7 days of infection, before adaptive immune maturation is complete. This raises the question of whether these early autoantibodies are predominantly IgM (rapid, low-affinity, complement-activating — consistent with Lin2006's characterisation of anti-platelet IgM) or whether rapid secondary infection anamnestic responses (IgG) contribute. Lin2006 identifies the anti-platelet autoantibodies as predominantly IgM; IgG contribution is referenced as unpublished in the same paper.

The "intrinsic ADE" hypothesis from [[Wan2012 - Autoimmunity in Dengue Pathogenesis]] adds a mechanistic link between ADE and autoantibody production: FcγR-mediated DENV entry suppresses type I IFN while promoting IL-10 and Th2 skewing, creating conditions for enhanced antibody production alongside high viral loads. If correct, ADE doesn't merely increase viral replication — it actively tilts the immune response toward the antibody-producing phenotype that generates cross-reactive autoantibodies via NS1 molecular mimicry. This would explain why DHF/DSS patients (where ADE is most active) show the highest anti-platelet and anti-endothelial autoantibody levels (Lin2006), and may explain why the IL-10-driven IGHG1+ plasmablast expansion documented in DHF by [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]] is so pronounced.

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

---

## 9. Host Factors Modifying the ANA Response

Several host factors modulate who develops ANA after dengue and whether it persists:

**FcγRIIa genotype.** The FcγRIIa-HH genotype impairs IC clearance and is associated with post-dengue sequelae (OR 2.83, Garcia2009) and, by extension, with the immune complex accumulation that sustains inflammatory stimulation. Critically, FcγRIIa acts primarily as a binary gate — controlling *symptomatic vs. asymptomatic* infection — rather than a severity dial within symptomatic disease (see [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]], [[Notable Findings]]). This means FcγRIIa genotype is relevant to whether autoimmune markers are elevated at all, not to how severe they become.

**Sex.** Post-dengue symptomatic sequelae in Garcia2009 were strongly female-predominant (65.7% of women vs. 36.7% of men, p = 0.008). This mirrors the well-established female predominance of ANA positivity in general (roughly 2× higher, driven partly by X-linked TLR7 double dosing and estrogen-driven immune activation — see [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]]). Whether sex interacts specifically with dengue-driven ANA production (beyond the baseline demographic effect) is unknown from available data.

**Prior infection history.** 21/26 patients with autoimmune marker elevations in Garcia2009 had ≥1 prior dengue infection; 12/26 had tetravalent infection history. Multiple prior infections likely increase cumulative NS1-antigen exposure and may shift from IgM-dominant to IgG-dominant autoantibody profiles — potentially sustaining autoimmune stimulation through longer-lived plasma cells.

**Severity.** Counterintuitively, acute illness severity (DF vs. DHF/DSS) did not predict development of post-dengue sequelae in Garcia2009 (p = 0.086). However, anti-platelet and anti-endothelial autoantibody levels *during* the acute phase are higher in DHF/DSS than DF (Lin2006). These may resolve at similar rates regardless of peak severity, or the relationship may be non-linear.

---

## 10. Key Open Questions

The following gaps emerge directly from the synthesis above:

1. **The intermediate trajectory.** What happens to the acute HEp-2 IIFA rate (54.8%) at 1, 3, and 6 months post-dengue? Without this, it is impossible to determine whether Garcia2009's 2-year finding represents persistence of the acute spike or near-complete resolution. A single longitudinal study using HEp-2 IIFA at multiple time points in a lab-confirmed dengue cohort would resolve this.

2. **Titer distribution of the IIFA-positive fraction.** Are the IIFA-positive, LIA-negative dengue ANAs predominantly low-titer (1:40–1:80) or do some reach ≥1:160? Titer data would distinguish polyclonal noise from genuinely elevated self-reactive antibodies and allow meaningful comparison with the SLE classification threshold.

3. **NS1 homology with nuclear antigens.** The established dengue molecular mimicry targets are surface-accessible cytoplasmic and transmembrane proteins (PDI, vimentin, ATP synthase β). Do dengue NS1 or other viral proteins share structural homology with canonical nuclear antigens (Sm, dsDNA, Ro, La)? If they do, this would recast dengue as capable of directly generating disease-relevant ANA through molecular mimicry rather than only through non-specific bystander or epitope-spreading mechanisms.

4. **ANA-FcγRIIa genotype interaction.** Does ANA rate and persistence correlate with FcγRIIa genotype (HH > RR > HR) in dengue patients? If the IC-persistence model is correct — impaired clearance → prolonged antigen stimulation → sustained ANA production — this would be the expected finding and would provide a mechanistic explanation for why Garcia2009's post-dengue ANA persists.

5. **The Chatterjee2024 MCTD and myositis signals.** Do the 18.5% LIA-positive dengue patients go on to develop clinical MCTD or autoimmune myositis at higher rates? The 6–7 month follow-up in Chatterjee2024 is insufficient to determine progression to clinical disease. A 2–5 year longitudinal follow-up of this LIA-positive subgroup is needed.

6. **Whether Shih2023's null SARD findings have adequate statistical power for rare outcomes.** MCTD and autoimmune myositis would be very rare even in a 63,814-patient cohort. The absence of a significant signal for these specific diseases in Shih2023 does not rule out a clinically meaningful risk — it may simply reflect insufficient power. Sample size calculations for MCTD-incidence studies in post-dengue cohorts have not been published.

---

## 11. Summary and Synthesising Framework

A coherent picture emerges from this wiki's 12 sources on ANA and dengue, best captured in three claims of different epistemic weight:

**Established (convergent evidence across ≥3 sources):**
- Dengue massively upregulates ANA during acute infection: ~55% by HEp-2 IIFA (Chatterjee2024), far exceeding the healthy-population baseline (13–16% at 1:80) and the generic viral-infection rate (~22% by narrower ELISA, Berlin2007).
- The vast majority (~66%) of this acute IIFA positivity is non-specific: it does not correspond to established SARD autoantibody specificities on LIA testing.
- Dengue-associated autoimmunity manifests during the *acute phase* of infection, not post-infectious — an unusual and mechanistically distinctive timing relative to other infection-triggered autoimmunities.
- At the population level, dengue does not broadly elevate clinical autoimmune disease incidence; only ADEM is robustly elevated, and only in the first month (Shih2023).

**Probable (supported by ≥2 sources with methodological limitations):**
- ANA positivity remains elevated at 2 years post-dengue in symptomatic patients (Garcia2009), consistent with the molecular mimicry + FcγRIIa IC-persistence model, but constrained by rat-liver substrate and lack of a contemporaneous control group.
- NS1 molecular mimicry — producing anti-PDI, anti-vimentin, anti-HSP60 autoantibodies — is the primary dengue-specific mechanism for the autoimmune component of thrombocytopenia and vascular leakage (Lin2006, Lin2011, Wan2012, Guzman2016).
- Bystander activation is likely insufficient on its own to explain dengue-associated ANA (inference from Johnson2022's COVID-19 ICU finding).

**Hypothesis-generating (single source or indirect inference):**
- MCTD and autoimmune myositis may be specifically elevated in dengue-associated ANA (Chatterjee2024 — wide CIs, small n).
- The "intrinsic ADE" mechanism may create a positive feedback loop between viral enhancement and autoantibody production (Wan2012).
- The acute plasmablast clonotype expanded in symptomatic dengue disappears at convalescence (Sungnak2025), raising the possibility that autoreactive clones may be among those cleared — or alternatively, that they leave no persistent memory precisely because they target self-antigens and tolerance is re-established.

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
- [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]]
- [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]]
- [[Wan2012 - Autoimmunity in Dengue Pathogenesis]]
- [[Garcia2009 - Long-term Clinical Symptoms Post-Dengue]]
- [[Chatterjee2024 - ANA Detection in Dengue Kolkata]]
- [[Shih2023 - Autoimmune Disease Risk After Dengue]]
- [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]
- [[Guzman2016 - Dengue Infection]]
