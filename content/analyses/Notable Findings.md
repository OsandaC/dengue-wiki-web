---
type: analysis
tags: [notable-findings, flags, cross-cutting, observations]
created: 2026-04-12
updated: 2026-04-18 (Jardim2012 ingest)
sources: 20
---

# Notable Findings

A running log of observations that are striking, unexpected, or carry implications beyond the paper they came from. Each entry is a flag — something worth returning to, following up on, or building an analysis around. Entries are added during ingest whenever something catches the eye.

---

## [2026-04-18] Dengue can produce a mitotic spindle ANA pattern — spindle apparatus antigens join the dengue autoantibody target repertoire

**Source:** [[Jardim2012 - Autoimmune Features DHF Case Report]]

**Finding:** A 25-year-old woman with secondary DENV-3 DHF developed ANA 1/320 with a **mitotic spindle fluorescent pattern** — targeting centromere/spindle apparatus proteins rather than nuclear DNA or histones. Co-occurring autoimmune features included cryoglobulinemia (mixed immune complexes), selective C3 depression (C4 normal), and LE cells in pleural fluid. All markers — including ANA — resolved completely at follow-up. Anti-dsDNA was negative throughout.

**Why notable:** Every other dengue ANA case with a reported pattern in this wiki shows a **homogeneous nuclear** signal (AC-1 type in Gawali2021; homogeneous 4+ in Rajadhyaksha2012; homogeneous+cytoplasmic or fine speckled in Velazqueza2017) — consistent with anti-dsDNA/histone/nucleosome targets. The mitotic spindle pattern is a different autoantigen class: proteins of the spindle apparatus and centromere (pericentrin, NuMA, tubulin-associated antigens) that are extranuclear in interphase cells and exposed during mitosis on HEp-2 cells. These are not NS1 mimicry targets (PDI, vimentin, HSP60, ATP synthase β — see [[NS1 Molecular Mimicry in Dengue]]). Their appearance suggests dengue can trigger autoantibody formation against a broader range of cellular proteins than NS1 molecular mimicry alone can explain. Whether this reflects epitope spreading from dengue-induced apoptosis releasing spindle apparatus antigens, polyreactive IgM binding, or a different mimicry target is unknown — the substrate and LIA confirmatory status are not reported. The full ANA resolution at follow-up is consistent with any of these mechanisms. The cryoglobulinemia finding is also the first documentation of dengue-associated mixed immune complex cryoprecipitation in this wiki — mechanistically expected given dengue's IC-generating pathophysiology but not previously a primary-source observation.

**Follow-up questions:**
- Has the mitotic spindle ANA pattern been documented in any other dengue case in the literature? If so, it would establish a specific dengue → spindle apparatus autoantigen axis analogous to the NS1 → PDI/vimentin platelet/endothelial axis.
- Does the mitotic spindle pattern on HEp-2 represent anti-centromere antibodies (associated with limited systemic sclerosis in autoimmune disease settings) or anti-spindle antibodies (MSA-36, anti-pericentrin, anti-NuMA) — specific antigens would substantially narrow the mechanistic interpretation.
- Does selective C3 depression with normal C4 distinguish dengue complement activation pattern from SLE-type classical pathway complement consumption — could this be used clinically to differentiate dengue serositis from SLE serositis in endemic settings?

**Related pages:** [[Antinuclear Antibodies]], [[Autoimmunity in Dengue]], [[NS1 Molecular Mimicry in Dengue]], [[Dengue Pathophysiology]]

---

## [2026-04-17] The two-thirds non-specific dengue ANA fraction has a name: polyreactive IgM

**Source:** [[Zhou2007 - Polyreactive Antibodies Natural Antibody Function]] interpreted against [[Chatterjee2024 - ANA Detection in Dengue Kolkata]] and [[Vo2020 - Autoantibody Profiling in Dengue]]

**Finding:** Germline-encoded polyreactive IgM — normal antibodies present constitutively in all individuals that bind structurally unrelated self and non-self antigens with low affinity — has a half-life of ~8 hours and constitutes 15–20% of adult peripheral blood B cell output at rest. In acute viral infection, amplification of this pool would produce a transient, IgM-dominated, broadly self-reactive signal detectable by HEp-2 IIFA but negative on disease-specific LIA panels. The properties match exactly the fingerprint of the "non-specific" dengue ANA fraction: IgM dominant (Vo2020: 80 elevated IgM vs. 6 IgG), fails LIA confirmation (~66% of IIFA-positives in Chatterjee2024), and expected to be transient.

**Why notable:** The wiki's existing Notable Finding ([2026-04-12]) flags the ~66% LIA-negative IIFA fraction as "non-specific" and asks what mechanism produces it. Zhou2007 provides the mechanism — it has a name, a molecular basis, and known properties. This reframes the dengue ANA story in a materially important way: the massive acute IIFA spike (54.8%) is not predominantly a sign of *induced* autoimmunity at all. Much of it may be the normal polyreactive IgM background, temporarily amplified by dengue's inflammatory milieu. The implication is that the clinically and mechanistically meaningful dengue autoantibody signal — the genuinely induced, antigen-specific fraction — is considerably smaller than the raw IIFA prevalence suggests, and is better approximated by LIA positivity (18.5%) than IIFA. This does not dismiss the dengue autoimmunity literature (the anti-platelet/anti-endothelial findings from Lin2001/Lin2006 are antigen-specifically driven and pathologically real), but it explains why most IIFA-positive dengue patients never develop clinical autoimmune disease: they never had antigen-induced autoimmunity — they had an acute polyreactive IgM transient.

**Follow-up questions:**
- Can the IIFA-positive, LIA-negative dengue ANA fraction be confirmed as polyreactive IgM by BCR V-region sequencing — are the relevant B cells using germline sequences without somatic hypermutation?
- Does the IIFA rate and LIA rate diverge differently between mild dengue (DF) and severe dengue (DHF) — if the polyreactive IgM fraction is severity-independent, only the LIA-positive fraction should track severity?
- Is the Berlin2007 finding (21.7% ANA in acute viral infections) similarly composed largely of polyreactive IgM background noise rather than virus-specific induction?

**Related pages:** [[Polyreactive Antibodies]], [[Antinuclear Antibodies]], [[Autoimmunity in Dengue]], [[Infection-Triggered Autoimmunity]]

---

## [2026-04-17] ADE is not just a threshold phenomenon — there is a discrete quantitative enhancement window (titer 1:21–1:80)

**Source:** [[Bhatt2020 - Dengue Pathogenesis Review]] (citing Katzelnick et al. 2017, *Science*)

**Finding:** In a prospective cohort of 6,684 Nicaraguan children followed for nine years, pre-existing anti-dengue antibody titres of 1:21–1:80 were associated with peak dengue hospitalisation risk — the ADE enhancement window. Below this range, antibody levels are insufficient to mediate meaningful FcγR-dependent viral uptake. Above 1:1,280, neutralisation dominates and protection is conferred. The ADE danger zone is thus bounded on both ends by a discrete quantitative range.

**Why notable:** Prior wiki sources (Guzman2016, Wan2012, Dejnirattisai2010) established ADE as a qualitative mechanism — cross-reactive antibodies below the neutralisation threshold are enhancing. The Katzelnick data convert this into a quantitative prediction with practical implications. The "enhancement window" framing changes how waning immunity should be evaluated: it is not simply that waning immunity is risky as neutralising titres fall, but that there is a specific titer band where an individual has *exactly the wrong amount of antibody* — enough to load Fc receptors with virus but not enough to neutralise. This is directly relevant to: (1) vaccine safety monitoring — post-vaccination titre waning should be tracked against this window, not just against a binary seropositive/seronegative threshold; (2) the risk model for CYD-TDV seronegatives — their primed-but-waned antibody titres likely fell into this range upon natural DENV challenge; (3) the Bos2025 (PREPRINT) observation that cross-reactive E-IgG *rises* post-primary — the question of whether rising XR E-IgG titres pass through or above the enhancement window has direct bearing on when and whether ADE risk peaks.

**Follow-up questions:**
- What are the post-vaccination antibody waning kinetics for TAK-003 and TV003 in seronegative vaccinees, and do their waning trajectories pass through the 1:21–1:80 window?
- Is the 1:21–1:80 window specific to total anti-dengue IgG, or do anti-prM and anti-E antibodies each have their own enhancement windows?
- Does the quantitative ADE window shift by infecting serotype sequence (e.g., is the enhancement window for DENV2 secondary different from DENV4)?

**Related pages:** [[Antibody-Dependent Enhancement]], [[Dengue Vaccine Candidates]], [[Cross-Reactive Antibodies]], [[CYD-TDV]], [[Secondary Dengue Infection]]

---

## [2026-04-17] Anti-prM antibodies are the dominant structural antibody in dengue infection — and the most potent ADE mediators

**Source:** [[Dejnirattisai2010 - Anti-prM Antibodies Enhance Dengue ADE]]

**Finding:** In DENV-infected humans, approximately 60% of anti-dengue structural antibodies are directed against the prM (pre-membrane) protein — not the E protein, which had been assumed to dominate the structural humoral response. Anti-prM antibodies are fully cross-reactive across all four DENV serotypes, cannot neutralise above a 10–60% ceiling regardless of titre, and mediate ADE in primary human monocytes and dendritic cells at up to 10^5-fold enhancement — substantially exceeding typical anti-E ADE magnitudes.

**Why notable:** The entire established ADE and vaccine-design literature in this wiki frames anti-E antibodies as the relevant ADE-mediating population, with the neutralisation threshold as the key variable separating protective from enhancing antibody. Dejnirattisai2010 introduces a parallel ADE pathway with two fundamental differences: (1) the dominant antibody class is anti-prM, not anti-E; (2) the neutralisation ceiling is structural — from incomplete prM cleavage leaving a non-neutralisable mature virion fraction — not a matter of titre falling below a threshold. These are not competing models; both pathways likely operate in vivo. But if anti-prM is the numerically dominant pathway, then: (a) prior conclusions about sub-threshold anti-E as the ADE driver need qualification; (b) standard vaccine immunogenicity readouts (anti-E neutralising titres) may be measuring a minority antibody population while ignoring the majority enhancing one; (c) all three leading vaccine platforms (CYD-TDV, TAK-003, TV003) prime anti-prM responses that are, by this paper's characterisation, structurally incapable of providing complete neutralisation and constitutively ADE-prone. The 10^5-fold monocyte/DC enhancement also substantially exceeds prior quantifications of ADE magnitude in the wiki, implying a more explosive viral amplification upon Fc-mediated uptake than the classical model suggests.

**Follow-up questions:**
- What are the relative anti-prM and anti-E antibody titres at the point of secondary infection — does anti-prM dominate at the time of heterotypic challenge as it does at the B cell population level?
- Have post-2010 vaccine candidates (especially DNA vaccines or mRNA platforms) adopted modified or deleted prM sequences in response to this finding?
- Is there any clinical correlate of anti-prM titre with DHF risk in prospective secondary-infection cohorts?

**Related pages:** [[prM Protein]], [[Antibody-Dependent Enhancement]], [[Cross-Reactive Antibodies]], [[Dengue Vaccine Candidates]], [[E Protein]], [[Secondary Dengue Infection]]

---

## [2026-04-17] Secondary dengue PAIgM is an anti-dengue immune complex — not an autoantibody — refining the bifurcation model

**Sources:** [[Saito2004 - PAIgG and PAIgM in Secondary Dengue]], [[Oishi2003 - PAIgG and Thrombocytopenia in Secondary Dengue]], [[Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients]]

**Finding:** Saito2004 confirms that IgM elevated on platelets in secondary dengue infection carries **anti-dengue virus IgM specificity** (confirmed by platelet eluate ELISA), not anti-platelet autoantibody specificity. Combined with Oishi2003 (PAIgG also carries anti-dengue IgG specificity), the secondary-infection mechanism is now fully characterised as two-isotype anti-dengue immune complex deposition — not autoimmunity. PAIgM is additionally an FcγR-independent predictor of DHF (specificity 92.1%, cut-off >20 ng/10⁷ platelets).

**Why notable:** The wiki's existing Notable Finding [2026-04-15] ("thrombocytopenia bifurcates by infection order") describes the secondary mechanism as "anti-dengue IgG immune complexes." Saito2004 now adds a second immune complex isotype (IgM) to the secondary picture. This matters because the primary-infection mechanism (Lin2001) involves IgM anti-platelet *autoantibodies* — the same isotype now documented as anti-dengue immune complexes in secondary infection. The two IgM species are therefore mechanistically opposite: one is anti-self (NS1 molecular mimicry), the other is anti-viral (immune complex). The bifurcation is now precisely: primary infection → IgM anti-platelet autoantibody; secondary infection → PAIgG + PAIgM anti-dengue immune complexes (both FcγRII-independent at platelet docking; PAIgM additionally FcγR-independent at clearance). Any future study measuring "IgM on platelets" in dengue must distinguish IgM origin (autoantibody vs. immune complex) — simple PAIgM elevation cannot be interpreted without eluate specificity testing.

**Follow-up questions:**
- Is PAIgM's complete FcγR independence the mechanistic reason it outperforms PAIgG as a DHF severity predictor? (FcγRIIa genotype would modulate PAIgG clearance but not PAIgM clearance — the more severe DHF cases may be those in which the complement-driven PAIgM pathway predominates.)
- Does a study of PAIgG/PAIgM in primary dengue infection find PAIgG elevated (anti-dengue IgG IC mechanism from prior sensitisation is absent in primary — so PAIgG should be low if Oishi2003 is correct)?

**Related pages:** [[Secondary Dengue Infection]], [[Dengue Pathophysiology]], [[FcγRIIa Receptor]], [[Platelet-Associated Immunoglobulin ELISA]], [[Autoimmunity in Dengue]]

---

## [2026-04-15] Thrombocytopenia mechanism bifurcates by infection order: autoantibody in primary, immune complex in secondary — with FcγRII bypassed in both

**Sources:** [[Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients]], [[Oishi2003 - PAIgG and Thrombocytopenia in Secondary Dengue]]

**Finding:** Taken together, Lin2001 and Oishi2003 reveal that dengue thrombocytopenia has two mechanistically distinct modes depending on infection history. In primary DENV infection, thrombocytopenia is driven by **IgM anti-platelet autoantibodies** generated through NS1 molecular mimicry; complement-mediated platelet lysis is severity-correlated. In secondary DENV infection, anti-platelet autoantibodies are essentially absent (1/53 patients); instead, **anti-dengue virus IgG immune complexes** deposit on platelets via direct dengue-platelet binding — and FcγRII is explicitly not required for this binding step.

**Why notable:** The clean infection-order dependency is not described in any single paper — it only emerges from holding Lin2001 and Oishi2003 against each other. Prior to Lin2001's ingest, the wiki described dengue thrombocytopenia primarily as an autoimmune phenomenon (NS1 mimicry). Oishi2003 shows that the *secondary* infection mechanism is not autoimmune at all: it is immune complex-mediated, not self-directed, and bypasses FcγRII at the platelet surface. This has three downstream implications: (1) NS1-targeted interventions to prevent thrombocytopenia would primarily help primary infection, not secondary; (2) the FcγRIIa genotype's enormous effect on DHF risk (Garcia2010, OR 10.56 for HH) must operate via a mechanism *other* than platelet destruction — most likely ADE viral uptake in monocytes/macrophages; (3) platelet-targeted therapies in severe secondary dengue should target immune complex clearance, not autoantibody production.

**Follow-up questions:**
- Are both mechanisms (IgM autoAb + immune complex) active simultaneously in secondary infection, with the immune complex pathway simply dominant — or does the secondary anamnestic IgG response suppress IgM autoantibody production entirely?
- Does FcγRIIa genotype modulate downstream macrophage clearance of PAIgG-coated platelets in secondary infection (even if FcγRII is not involved in the initial dengue-platelet docking step)?
- Can platelet eluate studies in primary DENV infection directly test whether anti-dengue virus IgG is absent (as would be expected if Lin2001's IgM autoAb pathway is the dominant route)?

**Related pages:** [[NS1 Protein]], [[Secondary Dengue Infection]], [[FcγRIIa Receptor]], [[Autoimmunity in Dengue]], [[Dengue Pathophysiology]]

---

## [2026-04-15] IgM anti-platelet lysis tracks severity; aggregation inhibition does not — and both occur in primary infection

**Source:** [[Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients]]

**Finding:** In a DENV-3 Taiwan outbreak cohort (n=9, mostly primary infection), dengue patient sera have two functionally distinct effects on platelets with opposite severity correlations: (1) complement-mediated platelet **lysis** — present, and significantly *higher* in DHF/DSS than DF at both acute and convalescent stages; (2) ADP-induced platelet aggregation **inhibition** — present, but NOT higher in DHF/DSS than DF, and paradoxically higher in convalescence than acute. The paper also establishes that IgM anti-platelet production is present in the majority-primary-infection context of this outbreak, making the mechanism independent of prior dengue exposure.

**Why notable:** The existing wiki attributes "anti-platelet autoAbs cause thrombocytopenia in severe dengue" as a single mechanism. Lin2001 shows this is at least two mechanisms — lysis and aggregation inhibition — with the lysis component being the functionally relevant severity correlate. The wiki's current narrative, derived from later Lin2006/Lin2011 synthesis papers, had blurred this distinction. More importantly, the primary-infection context directly qualifies the ADE-dependent secondary infection narrative: a sufficient anti-platelet IgM response in primary infection is mechanistically capable of driving DHF/DSS severity through complement-mediated platelet lysis, entirely independently of cross-reactive IgG from prior exposure. This provides the cleanest known ADE-independent mechanism for primary-infection DHF/DSS in the wiki — a gap that the ADE literature never fully closes. The aggregation inhibition finding also raises a puzzling mechanistic question: why does aggregation inhibition *increase* from acute to convalescence while IgM binding *decreases*? These are not the same antibody effect, and their kinetic divergence implies a second, non-IgM mechanism for aggregation interference that builds over time.

**Follow-up questions:**
- What drives the convalescent increase in aggregation inhibition if IgM levels are falling? Is a different antibody class (IgG?) mediating aggregation inhibition at the PDI level?
- Can the prevalence of primary-infection DHF/DSS in hyperendemic settings be predicted by anti-platelet IgM titres in the first dengue episode?
- Does complement activation status (C3/C4 levels, complement pathway polymorphisms) predict whether anti-platelet IgM causes clinically significant platelet lysis — and thereby explains why some primary infections progress to DHF?

**Related pages:** [[NS1 Molecular Mimicry in Dengue]], [[NS1 Protein]], [[Secondary Dengue Infection]], [[Antibody-Dependent Enhancement]], [[Dengue Pathophysiology]], [[DENV-3]], [[Taiwan]]

---

## [2026-04-15] Dengue-triggered MAS is ANA-negative — severe immune pathology without conventional autoantibodies

**Sources:** [[Morel2014 - Autoimmune Response in Children With Dengue]], [[Palacios2016 - Autoimmunity in Dengue Literature Review]]

**Finding:** Three paediatric dengue cases in Paraguay (Morel2014) show ANA and anti-dsDNA negative in all three, including the two most severe cases that fulfilled Macrophage Activation Syndrome (MAS/secondary HLH) criteria and required methylprednisolone (hyperferritinemia up to 3828 mg/dl, cytopenias, hepatosplenomegaly). The milder, self-limiting case (Case 1) showed IgM anticardiolipin positivity and hypocomplementemia — more conventional autoimmune markers — yet was less severe. This apparent inversion is biologically coherent: MAS is macrophage/T cell–driven, not autoantibody-mediated.

**Why notable:** The entire wiki autoimmunity thread (Chatterjee2024's 54.8% IIFA, Garcia2009's 2-year ANA persistence, Lin2006/Lin2011 NS1 mimicry, Wan2012's autoantibody kinetics) frames dengue autoimmunity through antinuclear and anti-platelet/endothelial antibody production. Morel2014 introduces a second, mechanistically distinct dengue immune complication that the existing framework cannot accommodate: macrophage hyperactivation producing severe clinical disease (MAS) with *no* detectable conventional autoantibodies. The NS1 molecular mimicry model generates anti-platelet/endothelial autoantibodies; the NS1-TLR4/ADE-macrophage model generates cytokine storm and macrophage hyperactivation. Both are NS1-dependent but downstream of entirely different effector arms. The practical clinical implication is sharp: **a negative ANA in dengue does not rule out severe autoimmune complication** — it only rules out one mechanism. Palacios2016 adds a supporting adult MAS+nephrotic syndrome case (Lai 2012) and, contrasting with Morel, a case of dengue-triggered SLE with *positive* ANA and anti-dsDNA (Talib 2013) — confirming that ANA-positive and ANA-negative dengue autoimmune presentations coexist. The field has no study systematically comparing autoantibody profiles between ANA-positive dengue autoimmunity and ANA-negative dengue-MAS.

**Follow-up questions:**
- Do Morel2014's MAS cases have elevated anti-endothelial cell Abs by flow cytometry (Wan2012 method) despite negative standard ANA — or is the anti-endothelial response also suppressed in macrophage-dominant disease?
- Do dengue-MAS patients carry heterozygous HLH predisposition variants (PRF1, UNC13D, STX11) that lower the macrophage activation threshold — or is MAS stochastic given sufficient dengue-induced macrophage load?
- Can hyperferritinemia ≥500 mg/dl serve as a practical dengue-MAS flag in endemic settings to trigger corticosteroid consideration before further workup?

**Related pages:** [[Macrophage Activation Syndrome in Dengue]], [[Autoimmunity in Dengue]], [[NS1 Molecular Mimicry in Dengue]], [[Cytokine Storm]], [[NS1 Protein]]

---

## [2026-04-14] Cross-reactive E protein IgG rises — not wanes — in the ADE risk window (Bos2025, PREPRINT)

**Source:** [[Bos2025 - Longitudinal Antibody Dynamics After Dengue]]

**Finding:** In a Nicaraguan pediatric cohort (n=79) followed to 18 months post-dengue, cross-reactive E protein IgG (XR E-IgG) targeting domains I and II (EDI/II) increases from 6 to 18 months post-primary infection, with a calculated t½ of −2.13 years (growth trajectory). NS1-IgG, by contrast, wanes conventionally (t½ ≈ 2.1 years). EDIII-targeting antibodies — the more serotype-specific, more neutralising fraction — remain flat. IgA seropositivity persists at ~100% and IgM at ~50% at 18 months, far exceeding standard expectations.

**Why notable:** The foundational assumption of the classical ADE model is that cross-reactive antibodies wane passively after primary dengue, eventually dropping below the neutralisation threshold and converting from protective to enhancing — with the inter-infection interval determining ADE risk. Bos2025 challenges this with an opposite trajectory: the cross-reactive EDI/II-targeting IgG pool is actively expanding during the 6–18M window. Critically, EDI/II-targeting antibodies are the cross-reactive, non-neutralising class most likely to mediate ADE upon heterotypic re-exposure. If this finding is confirmed in peer-reviewed form, the ADE risk window is not opened by passive decay — it is *created* by an active immunological process of cross-reactive antibody accumulation. This also reframes the inter-infection interval effect: a longer interval may produce higher ADE risk not because neutralising antibodies wane further, but because the non-neutralising XR EDI/II pool has had more time to expand. The kinetic divergence between NS1-IgG (waning) and XR E-IgG (rising) is itself a novel finding — it implies antibody trajectories are antigen-specific, not a uniform property of the post-dengue immune response. The NS1-IgG waning also provides the first kinetic anchor in this wiki for the ANA trajectory: the NS1-mimicry component of dengue ANA likely declines with NS1-IgG (t½ ≈ 2.1 years), while the epitope-spreading component may be more durable.

> **Caveat:** Bos2025 is a medRxiv preprint. These findings require peer review before the mechanistic interpretations can be treated as established.

**Follow-up questions:**
- Are the rising XR EDI/II IgG antibodies functionally non-neutralising — i.e., do they enhance infection in ADE assays rather than neutralise it?
- Does the inter-infection interval correlate with peak XR EDI/II IgG titre at the time of secondary infection — and does that titre predict DHF severity?
- Does NS1-IgG waning (t½ ≈ 2.1 years) correlate with declining anti-platelet / anti-endothelial autoantibody titres, directly linking NS1-IgG dynamics to resolution of NS1-mimicry-derived autoimmunity?

**Related pages:** [[Cross-Reactive Antibodies]], [[Antibody-Dependent Enhancement]], [[E Protein]], [[NS1 Protein]], [[Autoimmunity in Dengue]]

---

## [2026-04-13] The FcγRIIa H131/R131 effect in dengue is IgG2-specific — the conventional IgG1/IgG3 model is unsupported by affinity data

**Source:** [[Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses]]

**Finding:** By SPR measurement, FcγRIIA-H131 and -R131 bind IgG1 with nearly equal affinity (KA 52 vs. 35 ×10⁵ M⁻¹; ~1.5× difference) and IgG3 identically (9.1 vs. 8.9 ×10⁵ M⁻¹). The primary allele-dependent difference is for IgG2: H131 binds IgG2 4.5× more efficiently than R131 (4.5 vs. 1.0 ×10⁵ M⁻¹). Separately, FcγRIIB (inhibitory receptor) has ~43× lower affinity for IgG1 than FcγRIIA-H131 — making it incapable of independently intercepting ICs, and dependent entirely on co-engagement with activating receptors.

**Why notable:** The standard explanation for why FcγRIIa-HH is associated with worse dengue outcomes (Garcia2009/2010) and for why RR is protective against symptomatic infection has always been that HH has *lower* IgG1/IgG3 affinity → poorer IC clearance → IC accumulation → ADE/inflammation. Bruhns2009 directly contradicts the affinity premise: H131 binds IgG1 *more* efficiently than R131, and IgG3 identically. The existing wiki pages have now been corrected, but the deeper implication remains unresolved: if the affinity model is wrong, the mechanism by which HH is harmful in dengue is unknown. The IgG2 asymmetry (4.5×) now becomes the most mechanistically plausible explanation — but only if IgG2 anti-dengue antibodies are abundant enough in secondary infection to drive differential FcγRIIA engagement. Additionally, the FcγRIIB weakness quantifies something previously only assumed: the inhibitory checkpoint is structurally too weak to independently terminate IC-driven activation, providing a molecular basis for why dengue IC accumulation (Garcia2009) sustains inflammation without effective negative feedback.

**Follow-up questions:**
- What is the IgG subclass distribution of anti-dengue antibodies in primary vs. secondary infection, and particularly at the time post-infection when Garcia2009's IC/ANA measurements were made?
- If IgG2 anti-dengue antibodies are substantial in secondary infection, do H131/H131 individuals have measurably higher IC-driven cytokine release than R131/R131 individuals in ex vivo assays?
- Can FcγRIIB's ~43× affinity deficit relative to FcγRIIA be experimentally demonstrated in dengue IC models — confirming that inhibitory signalling only engages when activating receptors are co-occupied?

**Related pages:** [[FcγRIIa Receptor]], [[Antibody-Dependent Enhancement]], [[Autoimmunity in Dengue]], [[Post-Dengue Syndrome]]

---

## [2026-04-13] ADEM is the one post-dengue autoimmune signal robust enough to survive methodological opposite study designs

**Sources:** [[Li2018 - Increased Risk of Autoimmune Diseases in Dengue]], [[Shih2023 - Autoimmune Disease Risk After Dengue]]

**Finding:** Li2018 (ICD-coded dengue, n=12,506, no multiple comparison correction) and Shih2023 (lab-confirmed dengue, n=63,814, Bonferroni correction) are methodologically as different as two studies using the same database can be — yet both find ADEM significantly elevated after dengue, with convergent relative risk estimates (aHR 3.80 and aHR 2.72 respectively). Of all specific autoimmune diseases tested across either paper, ADEM is the only finding that holds across both. Conversely, GBS is non-significant in both (aHR 0.97 and non-significant after correction), despite being the most commonly cited post-infectious dengue neurological complication in case reports.

**Why notable:** The conventional approach to assessing a methodologically weaker study is to discount its positive findings when a stronger study fails to replicate them. But the ADEM convergence inverts this: both studies agree, from opposite methodological starting points. This cross-design robustness is a stronger form of replication than two studies using the same method. It establishes ADEM as the most methodologically secure disease-specific finding in the dengue–autoimmunity literature. The GBS null convergence is similarly informative: if GBS were elevated, it would appear in at least one of two studies — its absence in both suggests the GBS case reports represent genuine but rare individual events below population-level detectability rather than a generalizable dengue sequela. Separately, Li2018 flags **primary adrenocortical insufficiency** as the most *frequent* outcome by case count (n=19; aHR 2.05), proposing a TLR-mediated adrenal mechanism that Shih2023 did not specifically test and that remains unvalidated.

**Follow-up questions:**
- Can the Li2018 adrenocortical insufficiency finding be retested in a lab-confirmed cohort with sufficient power? Shih2023 likely had too few cases to detect a 2.05× risk for a rare outcome.
- Is dengue ADEM biologically distinct from ADEM triggered by other viral infections (measles, EBV, influenza) — or is it an instance of generic post-viral demyelination?
- Do the case reports of dengue-associated GBS represent a real rare phenotype, or diagnostic misclassification (severe dengue with neuropathy vs. GBS)?

**Related pages:** [[Autoimmunity in Dengue]], [[Dengue Neurological Complications]], [[Taiwan]], [[Infection-Triggered Autoimmunity]]

---

## [2026-04-13] NS1 molecular mimicry cannot explain the nuclear ANA — epitope spreading is the implied mechanism

**Sources:** [[Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection]], [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]], [[Wan2012 - Autoimmunity in Dengue Pathogenesis]], [[Chatterjee2024 - ANA Detection in Dengue Kolkata]], [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]]

**Finding:** The NS1 molecular mimicry mechanism — the best-evidenced dengue-specific autoimmune pathway — produces cross-reactive antibodies against PDI, vimentin, HSP60, and ATP synthase β on platelet and endothelial surfaces. None of these targets are nuclear antigens. Yet Chatterjee2024 shows 54.8% of dengue patients are ANA-positive by HEp-2 IIFA, which detects antibodies against *nuclear* components. Of the three candidate mechanisms for infection-triggered ANA (molecular mimicry, bystander activation, epitope spreading), bystander activation has been functionally ruled out by the COVID-19 ICU null finding (Johnson2022). By elimination, **epitope spreading from dengue-induced tissue damage releasing cryptic nuclear antigens** is the most plausible explanation for the HEp-2-positive fraction of dengue ANA — a conclusion not stated in any individual source, only visible from synthesis.

**Why notable:** The dengue autoimmunity literature has focused almost entirely on NS1/platelet/endothelial cross-reactivity as the mechanism — understandably, because that is where the experimental evidence is. But this mechanism cannot, by definition, produce antinuclear antibodies on HEp-2 IIFA. The 54.8% IIFA rate therefore implicates a *second, independent mechanism* (epitope spreading) operating in parallel with NS1 mimicry. If correct, this means dengue-associated ANA represents the output of at least two distinct processes with different kinetics: (1) early molecular mimicry producing non-nuclear autoantibodies that peak acutely and resolve over months; and (2) epitope spreading from tissue damage releasing nuclear antigens, potentially with a delayed onset and longer persistence curve — which would fit Garcia2009's 2-year ANA persistence better than NS1 mimicry alone can. It also reframes the research question: the key unanswered question is not "what does NS1 cross-react with?" (largely answered) but "what nuclear antigens are released by dengue-induced endothelial apoptosis and platelet lysis?"

**Follow-up questions:**
- What nuclear antigens are released from endothelial cells undergoing the anti-NS1-induced apoptosis pathway (caspase-3 activation)? This is directly testable: add anti-NS1 Abs to endothelial cell cultures, collect the apoptotic supernatant, run it against HEp-2 cells.
- Does dengue ANA on HEp-2 show a specific staining pattern (homogeneous, speckled, nucleolar) suggesting particular nuclear antigen targets — and does this pattern correlate with the LIA-positive subgroup?
- Is the HEp-2-positive ANA fraction higher in patients with more endothelial damage (DHF vs. DF), as predicted by the epitope spreading model?

**Related pages:** [[NS1 Molecular Mimicry in Dengue]], [[Antinuclear Antibodies]], [[Autoimmunity in Dengue]], [[Infection-Triggered Autoimmunity]], [[Indirect Immunofluorescence ANA Test]]

---

## [2026-04-12] Dengue drives a massive acute ANA spike (55% by HEp-2 IIFA) — but two-thirds are non-specific

**Source:** [[Chatterjee2024 - ANA Detection in Dengue Kolkata]]

**Finding:** In 135 laboratory-confirmed dengue patients presenting to fever clinics in Kolkata, India, 54.8% tested ANA-positive by HEp-2 IIFA — the gold-standard, most sensitive ANA platform. When these IIFA-positive patients were retested with Line Immunoassay (LIA) covering 18 specific autoantibody targets, only 18.5% of *all* dengue patients remained positive — meaning roughly two-thirds of IIFA-positive dengue patients had no detectable disease-specific autoantibody. Among dengue-negative febrile controls, the IIFA:LIA ratio was much tighter (10.3% vs. 7.1%), indicating the non-specific IIFA positivity is dengue-specific.

**Why notable:** This is the first measurement in this wiki of ANA in *acute* dengue using HEp-2 cells, and the 54.8% rate is far higher than any prior estimate. But the 3:1 IIFA:LIA ratio reframes the whole dengue-ANA story. It means: (1) dengue acutely perturbs nuclear antigen reactivity on a massive scale — half of patients show fluorescent staining; (2) almost none of this corresponds to the targeted specificities (Sm, dsDNA, Ro/La, Scl-70, U1-RNP, Jo-1, etc.) of named autoimmune diseases. This is the immunological equivalent of broad collateral fire: dengue activates many self-reactive B cell clones, but almost none are the clones driving established AARDs. It provides the most direct evidence yet that the acute-phase autoimmune activation in dengue is largely non-specific — consistent with Shih2023's population-level null finding for clinical autoimmune disease incidence. It also raises a calibration problem for Garcia2009's 23.1% (rat liver IIF, 2 years post-dengue): if the *acute* HEp-2 rate is ~55%, what is the trajectory — does it fall to ~23% rat-liver-equivalent, or does something persist? The substrate gap makes this unanswerable from current data.

**Follow-up questions:**
- What is the HEp-2 IIFA rate at 6 months and 2 years post-dengue? Charting the decline of the acute spike would determine whether the Garcia2009 2-year finding represents persistence or near-complete resolution.
- Are the IIFA-positive, LIA-negative dengue ANAs predominantly low-titer (1:40–1:80) or do some reach clinically relevant titers (≥1:160)? Titer data would clarify whether this is a polyclonal noise phenomenon or something more targeted.
- Do the 18.5% LIA-positive patients go on to develop clinical autoimmune disease at higher rates? The 6–7 month follow-up in Chatterjee2024 is insufficient to answer this.

**Related pages:** [[Antinuclear Antibodies]], [[Autoimmunity in Dengue]], [[Indirect Immunofluorescence ANA Test]], [[Line Immunoassay ANA]], [[Infection-Triggered Autoimmunity]]

---

## [2026-04-12] The prior "dengue causes broad autoimmune disease" claim is largely an artifact of misclassification

**Source:** [[Shih2023 - Autoimmune Disease Risk After Dengue]]

**Finding:** A 2018 population-based study (Li et al.) reported dengue patients had 1.88× the risk of more than 20 autoimmune diseases. Shih2023, using a 5× larger cohort of *laboratory-confirmed* dengue cases (63,814 vs. 12,506), finds no such broad signal after correcting for multiple comparisons. Only autoimmune encephalomyelitis (ADEM) is significantly elevated — and only in the first month. Li et al.'s "dengue" cases were not lab-confirmed; when Shih2023 cross-checked the same era's NHIRD against Taiwan CDC records, only 51.4% of hospitalised "dengue" patients were actually lab-confirmed. The rest likely included febrile illnesses that were initially mistaken for dengue, some of which may have been early presentations of autoimmune diseases (which can mimic dengue acutely: fever, rash, thrombocytopenia).

**Why notable:** This is a direct, large-scale refutation of a published finding using the same national database, with a methodologically stronger study design. It has two compounding implications for this wiki. First, it closes the gap between Garcia2009's finding of elevated autoimmune markers at 2 years post-dengue and the absence of clinically manifest autoimmune disease: the markers appear to be largely sub-clinical and transient, not progressing to disease. Second, it extends beyond dengue: it documents that a 51.4% diagnostic accuracy rate in a hospitalized cohort can produce a spuriously elevated autoimmune risk estimate of aHR 1.88. Any cohort study using clinically diagnosed dengue (without lab confirmation) in an outbreak setting should be viewed with similar suspicion — this is a general methodological lesson for post-infectious autoimmunity research.

**Follow-up questions:**
- Does the same misclassification problem affect other published associations between dengue and specific outcomes (e.g., cancer, cardiovascular disease, psychiatric conditions) that relied on clinical dengue diagnoses?
- Does the Garcia2009 ANA/IC/CRP elevation at 2 years represent genuine but subclinical autoimmune activation — and if so, what determines whether it stays subclinical vs. progresses to disease?
- Can the modest but statistically significant overall autoimmune risk (aHR 1.16) in Shih2023 be attributed to ADEM carrying the overall estimate, or is there a genuine diffuse sub-threshold risk?

**Related pages:** [[Autoimmunity in Dengue]], [[Infection-Triggered Autoimmunity]], [[Dengue Neurological Complications]], [[NS1 Antigen Detection]], [[Taiwan]]

---

## [2026-04-12] WGNGCG motif tracks haemorrhagic phenotype across flaviviruses

**Source:** [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]]

**Finding:** The dengue E protein contains a six-amino-acid motif WGNGCG (aa 101–106) with sequence homology to coagulation factors XI, X, IX, VII, II (thrombin), plasminogen, and tPA. Anti-E Abs raised against this motif inhibit plasmin activity. The motif is conserved in all flaviviruses associated with haemorrhagic disease — JEV, WNV, YFV, TBE, OHFV — but is absent in HCV, which does not typically cause haemorrhage.

**Why notable:** This is not just a dengue finding — it is a proposed molecular explanation for why haemorrhage is a flavivirus-class phenotype rather than a dengue-specific one. The presence/absence of a single six-residue motif tracks with haemorrhagic vs. non-haemorrhagic outcome across an entire viral genus. If validated, it would suggest the coagulation-interference mechanism is ancestral to the haemorrhagic flaviviruses rather than independently evolved in dengue. It also raises the question of whether vaccines or therapeutics targeting this motif could be broadly active across haemorrhagic flaviviruses.

**Follow-up questions:**
- Has the WGNGCG homology been experimentally validated with JEV/WNV/YFV anti-E antibodies — do they also inhibit plasmin?
- Are there any flaviviruses that carry the motif but do not cause haemorrhage (which would falsify the hypothesis)?
- Does primary vs. secondary dengue infection produce different titres of anti-E Abs targeting this motif?

**Related pages:** [[NS1 Molecular Mimicry in Dengue]], [[NS1 Protein]], [[Antibody-Dependent Enhancement]]

---

## [2026-04-12] FcγRIIa genotype controls the symptomatic/asymptomatic threshold, not DF vs. DHF severity

**Source:** [[Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism]]

**Finding:** The FcγRIIa-HH genotype is dramatically enriched in DHF (51.5%) vs. asymptomatic infection (9.1%), giving an OR of 10.56 (95% CI 2.33–54.64) for DHF vs. asymptomatic. However, when only the two symptomatic groups are compared (DF vs. DHF), the allele frequency difference is not significant (χ² = 0.59, p = 0.44). The FcγRIIa effect is almost entirely about whether you develop symptoms at all, not about how severe those symptoms become.

**Why notable:** The conventional framing is that FcγRIIa drives *severity* — the ADE model predicts worse viral uptake in HH individuals leading to worse disease. But this data says the genotype acts as a binary gate (symptomatic or not), not a severity dial. If HH predisposes to symptomatic infection via impaired immune complex clearance, then something else controls progression from DF to DHF — viral load, serotype, prior immunity, or another host factor not captured here. The finding decouples acute pathology (DHF) from post-acute sequelae differently than expected: Garcia2009 from the same cohort also shows DF vs. DHF does not predict post-dengue sequelae (p = 0.086), reinforcing the idea that severity gradations above the symptom threshold may be governed by mechanisms separate from FcγRIIa.

**Follow-up questions:**
- What does control the DF→DHF transition if FcγRIIa genotype does not?
- Does the same symptomatic/asymptomatic gating effect of FcγRIIa hold in other dengue epidemics and serotypes?
- Is there a second genetic locus that specifically modifies DF→DHF severity, independent of FcγRIIa?

**Related pages:** [[FcγRIIa Receptor]], [[Asymptomatic Dengue Infection]], [[Antibody-Dependent Enhancement]]

---

## [2026-04-12] Potentially ADE-capable plasmablast clonotype is fully absent at convalescence

**Source:** [[Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue]]

**Finding:** A public BCR clonotype network — 79 plasmablasts from 8 symptomatic donors, 83.5% using IGHV4-39*01/IGKV1-9*01 — is enriched exclusively in symptomatic (not asymptomatic) dengue. In the longitudinal paired samples (febrile phase → 2-month convalescence), no matched BCR clones from the febrile phase plasmablasts were found at convalescence. The clonotype is completely absent at recovery.

**Why notable:** The ADE model predicts that cross-reactive IgG1 antibodies from a prior infection mediate enhanced viral uptake during a subsequent infection. If the public clonotype identified here produces such antibodies, and if those clones leave no persistent memory, then ADE from this specific clonal lineage cannot be the mechanism of secondary-infection severity — the cells producing these antibodies don't survive to the next encounter. This does not rule out ADE (other clones producing cross-reactive IgG1 may persist), but it challenges the assumption that the most abundant and clonally expanded plasmablast population during symptomatic dengue is the source of ADE-mediating memory antibodies. It may instead represent a dead-end acute response.

**Follow-up questions:**
- Does the total IGHG1+ plasmablast pool (not just this clonotype) leave any long-lived memory cells after acute dengue?
- What antigen does the IGHV4-39*01/IGKV1-9*01 clonotype target — if it is self-antigen, the transience makes immunological sense (tolerance re-establishment); if it is dengue antigen, the absence from memory is puzzling?
- Are the plasmablasts present at 2-month convalescence a distinct lineage from the acute clonotype, or simply a lower-level contraction of the same population?

**Related pages:** [[Antibody-Dependent Enhancement]], [[Asymptomatic Dengue Infection]], [[V(D)J Sequencing]]

---

## [2026-04-12] Anti-prothrombin in 69.6% of acute viral infections — coagulation interference is not dengue-specific

**Sources:** [[Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections]], [[Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis]]

**Finding:** Berlin2007 found anti-prothrombin antibodies in 69.6% of patients with acute viral infections (HAV, HBV, HCV). Lin2011 independently identified that the dengue E protein contains a WGNGCG motif (aa 101–106) with direct sequence homology to prothrombin (factor II) and other coagulation factors, and showed that anti-E antibodies inhibit plasmin activity. These two findings arrive at the same target — coagulation factor cross-reactivity — from entirely different methodologies and study populations, with no dengue patients in Berlin2007.

**Why notable:** This convergence suggests coagulation factor cross-reactivity during acute viral infection may be a general feature of hepatotropic and haemorrhagic virus immunopathology, not a dengue-specific quirk. Lin2011 attributes it to molecular mimicry of the WGNGCG motif; Berlin2007 likely reflects bystander activation or independent mimicry (prothrombin is a common autoantibody target in antiphospholipid syndrome triggered by many infections). Together they predict that dengue patients will have measurable anti-prothrombin antibodies during acute infection — a testable hypothesis not yet directly examined in this wiki's dengue-specific sources. If confirmed, it would add an independent second mechanism (anti-prothrombin from generic viral infection) to the dengue-specific WGNGCG coagulation interference already described.

**Follow-up questions:**
- Have anti-prothrombin levels been measured directly in DHF/DSS patients — and do they correlate with haemorrhage severity independently of anti-NS1?
- Are anti-prothrombin antibodies in viral infection the result of molecular mimicry (shared epitopes) or bystander activation (non-specific)?
- Does the Berlin2007 anti-prothrombin finding apply to dengue specifically, or is dengue unusual in having an additional E-protein molecular mimicry layer on top?

**Related pages:** [[NS1 Molecular Mimicry in Dengue]], [[Infection-Triggered Autoimmunity]], [[Autoimmunity in Dengue]]

---

## [2026-04-12] APTT is the strongest laboratory correlate of vascular permeability — connecting coagulopathy and plasma leakage

**Source:** [[Guzman2016 - Dengue Infection]]

**Finding:** Among all laboratory parameters measured in dengue patients, prolongation of APTT (activated partial thromboplastin time) shows the strongest statistical correlation with the degree of vascular permeability (plasma leakage). This is an epidemiological/clinical association, not a mechanistic proof — but APTT prolongation reflects coagulation pathway disruption, while plasma leakage is an endothelial barrier phenomenon. That the best predictor of one should be a marker of the other suggests they share a common upstream effector.

**Why notable:** The three leading mechanisms for vascular permeability in dengue are (1) NS1-TLR4 cytokine storm, (2) anti-NS1 autoantibody endothelial damage, and (3) direct sNS1 endothelial barrier disruption. None of these inherently predicts that APTT should be the strongest correlate. However, Guzman2016 also documents that sNS1 binds thrombin in vivo and inhibits prothrombin activation — directly prolonging APTT. If sNS1 is both the driver of APTT prolongation AND the driver of endothelial permeability, the APTT-permeability correlation becomes mechanistically coherent: they are two parallel outputs of the same sNS1 effector. This reframes APTT from a coagulopathy marker to a surrogate biomarker of pathogenic sNS1 activity — potentially more informative than platelet count, which Guzman2016 specifically notes is NOT a reliable predictor of bleeding severity.

**Follow-up questions:**
- Has APTT been tested as an early prognostic biomarker for DHF risk in prospective dengue cohorts — and does it outperform NS1 titre or platelet count in predicting plasma leakage?
- Is the APTT-permeability correlation equally strong in primary and secondary infection, or only in the secondary setting where sNS1 levels are higher?
- Does NS1-thrombin complex concentration in patient plasma correlate with both APTT prolongation and with clinical plasma leakage severity?

**Related pages:** [[NS1 Protein]], [[Dengue Pathophysiology]], [[NS1 Molecular Mimicry in Dengue]], [[Viraemia]]

---

## [2026-04-12] Severe viral illness (ICU-level COVID-19) does not elevate ANA — ruling out bystander activation for Garcia2009

**Source:** [[Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity]]

**Finding:** Trahtemberg et al. (cited in Johnson2022) found no significant difference in ANA prevalence between COVID-19-positive ICU patients and COVID-19-negative ICU patients. Severe viral infection with a massive cytokine storm — the classic setting for bystander polyclonal B cell activation — does not reliably elevate ANA above a matched severity baseline.

**Why notable:** The 23.1% ANA positivity in Garcia2009's post-dengue cohort needs a mechanistic explanation. Three candidates exist: molecular mimicry, bystander activation, or epitope spreading. This finding eliminates bystander activation as a sufficient explanation — if it were enough, severe COVID-19 ICU patients would show elevated ANA relative to other ICU patients, and they don't. This sharply narrows the mechanism: dengue-associated ANA must involve either dengue-specific molecular mimicry (NS1 → self-antigen cross-reactivity, well-documented for platelet/endothelial surface proteins in Lin2006/Lin2011, though ANA targets nuclear antigens) or epitope spreading from dengue-induced tissue damage releasing cryptic nuclear antigens. The negative COVID result makes the Garcia2009 ANA finding specifically interesting rather than a generic feature of severe illness.

**Follow-up questions:**
- Is dengue's ANA-inducing potential greater than COVID-19's because dengue has higher cross-reactive mimicry (NS1 homology with nuclear targets) — or because dengue-specific FcγRIIa-mediated IC persistence creates a unique chronic antigen stimulation loop?
- Does dengue NS1 share structural homology with nuclear antigens (Sm, SSA, dsDNA) in addition to the platelet/endothelial surface targets already established by Lin2006/Lin2011?
- Would ANA levels in dengue patients correlate with FcγRIIa genotype (HH > RR), as predicted by the impaired IC clearance model?

**Related pages:** [[Autoimmunity in Dengue]], [[Infection-Triggered Autoimmunity]], [[Antinuclear Antibodies]], [[FcγRIIa Receptor]]

---

## [2026-04-12] Intrinsic ADE may mechanistically link viral enhancement to autoantibody production

**Source:** [[Wan2012 - Autoimmunity in Dengue Pathogenesis]]

**Finding:** The "intrinsic ADE" hypothesis proposes that FcγR-mediated DENV entry does not merely increase viral load — it actively suppresses type I IFN antiviral responses while promoting IL-10 production and Th2 skewing. This creates a dual state: high viral replication AND enhanced antibody (including autoantibody) production.

**Why notable:** This connects two mechanisms previously treated as parallel — ADE and autoimmunity — into a potential causal chain. If intrinsic ADE drives Th2/antibody-dominant responses while suppressing Th1/IFN-mediated viral clearance, then ADE doesn't just increase viral load; it actively tilts the immune response toward the antibody-producing phenotype that generates cross-reactive autoantibodies via NS1 molecular mimicry. This would explain why severe dengue (DHF/DSS, where ADE is most active) shows the highest anti-platelet and anti-endothelial autoantibody levels (Lin2006). It also raises the question of whether the IL-10-driven IGHG1+ plasmablast expansion documented in DHF by Sungnak2025 is partly a consequence of intrinsic ADE.

**Related pages:** [[Antibody-Dependent Enhancement]], [[NS1 Molecular Mimicry in Dengue]], [[Autoimmunity in Dengue]], [[Type I Interferon Response in Dengue]]

---

## [2026-04-17] Dengue→SLE+lupus nephritis carries a persistent antiphospholipid signal not previously documented in primary dengue

**Source:** [[Rajadhyaksha2012 - Dengue Evolving into SLE and Lupus Nephritis]]

**Finding:** In a 22-year-old woman with no prior autoimmune history, primary DENV-1 infection (IgM+/IgG-, RT-PCR confirmed) was followed 4 weeks later by ANA 1:320, anti-dsDNA 1:80, severe hypocomplementemia (C3 22 mg/dL), and biopsy-confirmed Class IV diffuse proliferative glomerulonephritis. Anti-cardiolipin antibodies were elevated in both IgM (44 MPLU/mL) and IgG (12 GPLU/mL) subclasses and remained elevated at 4-month follow-up (IgM 46, IgG 18).

**Why notable:** The wiki already contains dengue-SLE case reports ([[Velazqueza2017 - SLE vs Dengue Case Series]]; Talib 2013 cited via [[Palacios2016 - Autoimmunity in Dengue Literature Review]]). What Rajadhyaksha2012 adds that none of the others provide: (1) **biopsy-confirmed Class IV lupus nephritis** — the most objective histological confirmation of dengue-associated lupus in the wiki as a primary source; (2) **combined IgM + IgG anti-cardiolipin elevation persisting to 4 months** — a durable antiphospholipid response. Prior dengue-antiphospholipid signals in this wiki ([[Morel2014 - Autoimmune Response in Children With Dengue]] Case 1) were transient IgM-only. Persistent combined isotype aCL raises the question of whether dengue can initiate lasting antiphospholipid syndrome in susceptible individuals — a thrombotic risk not tracked in any wiki source. The anti-cardiolipin persistence is also inconsistent with a purely dengue-induced transient response and supports SLE-driven antiphospholipid antibody production. (3) The **primary infection context** (IgM+/IgG-, DENV-1) aligns with [[Vo2020 - Autoantibody Profiling in Dengue]]'s finding that primary DENV-1 infection generates broader IgG autoantibody repertoires than secondary — potentially relevant to why severe autoimmune manifestations can arise after first infection in genetically susceptible individuals.

**Caveat:** n=1 case report; no pre-dengue autoantibody baseline (causal direction unresolved); not generalizable.

**Follow-up questions:**
- Does dengue specifically induce persistent combined IgM+IgG antiphospholipid antibodies in patients who go on to develop SLE — or are the aCL antibodies already present at dengue onset (as pre-existing subclinical APS)?
- What immune deposits (viral antigen ICs vs. anti-nuclear ICs) were present in the renal biopsy immunofluorescence? The biopsy findings beyond grade classification are not reported.
- Given the primary DENV-1 primary infection context and Vo2020's primary>secondary IgG autoantibody inversion, is first dengue infection a higher autoimmunity-triggering event than reinfection in susceptible hosts?

**Related pages:** [[Autoimmunity in Dengue]], [[Infection-Triggered Autoimmunity]], [[Dengue Pathophysiology]], [[DENV-1]], [[India]]

---

## [2026-04-17] Primary DENV infection generates more IgG autoantibodies than secondary infection

**Source:** [[Vo2020 - Autoantibody Profiling in Dengue]]

**Finding:** In a Cambodian pediatric cohort screened with a 123-antigen protein array, primary DENV infection was associated with significantly higher IgG autoantibody levels than secondary infection (p < 0.01; 70 IgG autoantibodies individually elevated in primary vs. secondary). IgM autoantibody load did not differ significantly. The total IgG autoantibody NFI in primary patients exceeded even the secondary-infection level despite lower disease severity (no primary-infection DHF was observed in this cohort).

**Why notable:** The standard immunopathological expectation is that secondary infection — the context of ADE, higher viral loads, and greater disease burden — would also show more immunological dysregulation. That primary infection shows *more* IgG autoantibody breadth inverts this. The Vo2020 interpretation (B cell tolerance checkpoint leakiness preferentially in primary infection) is consistent with work showing that DENV directly infects B cells and can disrupt checkpoint deletion of autoreactive clones. This also implies that the dengue autoimmunity risk may be partially concentrated in *first* infection rather than reinfection — a reversal of conventional severity-centric thinking. However, the finding is limited by a very small primary group (n=6, all male, all DENV-1) and requires replication. Notably, this inversion applies to breadth (number/range of IgG autoantibodies), not necessarily to the specific pathogenic anti-endothelial and anti-platelet autoantibodies tracked by Lin2006/Wan2012, which do correlate positively with DHF severity.

**Follow-up questions:**
- Does the primary-infection IgG autoantibody excess persist longitudinally (kinetics past the sampling point), or does tolerance re-establishment rapidly deplete it?
- Is the inversion (primary > secondary for IgG autoantibodies) serotype-specific (all 6 primary patients were DENV-1), or a general feature of first DENV exposure?
- Do the specific pathogenic anti-platelet/anti-endothelial autoantibodies (Lin2001/Lin2006 targets) also show this inversion, or is the breadth signal driven by non-pathogenic bystander-activated clones?

**Related pages:** [[Autoimmunity in Dengue]], [[Secondary Dengue Infection]], [[Antibody-Dependent Enhancement]], [[Cambodia]]

---
