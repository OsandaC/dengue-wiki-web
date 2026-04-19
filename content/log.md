# Wiki Operation Log

---

## [2026-04-19] maintenance | Resolve all curator highlights — ANA V2.0 + Antinuclear Antibodies

**Scope:** All `<mark>` annotations in both marked pages resolved and stripped.

**[[ANA and Dengue - Review V2.0]]** (29 marks removed):
- 🟢 Green (20): verified claims, marks stripped, text unchanged
- 🟠 Orange (6): three required text changes — (1) Chatterjee2024 dilution limitation rewritten as formal analytical prose; (2) IgM half-life bullet expanded with IgG contrast (~8 hr vs ~21 days); (3) four already-addressed caveats had marks stripped without text change
- 🔵 Blue (1): wikilink added → `[[Polyreactive Antibodies|germline-encoded polyreactive IgM]]`
- 🩷 Pink (4): important ideas confirmed well-stated in text; marks stripped

**[[Antinuclear Antibodies]]** (15 marks removed): all green marks stripped; text unchanged.

**Curator Highlights** regenerated as a resolution log documenting all actions taken.

---

## [2026-04-19] correction | ANA and Dengue V2.0 — §3.2 Vo2020 cohort + PABs + Curator Highlights reformat

**Issues corrected in `wiki/analyses/ANA and Dengue - Review V2.0.md`:**

1. **Vo2020 cohort size** — corrected from `n=40 dengue` to `n=32 DENV-infected` (21 hospitalized: 13 DF, 8 DHF; 11 asymptomatic); 8 HD; total enrolled = 40. Confirmed from raw PDF §2.1.
2. **Array size discrepancy** — resolved: 128 = total antigens on physical array (Abstract/Discussion); 123 = antigens analysed after quality filtering (Results/Figure 4). Both figures confirmed in source. Red mark and comment removed.
3. **PABs terminological framing** — red marks removed from PAB characteristic bullets; bullets re-sourced with explicit Zhou2007 citation. Added terminological note quoting Zhou2007 directly: PABs are a "normal self-reactive component of the immune system," not pathological autoantibodies. Non-specific IIFA fraction reframed as "amplified natural polyreactive IgM."
4. **Vo2020 hospitalized IgG statement integrated into §3.4** — Vo2020's conclusion ("presence of a subset of IgG autoantibodies in individuals infected with DENV that required hospitalization") now explicitly cited in the Nuclear Antigen Consumption section, with clarification that IgG autoantibodies being *present* in hospitalized patients vs. *consumed* in DHF are complementary, not contradictory, findings.

**Curator Highlights regenerated** — full rewrite with:
- Hex codes added for all five colour categories (Orange `#FFB86CA6`, Blue `#ADCCFFA6`, Pink `#FFB8EBA6`)
- New section added for [[ANA and Dengue - Review V2.0]] (23 new highlights across Green/Orange/Blue/Pink)
- Resolved red items documented under Antinuclear Antibodies
- Total active highlights: 46 across 2 pages

---

## [2026-04-19] maintenance | Fix state.md YAML frontmatter; web redeployed

**Fix:** `state.md` `updated:` field had a parenthetical comment breaking Quartz YAML parsing. Trimmed to plain date `2026-04-19`. Web rebuilt and pushed clean (113 files, 0 errors).

---

## [2026-04-19] lint | Deep lint — forward propagation focus; 2 recent ingests (Hung2008, Ghorai2024)

**Scope:** Full wiki scan (111 pages). Batched: sources/ → entities+concepts → methods+geography → analyses. Forward-propagation check for the 2 most recently ingested sources (Hung2008 2026-04-19, Ghorai2024 2026-04-19). All entity/concept/method/geography pages listed in their Entities Mentioned / Concepts Addressed / Methods Used sections verified.

**Issues found and fixed (11):**

1. **DENV-1.md** — missing Ghorai2024 (all 4 serotypes listed as Ghorai2024 entities; DENV-1 had not been updated). Fixed: Ghorai2024 added to Sources; `sources: 11 → 12`.

2. **DENV-3.md** — missing Ghorai2024. Fixed: Ghorai2024 added to Sources; `sources: 13 → 14`.

3. **Aedes aegypti.md** — missing Hung2008 (Hung2008 lists [[Aedes aegypti]] as an entity; page not updated during ingest). Fixed: Hung2008 added to Sources; `sources: 11 → 12`.

4. **RT-PCR.md** — missing Ghorai2024 (Ghorai2024 Methods Used section links [[RT-PCR]]). Fixed: Ghorai2024 added; `sources: 10 → 11`.

5. **ELISA.md** — missing Ghorai2024 (Ghorai2024 Methods Used links [[ELISA]]). Fixed: Ghorai2024 added; `sources: 2 → 3`.

6. **NS1 Antigen Detection.md** — missing Ghorai2024 (Ghorai2024 Methods Used had stale link `[[NS1 Antigen ELISA]]` rather than `[[NS1 Antigen Detection]]`; page also not in Sources). Fixed: stale link corrected in Ghorai2024 source page; Ghorai2024 added to NS1 Antigen Detection; `sources: 12 → 13`.

7. **Ghorai2024 source page** — stale wikilink: `[[NS1 Antigen ELISA]]` → `[[NS1 Antigen Detection]]`.

8. **index.md** — `Concepts (23)` → `Concepts (24)` (24 concept pages exist; header was off-by-one). `Methods (16)` → `Methods (17)` (17 method pages exist; header was off-by-one). Entity/method source counts updated: DENV-1 11→12, DENV-3 13→14, Aedes aegypti 11→12, RT-PCR 10→11, NS1 Antigen Detection 12→13, ELISA 2→3.

9. **Paraguay.md** — standalone file existed despite ≥2-source rule (only 1 source: Morel2014) and index saying "no standalone page". Folded into Latin America.md §Paraguay. Paraguay.md deleted. All `[[Paraguay]]` wikilinks updated to `[[Latin America]]` in Autoimmunity in Dengue.md and Macrophage Activation Syndrome in Dengue.md. Latin America.md: §Paraguay section added; sources 7→8; tags updated; Related Pages: `[[Macrophage Activation Syndrome in Dengue]]` added. index.md: Latin America sources 7→8, Paraguay entry updated, Geography (11)→(10), total pages 112→111.

10. **ANA and Dengue - Review V2.0** — missing Ghorai2024 (sources 40, should be 41). Fixed: Ghorai2024 added to Sources Used with tangential-contribution note; `sources: 40 → 41`; intro text updated to "all 41 source papers"; index entry updated to "All 41 wiki sources".

11. **Curator Highlights** — 0 active highlights in wiki content pages (confirmed by grep). No refresh needed.

**General health:** No orphan pages beyond the known Reading Plan (index-only link, acceptable meta document). No other stale wikilinks detected. No missing concept/entity pages surfaced.

---

## [2026-04-19] update | ANA and Dengue - Review V2.0 — Hung2008 + Santosa2012 + Farias2024 integration

**Sources added (3):** Hung2008, Santosa2012, Farias2024; sources count 37→40.

**Content added:**
- §4.1 infection-order independence: extended to four independent sources (Lin2001, Cheng2015, Saito2004, Hung2008); new paragraphs on anti-EC isotype shift (IgM→IgM+IgG in secondary infection, Hung2008) and TM elevation as constitutive endothelial damage marker; Wan2012–Hung2008 anti-EC severity discrepancy flagged with methodological explanation
- §5.1 (Primary Infection thrombocytopenia): Vietnamese endemic-setting replication paragraph (Hung2008 infants + children; anti-platelet IgM level vs. complement-mediated lysis distinction)
- New §7.4 (Bidirectional Diagnostic Confusion): SLE→dengue false-positive serology (Santosa2012: RF-positive SLE; ANA-positive SLE patients at no increased false-positive risk); dengue→autoimmune misclassification (Farias2024: 2024 Brazil epidemic; dengue satisfying ≥4 SLE criteria); practical NS1 antigen anchor for resolution
- Epistemic Framework established claim: "Three independent sources" → "Four independent sources" with Hung2008 added

---

## [2026-04-19] verify | Antinuclear Antibodies — 2 red highlights resolved; Curator Highlights populated

**Highlights investigated against raw PDFs:**

1. **Red → resolved:** `~86% of individuals who test ANA-positive at 1:80 in the general population do not have SLE` — Not found in Aringer2019; the paper reports ANA sensitivity (97.8%) but not this derived population-level specificity figure. Replaced with an accurate population-prevalence-grounded statement citing Satoh2012/Dinse2022 (~14% population ANA positive at 1:80 vs. ~0.1% SLE prevalence). Now green.

2. **Red → resolved:** `HAV patients were positive for all 8 tested ANA specificities` — Berlin2007 **Results** section states "Three patients with HAV and one with HBV were positive for all eight antigens" (not all 10 HAV patients). Berlin2007's own Discussion section overstates this as "all patients with HAV." The wiki had followed the erroneous Discussion language. Corrected to "three of ten HAV patients." Now green. Internal paper discrepancy documented.

**Pages updated (3):**
- `wiki/concepts/Antinuclear Antibodies.md` — both red highlights corrected to green
- `wiki/sources/Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections.md` — HAV claim corrected (3/10, not all 10); ⚠ internal discrepancy note added
- `wiki/analyses/Curator Highlights.md` — full overwrite: colour code legend added; all 13 current highlights listed with verification status and source confirmations; resolved red highlights documented with findings and resolutions

---

## [2026-04-19] ingest | Hung2008 - Anti-Platelet Anti-Endothelial Autoantibodies Vietnam

**New pages created (4):**
- `wiki/sources/Hung2008 - Anti-Platelet Anti-Endothelial Autoantibodies Vietnam.md`
- `wiki/geography/Vietnam.md` (2 sources: Hung2008 + Cheng2015)
- `wiki/geography/Southeast Asia.md` (regional page; Cambodia § folded in)
- `wiki/methods/Flow Cytometry.md` (3 sources: Lin2001, Hung2008, Sungnak2025)

**Pages deleted (1):**
- `wiki/geography/Cambodia.md` — folded into Southeast Asia.md

**Pages updated (19):**
- `wiki/concepts/Autoimmunity in Dengue.md` (sources 33→34)
- `wiki/concepts/NS1 Molecular Mimicry in Dengue.md` (sources 12→13; new anti-EC isotype shift subsection)
- `wiki/concepts/Dengue Pathophysiology.md` (sources 14→15; new thrombomodulin biomarker section)
- `wiki/concepts/Secondary Dengue Infection.md` (sources 14→15)
- `wiki/concepts/Cross-Reactive Antibodies.md` (sources 13→14)
- `wiki/concepts/Infection-Triggered Autoimmunity.md` (sources 14→15)
- `wiki/entities/NS1 Protein.md` (sources 16→17)
- `wiki/entities/DENV-2.md` (sources 11→12)
- `wiki/entities/DENV-3.md` (sources 12→13)
- `wiki/entities/DENV-4.md` (sources 10→11)
- `wiki/methods/IgM-IgG Serology ELISA.md` (sources 17→18)
- `wiki/methods/NS1 Antigen Detection.md` (sources 11→12)
- `wiki/methods/ELISA.md` (sources 1→2)
- `wiki/methods/RT-PCR.md` (sources 9→10)
- `wiki/geography/Thailand.md` ([[Southeast Asia]] added to Related Pages)
- `wiki/geography/Singapore.md` ([[Southeast Asia]] added to Related Pages)
- `wiki/geography/Philippines.md` ([[Southeast Asia]] added to Related Pages)
- `wiki/analyses/Notable Findings.md` (anti-EC isotype shift notable finding added; Cambodia→Southeast Asia wikilink fixed; sources 20→21)
- `wiki/index.md` (sources 39→40; pages 107→109; new/updated page entries)

**Geography cascade triggered:** Vietnam reached 2 sources → Vietnam.md created. Vietnam + Singapore + Philippines = 3 SEA country pages → Southeast Asia.md created. Cambodia (1 source, thin) folded into Southeast Asia.md §Cambodia; Cambodia.md deleted; all [[Cambodia]] wikilinks updated.

**Key findings:** Anti-EC autoantibody isotype shifts from IgM-only (infants, primary infection) to IgM+IgG (children, predominantly secondary infection), but levels do not correlate with severity in either group. Thrombomodulin elevated in both groups as in vivo endothelial structural damage marker, independent of autoantibody levels. Citations: SS=3, CR=1.

## [2026-04-19] ingest | Ghorai2024 - Autoantibodies in Dengue Pathogenesis Review

**New pages created (3):**
- `wiki/sources/Ghorai2024 - Autoantibodies in Dengue Pathogenesis Review.md`
- `wiki/concepts/Coagulation and Fibrinolysis in Dengue.md` (4 sources: Lin2011, Guzman2016, Wan2012, Ghorai2024)
- `wiki/concepts/Pemphigus and Acantholysis in Dengue.md` (1 source: Ghorai2024)

**Pages updated (13):**
- `wiki/concepts/Autoimmunity in Dengue.md` (sources 34→35; anti-DSG/pemphigus section added)
- `wiki/concepts/NS1 Molecular Mimicry in Dengue.md` (sources 13→14; hepatic murine model Lin2008 detail added)
- `wiki/concepts/Dengue Pathophysiology.md` (sources 15→16; profibrinolysis/hyperfibrinolysis section added)
- `wiki/concepts/Infection-Triggered Autoimmunity.md` (sources 15→16)
- `wiki/concepts/Cross-Reactive Antibodies.md` (sources 14→15)
- `wiki/concepts/Cytokine Storm.md` (sources 12→13)
- `wiki/entities/NS1 Protein.md` (sources 17→18)
- `wiki/entities/E Protein.md` (sources 5→6)
- `wiki/entities/prM Protein.md` (sources 3→4)
- `wiki/entities/DENV-2.md` (sources 12→13)
- `wiki/entities/DENV-4.md` (sources 11→12)
- `wiki/geography/India.md` (sources 5→6; 6th Indian research setting: DAC Regional Research Institute + Peerless Hospital + CCRH New Delhi, Kolkata)
- `wiki/analyses/Notable Findings.md` (anti-DSG/pemphigus notable finding added)
- `wiki/index.md` (sources 40→41; pages 109→112)

**Key findings:** Three genuinely new contributions from a secondary review: (1) profibrinolysis/hyperfibrinolysis dual mechanism — anti-plasminogen auto-Abs acting on fibrinogen and fibrinogen complexes respectively (Chuang 2013/2014, via Ghorai2024); (2) anti-DSG pemphigus vulgaris/foliaceus — a completely new auto-antibody target class (desmosomal proteins) not previously in this wiki; (3) hepatic inflammation murine model detail from Lin 2008 — anti-NS1 targeting central and portal hepatic vein endothelium → fatty liver + fibrosis + mononuclear infiltration. Citations: SS=7, CR=8.

---

## [2026-04-18] lint | Deep lint — forward-propagation focus; 6 recent sources × all linked targets

**Scope:** Forward-propagation check for the 6 most recently ingested sources: Santosa2012, Farias2024, Cheng2015, Chaturvedi2001, Jardim2012, Codes2002. For each source, every page listed under "Entities Mentioned," "Concepts Addressed," "Methods Used," and geography was visited and confirmed for source inclusion.

**Pages scanned:** 39 source pages (all); 12 entity pages; 21 concept pages; 15 method pages; 10 geography pages; 6 analysis pages. Total: 103 pages.

**Gaps found and fixed (2):**

1. `wiki/concepts/Infection-Triggered Autoimmunity.md` — **missing Santosa2012** in Sources section. Santosa2012 lists [[Infection-Triggered Autoimmunity]] under Concepts Addressed; the concept page had not been updated during ingest. Fixed: Santosa2012 added to Sources; `sources: 13 → 14`.

2. `wiki/methods/IgM-IgG Serology ELISA.md` — **missing Chaturvedi2001** in Sources section. Chaturvedi2001 used IgM-capture ELISA for patient enrollment; the method page had not been updated. Fixed: Chaturvedi2001 added to Sources; `sources: 16 → 17`.

**General health:** No orphan pages, no stale wikilinks, no new thin pages discovered. Curator Highlights: 0 active highlights. All analyses pages current.

## [2026-04-18] ingest | Farias2024 - Dengue Mimickers

**Source:** Farias LABG, Lima GCS, Velasque L, et al. *Dengue Mimickers: Which Clinical Conditions Can Resemble Dengue Fever?* Rev Soc Bras Med Trop. 2024;57:e00206-2024. doi:10.1590/0037-8682-0334-2024
**Citations:** SS 13 / CR 11
**Type:** Narrative review (7 Brazilian clinical experts; secondary source — no original patient data)

**Created:**
- `wiki/sources/Farias2024 - Dengue Mimickers.md`

**Updated (18 pages):**
- `wiki/concepts/Autoimmunity in Dengue.md` — sources 32→33; new §SLE-Dengue Bidirectional Clinical Confusion
- `wiki/concepts/Dengue Pathophysiology.md` — sources 13→14; new §Acute Abdomen and GI Manifestations
- `wiki/concepts/Dengue Neurological Complications.md` — sources 4→5; new §Prevalence and Clinical Spectrum (Farias2024)
- `wiki/concepts/Cross-Reactive Antibodies.md` — sources 12→13; new §Arbovirus cross-reactivity in differential diagnosis
- `wiki/concepts/Infection-Triggered Autoimmunity.md` — sources 12→13; Farias2024 added to Sources
- `wiki/concepts/Dengue Clinical Classification.md` — sources 7→8; Farias2024 added to Sources
- `wiki/concepts/Cytokine Storm.md` — sources 11→12; Farias2024 added to Sources
- `wiki/entities/Aedes aegypti.md` — sources 10→11; new §Multi-arbovirus vector role and co-transmission (Farias2024)
- `wiki/entities/Aedes albopictus.md` — sources 4→5; CHIKV super-vector bullet added
- `wiki/entities/NS1 Protein.md` — sources 15→16; Farias2024 added to Sources
- `wiki/entities/DENV-1.md` — sources 10→11; Farias2024 added to Sources
- `wiki/entities/DENV-2.md` — sources 10→11; Farias2024 added to Sources
- `wiki/entities/DENV-3.md` — sources 11→12; Farias2024 added to Sources
- `wiki/entities/DENV-4.md` — sources 9→10; Farias2024 added to Sources
- `wiki/methods/NS1 Antigen Detection.md` — sources 10→11; clinical SLE-dengue differential context added
- `wiki/methods/IgM-IgG Serology ELISA.md` — sources 15→16; CHIKV/Zika/SLE/RA/malaria/leptospirosis cross-reactivity for differential diagnosis added
- `wiki/methods/RT-PCR.md` — sources 8→9; SLE-dengue differential recommendation added
- `wiki/geography/Latin America.md` — sources 6→7; Brazil § updated with 2024 epidemic data and Farias2024 as 3rd Brazilian source
- `wiki/index.md` — Sources 38→39; Total pages 106→107; all entity/concept/method/geography counts updated

**Notable Findings:** No entry — Farias2024 is a secondary narrative review synthesising established literature. No finding meets the bar of surprising given existing wiki content.

---

## [2026-04-18] ingest | Santosa2012 - Delayed SLE Diagnosis Dengue Serology

**Source:** Santosa A, Poh Z, Teng GG. *Scandinavian Journal of Rheumatology*. 2012;41(1):77–79. doi:10.3109/03009742.2011.633552
**Citations:** SS 16 / CR 11
**Type:** Letter (case report + targeted review — secondary source)

**Created:**
- `wiki/sources/Santosa2012 - Delayed SLE Diagnosis Dengue Serology.md`

**Updated (7 pages):**
- `wiki/geography/Singapore.md` — sources 2→3; new §SLE-Dengue Diagnostic Confusion
- `wiki/concepts/Autoimmunity in Dengue.md` — sources 31→32; new §False-Positive Dengue Serology in Pre-Existing SLE
- `wiki/methods/IgM-IgG Serology ELISA.md` — sources 14→15; new §False-Positive Dengue IgM in Patients with Autoantibodies
- `wiki/methods/NS1 Antigen Detection.md` — sources 9→10; Santosa2012 added to Sources
- `wiki/methods/RT-PCR.md` — sources 7→8; Santosa2012 added to Sources
- `wiki/concepts/Antinuclear Antibodies.md` — sources 13→14; Santosa2012 added to Sources
- `wiki/index.md` — Sources 37→38; Singapore 2→3; method and concept counts updated

**Notable Findings:** No entry — the false-positive serology finding is clinically important but does not meet the bar of surprising given wiki content (SLE-dengue overlap was already documented; mechanism is an extension of the existing low-affinity IgM / polyreactive antibody framework).

---

## [2026-04-18] analysis | ANA and Dengue - Review V2.0

**Operation:** New analysis page created from ground up. Supersedes the incrementally revised V1.x series.

**Created:**
- `wiki/analyses/ANA and Dengue - Review V2.0.md`

**Scope vs. V1.x:**
- All 37 wiki sources incorporated (up from 32 in V1.x; Li2018, Dejnirattisai2010, Bhatt2020, Pang2017, Sungnak2025 added/better integrated)
- New §IV.2 on anti-prM as a second molecular mimicry arm (Dejnirattisai2010) — absent from V1.x
- New §V (standalone thrombocytopenia bifurcation model) with FcγRIIa paradox clearly articulated
- New §X (vaccine design implications) — entirely new section
- New §XI (acute-phase timing) — consolidated from V1.x scattered notes
- Li2018 added to sources (was referenced in V1.x text but absent from sources list)
- Open questions renumbered 1–16 (V1.x had Q14 before Q13 and was missing Q13)
- Revision notes removed; clean document

**Index update:** Analyses table updated (5→6 pages).

---

## [2026-04-18] ingest | Cheng2015 - NS1 P311-330 Anti-PDI Autoantibodies in DHF

**Source:** Cheng HJ et al. *Am J Trop Med Hyg*. 2015. doi:10.4269/ajtmh.14-0162
**Citations:** SS 22 / CR 19

**Created:**
- `wiki/sources/Cheng2015 - NS1 P311-330 Anti-PDI Autoantibodies in DHF.md`
- `wiki/methods/ELISA.md` (new method page — no prior standalone ELISA page existed; Cheng2015 is first source)

**Updated (content + frontmatter):**
- `wiki/concepts/NS1 Molecular Mimicry in Dengue.md` (11→12 sources; P311–330 PDI epitope section + primary/secondary independence section added)
- `wiki/entities/NS1 Protein.md` (14→15 sources; P311–330 PDI-specific epitope bullet + HSP60 distinct epitope note added)
- `wiki/geography/Taiwan.md` (4→5 sources; Cheng2015 NCKU/Vietnamese cohort subsection added)
- `wiki/concepts/Autoimmunity in Dengue.md` (30→31 sources; NS1 mimicry P311–330 note added to Sources)
- `wiki/concepts/Cross-Reactive Antibodies.md` (11→12 sources; anti-NS1 section updated with P311–330 PDI epitope specificity)
- `wiki/concepts/Dengue Pathophysiology.md` (12→13 sources; anti-PDI integrin activation disruption bullet added to Vascular Permeability)
- `wiki/entities/DENV-1.md` (9→10 sources)
- `wiki/entities/DENV-2.md` (9→10 sources)
- `wiki/entities/DENV-3.md` (10→11 sources)
- `wiki/entities/DENV-4.md` (8→9 sources)
- `wiki/methods/RT-PCR.md` (6→7 sources)
- `wiki/analyses/Notable Findings.md` (NS1 mimicry infection-order independence notable finding added)
- `wiki/index.md` (Sources 36→37, pages 102→104; all tables updated; Vietnam note added)

**Notable finding flagged:** NS1 mimicry anti-endothelial autoantibodies are infection-order independent — convergent across Cheng2015 + Lin2001 + Saito2004
**Geography note:** Vietnam first appearance (patient sera from Ho Chi Minh City); no standalone Vietnam page per <2 source rule.

---

## [2026-04-18] ingest | Chaturvedi2001 - Cytotoxic Factor Autoantibodies DHF

**Source:** Chaturvedi UC et al. FEMS Immunol Med Microbiol 30 (2001) 181–186. DOI: 10.1016/S0928-8244(00)00251-0
**Citations:** SS null / CR 1

**Created:**
- `wiki/sources/Chaturvedi2001 - Cytotoxic Factor Autoantibodies DHF.md`
- `wiki/concepts/Cytotoxic Factor in Dengue.md` (new concept page — group-specific concept, ⚠ unvalidated)

**Updated (content + frontmatter):**
- `wiki/concepts/Cytokine Storm.md` (10→11 sources; hCF cascade section added)
- `wiki/concepts/T Cell Responses in Dengue.md` (4→5 sources; hCF CD4 producer section added)
- `wiki/concepts/Dengue Pathophysiology.md` (11→12 sources; hCF/anti-hCF section added)
- `wiki/concepts/Dengue Clinical Classification.md` (6→7 sources; Chaturvedi2001 1997 WHO DHF application added)
- `wiki/concepts/Autoimmunity in Dengue.md` (29→30 sources; anti-hCF as protective autoantibody added to Related Pages + Sources)
- `wiki/geography/India.md` (4→5 sources; Lucknow/AIIMS 1996 epidemic section added)
- `wiki/analyses/Notable Findings.md` (anti-hCF protective autoantibody notable finding added)
- `wiki/index.md` (Sources 35→36, pages 100→102; Concepts table updated; India 4→5; Cytotoxic Factor concept added)

**Notable finding flagged:** Anti-hCF autoantibodies — first protective autoantibody in dengue; 96% DF → 8% DHF-IV (⚠ external validation lacking)

---

## [2026-04-18] restructure | Americas regional page created

**Change:** Created `wiki/geography/Latin America.md` consolidating Cuba, Nicaragua, and Brazil country pages. Trigger condition met: 3 standalone Americas country pages (Cuba 3 sources, Nicaragua 1, Brazil 2).
**Scope:** Latin America.md created (6 sources); Cuba.md, Nicaragua.md, Brazil.md deleted; 10 pages updated (DENV-1, DENV-2, DENV-3, DENV-4, Aedes aegypti, FcγRIIa Receptor, Asymptomatic Dengue Infection, Post-Dengue Syndrome, Cross-Reactive Antibodies, Singapore); index.md Geography table revised (10→8 rows, Latin America replaces Cuba/Nicaragua/Brazil); page count 102→100.
**Reason:** CLAUDE.md geography hierarchy rule — next ingest after ≥3 Americas country pages triggers regional page and folds thin country pages in.

---

## [2026-04-18] schema-update | Curator Highlights workflow added

**Change:** Added `Curator Highlights` as a new light-maintenance workflow — scans wiki pages for `==highlights==` and `%%comments%%` and aggregates them into `wiki/analyses/Curator Highlights.md`. Refreshed during lint and on "update highlights" command.
**Scope:** CLAUDE.md §Architecture, §Workflows/Lint (new step 5), §Workflows/Curator Highlights (new section)
**Pages affected:** 3 (CLAUDE.md, wiki/index.md, wiki/analyses/Curator Highlights.md created)
**Reason:** Curator wanted to use Obsidian's native ==highlight== and %%comment%% features for manual annotation during reading, with a single aggregated page to review all annotations across the wiki.

---

## [2026-04-18] ingest | Codes2002 - Autoantibodies in Acute Viral Hepatitis

**Source:** Codes L, Santos de Jesus R, Cunha S, Cruz M, Paraná R. *Rev Soc Bras Med Trop* 35(5): 465–469, 2002.

**Context:** Non-dengue paper — viral hepatitis (HAV/HBV/HCV/HEV/non A-E); included as the primary sourced data for the 20.5% acute / 6.4% convalescent ANA figures previously cited across multiple wiki pages as "a study cited by Berlin2007" without full attribution.

**Created:**
- `sources/Codes2002 - Autoantibodies in Acute Viral Hepatitis.md`
- `geography/Brazil.md` (now 2 sources: Jardim2012 + Codes2002; Americas regional page trigger met — Cuba + Nicaragua + Brazil = 3 pages)

**Updated (citation fix — 4 pages):**
- `sources/Berlin2007`: "prior study (not fully detailed)" → direct [[Codes2002]] link + ASMA detail
- `analyses/ANA and Dengue - A Literature Review`: anonymous citation → [[Codes2002]] with full study descriptor
- `concepts/Infection-Triggered Autoimmunity`: "One study (cited in Berlin2007)" → [[Codes2002]] in two locations
- `concepts/Autoimmunity in Dengue`: anonymous "cited study" → [[Codes2002]]

**Updated (propagation):**
- `concepts/Antinuclear Antibodies`: anonymous citation → [[Codes2002]]; sources 12→13
- `concepts/Infection-Triggered Autoimmunity`: sources 11→12; Codes2002 added to Sources list
- `concepts/Autoimmunity in Dengue`: sources 28→29; Codes2002 added to Sources list
- `methods/Indirect Immunofluorescence ANA Test`: sources 10→11; Codes2002 added to Sources list
- `wiki/index.md`: Sources 34→35, Pages 100→102, Geography 9→10; Brazil entry updated

**Citations:** null / null (2002 regional Brazilian journal paper; not indexed in Semantic Scholar or CrossRef)

**Notable Findings:** None — this ingest resolves an attribution gap, not a new finding.

---

## [2026-04-18] lint | Deep batched health check (post-Jardim2012)

**Method:** Batched by folder (sources → entities/concepts → methods/geography → analyses). Forward propagation check for all 8 ingests since 2026-04-17 lint (Pang2017, Velazqueza2017, Gawali2021, Zhou2007, Bhatt2020, Dejnirattisai2010, Rajadhyaksha2012, Jardim2012). Orphan check, stale link scan, thin-page audit.

**Stale cross-references:** 0. Checked Brazil, Mexico, Herd Immunity — no live wikilinks to non-existent pages.

**Orphans:** Reading Plan - ANA and Dengue Dynamics (only linked from index.md) — unchanged, acceptable meta document.

**Forward propagation gaps found and fixed (6 pages):**
1. `entities/NS1 Protein.md` — Jardim2012 missing; sources 13→14
2. `entities/Aedes aegypti.md` — Jardim2012 missing; sources 9→10
3. `concepts/Dengue Clinical Classification.md` — Jardim2012 missing; sources 5→6
4. `methods/Indirect Immunofluorescence ANA Test.md` — Jardim2012 missing; sources 9→10
5. `entities/E Protein.md` — Pang2017 missing; sources 4→5
6. `concepts/Cross-Reactive Antibodies.md` — Bhatt2020 missing; sources 10→11

**Analysis page gap fixed:**
- `analyses/ANA and Dengue - A Literature Review.md` — Jardim2012 not integrated (missed during ingest); fourth-pass revision added: case table row (mitotic spindle ANA, full resolution, anti-dsDNA negative), discussion point 5 (transient multi-autoantibody pole, selective C3/C4-normal differential); sources 28→29

**Index fixes:**
- Methods section header: `(14)` → `(15)` (actual count was 15, header was wrong)
- NS1 Protein: 13→14; Aedes aegypti: 9→10; E Protein: 4→5
- Dengue Clinical Classification: 5→6; Cross-Reactive Antibodies: 10→11; Indirect Immunofluorescence ANA Test: 9→10

**Minor inconsistency noted (not fixed):** Pang2017 appears in NS1 Antigen Detection Sources as background citation, but Pang2017 source page lists "Methods Used: N/A". Extra connection (benign direction) — not a propagation gap from the source's perspective.

**Thin pages confirmed (all already in Watch Items):** Wolbachia (1), CYD-TDV (2), Polyreactive Antibodies (1), NK Cell Responses in Dengue (1), Viraemia (2); thin methods: ELISA Inhibition Method, Single-Cell RNA Sequencing, V(D)J Sequencing, qRT-PCR, Autoantigen Microarray, Line Immunoassay ANA, Surface Plasmon Resonance; thin geography: Nicaragua (1), Paraguay (1), Cambodia (1).

---

## [2026-04-18] ingest | Jardim2012 - Autoimmune Features DHF Case Report

**Citation:** Jardim DLF, Tsukumo DML, Angerami RN, de Carvalho Filho MA, Saad MJA. "Autoimmune features caused by dengue fever: a case report." *Braz J Infect Dis*. 2012;16(1):92–95. DOI: 10.1590/s1413-86702012000100018. Citations: 6 (SS) / 12 (CR).

**Type:** Case report (n=1). Universidade Estadual de Campinas (UNICAMP), Campinas, São Paulo, Brazil. DENV-3 outbreak May 2007; secondary infection.

**Created:** `wiki/sources/Jardim2012 - Autoimmune Features DHF Case Report.md`

**Updated:**
- `wiki/entities/DENV-3.md` — Brazil 2007 São Paulo DENV-3 outbreak; sources 9→10
- `wiki/concepts/Autoimmunity in Dengue.md` — new subsection on Jardim2012: mitotic spindle ANA, cryoglobulinemia, selective C3 depression, LE cells, full resolution; sources 27→28
- `wiki/concepts/Dengue Pathophysiology.md` — new section on cryoglobulinemia and serositis in DHF; selective C3-normal C4 complement pattern; sources 10→11
- `wiki/concepts/NS1 Molecular Mimicry in Dengue.md` — citation added; sources 10→11
- `wiki/concepts/Infection-Triggered Autoimmunity.md` — Jardim2012 as transient dengue autoimmunity example; sources 10→11
- `wiki/concepts/Antinuclear Antibodies.md` — new subsection on mitotic spindle ANA pattern; sources 11→12
- `wiki/concepts/Secondary Dengue Infection.md` — citation added; sources 13→14
- `wiki/methods/IgM-IgG Serology ELISA.md` — PanBio MAC-ELISA + DuoCassette; sources 13→14
- `wiki/analyses/Notable Findings.md` — new entry: mitotic spindle ANA pattern + cryoglobulinemia
- `wiki/index.md` — sources 33→34, pages 99→100; Brazil geography noted (1 source, no page)

**Geography:** Brazil (Campinas, São Paulo) — first source; no standalone page per ≥2-source rule.

---

## [2026-04-17] ingest | Rajadhyaksha2012 - Dengue Evolving into SLE and Lupus Nephritis

**Citation:** Rajadhyaksha A, Mehra S. "Dengue fever evolving into systemic lupus erythematosus and lupus nephritis: a case report." *Lupus*. 2012;21(9):999–1002. DOI: 10.1177/0961203312437807. Citations: 54 (SS) / 35 (CR).

**Type:** Case report (n=1). KEM Hospital and Seth GS Medical College, Mumbai, Maharashtra, India.

**Key findings:**
- Primary DENV-1 infection (IgM+/IgG-, RT-PCR confirmed genotype 1) in a 22-year-old woman with no prior autoimmune history
- 4 weeks post-dengue: ANA 1:320 homogeneous 4+, anti-dsDNA 1:80 4+, C3 22 mg/dL (severely low), C4 5 mg/dL (low)
- Anti-cardiolipin IgM 44 MPLU/mL and IgG 12 GPLU/mL — persistent at 4 months (IgM 46, IgG 18)
- Renal biopsy: diffuse proliferative glomerulonephritis grade IV (ISN/RPS Class IV lupus nephritis)
- Proposed mechanism: viral antigen–antibody IC deposition → renal pathology in susceptible individuals

**Created:** `wiki/sources/Rajadhyaksha2012 - Dengue Evolving into SLE and Lupus Nephritis.md`

**Updated:**
- `wiki/geography/India.md` (sources 3→4; Mumbai KEM Hospital subsection added)
- `wiki/concepts/Autoimmunity in Dengue.md` (sources 26→27; new subsection for Rajadhyaksha2012 biopsy-confirmed SLE+LN; Wan2012 mention resolved to primary source)
- `wiki/concepts/Infection-Triggered Autoimmunity.md` (sources 9→10; dengue-SLE case reports expanded to include Rajadhyaksha2012)
- `wiki/concepts/Dengue Pathophysiology.md` (sources 9→10; new subsection on immune complex-mediated renal pathology)
- `wiki/concepts/Dengue Clinical Classification.md` (sources 4→5; 1997 WHO DHF criteria background mention)
- `wiki/entities/DENV-1.md` (sources 8→9; primary DENV-1 infection context)
- `wiki/entities/Aedes aegypti.md` (sources 8→9; background vector mention)
- `wiki/methods/IgM-IgG Serology ELISA.md` (sources 12→13; IgM+/IgG- primary infection serology)
- `wiki/methods/RT-PCR.md` (sources 5→6; DENV-1 genotype 1 confirmation)
- `wiki/methods/Indirect Immunofluorescence ANA Test.md` (sources 8→9; ANA 1:320 homogeneous 4+ in dengue→SLE)
- `wiki/analyses/Notable Findings.md` (sources 19→20; new entry: dengue→SLE+LN with persistent anti-cardiolipin IgM+IgG)
- `wiki/index.md` (sources 32→33, pages 98→99; all affected page counts updated)

---

## [2026-04-17] ingest | Pang2017 - DHF Pathogenesis Review

**Citation:** Pang X, Zhang R, Cheng G. "Progress towards understanding the pathogenesis of dengue hemorrhagic fever." *Virologica Sinica*. 2017;32(1):16–22. DOI: 10.1007/s12250-016-3855-9. Citations: 74 (SS) / 67 (CR).

**Type:** Narrative review (no original data). Tsinghua University, Beijing, China.

**New content added:**
1. **NS1 Protein** — anti-NS1 antibody binding to GPI-anchored NS1 → protein tyrosine phosphorylation → enhanced DENV replication (Jacobs 2000 via Pang2017); distinct from NF-κB cytokine pathway.
2. **Dengue Pathophysiology** — C5b-C9 complex formation correlates with NS1 concentration → NLRP3 inflammasome activation → DHF-associated cytokines (Kurosu 2007 + Suresh 2016 via Pang2017). Note: Suresh 2016 is a general complement paper; direct dengue confirmation not in wiki sources.
3. **T Cell Responses in Dengue / Cytokine Storm** — IL-10 directly induces T cell apoptosis in acute dengue; IL-10 blockade reduces apoptosis; reduced T cell numbers in DHF vs. DF (Green 1999, Mathew & Rothman 2008 via Pang2017) → impaired viral clearance.

**Updated:** [[Pang2017 - DHF Pathogenesis Review]] (created) + 21 existing pages — NS1 Protein, Dengue Pathophysiology, T Cell Responses in Dengue, Cytokine Storm (substantive), plus source-only: ADE, Type I IFN, Original Antigenic Sin, Secondary Dengue Infection, Cross-Reactive Antibodies, NS1 Molecular Mimicry in Dengue, Dengue Clinical Classification, NS1 Antigen Detection, DENV-1–4, Aedes aegypti, Aedes albopictus, prM Protein, CYD-TDV, index.md, log.md.

---

## [2026-04-17] ingest | Velazqueza2017 - SLE vs Dengue Case Series

**Citation:** Luevanos-Velázquez A, Vega-Cornejo G, Monteón-Galván D. "What are we looking for? Systemic lupus erythematosus vs. dengue infection: A case series report." *Rev Colomb Reumatol*. 2018. DOI: 10.1016/j.rcreu.2017.05.006. Citations: 1 (SS) / 1 (CR).

**New pages created (1):**
- `wiki/sources/Velazqueza2017 - SLE vs Dengue Case Series.md`

**Pages updated (10):**
- `wiki/concepts/Autoimmunity in Dengue.md` — new "Pediatric SLE-Dengue Co-presentation" subsection; sources 25→26
- `wiki/concepts/Macrophage Activation Syndrome in Dengue.md` — new "Full Dengue-Autoimmune Spectrum" section documenting ANA-positive SLE contrast; sources 2→3; updated date 04-15→04-17
- `wiki/concepts/Infection-Triggered Autoimmunity.md` — dengue-triggered SLE de novo case added to Transience vs. Persistence section; sources 8→9
- `wiki/concepts/Antinuclear Antibodies.md` — new "Dengue-Associated SLE: High-Titer ANA" subsection; sources 10→11
- `wiki/concepts/Dengue Neurological Complications.md` — Case 2 convulsive crisis added; sources 3→4; updated date 04-15→04-17
- `wiki/concepts/NS1 Molecular Mimicry in Dengue.md` — source added (NS1 endothelial/plasminogen mimicry cited); sources 8→9
- `wiki/entities/NS1 Protein.md` — source added; sources 11→12
- `wiki/entities/FcγRIIa Receptor.md` — source added (FcR polymorphism in autoimmunity); sources 6→7
- `wiki/methods/IgM-IgG Serology ELISA.md` — source added; sources 11→12
- `wiki/methods/Indirect Immunofluorescence ANA Test.md` — source added (ANA 1:1280 cases); sources 7→8

**Geography:** Mexico (Guadalajara, Jalisco) — 1 source; no standalone page created per ≥2-source rule; noted in index.

**Notable Findings:** No entry — paper confirms existing pattern (dengue + ANA-positive SLE) rather than producing a surprising cross-cutting finding.

---

## [2026-04-17] ingest | Gawali2021 - ANA Prevalence in Seroconverted Dengue Patients

**Citation:** Gawali D, Misra V, Gaharwar R, Mittal A, Jain SB, Khetan R. "Understanding the ANA prevalence and its common pattern in seroconverted dengue infected patients." *International Journal of Applied Research* 2021; 7(10):154–158. DOI: null. Citations: null (SS) / null (CR). **⚠ Journal quality note:** IJAR is not indexed in PubMed/Scopus/WoS; its claimed "Impact Factor: 8.4" is not from Clarivate/JCR.

**New pages created (1):**
- `wiki/sources/Gawali2021 - ANA Prevalence in Seroconverted Dengue Patients.md`

**Pages updated (11):**
- `wiki/concepts/Antinuclear Antibodies.md` — 6-month ANA time point added to post-dengue section and comparison table; sources 9→10
- `wiki/concepts/Autoimmunity in Dengue.md` — new "ANA at 6-Month Follow-Up" subsection; sources 24→25
- `wiki/concepts/Infection-Triggered Autoimmunity.md` — 6-month data added to Transience vs. Persistence section; sources 7→8
- `wiki/methods/Indirect Immunofluorescence ANA Test.md` — Gawali2021 6-month IIFA data added; sources 6→7; section header updated to "Acute and Post-Acute"
- `wiki/methods/IgM-IgG Serology ELISA.md` — Gawali2021 added to Sources; sources 10→11
- `wiki/methods/NS1 Antigen Detection.md` — Gawali2021 added to Sources; sources 7→8
- `wiki/entities/Aedes aegypti.md` — background mention added; sources 6→7
- `wiki/entities/Aedes albopictus.md` — background mention added; sources 2→3
- `wiki/geography/India.md` — new Gwalior section (third Indian research centre); sources 2→3
- `wiki/index.md` — sources 29→30; pages 95→96; all entity/concept/method/geography counts updated; Sources section header corrected (28→30); Concepts section header corrected (20→21)
- `wiki/log.md` — this entry

**Notable finding:** None. The 18.33% ANA positivity at 6 months is an interesting time point but the lack of a control group prevents definitive attribution to dengue; it is barely above the available healthy-population baseline (Li2019 14.01% at >1:100). No new mechanism or cross-cutting finding above the wiki's current knowledge.

---

## [2026-04-17] ingest | Zhou2007 - Polyreactive Antibodies Natural Antibody Function

**Citation:** Zhou ZH, Tzioufas AG, Notkins AL. "Properties and function of polyreactive antibodies and polyreactive antigen-binding B cells." *Journal of Autoimmunity* 2007; 29(4):219–228. DOI: 10.1016/j.jaut.2007.07.015. Citations: 194 (SS) / 176 (CR).

**New pages created (2):**
- `wiki/sources/Zhou2007 - Polyreactive Antibodies Natural Antibody Function.md`
- `wiki/concepts/Polyreactive Antibodies.md`

**Pages updated (5):**
- `wiki/concepts/Infection-Triggered Autoimmunity.md` — new subsection: polyreactive antibodies as a fourth interpretive layer; practical IIFA/LIA interpretation rule; sources 6→7
- `wiki/concepts/Antinuclear Antibodies.md` — new paragraph: polyreactive IgM interpretation of IIFA-positive, LIA-negative dengue fraction; link to Polyreactive Antibodies; sources 8→9
- `wiki/concepts/Autoimmunity in Dengue.md` — new inline paragraph: polyreactive IgM interpretation of ~66% non-specific IIFA fraction; Polyreactive Antibodies added to Related Pages and Sources; sources 23→24
- `wiki/analyses/Notable Findings.md` — new entry [2026-04-17]: polyreactive IgM framework names the non-specific dengue ANA fraction; sources 18→19
- `wiki/index.md` — sources 28→29; pages 93→95; Infection-Triggered Autoimmunity 6→7, Antinuclear Antibodies 8→9, Autoimmunity in Dengue 23→24; Polyreactive Antibodies added (1 source)

**Notable finding flagged:** The two-thirds IIFA-positive, LIA-negative dengue ANA fraction is consistent with amplification of normal polyreactive IgM — not induced autoimmunity. This names a mechanism previously labelled "non-specific" and has interpretive implications across Chatterjee2024, Vo2020, and Berlin2007.

---

## [2026-04-17] ingest | Bhatt2020 - Dengue Pathogenesis Review

**Citation:** Bhatt P, Sabeena SP, Varma M, Arunkumar G. "Current Understanding of the Pathogenesis of Dengue Virus Infection." *Current Microbiology* 2021; 78(1):17–32. DOI: 10.1007/s00284-020-02284-w. Citations: 300 (SS) / 294 (CR).

**New pages created (1):**
- `wiki/sources/Bhatt2020 - Dengue Pathogenesis Review.md`

**Pages updated (16):**
- `wiki/concepts/Type I Interferon Response in Dengue.md` — new section: sfRNA1→TRIM25→RIG-I K172 ubiquitination block → IFN suppression; sfRNA→Dicer siRNA pathway inhibition; XRN1 stalling mechanism; relationship to Sungnak2025 IFN-α2 paradox; sources 2→3
- `wiki/concepts/Original Antigenic Sin.md` — new section: OAS T cell mechanism (low-avidity CD8+ preferential expansion; cytolytic loss; TNF-α/IL-6 excess without killing; delayed clearance → positive feedback → DHF/DSS); sources 1→2
- `wiki/concepts/Antibody-Dependent Enhancement.md` — new section: Katzelnick 2017 quantitative ADE window 1:21–1:80 (n=6684 Nicaraguan children); bounded enhancement zone; vaccine design implications; sources 10→11
- `wiki/concepts/T Cell Responses in Dengue.md` — new "OAS-driven CD8+ dysfunction" subsection (low-avidity expansion; cytolytic loss + TNF-α/IL-6; Bhatt2020 + Sungnak2025 exhaution data as complementary); sources 2→3
- `wiki/concepts/Cytokine Storm.md` — new sections: MIF-autophagy viral amplification loop; Th1→Th2 shift + Treg IL-10 mechanism; OAS cytokine excess updated with Bhatt2020 specifics (TNF-α/IL-6 without cytolysis); sources 8→9
- `wiki/concepts/Dengue Pathophysiology.md` — new section: glycocalyx degradation via heparanase (NS1-activated, cleaves heparan sulfate chains) and cathepsin L (NS1-activated, cleaves proteoglycan cores); dual enzymatic route; sources 7→8
- `wiki/concepts/Dengue Vaccine Candidates.md` — new section: Katzelnick 2017 ADE window as quantitative safety benchmark for post-vaccination titre monitoring; CYD-TDV seronegative risk framed against 1:21–1:80 window; sources 5→6
- `wiki/concepts/NS1 Molecular Mimicry in Dengue.md` — Bhatt2020 source added confirming NF-κB/MCP-1/IL-6/IL-8 pathway; sources 7→8
- `wiki/entities/NS1 Protein.md` — new section: NS1 ER-membrane replication complex cofactor (with NS2A/B, NS3, NS4A/B); heparanase + cathepsin L activation; MIF-autophagy context; sources 10→11
- `wiki/entities/prM Protein.md` — new section: anti-prM HSP60 cross-reactivity (molecular mimicry) noted; sources 1→2
- `wiki/entities/DENV-1.md` — DENV-1 primary: higher NS1 levels and viraemia than DENV-2 primary; sources 6→7
- `wiki/entities/DENV-2.md` — Asian genotype NS3 salivary gland replication efficiency specified; DENV-2 secondary highest overall viraemia; sources 7→8
- `wiki/entities/Aedes aegypti.md` — new section: Asian genotype DENV-2 enhanced salivary gland replication; sources 5→6
- `wiki/geography/India.md` — new Manipal, Karnataka subsection (Kasturba Medical College); sources 1→2
- `wiki/analyses/Notable Findings.md` — new entry [2026-04-17]: Katzelnick quantitative ADE window 1:21–1:80; sources 17→18
- `wiki/index.md` — sources 27→28; pages 92→93; all affected entity/concept/geography counts updated

**Notable finding flagged:** ADE has a discrete quantitative "danger zone" at antibody titer 1:21–1:80 (Katzelnick 2017 via Bhatt2020; n=6684) — converting the qualitative "sub-threshold ADE" model into a bounded enhancement window with direct vaccine safety implications.

---

## [2026-04-17] ingest | Dejnirattisai2010 - Anti-prM Antibodies Enhance Dengue ADE

**Citation:** Dejnirattisai W et al. "Cross-Reacting Antibodies Enhance Dengue Virus Infection in Humans." *Science* 2010; 328:745–748. DOI: 10.1126/science.1185181. Citations: 891 (SS) / 820 (CR).

**New pages created (2):**
- `wiki/sources/Dejnirattisai2010 - Anti-prM Antibodies Enhance Dengue ADE.md`
- `wiki/entities/prM Protein.md` (new entity; 1 source)

**Pages updated (14):**
- `wiki/concepts/Antibody-Dependent Enhancement.md` — new "Anti-prM Antibodies" section (dominant class, ~60%; neutralisation ceiling; 10^5-fold monocyte/DC ADE; mechanism via incomplete prM cleavage); two new Contradictions entries; sources 9→10
- `wiki/entities/E Protein.md` — new section on anti-E as minority (~35%) vs. anti-prM (~60%); E vs. prM ADE comparison; sources 3→4
- `wiki/concepts/Cross-Reactive Antibodies.md` — new "Anti-prM dominant non-neutralising class" section; new Contradiction (neutralisation ceiling vs. sub-threshold model); sources 8→9
- `wiki/concepts/Dengue Vaccine Candidates.md` — new "Anti-prM ADE risk from native prM sequences" section; new Contradiction (anti-prM as untracked dominant ADE pathway in vaccine immunogenicity readouts); sources 4→5
- `wiki/concepts/Secondary Dengue Infection.md` — new section on anti-prM as dominant cross-reactive ADE pool in secondary infection context; sources 11→12
- `wiki/geography/Thailand.md` — Khon Kaen + Songkhla donor recruitment context; sources 1→2
- `wiki/entities/DENV-1.md` — anti-prM cross-reactivity note; sources 5→6
- `wiki/entities/DENV-2.md` — anti-prM cross-reactivity note; sources 6→7
- `wiki/entities/DENV-3.md` — anti-prM cross-reactivity note; sources 7→8
- `wiki/entities/DENV-4.md` — anti-prM cross-reactivity note; sources 6→7
- `wiki/methods/PRNT.md` — neutralisation plateau finding (anti-prM 10–60% ceiling); sources 2→3
- `wiki/methods/IgM-IgG Serology ELISA.md` — research ELISA for anti-prM/anti-E characterisation; sources 9→10
- `wiki/analyses/Notable Findings.md` — new entry [2026-04-17]: anti-prM dominant structural antibody and most potent ADE mediator
- `wiki/index.md` — sources 26→27; pages 90→92; entity/concept/method/geography counts updated

**Notable finding flagged:** Anti-prM as dominant (~60%) structural antibody, fully cross-reactive across all four DENV serotypes, incapable of complete neutralisation (structural ceiling from incomplete prM cleavage), mediating 10^5-fold monocyte/DC ADE — substantially exceeding typical anti-E ADE. All current vaccine platforms will prime this response.

---

## [2026-04-17] update | ANA and Dengue - A Literature Review — integrated Vo2020 and Saito2004

**Sources added:** Vo2020 (autoantigen microarray, Cambodian pediatric cohort, n=40), Saito2004 (PAIgM in secondary dengue, n=78). Source count: 22 → 24.

**New content:**
- §4.4: Nuclear antigen IgG consumption model — 19 DHF-correlated IgGs (including KU, Smith, histone, Sm/RNP, nucleosome) positively correlated with platelet count in DHF (Vo2020); proposed interpretation: ANA testing at peak disease may underestimate autoimmune burden in DHF due to IC sequestration; provides mechanistic explanation for ANA-negative severe dengue cases
- §5.4 extended: Saito2004 PAIgM characterised as anti-dengue IgM immune complex (not anti-platelet autoantibody); completely FcγR-independent; independently predicts DHF with 92.1% specificity; thrombocytopenia now fully three-pathway (primary IgM autoAb + secondary PAIgG IC + secondary PAIgM IC)
- §7 addition: Vo2020 primary>secondary IgG inversion complicates the "ADE drives autoantibody production" model
- §9 addition: Infection order (primary vs. secondary) as host factor
- §10 Q12–Q13: Nuclear antigen consumption model testing; PAIgM FcγR-independence and DHF predictive superiority
- §11: Established claim updated (3-pathway thrombocytopenia); two new hypothesis-generating entries (Vo2020 consumption model; primary>secondary inversion)

**Watch Item resolved:** "ANA analysis page not updated with Vo2020/Saito2004" (from post-ingest lint flag 2026-04-17)

---

## [2026-04-17] lint | batched full-wiki health check

**Method:** Batched by folder (sources → entities/concepts → methods/geography → analyses) per new CLAUDE.md context-scaling convention.

**Stale cross-references:** 0 in content pages. Two apparent stale links (`[[IgM/IgG Serology ELISA]]`, `[[Lin2006]]`) confirmed as backtick code spans in log.md (historical documentation, not live wikilinks — confirmed from prior lint).

**Forward propagation:** 27/27 checks passed for Saito2004 and Vo2020 across all linked entity, concept, method, and geography pages.

**Orphans:** Reading Plan - ANA and Dengue Dynamics (only linked from index.md) — unchanged, acceptable for a meta document.

**Fixes applied:**
- `wiki/methods/IgM-IgG Serology ELISA.md` H1 title corrected from "IgM/IgG" to "IgM-IgG" (cosmetic, aligns with filename and all wikilinks)
- `wiki/state.md` Geography gaps Watch Item updated (stale "4 countries" → correct "8 countries")
- New Watch Items added: NK Cell Responses in Dengue (1 source), Original Antigenic Sin (1 source), Line Immunoassay ANA (1 source), Surface Plasmon Resonance (1 source), thin geography pages under retroactive hierarchy rule (Thailand, India, Paraguay)

**Outstanding gaps flagged (not fixed during lint):**
- `ANA and Dengue - A Literature Review` not updated with Vo2020 or Saito2004 — highest-priority follow-on task
- Thin pages: CYD-TDV (1), Wolbachia (1), NK Cell Responses in Dengue (1), Original Antigenic Sin (1); thin methods: Single-Cell RNA Sequencing, V(D)J Sequencing, qRT-PCR, ELISA Inhibition Method, Autoantigen Microarray, Line Immunoassay ANA, Surface Plasmon Resonance; thin geography: Thailand (1), India (1), Paraguay (1), Cambodia (1), Nicaragua (1)

---

## [2026-04-17] schema-update | CLAUDE.md — 8 workflow and convention improvements

**Changes:**
1. **Architecture block** — added `CLAUDE_UPDATE.md` reference
2. **Analyses page template** — new convention section with minimum required structure (Research Question, Sources Used, Synthesis, Open Questions, Related Pages)
3. **Evidence weighting** — new convention requiring study type + sample size inline on all concept/entity/method "Key Points from Literature" citations
4. **Geography hierarchy** — new convention: country pages require ≥2 sources; regional pages trigger on next relevant ingest when ≥3 country pages exist in region; retroactive rule flags Cambodia and Nicaragua as thin pending fold
5. **Ingest workflow** — added `--fast` flag (skips discussion step); added git snapshot as step 1; renumbered steps 1→14; step 13 now propagates "Questions Raised" to state.md Watch Items
6. **Lint workflow** — added context-scaling note: batch by folder when wiki >80 pages (currently above threshold)
7. **Retract/Correct workflow** — new workflow for handling retracted or corrected papers (warning banner, frontmatter flag, inline citation warnings, Watch Item, log entry)
8. **commands.md** — updated with all new commands (`ingest --fast`, `retract`, `correct`) and revised descriptions

**Sections of CLAUDE.md modified:** Architecture, Conventions (Page naming, new Geography hierarchy, new Analyses pages, new Evidence weighting), Workflows (Ingest, Lint, new Retract/Correct)
**Pages affected:** `wiki/state.md` (Watch Items updated for Cambodia, Nicaragua), `wiki/commands.md`
**Reason:** Token efficiency (fast-track ingest, batched lint, analyses template) and inter-session memory (Questions Raised propagation, retraction workflow, geography hierarchy rules)

---

## [2026-04-17] ingest | Vo 2020 - Autoantibody Profiling in Dengue

**Source:** Vo HTM et al. *Pathogens*. 2020;9(12):1060. doi:10.3390/pathogens9121060

**Citations:** SS = 10 / CR = 12 (retrieved 2026-04-17)

**Created:**
- `wiki/sources/Vo2020 - Autoantibody Profiling in Dengue.md`
- `wiki/methods/Autoantigen Microarray.md` (new method page)
- `wiki/geography/Cambodia.md` (new geography page)

**Updated:**
- `wiki/concepts/Autoimmunity in Dengue.md` (sources 22→23; new §"Systematic Autoantibody Profiling" covering primary>secondary IgG inversion, 80 IgM elevation, 19 DHF autoantibody-platelet correlations including nuclear antigen IgGs)
- `wiki/concepts/Dengue Pathophysiology.md` (sources 6→7; new §"Autoantibodies Against Complement and Coagulation Components" covering Factor P/C4/prothrombin IgG-platelet correlation + anti-heparan sulfate reduction in DF/DHF)
- `wiki/concepts/Secondary Dengue Infection.md` (sources 10→11; new §"IgG Autoantibody Paradox: Primary > Secondary" with Wan2012 reconciliation)
- `wiki/concepts/Asymptomatic Dengue Infection.md` (sources 4→5; ASD as comparator group; no autoantibody severity difference)
- `wiki/concepts/Cross-Reactive Antibodies.md` (sources 7→8; cross-reactivity context added)
- `wiki/concepts/Antibody-Dependent Enhancement.md` (sources 8→9; background citation)
- `wiki/concepts/Cytokine Storm.md` (sources 7→8; background citation)
- `wiki/concepts/Dengue Clinical Classification.md` (sources 2→3; WHO 1997 criteria applied)
- `wiki/entities/NS1 Protein.md` (sources 9→10; anti-NS1 cross-reactivity citation added)
- `wiki/entities/DENV-1.md` (sources 4→5; Cambodia 2012–2013 dominant serotype)
- `wiki/entities/DENV-2.md` (sources 5→6; minority serotype in Cambodia cohort)
- `wiki/entities/DENV-4.md` (sources 5→6; minority serotype in Cambodia cohort)
- `wiki/methods/RT-PCR.md` (sources 4→5; RT-qPCR for DENV confirmation and serotyping, Cambodia cohort)
- `wiki/methods/IgM-IgG Serology ELISA.md` (sources 8→9; IgM seroconversion diagnosis criterion)
- `wiki/methods/NS1 Antigen Detection.md` (sources 6→7; SD Bioline NS1 RDT diagnosis criterion)
- `wiki/analyses/Notable Findings.md` (new entry: primary > secondary IgG autoantibody inversion)
- `wiki/index.md` (sources 25→26; pages 87→90; new entries for Vo2020 source, Autoantigen Microarray method, Cambodia geography; updated counts for DENV-1/2/4, NS1 Protein, Autoimmunity, ADE, Asymptomatic, Pathophysiology, Clinical Classification, Secondary Infection, Cross-Reactive Abs, Cytokine Storm, RT-PCR, NS1 Antigen Detection, IgM-IgG ELISA)

**Key finding:** First systematic autoantibody microarray in dengue. Primary infection has higher IgG autoantibody breadth than secondary (counterintuitive). IgG autoantibodies against nuclear antigens (KU, Smith, histone, Sm/RNP, nucleosome), complement (Factor P, C4) and coagulation (prothrombin) positively correlate with platelet counts in DHF — suggesting consumption not production is pathologically significant. No severity difference in total autoantibody load between asymptomatic and hospitalised patients.

---

## [2026-04-17] ingest | Saito 2004 - PAIgG and PAIgM in Secondary Dengue

**Source:** Saito M et al. *Clinical and Experimental Immunology*, 2004; 138:299–303. doi:10.1111/j.1365-2249.2004.02626.x

**Citations:** SS = 138 / CR = 89 (retrieved 2026-04-17)

**Created:**
- `wiki/sources/Saito2004 - PAIgG and PAIgM in Secondary Dengue.md`
- `wiki/methods/Platelet-Associated Immunoglobulin ELISA.md` (new method page; retroactively covers Oishi2003 + Saito2004)

**Updated:**
- `wiki/geography/Philippines.md` (sources 1→2; added Saito2004 study details; updated tags)
- `wiki/concepts/Secondary Dengue Infection.md` (sources 9→10; PAIgM subsection added; bifurcation model refined to primary: IgM autoAb, secondary: PAIgG + PAIgM immune complexes)
- `wiki/concepts/Dengue Pathophysiology.md` (sources 5→6; thrombocytopenia section expanded with infection-order split and PAIgM FcγR bypass)
- `wiki/concepts/Autoimmunity in Dengue.md` (sources 21→22; Saito2004 added to sources with distinction of secondary-infection IgM immune complex from primary-infection IgM autoantibody)
- `wiki/entities/FcγRIIa Receptor.md` (sources 5→6; PAIgM FcγR bypass deepens FcγRIIa paradox)
- `wiki/methods/IgM-IgG Serology ELISA.md` (sources 7→8; Saito2004 added)
- `wiki/methods/Hemagglutination Inhibition Test.md` (sources 1→2; Saito2004 added)
- `wiki/methods/RT-PCR.md` (sources 3→4; Saito2004 + platelet RNA detection finding added)
- `wiki/sources/Oishi2003 - PAIgG and Thrombocytopenia in Secondary Dengue.md` (Methods Used: "Competitive ELISA for PAIgG" → `[[Platelet-Associated Immunoglobulin ELISA]]`)
- `wiki/analyses/Notable Findings.md` (new entry: secondary-infection PAIgM as anti-dengue immune complex; bifurcation model refinement)
- `wiki/index.md` (sources 24→25; pages 84→87; new entries for Saito2004 source + Platelet-Associated Immunoglobulin ELISA method; updated counts for Philippines, Secondary Dengue Infection, Dengue Pathophysiology, Autoimmunity in Dengue, FcγRIIa Receptor, RT-PCR, IgM-IgG Serology ELISA, Hemagglutination Inhibition Test)

**Key finding:** PAIgM in secondary dengue carries anti-dengue virus IgM (not anti-platelet autoantibody IgM; confirmed by platelet eluate). PAIgM >20 ng/10⁷ is a DHF predictor (92.1% specificity). FcγR completely bypassed for PAIgM. Bifurcation model now fully specified: primary = IgM anti-platelet autoantibody; secondary = PAIgG + PAIgM anti-dengue immune complexes.

---

## [2026-04-17] analysis update | ANA and Dengue — A Literature Review (12→22 sources)

**Scope:** Expanded the ANA literature review to incorporate the 5 ingests since 2026-04-13 (Bos2025, Lin2001, Oishi2003, Morel2014, Palacios2016) plus Garcia2010 and Bruhns2009 (referenced in body but missing from sources list).

**Sections added/changed:**
- Frontmatter: `sources: 12→22`, `updated: 2026-04-13→2026-04-17`, tags expanded (MAS, HLH, macrophage-activation, NS1-IgG-kinetics, primary-infection, PAIgG, ANA-negative, Talib2013).
- Revision note blockquote added at top.
- §5.1: Lin2001 attribution correction (foundational IgM anti-platelet autoantibody — precedes Lin2006 by 5 years).
- §5.4: Oishi2003 inserted — NS1-IC pathway distinct from Lin2001/Lin2006 IgM autoantibody pathway; FcγRII bypassed at platelet surface.
- **New §5.5 "Macrophage-Driven Autoimmunity Without ANA":** Morel2014's two MAS cases (ANA-/anti-dsDNA-negative, hyperferritinaemia 3828 mg/dl) + Palacios2016/Lai2012 MAS+nephrotic case. Establishes parallel macrophage-hyperactivation axis distinct from NS1-mimicry → autoantibody axis.
- **New §6.3 "What the NS1-IgG Kinetics Tell Us":** Bos2025 NS1-IgG t½ ≈ 2.1 y constraint; reframes Garcia2009 2-year ANA persistence as residual NS1-mimicry + epitope-spreading + IC-persistence components rather than continued NS1 mimicry. Counter-trajectory note: XR E-IgG actively rises 6–18M (t½ = −2.13 y), implying anti-coagulation-factor reactivity may follow opposite vector.
- §8: Morel/Talib case contrast table — ANA-negative MAS vs. ANA-positive SLE+lupus nephritis (Talib 2013) as opposite poles within the dengue-autoimmune disease space.
- §10: Five new open questions (Q7–Q11) — MAS axis invisibility to ANA; Talib SLE de novo vs. flare; NS1-IgG → autoantibody decay correlation; rising XR E-IgG → coagulation-factor reactivity; relative contribution of Lin2001 IgM autoreactive vs. Oishi2003 NS1-IC pathways to thrombocytopenia.
- §11: Revised epistemic taxonomy. Two new "Established" claims (ANA-negative MAS axis; bifurcated thrombocytopenia mechanisms). One new "Probable" (NS1-IgG t½ ≈ 2.1 y reframes Garcia2009 persistence). Two new "Hypothesis-generating" (Talib SLE; rising XR E-IgG counter-trajectory).
- Sources list: appended Lin2001, Oishi2003, Garcia2010, Bos2025, Bruhns2009, Morel2014, Palacios2016.

**Commit:** `b791fb6` (master) — bundled with the 2026-04-16 lint propagation sweep and 9 source ingests since 2026-04-13. 57 files changed, 11,019 insertions, 209 deletions.

**Web deploy:** `sync-and-build.ps1` ran clean — Quartz built 85 input files → 564 emitted in 10s. Pushed `988cb04` to `OsandaC/dengue-wiki-web` v4 branch; Cloudflare Pages auto-redeploys at https://dengue-wiki-web.pages.dev within ~1 min.

---

## [2026-04-16] lint | Deep propagation sweep

**Scope:** Forward-propagation audit for the last five ingests (Bos2025, Lin2001, Oishi2003, Morel2014, Palacios2016). For each source page, enumerated every wikilink under Entities Mentioned / Concepts Addressed / Methods Used and confirmed the target page included that source in its Sources section AND had its frontmatter `sources` count incremented. Also: orphan check (Nicaragua), erroneous link audit (Morel2014 → DENV-1), and contradiction audit (FcγRIIa paradox, ANA-negative MAS).

**Clean:**
- 0 silent overwrites of existing contradictions; FcγRIIa Receptor and Macrophage Activation Syndrome in Dengue both preserve their respective contradiction sections with full sourcing
- All Bos2025/Lin2001/Oishi2003/Morel2014/Palacios2016 cross-source synthesis text remains intact in target pages

**Fixed (18 pages updated):**

*Concepts (7):*
1. `concepts/Antibody-Dependent Enhancement.md` — sources 7→8 (added Oishi2003 immune complex / FcγRII-bypass platelet binding)
2. `concepts/Autoimmunity in Dengue.md` — sources 20→21 (added Bos2025 NS1-IgG kinetic context)
3. `concepts/Cross-Reactive Antibodies.md` — sources 6→7 (added Palacios2016 Wan2012 cross-serotype data); Nicaragua added to Related Pages
4. `concepts/Cytokine Storm.md` — sources 6→7 (added Oishi2003 complement activation context)
5. `concepts/Dengue Pathophysiology.md` — sources 2→5 (added Lin2001 primary platelet pathology, Morel2014 MAS axis, Oishi2003 secondary thrombocytopenia mechanism)
6. `concepts/Dengue Vaccine Candidates.md` — sources 3→4 (added Lin2001 NS1-vaccine pathogenic-epitope discussion)
7. `concepts/Secondary Dengue Infection.md` — sources 7→9 (added Lin2001 primary-infection contrast, Palacios2016 Lai 2012 reinfection)

*Entities (5):*
8. `entities/NS1 Protein.md` — sources 7→9 (added Morel2014 NS1+ in 2/3 MAS cases, Palacios2016 NS1 across cited cases)
9. `entities/DENV-1.md` — sources 2→4 (added Bos2025 cohort serotype, Oishi2003 HI antigen panel); Nicaragua added to Related Pages
10. `entities/DENV-2.md` — sources 3→5 (added Oishi2003, Palacios2016)
11. `entities/DENV-3.md` — sources 4→7 (added Bos2025, Oishi2003, Palacios2016); Nicaragua added to Related Pages
12. `entities/DENV-4.md` — sources 3→5 (added Oishi2003, Palacios2016)
13. `entities/Aedes albopictus.md` — sources 1→2 (added Oishi2003 — C6/36 cell line for dengue antigen prep, methodological role only)

*Methods (3):*
14. `methods/IgM-IgG Serology ELISA.md` — sources 3→7 (added Lin2001 anti-NS1 IgG ELISA, Oishi2003 IgM-capture ELISA, Morel2014 IgG/IgM/anticardiolipin, Palacios2016 cited methodology)
15. `methods/NS1 Antigen Detection.md` — sources 3→6 (added Bos2025 NS1 antigen panel, Morel2014 cases 2/3 NS1+, Palacios2016 cited cases)
16. `methods/RT-PCR.md` — sources 2→3 (added Lin2001 DENV-3 confirmation patients 2/7)

*Geography (1):*
17. `geography/Singapore.md` — sources 1→2 (added Palacios2016 Chang 2007 retinal vasculitis case; new "Dengue-Associated Retinal Vasculitis" subsection)

*Source page correction (1):*
18. `sources/Morel2014 - Autoimmune Response in Children With Dengue.md` — removed erroneous `[[DENV-1]]` entity link (paper does not specify serotype; explicit clarifying note added)

**Index synced:** `wiki/index.md` per-page source counts updated for all 17 content pages above; header date 2026-04-15→2026-04-16.

**Not fixed (known from prior Watch Items):**
- Thin entity pages: CYD-TDV (1), Wolbachia (1)
- Geography pages with single sources: Thailand, India, Nicaragua, Paraguay, Philippines
- Method pages with single sources: ELISA Inhibition Method, Single-Cell RNA Sequencing, V(D)J Sequencing, qRT-PCR, Line Immunoassay ANA, Surface Plasmon Resonance, Hemagglutination Inhibition Test
- Missing concept: Herd Immunity
- ELISA Inhibition Method protocol attribution for Bos2025
- Reading Plan orphan
- Raw filename typo `Jhonson2022.pdf` (immutable raw/)
- All open mechanism gaps documented in Watch Items

**Process improvement documented:** state.md gains a new decision entry codifying the forward-propagation check as an explicit lint step. Memory `feedback_ingest_secondary_sources.md` already recorded the secondary-source propagation rule; the new gap was that single-page metadata audits did not verify the inverse (source → linked-target propagation), which this lint added.

---

## [2026-04-15] ops | Raw filename typo fixed

**Fixed:** `raw/Jhonson2022.pdf` renamed to `raw/Johnson2022.pdf` by curator.
**Updated:** `wiki/sources/Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity.md` — Raw file link corrected from `[[raw/Jhonson2022.pdf]]` to `[[raw/Johnson2022.pdf]]`; correction note removed.
**Watch Item:** Resolved in state.md.

---

## [2026-04-15] lint | Health check

**Scope:** Full wiki audit (85 files; 84 content pages). Systematic checks: orphan pages, stale wikilinks, thin pages, frontmatter consistency, missing connections.

**Clean:**
- 0 orphan pages — all 84 content pages have ≥1 inbound link
- 0 genuine stale wikilinks in content pages — two apparent stale links (`[[IgM/IgG Serology ELISA]]`, `[[Lin2006]]`) found in log.md are inside backtick code spans (historical documentation); not resolved as Obsidian links
- Raw file links in source pages (e.g., `[[raw/lin2001.pdf]]`) resolve correctly to existing PDFs; not stale
- Index total page count 84 confirmed correct (all pages excluding index.md itself)
- All recently updated frontmatter source counts verified against page content: NS1 Protein ×7 ✓, FcγRIIa ×5 ✓, Autoimmunity in Dengue ×20 ✓, Secondary Dengue Infection ×7 ✓, NS1 Molecular Mimicry ×7 ✓, Cytokine Storm ×6 ✓, Cross-Reactive Antibodies ×6 ✓, MAS in Dengue ×2 ✓

**Fixed (3):**
1. `wiki/concepts/Dengue Neurological Complications.md` — Palacios2016 retinal vasculitis case (Chang et al. 2007, Singapore; immune complex deposition) added as new "Retinal Vasculitis" subsection under Other Neurological Manifestations; Palacios2016 added to Sources; `[[Singapore]]` added to Related Pages; frontmatter `sources: 2→3`, `updated: 2026-04-12→2026-04-15`; tags updated
2. `wiki/index.md` — Dengue Neurological Complications count `2→3`
3. `wiki/log.md` — documentation typo corrected: Oishi2003 ingest entry said "NS1 Protein 5→7" (should be 6→7; Lin2001 did the 5→6 step, Oishi2003 did the 6→7 step)

**Not fixed (known from prior Watch Items):**
- Thin pages: Aedes albopictus (1), CYD-TDV (1), Wolbachia (1), plus geography pages with single sources (Nicaragua, Thailand, India, Singapore, Paraguay, Philippines)
- Method pages with single sources: ELISA Inhibition Method, Single-Cell RNA Sequencing, V(D)J Sequencing, qRT-PCR, Line Immunoassay ANA, Surface Plasmon Resonance, Hemagglutination Inhibition Test
- Missing concept: Herd Immunity — no wiki sources address it directly
- ELISA Inhibition Method attribution (Bos2025 vs. Vazquez 2003 protocol) — cannot verify from wiki alone
- Reading Plan orphan — acceptable for meta document
- Raw filename typo `Jhonson2022.pdf` — immutable raw/
- All existing mechanism gaps and missing geography pages (see Watch Items in state.md)

---

## [2026-04-15] ingest | Oishi2003 - PAIgG and Thrombocytopenia in Secondary Dengue

**Source:** Oishi K et al. (2003). Correlation between increased platelet-associated IgG and thrombocytopenia in secondary dengue virus infections. *J Med Virol* 71:259–264. DOI: 10.1002/jmv.10478
**Citations:** Semantic Scholar 62; CrossRef 41 (retrieved 2026-04-15)

**Created (3 pages):**
- `wiki/sources/Oishi2003 - PAIgG and Thrombocytopenia in Secondary Dengue.md`
- `wiki/geography/Philippines.md` (new — San Lazaro Hospital / St. Luke's Medical Center, Manila)
- `wiki/methods/Hemagglutination Inhibition Test.md` (new — HI titer ≥1:2,560 = secondary infection classification)

**Updated (6 pages):**
- `wiki/concepts/Secondary Dengue Infection.md` — new PAIgG thrombocytopenia section; new contradiction (FcγRII not required vs. Garcia2010 HH-DHF risk); HI test added to Related Pages and Diagnostic Classification; Philippines added; sources 6→7
- `wiki/entities/NS1 Protein.md` — new contradiction entry: infection-order-dependent bifurcation (IgM autoAb in primary vs. IgG IC in secondary); Oishi2003 added to Sources; frontmatter sources 6→7, tags updated
- `wiki/entities/FcγRIIa Receptor.md` — new contradiction: FcγRII not required for dengue-platelet binding (Oishi2003/Wang 1995), paradox with Garcia2010 HH-DHF OR 10.56 documented; Oishi2003 added to Sources; frontmatter sources 4→5, tags updated
- `wiki/concepts/Autoimmunity in Dengue.md` — Oishi2003 added to Sources; frontmatter sources 19→20, tags updated
- `wiki/analyses/Notable Findings.md` — new entry: thrombocytopenia mechanism bifurcates by infection order (autoantibody in primary vs. immune complex in secondary; FcγRII bypassed); sources 15→16
- `wiki/index.md` — Sources 23→24; Total pages 80→84; FcγRIIa 4→5; NS1 Protein 6→7; Autoimmunity in Dengue 19→20; Secondary Dengue Infection 6→7; Methods 12→13; Geography 7→8; citation footnote updated; Oishi2003 added to ranked table

**Key cross-wiki synthesis documented:** Lin2001 + Oishi2003 together establish that dengue thrombocytopenia bifurcates by infection order — primary drives IgM anti-platelet autoantibodies (NS1 mimicry, complement lysis, severity-correlated); secondary drives anti-dengue IgG immune complexes on platelets via FcγRII-independent direct dengue-platelet binding. This bifurcation is only visible by reading the two papers against each other; neither paper makes the cross-infection comparison explicit. Notable Finding appended.

---

## [2026-04-15] ingest | Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients

**Created:**
- `wiki/sources/Lin2001 - IgM Anti-Platelet Autoantibody in Dengue Patients.md`

**Updated:**
- `wiki/entities/NS1 Protein.md` — attribution corrected (IgM anti-platelet finding originates in Lin2001, not Lin2006); new section distinguishing platelet lysis (severity-correlated) vs. aggregation inhibition (not severity-correlated); primary-infection context added; sources 5→6
- `wiki/concepts/NS1 Molecular Mimicry in Dengue.md` — attribution corrected; platelet effects table added (lysis vs. aggregation with severity correlation column); new section on primary-infection IgM production; sources 6→7; frontmatter updated
- `wiki/concepts/Autoimmunity in Dengue.md` — Lin2001 added to sources list; sources 18→19
- `wiki/entities/DENV-3.md` — new section on Taiwan 1998–1999 DENV-3 outbreak; sources 3→4
- `wiki/entities/DENV-2.md` — DENV-2 anti-platelet IgM cross-serotype finding added; sources 2→3
- `wiki/geography/Taiwan.md` — new section on 1998–1999 DENV-3 outbreak; Lin2001 added to sources; sources 3→4
- `wiki/analyses/Notable Findings.md` — new entry: lysis vs. aggregation divergence and primary-infection DHF/DSS; sources 14→15
- `wiki/index.md` — Sources 22→23; total pages 79→80; entity and concept counts updated

**Citation counts:** SS 195, CR 95. DOI 10.1002/1096-9071(20000201)63:2<143::aid-jmv1009>3.0.co;2-l

**Key attribution correction:** The IgM anti-platelet finding and the DHF/DSS > DF severity correlation were previously attributed exclusively to Lin2006. Lin2001 is the actual origin of both findings. Lin2006 confirmed and extended the mechanism (NS1 absorption, endothelial effects, molecular target identification). Wiki updated to credit both with Lin2001 as the original.

**Key new finding documented:** Platelet aggregation inhibition does NOT correlate with disease severity (DHF/DSS ≈ DF) — only complement-mediated platelet lysis does. This distinction was absent from the wiki before this ingest.

---

## [2026-04-15] ingest | Morel2014 - Autoimmune Response in Children With Dengue

**Created:**
- `wiki/sources/Morel2014 - Autoimmune Response in Children With Dengue.md`
- `wiki/geography/Paraguay.md` (new geography)
- `wiki/concepts/Macrophage Activation Syndrome in Dengue.md` (new concept)

**Updated:**
- `wiki/concepts/Autoimmunity in Dengue.md` — new MAS section; new contradiction (ANA-negative MAS vs. autoantibody-severity correlation); sources 16→18; related pages updated; tags updated
- `wiki/concepts/NS1 Molecular Mimicry in Dengue.md` — new contradiction entry; sources 4→6
- `wiki/concepts/Cytokine Storm.md` — MAS as extreme cytokine storm variant; related pages + sources updated (4→6)
- `wiki/analyses/Notable Findings.md` — new entry: ANA-negative dengue MAS; sources 12→14
- `wiki/index.md` — Sources 20→22; total pages 75→79; Concepts 19→20; Geography 6→7; Morel2014 and Palacios2016 added; citation footnote updated

**Citation counts:** Morel2014: SS null (not indexed at English-edition DOI), CR 0. DOI 10.1016/j.reumae.2014.03.008.

**Key contradiction handled:** ANA/anti-dsDNA negative in all 3 Morel cases (including 2 MAS) vs. Wan2012's autoantibody-severity correlation. Resolution documented: different assay types (standard serology vs. flow cytometric anti-endothelial Abs) and different mechanisms (MAS = macrophage/T cell-driven, not autoantibody-driven). Noted in Autoimmunity in Dengue Contradictions section and NS1 Molecular Mimicry Contradictions section.

---

## [2026-04-15] ingest | Palacios2016 - Autoimmunity in Dengue Literature Review

**Created:**
- `wiki/sources/Palacios2016 - Autoimmunity in Dengue Literature Review.md`

**Updated:**
- `wiki/index.md` (see Morel2014 entry above — joint update)

**Note:** Palacios2016 is a 2-page letter to the editor responding to Morel2014. No original data. Adds literature context: MAS+nephrotic syndrome (Lai 2012), dengue-triggered SLE with positive ANA and anti-dsDNA (Talib 2013), retinal vasculitis (Chang 2007). Confirms autoantibody-severity correlation from Wan2012. Separately ingested because it contains substantive additions (case examples, cross-serotype autoantibody comparison) beyond what Morel2014 covers, but flagged clearly as a letter/secondary source throughout.

**Citation counts:** SS 1, CR 0. DOI 10.1016/j.reumae.2015.05.015.

---

## [2026-04-15] ops | Cloudflare Pages deployment + workflow updates

**Deployed:**
- Site is now live at https://dengue-wiki-web.pages.dev (Cloudflare Pages, auto-deploy on push)
- GitHub repo: https://github.com/OsandaC/dengue-wiki-web (branch: v4)
- Merged 2 Dependabot PRs (CI deps + 21 production deps)
- Fixed `package-lock.json` out-of-sync issue (caused by rebase conflict resolution keeping pre-Dependabot lock file); regenerated from scratch and pushed

**Updated:**
- `webforshare/quartz.config.ts` — baseUrl set to `dengue-wiki-web.pages.dev`
- `webforshare/sync-and-build.ps1` — now includes `git add -A`, timestamped commit, and `git push` after build; `update web` is now a single end-to-end deploy command
- `wiki/commands.md` — removed port numbers from preview commands; removed Cloudflare Tunnel section (superseded by live site)

---

## [2026-04-14] lint | health check

**Errors fixed:**
- `wiki/index.md` — section header `Sources (19)` corrected to `Sources (20)`; `Geography (5)` corrected to `Geography (6)`; `Autoimmunity in Dengue | 15` corrected to `16`; `Secondary Dengue Infection | 5` corrected to `6`; `IgM-IgG Serology ELISA | 2` corrected to `3`
- `wiki/concepts/Antibody-Dependent Enhancement.md` — frontmatter `sources: 6` corrected to `sources: 7`; `updated:` corrected to 2026-04-14 (Bos2025 was added to content during ingest but frontmatter was not updated)
- `wiki/concepts/Autoimmunity in Dengue.md` — Seet2007 moved from Related Pages to Sources (data is directly cited in body text; sources 15→16); frontmatter updated
- `wiki/concepts/Secondary Dengue Infection.md` — Bos2025 section added (primary vs. secondary kinetics comparison; compressed/attenuated secondary responses); sources 5→6
- `wiki/methods/IgM-IgG Serology ELISA.md` — Bos2025 added as source for isotype-specific ELISA measurements; sources 2→3

**Flagged (not fixed):**
- ELISA Inhibition Method page: Bos2025 source page attributes this method to Bos2025, but the wiki page describes a specific Vazquez 2003 yellow-fever-adapted protocol; cannot verify from wiki whether Bos2025 used identical method — see raw PDF to confirm
- `Reading Plan - ANA and Dengue Dynamics` only linked from index.md — sparse connectivity but acceptable for meta document
- `raw/Jhonson2022.pdf` — filename typo (should be Johnson); link resolves correctly; raw/ is immutable

**Watch items updated in state.md:** stale thin-page alerts for DENV-1/DENV-3/E Protein corrected; new flags added for ELISA attribution, reading plan orphan, raw filename.

---

## [2026-04-14] ingest | Bos 2025 - Longitudinal Antibody Dynamics After Dengue (PREPRINT)

**Created:**
- `wiki/sources/Bos2025 - Longitudinal Antibody Dynamics After Dengue.md`
- `wiki/geography/Nicaragua.md` (new geography page — HIMJR Managua pediatric cohort)

**Updated:**
- `wiki/concepts/Cross-Reactive Antibodies.md` — new "Longitudinal kinetics" section: XR E-IgG rising 6–18M post-primary (t½=−2.13y); NS1-IgG waning (t½≈2.1y); EDI/II vs EDIII domain specificity; IgA/IgM/IgG3/IgG4 persistence at 18M; new Contradictions entry (rising XR vs. classical waning model); Sources updated; sources 5→6
- `wiki/entities/E Protein.md` — new longitudinal kinetics section: XR E-IgG rise 6–18M; EDI/II as driver; EDIII flat; ADE implication; Sources 2→3
- `wiki/entities/NS1 Protein.md` — new NS1-IgG waning kinetics section: t½≈2.1y; type-specific; autoimmunity thread context (NS1-mimicry component declines with NS1-IgG); Sources 4→5
- `wiki/concepts/Antibody-Dependent Enhancement.md` — new "Rising XR E-IgG" section: challenge to classical waning model; EDI/II specificity; IgG3 persistence; new Contradictions entry; Sources 6→7
- `wiki/analyses/Notable Findings.md` — new entry: XR E-IgG rises in ADE window; challenges classical waning model; NS1-IgG waning bridges acute ANA spike and 2-year ANA; sources 11→12
- `wiki/index.md` — Bos2025 added to Sources table and citation-ranked table; Nicaragua added to Geography; E Protein 2→3; NS1 Protein 4→5; Cross-Reactive Antibodies 5→6; ADE 6→7; Geography 5→6; total pages 73→75; sources 19→20

**Citation counts (retrieved 2026-04-14):** SS 0 / CR 0 (preprint — expected)

**Notable Findings:** 1 entry added — rising XR EDI/II E-IgG challenges classical waning ADE model; NS1-IgG waning (t½≈2.1y) provides kinetic anchor for NS1-mimicry component of ANA trajectory.

---

## [2026-04-13] ingest | Bruhns 2009 - FcγR Specificity and Affinity for IgG Subclasses

**Created:**
- `wiki/sources/Bruhns2009 - FcγR Specificity and Affinity for IgG Subclasses.md`
- `wiki/methods/Surface Plasmon Resonance.md` (new method page)

**Updated:**
- `wiki/entities/FcγRIIa Receptor.md` — Overview corrected (old claim that HH binds IgG1/IgG3 with lower affinity was wrong; Bruhns shows H131 binds IgG1 ~1.5× more than R131, IgG3 identically; principal difference is IgG2, 4.5×); new affinity table section added; Contradictions expanded with mechanism revision; Sources 3→4
- `wiki/concepts/Antibody-Dependent Enhancement.md` — new "FcγR Affinity Hierarchy" section added with Bruhns affinity values and dengue-specific interpretation; Contradictions updated; Related Pages + Sources updated; sources 5→6
- `wiki/analyses/Notable Findings.md` — new entry: H131/R131 effect is IgG2-specific; FcγRIIB inhibitory weakness quantified; conventional IgG1-clearance model unsupported; sources 10→11
- `wiki/index.md` — Bruhns2009 added to Sources table; citation-ranked table updated (1444 SS — now highest cited source in wiki); Methods 11→12; FcγRIIa 3→4; ADE 5→6; total pages 71→73

**Citation counts (retrieved 2026-04-13):** SS 1444 / CR 1303

**Notable Findings:** 1 entry added — FcγRIIa H131/R131 asymmetry is IgG2-specific; FcγRIIB affinity weakness quantified; both challenge the conventional IC-clearance model invoked in dengue.

---

## [2026-04-13] ingest | Li 2018 - Increased Risk of Autoimmune Diseases in Dengue

**Created:**
- `wiki/sources/Li2018 - Increased Risk of Autoimmune Diseases in Dengue.md`

**Updated:**
- `wiki/concepts/Autoimmunity in Dengue.md` — "Population-Level Autoimmune Disease Risk After Dengue" section expanded: Li2018 NHIRD cohort fully documented (aHR 1.88 overall; primary adrenocortical insufficiency n=19, aHR 2.05; ADEM aHR 3.80; GBS non-significant; TLR/adrenocortical mechanism); cross-study ADEM/GBS convergence with Shih2023 noted; Li2018 added to Sources list; sources 14→15
- `wiki/geography/Taiwan.md` — Li2018 NHIRD cohort section added; Contradictions section updated with ICD-coded vs. lab-confirmed methodological contrast; Related Pages and Sources updated; sources 2→3
- `wiki/analyses/Notable Findings.md` — new entry: ADEM cross-design convergence (Li2018 aHR 3.80, Shih2023 aHR 2.72) as most methodologically robust disease-specific finding; GBS null convergence noted; adrenocortical TLR mechanism flagged as unvalidated but novel; sources 9→10
- `wiki/index.md` — Li2018 added to Sources table; citation-ranked table updated; Autoimmunity in Dengue 14→15; Taiwan 2→3; total pages 70→71

**Citation counts (retrieved 2026-04-13):** SS 38 / CR 40

**Notable Findings:** 1 entry added — ADEM as the cross-design convergent finding (Li2018 × Shih2023); GBS null also convergent; adrenocortical TLR mechanism novel to wiki.

---

## [2026-04-13] ingest | Seet 2007 - Post-Infectious Fatigue Syndrome in Dengue

**Created:**
- `wiki/sources/Seet2007 - Post-Infectious Fatigue Syndrome in Dengue.md`
- `wiki/geography/Singapore.md` (new geography page)

**Updated:**
- `wiki/concepts/Post-Dengue Syndrome.md` — major addition: Seet2007 section with 24.4% fatigue rate, risk factor table, cross-cohort comparison table with Garcia2009; Contradictions expanded; Related Pages added Singapore and DENV-1; Sources updated (3→4)
- `wiki/concepts/Autoimmunity in Dengue.md` — new subsection: indirect evidence on sex-bias and severity-independence convergence with Garcia2009; Related Pages added Singapore and Seet2007 cross-reference; sources count unchanged (14, indirect link only)
- `wiki/entities/DENV-1.md` — Singapore 2005 outbreak section added (DEN-1 dominant, 20/27 typed); sources 1→2
- `wiki/entities/DENV-3.md` — Singapore 2005 section added (DEN-3 minor serotype, 6/27); sources 2→3
- `wiki/methods/IgM-IgG Serology ELISA.md` — Seet2007 added as source (double-sandwich capture ELISA, Innis 1989 protocol); sources 1→2
- `wiki/methods/RT-PCR.md` — Seet2007 added as source (Lanciotti 1992 nested PCR for serotyping); sources 1→2
- `wiki/index.md` — Seet2007 added to Sources table; Singapore added to Geography; counts updated throughout; total pages 68→70

**Citation counts (retrieved 2026-04-13):** SS 140 / CR 126

**Notable Findings:** No entry added — findings are directionally consistent with existing wiki content (severity-independence replicated; sex-bias confirmed); nothing rises to the "surprising given existing wiki" bar.

---

## [2026-04-14] infra | Citation counts in index + web workflow + commands.md

**Updated:**
- `wiki/index.md` — added `Citations (SS / CR)` column to Sources table; added ranked-by-citation subsection
- `wiki/commands.md` — new meta page; reference for all curator commands and terminal commands (build, preview, Cloudflare tunnel on port 1330)
- `wiki/index.md` — Meta section expanded to include commands.md; page count updated to 68
- `webforshare/quartz.config.ts` — baseUrl updated from localhost:8080 to localhost:1330
- `webforshare/HOW-TO-BUILD.md` — port updated; Cloudflare tunnel section added
- `webforshare/sync-and-build.ps1` — wiki source path corrected for new webforshare location (`../dengue-wiki/wiki`)
- `CLAUDE.md` — added `update web` workflow

---

## [2026-04-13] lint | Health check + structural fixes + new concept pages

**Lint findings (summary):**
- 0 broken wikilinks in content pages
- 0 orphan pages
- 2 source count discrepancies (fixed below)
- 17 thin pages (sources <= 1)
- 3 missing concept pages from CLAUDE.md domain context (2 created below; Herd Immunity deferred — no sources address it directly)
- Geography gaps persist: only 4 countries, no regional pages

**Fixed:**
1. `wiki/index.md`: Infection-Triggered Autoimmunity source count 5 → 6 (matched frontmatter)
2. `wiki/index.md`: Dengue Pathophysiology source count 1 → 2 (matched inline citation of Lin2006)
3. `wiki/concepts/Dengue Pathophysiology.md`: added `[[Lin2006]]` to Sources section; updated frontmatter `sources: 2`

**Created:**
- `wiki/concepts/Cross-Reactive Antibodies.md` — synthesises cross-reactive Ab biology across 5 sources (Guzman2016, Sungnak2025, Garcia2010, Lin2006, Lin2011); covers neutralising vs. enhancing threshold, isotype divergence (IgG1 vs. IgA), broadly neutralising Abs, CYD-TDV proof-of-concept, diagnostic cross-reactivity
- `wiki/concepts/Cytokine Storm.md` — synthesises cytokine-mediated pathogenesis across 4 sources (Sungnak2025, Wan2012, Guzman2016, Johnson2022); covers IL-10/TNF-alpha/IFN-alpha roles, NS1-TLR4 trigger, bystander activation, OAS amplification, temporal dynamics

**Updated:**
- `wiki/index.md` — added 2 new concept pages; updated concept count to 19; updated total page count to 67
- `wiki/concepts/Antibody-Dependent Enhancement.md` — added Related Pages links to Cross-Reactive Antibodies, Cytokine Storm
- `wiki/concepts/Dengue Pathophysiology.md` — added Related Pages links to Cytokine Storm, Cross-Reactive Antibodies
- `wiki/concepts/Secondary Dengue Infection.md` — added Related Pages links to Cross-Reactive Antibodies, Cytokine Storm
- `wiki/concepts/NS1 Molecular Mimicry in Dengue.md` — added Related Pages links to Cross-Reactive Antibodies, Cytokine Storm

---

## [2026-04-13] infra | Quartz static site setup in webforshare/

**Created:**
- `webforshare/` — Quartz v4 clone, configured as a static site for the wiki
- `webforshare/content/` — full mirror of `wiki/` (synced via cp)
- `webforshare/sync-and-build.ps1` — script to re-sync wiki → content and rebuild the site
- `webforshare/HOW-TO-BUILD.md` — setup and rebuild instructions for curator and colleagues

**Pending:**
- `npm install` inside `webforshare/` (requires Node.js LTS, install via `winget install OpenJS.NodeJS.LTS`)
- Hosting provider TBD; `baseUrl` in `quartz.config.ts` will be updated once chosen

---

## [2026-04-13] analysis | Wiki State and Gap Analysis 2026-04-13 + Notable Findings update

**Created:**
- `wiki/analyses/Wiki State and Gap Analysis 2026-04-13.md` — full state audit at 16 sources/65 pages; gap map against 2026-04-12 baseline; ANA thread status table; 6-priority ingest order; documents which 2026-04-12 priorities were addressed and which remain open

**Updated:**
- `wiki/analyses/Notable Findings.md` — added new entry: "NS1 molecular mimicry cannot explain the nuclear ANA — epitope spreading is the implied mechanism" (cross-cutting inference spanning Lin2006, Lin2011, Wan2012, Chatterjee2024, Johnson2022; visible only from synthesis)
- `wiki/index.md` — added new gap analysis; updated analyses count to 5; updated page count to 65

---

## [2026-04-13] analysis | ANA and Dengue — A Literature Review

**Created:**
- `wiki/analyses/ANA and Dengue - A Literature Review.md` — comprehensive synthesis of ANA dynamics in dengue across 15 sources; covers healthy-population baselines, acute dengue ANA (Chatterjee2024), generic viral-infection comparator (Berlin2007), three mechanistic pathways (molecular mimicry, bystander activation, epitope spreading), post-dengue persistence (Garcia2009), clinical outcome constraints (Shih2023), host modifiers (FcγRIIa, sex, prior infection), and 6 key open questions.

**Updated:**
- `wiki/index.md` — added analysis page entry; updated page count to 64

---

## [2026-04-13] schema | Added state.md and workflow updates

**Created:**
- `wiki/state.md` — persistent session context file tracking current focus, paper queue, structural decisions with rationale, and watch items

**Updated:**
- `CLAUDE.md` — added state.md to architecture diagram; added Session Start and Session End workflows; added state.md update steps to Ingest (step 12) and Lint (step 4) workflows; added proactive query compounding to Query workflow (step 5)
- `wiki/index.md` — added Meta section with state.md entry; updated page count to 63

**Rationale:** Inspired by Karpathy's LLM Wiki pattern (gist) and a community comment on `.brain` folders. Addresses context loss between sessions — priorities, queued work, structural decisions, and known issues now persist in a single file that every new session reads first.

---

## [2026-04-12] ingest | Chatterjee2024 - ANA Detection in Dengue Kolkata

**Created (3 pages):**
- `wiki/sources/Chatterjee2024 - ANA Detection in Dengue Kolkata.md` *(Chatterjee RP et al.; Virulence 2024; 135 lab-confirmed dengue patients; HEp-2 IIFA 54.8% vs. 10.3% controls; LIA 18.5%; MCTD and myositis significant; Kolkata India; doi:10.1080/21505594.2024.2400553)*
- `wiki/geography/India.md` *(new geography page; Kolkata hospital-based setting; endemic dengue context; 1997 WHO classification; predominantly IgM-confirmed cohort; endemic vs. epidemic distinctions)*
- `wiki/methods/Line Immunoassay ANA.md` *(new method page; LIA principle; 18 specific IgG autoantibody targets; IMTEC-ANA-LIA-XL; confirmatory test after IIFA; DFS70 exclusion marker; IIFA→LIA confirmation gap in dengue; disease association categorisation)*

**Updated (6 pages):**
- `wiki/concepts/Antinuclear Antibodies.md` — added Acute Dengue HEp-2 Gold Standard Data section (54.8% IIFA, 18.5% LIA, ~3:1 ratio); added Comparing ANA Rates Across Dengue Contexts table (Chatterjee2024/Berlin2007/Garcia2009 comparison); added Line Immunoassay ANA and India to Related Pages; added Chatterjee2024 to Sources. Sources 7→8.
- `wiki/concepts/Autoimmunity in Dengue.md` — added ANA in Acute Dengue section (Chatterjee2024 rates; MCTD/myositis findings with caveats); added MCTD/myositis vs. Shih2023 ADEM contradiction to Contradictions section; added India and Line Immunoassay ANA to Related Pages; added Chatterjee2024 to Sources. Sources 12→13.
- `wiki/methods/Indirect Immunofluorescence ANA Test.md` — added HEp-2 IIFA in Acute Dengue section (54.8% rate; IIFA→LIA gap; Immunoconcepts HEp-2000® kit); added Line Immunoassay ANA to Related Pages; added Chatterjee2024 to Sources. Sources 5→6.
- `wiki/analyses/Notable Findings.md` — added entry: "Dengue drives a massive acute ANA spike (55% by HEp-2 IIFA) — but two-thirds are non-specific" — the IIFA:LIA ratio reveals the scale and non-specificity of dengue-induced nuclear autoimmunity. Sources 7→8.
- `wiki/index.md` — added Chatterjee2024 source; added India geography; added Line Immunoassay ANA method; updated source count 14→15; updated concept/method/geography counts; updated total pages 60→66.
- `wiki/log.md` — this entry

**Context:** Chatterjee2024 is the first paper in the wiki to measure ANA in *acute* dengue using the gold-standard HEp-2 IIFA platform. Its most important contribution is not the absolute 54.8% rate (which is setting-specific and partly reflects HEp-2 sensitivity) but the IIFA→LIA gap: only ~34% of IIFA-positive dengue patients confirmed by LIA. This quantifies for the first time what the mechanistic literature suggested — dengue massively perturbs non-specific nuclear autoimmunity, but very little of this corresponds to the targeted specificities of established systemic autoimmune diseases. This is coherent with Shih2023's population-level null finding.

The MCTD/myositis signal is the paper's other key contribution. It diverges from Shih2023's ADEM signal, raising the possibility that dengue may have multiple narrow autoimmune sequelae (neurological → ADEM; rheumatological → MCTD/myositis) that appear in different study populations/settings. Both signals are hypothesis-generating rather than confirmed: Shih2023 is large but may lack power for rare rheumatological outcomes; Chatterjee2024 has wide CIs and a hospital-enriched sample. A definitive study would need Shih2023-scale population coverage with LIA-based outcome ascertainment.

Key cross-wiki connections:
- The 54.8% HEp-2 rate provides the missing platform-matched comparator for Garcia2009 (rat liver, 2 years) — substrate gap remains unresolvable but the magnitude difference is now quantified
- DFS70 exclusion marker methodology is now documented in the LIA method page — relevant to future ANA interpretation across all wiki sources
- The India geography page establishes that endemic-area hospital-based studies and non-endemic population-based studies may genuinely detect different autoimmune disease associations after dengue

---

## [2026-04-12] ingest | Shih2023 - Autoimmune Disease Risk After Dengue

**Created (3 pages):**
- `wiki/sources/Shih2023 - Autoimmune Disease Risk After Dengue.md` *(Shih H-I et al.; PLoS Negl Trop Dis 2023; 63,814 lab-confirmed dengue patients; Taiwan NHIRD+NDDCC; only ADEM elevated after dengue; doi:10.1371/journal.pntd.0011127)*
- `wiki/geography/Taiwan.md` *(new geography page; NHIRD coverage; epidemic history 2002–2015; 2014–2015 57K+ cases; NS1 RDT rollout 2015; NDDCC lab-confirmation system; 51.4% pre-2015 misclassification rate)*
- `wiki/concepts/Dengue Neurological Complications.md` *(new concept page; three neuropathogenesis pathways: encephalopathy/encephalitis/autoimmune; ADEM population-level risk [aHR 2.72, first month only]; GBS non-significant; DENV-2/3 CNS tropism; cross-flavivirus comparison)*

**Updated (9 pages):**
- `wiki/concepts/Autoimmunity in Dengue.md` — added Population-Level Autoimmune Disease Risk section (Shih2023: only ADEM survives Bonferroni; 51.4% misclassification in Li et al.); added new contradiction (Garcia2009 ANA elevation vs. Shih2023 no clinical disease); added Dengue Neurological Complications and Taiwan to Related Pages; added Shih2023 to Sources. Sources 11→12.
- `wiki/concepts/Infection-Triggered Autoimmunity.md` — added Population-Level Constraint section (Shih2023 ADEM finding; transient autoimmunity support); added biomarker-vs-disease contradiction; added Dengue Neurological Complications to Related Pages; added Shih2023 to Sources. Sources 5→6.
- `wiki/concepts/Post-Dengue Syndrome.md` — added Shih2023 section (ADEM only; autoimmune disease incidence not elevated long-term; Garcia2009 reconciliation); expanded Contradictions; added Dengue Neurological Complications and Taiwan to Related Pages; added Shih2023 to Sources. Sources 2→3.
- `wiki/entities/DENV-2.md` — added CNS Tropism and Neuropathogenesis section; added Dengue Neurological Complications to Related Pages; added Shih2023 to Sources. Sources 1→2.
- `wiki/entities/DENV-3.md` — added CNS Tropism and Neuropathogenesis section; added Dengue Neurological Complications to Related Pages; added Shih2023 to Sources. Sources 1→2.
- `wiki/methods/NS1 Antigen Detection.md` — added Epidemiological Impact section (51.4% pre-2015 confirmation gap; 2015 RDT rollout; methodological implications for clinical dengue cohorts); added Shih2023 to Sources. Sources 2→3.
- `wiki/analyses/Notable Findings.md` — added entry: "The prior 'dengue causes broad autoimmune disease' claim is largely an artifact of misclassification" — Shih2023 refutes Li et al. 2018 using 5× larger lab-confirmed cohort; 51.4% diagnostic accuracy problem has broad methodological implications. Sources 6→7.
- `wiki/index.md` — added Shih2023 source; added Dengue Neurological Complications concept; added Taiwan geography; updated source count 13→14; updated entity/concept/geography counts; updated total pages 55→60.
- `wiki/log.md` — this entry

**Context:** Shih2023 is methodologically the strongest paper ingested so far for the autoimmunity thread. It uses a larger, lab-confirmed cohort than any prior epidemiological study of post-dengue autoimmune disease, addresses multiple comparison problems explicitly (Bonferroni + Benjamini–Hochberg), and covers both inpatient and outpatient dengue. Its primary finding — that only ADEM is elevated after dengue, and only in the first month — substantially constrains the "dengue causes chronic autoimmunity" narrative that was supported primarily by case reports, the Garcia2009 Cuban cohort (autoimmune markers but not clinical diseases), and the Li et al. clinical cohort (shown here to have 51.4% misclassification). The Garcia2009 data (elevated ANA, IC, CRP at 2 years) remains unexplained by the Shih2023 population-level data, creating a productive new contradiction: biological autoimmune activation does not reliably produce clinical autoimmune disease.

Key cross-wiki connections:
- Shih2023's ADEM finding is directly consistent with the three-pathway neuropathogenesis model (Guzman2016 + Shih2023) — a new Dengue Neurological Complications page consolidates this content
- DENV-2 and DENV-3 CNS tropism is now documented on those entity pages
- The 51.4% misclassification rate contextualises NS1 Antigen Detection as epidemiologically transformative, not just diagnostically useful
- The notable finding entry extends the methodological lesson beyond dengue: clinical-diagnosis-only cohorts for post-infectious autoimmunity may systematically overestimate risk

---

---

## [2026-04-12] ingest | Guzman2016 - Dengue Infection (Nature Reviews Disease Primers)

**Created (16 pages):**
- `wiki/sources/Guzman2016 - Dengue Infection.md` *(Guzman MG, Gubler DJ, Izquierdo A, Martinez E, Halstead SB; doi:10.1038/nrdp.2016.55; comprehensive dengue Primer)*
- `wiki/entities/DENV-1.md` *(Cuban epidemic history; DENV1→DENV2 severity sequence; conditional virulence)*
- `wiki/entities/DENV-2.md` *(Asian vs American genotype; 1981 first Americas DHF; PDK-53 backbone; Santiago 1997)*
- `wiki/entities/DENV-3.md` *(displacement dynamics; Cuba 2001; Sri Lanka genotype changes)*
- `wiki/entities/Aedes albopictus.md` *(secondary vector; Europe/USA sporadic transmission; broader breeding sites)*
- `wiki/entities/CYD-TDV.md` *(ChimeriVax; phase III efficacy 56.5%/60.8%; 5× seronegative hospitalisation; approved 9–45 years; ADE mechanism)*
- `wiki/entities/E Protein.md` *(DI/DII/DIII domains; 90 monomers; DIII receptor binding; DII fusion loop; WGNGCG coagulation homology)*
- `wiki/entities/Wolbachia.md` *(wMel strain; cytoplasmic incompatibility spread; DENV replication suppression; field trials)*
- `wiki/concepts/Viraemia.md` *(timing 24–48h pre-fever; 5–6 days; diagnostic test windows; sNS1 severity correlation secondary; asymptomatic transmission)*
- `wiki/concepts/Dengue Pathophysiology.md` *(vascular permeability; NS1-TLR4; APTT strongest correlate; thrombocytopenia dual mechanism; coagulopathy; complement; liver Councilman bodies)*
- `wiki/concepts/Dengue Clinical Classification.md` *(2009 WHO 3 categories + 3 phases; warning signs; 1997 vs 2009 debate; diagnosis timeline; Zika cross-reactivity)*
- `wiki/concepts/Dengue Vaccine Candidates.md` *(challenge framing; CYD-TDV/DENVax/TV003/subunit/inactivated; Sungnak2025 NS-epitope T cell vaccine implications)*
- `wiki/concepts/Original Antigenic Sin.md` *(cross-reactive T cell memory dominance; OAS in secondary dengue; Sungnak2025 exhaustion markers consistent)*
- `wiki/methods/RT-PCR.md` *(DENV RNA detection; days 0–5; serotyping; qRT-PCR quantification; WHO tiered structure)*
- `wiki/methods/NS1 Antigen Detection.md` *(sNS1 ELISA + RDT; day 1–day 5–9; sensitivity by serotype/parity; sNS1 as pathogenic effector; Zika complications)*
- `wiki/methods/IgM-IgG Serology ELISA.md` *(MAC-ELISA; IgM from day 5–6; IgG seroconversion; primary vs secondary discrimination; Zika cross-reactivity)*

**Updated (11 pages):**
- `wiki/entities/NS1 Protein.md` — revised Overview (three structural forms); added Direct sNS1 pathogenic mechanisms section (TLR4, endothelial barrier, thrombin binding in vivo, glycocalyx shedding, APTT prolongation, diagnostic correlate); renamed Coagulation interference section to clarify antibody-mediated mechanism. Sources 2→3.
- `wiki/entities/Aedes aegypti.md` — added Vector biology section (extrinsic/intrinsic incubation; lifetime infectivity; blood meal timing); added Vector control programmes section (Cuba 1981; Singapore; Wolbachia; SIT). Sources 4→5.
- `wiki/entities/FcγRIIa Receptor.md` — added FCGR2A in broader host genetics landscape section (Table 2: HLA, IL-10, TNF, DCSIGN1, VDR). Sources 2→3.
- `wiki/entities/DENV-4.md` — added DENV-4 in Cuban serial serotype introduction section; 2006 Havana containment; 1981 Americas DHF significance. Sources 2→3.
- `wiki/concepts/Antibody-Dependent Enhancement.md` — added Conditional virulence section (primary infections subclinical; 3rd/4th mild; maternal antibody ADE; inter-infection interval risk; CYD-TDV clinical proof-of-concept; DI-DII broadly neutralising Abs). Sources 3→4.
- `wiki/concepts/NS1 Molecular Mimicry in Dengue.md` — added Direct sNS1 mechanisms section (TLR4; thrombin binding; endothelial barrier; glycocalyx; APTT); clarified relationship with anti-NS1 autoantibody pathway. Sources 2→3.
- `wiki/concepts/Asymptomatic Dengue Infection.md` — added Infection parity section (primary infections predominantly subclinical; 3rd/4th mild; Cuban 1981 overt:subclinical ratios; inverted U severity pattern). Sources 3→4.
- `wiki/concepts/Post-Dengue Syndrome.md` — major expansion: added 6-month QoL data (weakness 27.6%, headache 14.8%, arthralgia 10.6%); neurological complications (encephalopathy, encephalitis, GBS, transitory Parkinsonism, maculopathy); renal (AKI, GN, HUS); haematological (HLH). Sources 1→2.
- `wiki/concepts/T Cell Responses in Dengue.md` — added T cell biology from Guzman2016 section (NS protein epitope CD8; CD4 multifunctionality; OAS cross-reactive T cells; vaccine NS antigen implication). Sources 1→2.
- `wiki/concepts/Type I Interferon Response in Dengue.md` — added IFN-β and bone marrow suppression section (early febrile phase; LCMV analogy; comparison with Sungnak2025 IFN-α2). Sources 1→2.
- `wiki/geography/Cuba.md` — added 1997 Santiago DENV-2 epidemic (overt:subclinical; amino acid E protein change; month-by-month severity increase); Cuban vector control programme history (1981 launch; three pillars + space spraying; 30-year success; eventual failure); 2013 La Habana classification consensus (lethality decrease with 2009 WHO system). Sources 2→3.

**Notable Findings added (1):**
- APTT as strongest laboratory correlate of vascular permeability — connecting NS1-thrombin binding to plasma leakage via a shared sNS1 effector mechanism; implications for APTT as a prognostic biomarker superior to platelet count

**Updated:**
- `wiki/analyses/Notable Findings.md` — sources 5→6
- `wiki/index.md` — Sources 12→13, Entities 4→11, Concepts 10→15, Methods 7→10, Cuba sources 2→3; Total pages 39→55
- `wiki/log.md` — this entry

**Context:** Guzman2016 is a comprehensive dengue primer from five leading dengue researchers. It required new pages for 7 entities not previously in the wiki (DENV-1, DENV-2, DENV-3, Aedes albopictus, CYD-TDV, E Protein, Wolbachia), 5 new concepts central to dengue pathogenesis (Viraemia, Dengue Pathophysiology, Dengue Clinical Classification, Dengue Vaccine Candidates, Original Antigenic Sin), and 3 new method pages (RT-PCR, NS1 Antigen Detection, IgM/IgG Serology ELISA). The paper substantially deepens the wiki's dengue-specific content, which had previously been sourced mainly from autoimmunity-focused papers (Lin group, Garcia group, Sungnak2025). Key additions: the conditional virulence framing of ADE; the NS1 dual-pathway model (direct sNS1 + anti-NS1 autoantibodies); the APTT-vascular permeability mechanistic convergence; the CYD-TDV seronegative safety signal as clinical ADE proof-of-concept; and the comprehensive 2009 WHO clinical classification system.

---

## [2026-04-12] lint | Full wiki audit (post-Lin ingests)

**Issues found and fixed (8 total):**

**Wrong page count in index (1):**
- `index.md`: Total pages header read "41" but filesystem contains 39 files (12 sources + 4 entities + 10 concepts + 7 methods + 2 geography + 2 analyses + index + log = 39). Corrected 41 → 39. Root cause: Lin2006/Lin2011 ingest log entry overcounted; adding 4 pages to a pre-ingest count of 37 (itself slightly off) yielded 41 instead of 39.

**Missing source citations (3):**
- `PRNT`: Sungnak2025 used PRNT for primary/secondary infection classification in the DENFREE Thailand cohort (alongside HI assay), but was not listed as a source. Added. Sources 1→2; frontmatter updated; index PRNT sources 1→2.
- `Aedes aegypti`: Lin2006, Lin2011, and Sungnak2025 all list `[[Aedes aegypti]]` in their Entities Mentioned sections but were not reflected in the entity page's Sources list. Added all three. Sources 1→4; frontmatter updated; index Aedes aegypti sources 1→4.
- `Autoimmunity in Dengue`: Sungnak2025 is cited inline in the body (negative autoantibody finding: 120-antigen panel showed no significant differences across severity groups) but was missing from the Sources list at the bottom. Added. Sources 10→11; index count 10→11.

**Stale link annotation (1):**
- `Wiki State and Gap Analysis 2026-04-12`: Related Pages listed `[[NS1 Protein]] *(page not yet created)*`. NS1 Protein was created during the Lin2006/Lin2011 ingest on 2026-04-12. Updated note to reflect creation date.

**Missing connections (3):**
- `Thailand`: Did not link to `[[NK Cell Responses in Dengue]]` or `[[Type I Interferon Response in Dengue]]` despite both being major findings from the DENFREE Thailand cohort (Sungnak2025). Added to Related Pages.
- `Asymptomatic Dengue Infection`: Did not link to `[[qRT-PCR]]` despite qRT-PCR being the definitional method for identifying viremic asymptomatic dengue in Sungnak2025 (also already in Related Pages of `qRT-PCR`). Added to Related Pages.
- `Wiki State and Gap Analysis 2026-04-12` → `Notable Findings`: Notable Findings had no inbound links except from index.md (true orphan for analysis page). Added cross-link from the companion analysis page.

**Thin pages still present (acceptable at current wiki size):**
- `ELISA Inhibition Method` (1 source), `Post-Dengue Syndrome` (1 source), `T Cell Responses in Dengue` (1 source), `NK Cell Responses in Dengue` (1 source), `Type I Interferon Response in Dengue` (1 source), `Single-Cell RNA Sequencing` (1 source), `V(D)J Sequencing` (1 source), `qRT-PCR` (1 source), `Thailand` (1 source) — all thin because the wiki contains limited sources for each topic. To be expanded as review grows.

**Suggested gaps / future ingests:**
- A Bruhns et al. 2009 (*Blood*) ingest would resolve the flagged FcγRIIa/IgG1 binding contradiction in `FcγRIIa Receptor` and `Antibody-Dependent Enhancement`.
- DENV-1, DENV-2, DENV-3 entity pages are missing; Sungnak2025 references all three serotypes but they lack pages (note: DENV-2 was absent from that cohort). These stubs could be created pre-emptively.
- A second post-dengue cohort paper (e.g., Seet et al. 2007) would lift `Post-Dengue Syndrome` off its single-source dependency and allow geographic/serotype generalisation of the core claim.
- The `Aedes albopictus` vector is mentioned in the CLAUDE.md domain context but has no page and no source that discusses it; not currently a gap given the autoimmunity focus but worth noting for future vector-biology expansion.

---

## [2026-04-12] ingest | Lin2006 + Lin2011 — NS1 Molecular Mimicry Series (NCKU Taiwan)

**Created (4 pages):**
- `wiki/sources/Lin2006 - Autoimmune Pathogenesis in Dengue Virus Infection.md` *(review; anti-NS1 platelet IgM autoAbs; endothelial apoptosis + NF-κB inflammation; murine in vivo permeability and hepatitis-like effects; absorption experiments)*
- `wiki/sources/Lin2011 - Molecular Mimicry Virus Host Dengue Pathogenesis.md` *(minireview; NS1 molecular targets: PDI/vimentin/HSP60/ATP synthase β; C-terminal NS1 aa 311–352; WGNGCG E protein coagulation motif; flavivirus comparison; anti-prM/HSP60; acute-phase autoimmunity timing; virus-autoimmune disease catalogue)*
- `wiki/entities/NS1 Protein.md` *(new entity page; autoantigenic properties; C-terminal domain; platelet and endothelial targets; vaccine implications; IgM vs IgG anti-platelet debate)*
- `wiki/concepts/NS1 Molecular Mimicry in Dengue.md` *(new concept page; synthesis of both Lin papers; platelet effects; endothelial apoptosis + inflammation pathways; anti-prM; WGNGCG motif; acute-phase timing; contradictions)*

**Updated (4 pages):**
- `wiki/concepts/Autoimmunity in Dengue.md` — added NS1 Molecular Mimicry section with both Lin papers (PDI/vimentin/HSP60/ATP synthase β targets, C-terminal domain, WGNGCG motif, acute-phase timing); updated tags, sources 8→10; added NS1 Molecular Mimicry in Dengue and NS1 Protein to Related Pages
- `wiki/concepts/Infection-Triggered Autoimmunity.md` — added dengue NS1 as detailed molecular mimicry case study; added Lin2011 Table 1 virus-autoimmunity catalogue; updated tags, sources 3→5; added NS1 Molecular Mimicry in Dengue and NS1 Protein to Related Pages
- `wiki/index.md` — added 2 new sources, 1 new entity, 1 new concept; updated totals to Sources: 12, Pages: 41
- `wiki/log.md` — this entry

**Context:** These two NCKU Taiwan review papers directly fill the highest-priority gap identified in the 2026-04-12 wiki analysis: "Papers on dengue NS1 molecular mimicry (endothelial/platelet cross-reactivity) would directly connect Infection-Triggered Autoimmunity to dengue biology." Lin2006 establishes the autoantibody correlates and functional mechanisms (platelet lysis, endothelial apoptosis + inflammation); Lin2011 resolves the molecular targets (PDI, vimentin, HSP60, ATP synthase β) and the responsible NS1 domain (C-terminal aa 311–352). Together they make NS1 molecular mimicry the best-evidenced mechanism for the haemorrhagic syndrome in DHF/DSS, and establish dengue as a distinctive case of acute-phase (rather than post-infectious) virus-induced autoimmunity.

Key cross-wiki connections reinforced:
- Lin2006 anti-platelet IgM finding does not contradict Garcia2010 FcγRIIa/IgG findings — different isotypes, different phases/mechanisms
- Lin2011 cites Garcia2009 (as Garcia G et al. 2011) for post-dengue autoimmune syndrome, confirming NCKU group awareness of the Cuban cohort data
- WGNGCG flavivirus motif provides independent molecular support for haemorrhagic phenotype, complementing the NS1/platelet mechanism
- C-terminal NS1 domain mapping has direct implications for NS1-based vaccine design (epitope exclusion required to avoid autoimmune risk)

---

## [2026-04-12] ingest | Sungnak 2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue

**Created (8 pages):**
- `wiki/sources/Sungnak2025 - Distinct Immune Responses Asymptomatic Symptomatic Dengue.md`
- `wiki/methods/Single-Cell RNA Sequencing.md` *(new method page; scRNA-seq workflow, CITE-seq reference mapping, limitations for dengue)*
- `wiki/methods/V(D)J Sequencing.md` *(new method page; BCR/TCR repertoire, clonotype networks, IGHV4-39*01 public clonotype)*
- `wiki/methods/qRT-PCR.md` *(new method page; dengue viremia quantification, role in asymptomatic dengue identification)*
- `wiki/concepts/T Cell Responses in Dengue.md` *(new concept page; CD8 TEM effector vs. exhausted phenotypes, MAIT/iNKT, longitudinal clonal tracking)*
- `wiki/concepts/NK Cell Responses in Dengue.md` *(new concept page; FcεRIγ phenotype, NKG2D/NKp46 activating receptors, CD94 inhibitory receptor, NKG2D-MICB genetics link)*
- `wiki/concepts/Type I Interferon Response in Dengue.md` *(new concept page; IFN-α2 elevation in symptomatic dengue, ADE-IFN axis, pattern recognition receptors)*
- `wiki/geography/Thailand.md` *(new geography page; DENFREE cohort sites, serotype distribution, institutional context)*

**Updated (4 pages):**
- `wiki/concepts/Asymptomatic Dengue Infection.md` — major expansion: added entire single-cell immune profiling section from Sungnak2025 (cell composition, MHC-I presentation signals, CD8 TEM effector profile, IGHA1+ plasmablasts, NK phenotype); updated tags, sources count 2→3, updated date; added new related pages (Thailand, T Cell Responses, NK Cell Responses, Type I IFN, scRNA-seq)
- `wiki/concepts/Antibody-Dependent Enhancement.md` — added full section on transcriptomic ADE evidence (FcR/endocytosis pathway enrichment in DHF, IGHG1/IGHA1 isotype bias, public BCR clonotype, IL-10→plasmablast axis); updated tags, sources count 2→3, date; added contradictions note on correlational nature of transcriptomic evidence; added new related pages
- `wiki/index.md` — added Sungnak2025 source, 3 new concepts, 3 new methods, 1 new geography; updated totals to Sources: 10, Pages: 37
- `wiki/log.md` — this entry

**Context:** Sungnak2025 is a landmark paper — the first scRNA-seq study to include viremic asymptomatic dengue alongside symptomatic severity groups. It fundamentally advances the mechanistic understanding of protective vs. pathogenic immunity and is highly relevant to: (1) the asymptomatic dengue thread (protective immune correlates), (2) the ADE thread (transcriptomic evidence and IGHG1/IGHA1 isotype distinction), and (3) the autoimmunity thread (negative finding: no autoantibody differences between severity groups, no anti-IFN antibodies). The paper's vaccine implications — supporting CD8 T cell-targeting strategies and nonstructural protein inclusion — connect to TAK-003/TV-003 vs. CYD-TDV comparisons.

---

---

## [2026-04-12] analysis | Wiki State and Gap Analysis

**Created (1 page):**
- `wiki/analyses/Wiki State and Gap Analysis 2026-04-12.md`

**Updated (2 pages):**
- `wiki/index.md` — added Analyses section, updated total pages 27→28
- `wiki/log.md` — this entry

**Summary:** Curator-directed synthesis capturing the current research thread (dengue-associated autoimmunity, ANA persistence post-DENV-4) and six identified gap areas with specific paper recommendations. Priority ingest order: NS1 molecular mimicry → second post-dengue cohort → Bruhns et al. → post-dengue GBS → diagnostics review.

---

## [2026-04-11] ingest | Garcia 2009 - Long-term Clinical Symptoms Post-Dengue

**Created (10 pages — first ingest, bootstrapping wiki):**

- `wiki/sources/Garcia2009 - Long-term Clinical Symptoms Post-Dengue.md`
- `wiki/entities/DENV-4.md`
- `wiki/entities/FcγRIIa Receptor.md`
- `wiki/concepts/Post-Dengue Syndrome.md` *(dedicated page, curator request)*
- `wiki/concepts/Autoimmunity in Dengue.md`
- `wiki/concepts/Antibody-Dependent Enhancement.md`
- `wiki/methods/PRNT.md`
- `wiki/methods/ELISA Inhibition Method.md`
- `wiki/methods/FcγRIIa Genotyping.md`
- `wiki/geography/Cuba.md`
- `wiki/index.md` *(bootstrapped)*
- `wiki/log.md` *(bootstrapped)*

**Updated:** *(none — first ingest)*

---

## [2026-04-12] ingest | ANA Prevalence Series (5 papers: Tan1997, Satoh2012, Li2019, Aringer2019, Dinse2022)

**Created (7 pages):**
- `wiki/sources/Tan1997 - ANA Range in Healthy Individuals.md`
- `wiki/sources/Satoh2012 - ANA Prevalence in United States.md`
- `wiki/sources/Li2019 - ANA Epidemiology in Chinese Healthy Population.md`
- `wiki/sources/Aringer2019 - 2019 EULAR ACR SLE Classification Criteria.md`
- `wiki/sources/Dinse2022 - Increasing ANA Prevalence in United States.md`
- `wiki/concepts/Antinuclear Antibodies.md` *(new concept page; synthesises all 5 ANA papers + Garcia2009)*
- `wiki/methods/Indirect Immunofluorescence ANA Test.md` *(new method page)*

**Updated (3 pages):**
- `wiki/concepts/Autoimmunity in Dengue.md` — added ANA contextualisation section with healthy-population comparators from all 5 ANA papers; updated sources count to 6
- `wiki/index.md` — added 5 new sources, 1 new concept, 1 new method; updated total page count
- `wiki/log.md` — this entry

**Context:** These 5 papers provide healthy-population ANA baselines (at dilutions 1:40, 1:80, 1:100, 1:160, 1:320; in international, US, and Chinese populations; spanning 1988–2012) to contextualise the 23.1% ANA positivity reported in Garcia2009's post-dengue symptomatic cohort. The Dinse2022 paper notes an important publication history: originally published as art.41214 (2020), retracted due to NHANES data corrections by CDC (not author error), republished as art.42330 (2022); conclusions unchanged.

---

## [2026-04-11] ingest | Garcia 2010 - Asymptomatic Dengue FcγRIIa Polymorphism

**Created (3 pages):**
- `wiki/sources/Garcia2010 - Asymptomatic Dengue FcγRIIa Polymorphism.md`
- `wiki/concepts/Asymptomatic Dengue Infection.md` *(curator request)*
- `wiki/entities/Aedes aegypti.md` *(stub; background mention)*

**Updated (6 pages):**
- `wiki/entities/FcγRIIa Receptor.md` — added quantitative genotype/allele data, RR protective ORs, Havana population frequencies, Bruhns mechanism contradiction
- `wiki/concepts/Antibody-Dependent Enhancement.md` — added RR/HH mechanistic model and Bruhns et al. contradiction
- `wiki/geography/Cuba.md` — expanded epidemic history detail, added Havana FcγRIIa population frequencies
- `wiki/entities/DENV-4.md` — added Garcia2010 as second source using the same cohort
- `wiki/index.md` — added new source, new concept, new entity; updated source counts
- `wiki/log.md` — this entry

---

## [2026-04-12] ingest | ANA in Viral Infections Series (2 papers: Berlin2007, Johnson2022)

**Created (3 pages):**
- `wiki/sources/Berlin2007 - Autoantibodies in Nonautoimmune Individuals during Infections.md`
- `wiki/sources/Johnson2022 - Infectious Diseases Autoantibodies and Autoimmunity.md`
- `wiki/concepts/Infection-Triggered Autoimmunity.md` *(new concept page; synthesises Berlin2007, Johnson2022, Garcia2009)*

**Updated (4 pages):**
- `wiki/concepts/Autoimmunity in Dengue.md` — added section on viral-infection-triggered ANA (Berlin2007), mechanistic framework (Johnson2022); sources count updated 6→8; added Infection-Triggered Autoimmunity to Related Pages
- `wiki/concepts/Antinuclear Antibodies.md` — added section on ANA during acute infections (Berlin2007); sources count updated 6→7; added Infection-Triggered Autoimmunity to Related Pages
- `wiki/index.md` — added 2 new sources, 1 new concept; updated totals to Sources: 9, Pages: 27
- `wiki/log.md` — this entry

**Context:** Berlin2007 provides the critical cross-infection ANA comparator:

---

## [2026-04-12] lint | Full wiki audit

**Issues found and fixed (11 total):**

**Wrong links (3):**
- `Berlin2007` Entities Mentioned: removed spurious `[[Aedes aegypti]]` link (that vector has no connection to this paper)
- `Berlin2007` Methods Used: removed incorrect `[[ELISA Inhibition Method]]` link (that page is for dengue IgG inhibition ELISA; Berlin2007 uses Euroimmun ANA 8 Pro ELISA — no equivalent method page exists yet)
- `Johnson2022` Methods Used: removed incorrect `[[ELISA Inhibition Method]]` link (review paper; no dengue serology methods)

**Unlinked method (1):**
- `Garcia2009` Methods Used: linked plain-text ANA method to `[[Indirect Immunofluorescence ANA Test]]`; added inline note about rat liver tissue substrate

**Unflagged scientific contradiction — critical (1):**
- `Garcia2009` uses **rat liver tissue** as the IIF substrate (older, less sensitive than HEp-2). All healthy-population reference studies use HEp-2. This means the 23.1% post-dengue ANA rate is an underestimate; had HEp-2 been used the rate would be higher. Flagged in: `Indirect Immunofluorescence ANA Test` (Contradictions), `Autoimmunity in Dengue` (Contradictions), `Antinuclear Antibodies` (ANA in Post-Dengue Context)

**Thin method page (1):**
- `FcγRIIa Genotyping`: Garcia2010 uses the identical protocol but was not listed as a source; added finding summary and updated sources 1→2

**Duplicate line (1):**
- `Garcia2010`: duplicate `[[Antibody-Dependent Enhancement]]` entry in Concepts Addressed removed

**Missing connections (5):**
- `Post-Dengue Syndrome`: added `[[Antinuclear Antibodies]]` and `[[Infection-Triggered Autoimmunity]]` to Related Pages
- `DENV-4`: added `[[Autoimmunity in Dengue]]` to Related Pages
- `Cuba`: added `[[Autoimmunity in Dengue]]` to Related Pages
- `Antibody-Dependent Enhancement`: added `[[Infection-Triggered Autoimmunity]]` to Related Pages
- `index.md`: corrected `## Sources (7)` → `## Sources (9)` (heading was not updated after last ingest); corrected `FcγRIIa Genotyping` sources 1→2

**Thin pages still present (acceptable at current wiki size):**
- `PRNT` (1 source), `ELISA Inhibition Method` (1 source), `Post-Dengue Syndrome` (1 source), `Aedes aegypti` (1 source, stub) — all thin because only 2 dengue-specific source papers have been ingested; to be filled as review expands

**Suggested gaps / future ingests:**
- An ELISA page for specific-antigen ANA testing (e.g., ENA line blot, ELISA 8 Pro) would be needed to properly reference Berlin2007's method
- Post-dengue case series or prospective studies from other cohorts (non-Cuban, non-DENV-4) would resolve the thinness of Post-Dengue Syndrome
- Papers on dengue NS1 molecular mimicry (endothelial/platelet cross-reactivity) would directly connect `Infection-Triggered Autoimmunity` to dengue biology 21.7% ANA positive during acute viral infections (HAV/HBV/HCV) vs. 3.8% healthy blood donor controls (ELISA, ANA 8 Pro, 1:100). This closely matches Garcia2009's 23.1% post-dengue finding, raising the question of whether the dengue-associated elevation is a generic viral-infection phenomenon or dengue-specific. The transience evidence (20.5%→6.4% in acute vs. convalescent viral hepatitis) makes Garcia2009's 2-year persistence more significant. Johnson2022 provides the mechanistic framework — molecular mimicry, bystander activation, epitope spreading — with the notable finding that bystander activation from severe viral illness (COVID-19) does not significantly elevate ANA, implicating dengue-specific mechanisms (NS1 mimicry, FcγRIIa-driven IC persistence) as more likely explanations for the Garcia2009 ANA finding.

---

## [2026-04-12] lint | Wiki structure audit and cleanup

**Issues found and fixed:**
1. **Stray file removed:** `NS1 Protein.md` at project root (empty duplicate of `wiki/entities/NS1 Protein.md`)
2. **Broken wikilinks fixed (5 occurrences):** `[[IgM/IgG Serology ELISA]]` → `[[IgM-IgG Serology ELISA]]` in NS1 Antigen Detection, Guzman2016, RT-PCR, Dengue Clinical Classification, Viraemia
3. **Missing page created:** `[[Secondary Dengue Infection]]` — concept page with 4 sources (Guzman2016, Garcia2010, Sungnak2025, Lin2006); was linked from IgM-IgG Serology ELISA but had no page
4. **Page count corrected:** Index header said 66 pages; actual count is 60 (15 sources + 17 concepts + 11 entities + 11 methods + 4 geography + 2 analyses)

**Thin pages (≤1 source) — expected at current wiki size:**
- Entities: DENV-1, Aedes albopictus, CYD-TDV, Wolbachia
- Concepts: NK Cell Responses in Dengue, Dengue Pathophysiology, Dengue Clinical Classification, Original Antigenic Sin
- Methods: ELISA Inhibition Method, Single-Cell RNA Sequencing, V(D)J Sequencing, qRT-PCR, RT-PCR, IgM-IgG Serology ELISA, Line Immunoassay ANA
- Geography: Thailand, Taiwan, India

**No orphan pages found.** All pages have at least one inbound link.
**No stale cross-references found** (after fixes above).

---

## [2026-04-12] ingest | Wan2012 - Autoimmunity in Dengue Pathogenesis

**Source:** Wan SW et al. (2012) Autoimmunity in dengue pathogenesis. *J Formos Med Assoc* 112:3–11. DOI: 10.1016/j.jfma.2012.11.006
**Citations:** Semantic Scholar 92; CrossRef 77 (retrieved 2026-04-12)

**Created:**
- `wiki/sources/Wan2012 - Autoimmunity in Dengue Pathogenesis.md`

**Updated (7 pages):**
- `NS1 Protein`: added LYRIC mimicry, RGD structural mimicry, complement-mediated lysis protection; sources 3→4
- `NS1 Molecular Mimicry in Dengue`: added LYRIC/RGD/capsid mimicry targets, autoantibody kinetics section; sources 3→4
- `Antibody-Dependent Enhancement`: added intrinsic ADE section (IFN-I suppression, IL-10/Th2); sources 4→5
- `Autoimmunity in Dengue`: added autoantibody kinetics/temporal profile, dengue→SLE case reports, intrinsic ADE–autoimmunity link; sources 13→14
- `Dengue Vaccine Candidates`: added NS1 vaccine paradox section (protective + pathogenic); sources 2→3
- `Taiwan`: added epidemic history, age distribution, seasonal pattern; sources 1→2
- `Secondary Dengue Infection`: added Wan2012 as source; sources 4→5

**Notable Findings:** 1 entry added — intrinsic ADE as mechanistic link between viral enhancement and autoantibody production

**Index:** updated source count 15→16, total pages 61→62, source counts for 7 concept/entity pages
