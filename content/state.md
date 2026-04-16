---
type: meta
updated: 2026-04-16 (post-deep-lint propagation sweep)
---



# Wiki State

Persistent operational context for the dengue literature review. Read this at the start of every session. Update it after every session.

---

## Current Focus

- Primary research thread: **autoimmunity in dengue / ANA dynamics** — the comprehensive literature review ([[ANA and Dengue - A Literature Review]]) is now complete. The thread is substantially developed; remaining gaps are (1) the acute-to-chronic ANA trajectory on HEp-2, (2) whether NS1 shares homology with nuclear antigens, (3) FcγRIIa-ANA correlation. Bos2025 (preprint, ingested 2026-04-14) provides the first kinetic data contextualising gap #1 indirectly. Morel2014/Palacios2016 (ingested 2026-04-15) add a new dimension: **ANA-negative dengue autoimmunity** via MAS/macrophage hyperactivation.
- **Thrombocytopenia mechanism sub-thread (new, 2026-04-15):** Oishi2003 (ingested 2026-04-15) + Lin2001 now together establish an infection-order-dependent bifurcation — IgM anti-platelet autoantibody in primary vs. anti-dengue IgG immune complex in secondary, with FcγRII bypassed at the platelet surface in secondary infection. This creates a documented paradox with Garcia2010's FcγRIIa-HH DHF risk (OR 10.56) that is unresolved in the literature. The thrombocytopenia sub-thread is now well-defined but has two specific gaps (see Watch Items).
- Secondary thread: **asymptomatic vs. symptomatic dengue** — host genetics (FcγRIIa), immune signatures, and what distinguishes silent from clinical infection. Only 2 sources (Garcia2010, Sungnak2025); under-developed relative to the autoimmunity thread.

## Queue

Papers waiting to be ingested (add new entries at the top):

*(none currently queued)*

**Oishi2003 ingested 2026-04-15** — removed from queue.
**Lin2001 ingested 2026-04-15** — removed from queue.
**Morel2014 ingested 2026-04-15** — removed from queue.
**Palacios2016 ingested 2026-04-15** — removed from queue.
**Bos2025 ingested 2026-04-14** — removed from queue.
**Li2018 ingested 2026-04-13** — removed from queue.
**Seet2007 ingested 2026-04-13** — removed from queue.

## Decisions

Structural and workflow decisions with rationale. Append-only.

### [2026-04-14] Lint run completed; Bos2025 ingest had 5 metadata/connectivity gaps
**Decision:** Lint identified and fixed 5 issues from the Bos2025 ingest: (1) index section header counts wrong (Sources 19→20, Geography 5→6); (2) ADE page frontmatter not updated (sources 6→7, updated date stale); (3) Seet2007 misclassified under Related Pages in Autoimmunity in Dengue rather than Sources; (4) Secondary Dengue Infection not updated with Bos2025 kinetics data; (5) IgM-IgG Serology ELISA page missing Bos2025 as source. Three issues flagged but not fixed: ELISA Inhibition Method attribution uncertain (needs PDF verification), Reading Plan orphan, Jhonson2022 filename typo (immutable raw/).
**Why:** Pattern: during Bos2025 ingest, the log correctly recorded what should happen (ADE 6→7, etc.) but some frontmatter edits and secondary-concept-page updates were not executed.
**How to apply:** After any ingest, cross-check the log's "Updated" list against every page listed in the source's "Concepts Addressed" and "Entities Mentioned" — both content AND frontmatter (sources count, updated date) must be consistent.

### [2026-04-14] "update web" requires clearing public/ when new geography folders are added
**Decision:** When a new geography page is added (or any new subdirectory), the Quartz build may fail with `ENOTEMPTY: directory not empty, rmdir public/geography`. Fix: `rm -rf public/` before running sync-and-build.ps1. The script itself does not clear the public directory; the Quartz incremental clean can fail on new subdirectories.
**Rationale:** Discovered during Bos2025 ingest when Nicaragua.md created the first new geography in a session with an existing public/ directory.
**How to apply:** If `update web` fails with an ENOTEMPTY error, run `rm -rf webforshare/public/` and retry.

### [2026-04-14] Bos2025 preprint ingested with explicit preprint warnings
**Decision:** Ingested Bos2025 (medRxiv preprint, doi: 10.1101/2025.08.11.25333449) with prominent PREPRINT warnings in the source page, all updated concept/entity pages, and the Notable Findings entry. Citation counts are 0/0 as expected for an unreviewed preprint.
**Rationale:** The paper contains the most detailed longitudinal antibody kinetics data in the wiki and fills important gaps (XR E-IgG trajectories, NS1-IgG waning kinetics, Nicaragua geography). However, preprint findings require explicit caveating because they have not undergone peer review. Mechanistic claims derived from these kinetics (especially ADE risk reframing) are treated as hypotheses, not established findings.

### [2026-04-16] Deep lint propagation sweep — recurring miss across 5 recent ingests
**Decision:** Second-pass lint identified that ~18 pages were named in source pages' Entities/Concepts/Methods sections of the last 5 ingests (Bos2025, Lin2001, Oishi2003, Morel2014, Palacios2016) but had not been visited to add the source to their own Sources lists. Fixed in this session: NS1 Protein 7→9, Autoimmunity 20→21, Cross-Reactive Abs 6→7, Secondary Dengue 7→9, Dengue Pathophysiology 2→5, ADE 7→8, Cytokine Storm 6→7, Vaccine Candidates 3→4, DENV-1 2→4, DENV-2 3→5, DENV-3 4→7, DENV-4 3→5, Aedes albopictus 1→2, IgM-IgG ELISA 3→7, NS1 Antigen 3→6, RT-PCR 2→3, Singapore 1→2. Also: Nicaragua orphan resolved (added to DENV-1, DENV-3, Cross-Reactive Antibodies Related Pages); Morel2014 erroneous DENV-1 entity link removed (paper does not specify serotype). Index per-page counts and frontmatter `updated:` dates synced.
**Why:** The previous lint (2026-04-15) verified single-page metadata consistency but did not perform the inverse check — for each source's outbound link list, has every target page added the source to its Sources? This pattern was already in feedback memory ("ingest secondary sources require full propagation") but the lint workflow did not enforce it systematically.
**How to apply:** Lint should run a per-source forward propagation check: for each new source page, programmatically enumerate all wikilinks under "Entities Mentioned," "Concepts Addressed," and "Methods Used"; then for each target page confirm the source appears in its Sources section AND that the frontmatter sources count was incremented. Missing entries are propagation gaps to fix.

### [2026-04-15] Lint run completed; Palacios2016 → Dengue Neurological Complications connection was the only missed update
**Decision:** Lint found 1 content gap (Dengue Neurological Complications missing Palacios2016 retinal vasculitis case) and 1 log typo (NS1 Protein "5→7" should be "6→7"). Fixed both. All other frontmatter counts, link targets, and orphan checks clean. The "stale" log.md links (`[[IgM/IgG Serology ELISA]]`, `[[Lin2006]]`) are inside backtick code spans — not live wikilinks in Obsidian; no fix needed.
**Why:** Palacios2016 was ingested with minimal updates (only index.md), but its source page listed Dengue Neurological Complications as a concept addressed. The retinal vasculitis case (Chang 2007, Singapore; immune complex deposition) was never propagated to that concept page.
**How to apply:** When ingesting a secondary source (letter, review with no original data), still audit every concept listed in "Concepts Addressed" and confirm the concept page was updated — not just the index.

### [2026-04-15] Lin2001 attribution correction propagated across wiki
**Decision:** Lin2001 (2001) is the original source for IgM anti-platelet autoantibody findings in dengue — not Lin2006 (2006), which confirms and mechanistically extends the 2001 finding. NS1 Protein and NS1 Molecular Mimicry in Dengue pages were corrected to credit Lin2001 as the origin, with Lin2006 explicitly repositioned as the downstream confirmation paper. All pages that referenced this finding now carry both citations with the correct priority.
**Why:** The attribution error was propagated from Lin2006/Lin2011/Wan2012 back-citing each other without surfacing the founding paper. Lin2001 precedes these by 5 years and contains the original flow-cytometry MFI data; Lin2006 adds complement-mediated lysis mechanism.
**How to apply:** When ingesting new papers that cite anti-platelet IgM in dengue, credit Lin2001 first, then Lin2006 for mechanism detail.

### [2026-04-15] Site deployed live; update web now includes git push
**Decision:** Site is live at https://dengue-wiki-web.pages.dev (Cloudflare Pages, GitHub repo OsandaC/dengue-wiki-web, branch v4). sync-and-build.ps1 now ends with `git add -A`, a timestamped commit, and `git push` — `update web` is a single end-to-end deploy command. Port numbers removed from commands.md; Cloudflare Tunnel section removed (superseded). baseUrl set to `dengue-wiki-web.pages.dev`.
**Rationale:** Site is now permanently hosted; no tunnel needed. Single-command deploy reduces friction.
**How to apply:** When curator says "update web", run sync-and-build.ps1 — it syncs, builds, commits, and pushes. Cloudflare redeploys automatically in ~1 minute.
**Note:** After Dependabot PRs are merged on GitHub, always run `npm install` in webforshare/ and push the updated package-lock.json before the next deploy, or Cloudflare's `npm ci` will fail with a lock file sync error.

### [2026-04-14] "update web" workflow added; commands.md created
**Decision:** Added `update web` as a curator command in CLAUDE.md — triggers sync-and-build.ps1 via Bash. Created `wiki/commands.md` as a permanent reference for all curator and terminal commands.
**Rationale:** Curator needed a single-command web update workflow and a durable reference for all operational commands. (Superseded by [2026-04-15] decision above for hosting details.)

### [2026-04-14] Citation counts added to index sources table
**Decision:** The index Sources table now includes a `Citations (SS / CR)` column, and a ranked-by-citation subsection is appended below it.
**Rationale:** Quick signal for paper influence and field weight without opening individual source pages.

### [2026-04-13] Quartz static site set up in webforshare/
**Decision:** `webforshare/` folder is at `Literature Review Dengue/webforshare/` (sibling of `dengue-wiki/`, not inside it). Contains a Quartz v4 static site generator. Wiki files are synced from `dengue-wiki/wiki/` into `webforshare/content/` via `sync-and-build.ps1`. Hosting provider not yet decided — baseUrl will be updated to the permanent Cloudflare domain once chosen.
**Rationale:** Colleagues need to browse the wiki without Obsidian. Quartz natively supports wikilinks, frontmatter, search, backlinks, and graph view — no changes to wiki source files required.

### [2026-04-13] ANA literature review completed; Notable Findings and Gap Analysis updated
**Decision:** Completed the ANA and Dengue literature review as a synthesis analysis page drawing on all 16 sources. Updated Notable Findings with one new synthetic entry (NS1 mimicry targets are not nuclear antigens → epitope spreading implied). Created Gap Analysis 2026-04-13 superseding the 2026-04-12 version with a full status audit.
**Rationale:** The ANA thread had enough source coverage to support a comprehensive review. The new Notable Finding (epitope spreading implication) was only visible from full-wiki synthesis — it does not appear in any individual source page — making it a genuine addition to knowledge rather than a restatement.

### [2026-04-13] Added Epistemic Honesty Principle to CLAUDE.md
**Decision:** Added a top-level section to CLAUDE.md codifying the "caring honesty" framework — suppress sycophancy signals, preserve warmth signals, apply the "respected colleague" heuristic for edge cases.
**Rationale:** The wiki serves the curator's understanding, not comfort. Methodological criticism must not be softened because the curator seems invested; praise must be specific, not generic. This governs all interactions: ingest discussions, query answers, lint reports.

### [2026-04-13] Added proactive query compounding to Query workflow
**Decision:** The Query workflow now proactively suggests saving non-trivial synthesis answers as wiki pages, rather than waiting for the curator to ask.
**Rationale:** Inspired by Karpathy's LLM Wiki pattern — valuable query synthesis should compound into the wiki just like ingested sources do. Prevents good analysis from disappearing into chat history.

### [2026-04-13] Added `wiki/state.md` as persistent session context
**Decision:** Created this file to track operational state (focus, queue, decisions, watch items) across sessions.
**Rationale:** `CLAUDE.md` documents the schema (stable), `log.md` tracks what happened (history), `index.md` catalogs content. None of them captured *current priorities, queued work, or the reasoning behind structural choices*. This file fills that gap so every new session starts with full context.

### [2026-04-12] Citation count fields added to source frontmatter
**Decision:** Source pages include `citations_semantic_scholar`, `citations_crossref`, and `citations_retrieved` fields fetched from APIs during ingest.
**Rationale:** Provides a rough proxy for paper influence. Two sources (Semantic Scholar + CrossRef) because neither is complete alone.

### [2026-04-12] Notable Findings as a single running page
**Decision:** `wiki/analyses/Notable Findings.md` is one append-only page, not a folder of individual findings.
**Rationale:** Keeps striking observations in one scannable list. The bar is deliberately high — surprising given existing wiki content, crosses multiple concepts, or challenges an existing claim. Most ingests produce zero or one entry.

## Watch Items

Issues, thin areas, or things to revisit. Remove items as they're resolved.

- **Thin entity pages (post-2026-04-16 propagation sweep):** CYD-TDV (1 source), Wolbachia (1 source). Aedes albopictus now 2 (Oishi2003 added — methodological role only); DENV-1 now 4; DENV-3 now 7; DENV-2 now 5; DENV-4 now 5 — no longer thin.
- **Thin method pages:** Several methods (Single-Cell RNA Sequencing, V(D)J Sequencing, qRT-PCR, ELISA Inhibition Method) have only 1 source
- **Geography gaps:** Only 4 countries covered (Cuba, Thailand, Taiwan, India). No Southeast Asia regional page, no Americas/Latin America page
- **Missing concept page:** Herd immunity — mentioned in CLAUDE.md domain context but no dedicated page yet; no sources directly address it. Cross-Reactive Antibodies and Cytokine Storm pages created 2026-04-13
- **ANA thread substantially complete:** The literature review, gap analysis, and notable findings are all current. The remaining ANA gaps are specific and well-defined (see [[Wiki State and Gap Analysis 2026-04-13]]). No further source ingestion is needed to consolidate the current thread — but a longitudinal HEp-2 cohort paper would be the single highest-value addition.
- **Potential page split:** [[Autoimmunity in Dengue]] now has 15 direct sources; mechanistic (NS1 mimicry, endothelial, platelet) vs. epidemiological (Li2018, Shih2023, Garcia2009) content may warrant splitting into acute mechanisms and population-level risk pages.
- **Li2018 ingest complete:** The adrenocortical insufficiency TLR mechanism and ADEM cross-design convergence are now documented. The adrenocortical finding remains unvalidated in any lab-confirmed study — a targeted search for dengue + adrenal + cortisol literature would clarify whether this signal is real.
- **Bruhns2009 ingest complete:** FcγRIIa Receptor Overview corrected — old "HH lower IgG1 affinity" claim refuted; H131/R131 difference is IgG2-specific (4.5×). FcγRIIB inhibitory deficit quantified. The mechanism linking HH genotype to worse dengue outcomes is now an open question — the IgG2 angle is the leading candidate. A search for anti-dengue IgG2 subclass distribution in secondary infection would directly test this.
- **FcγRIIa mechanism gap (new):** No study in this wiki directly measures anti-dengue IgG2 titres in primary vs. secondary infection with genotype stratification. This is the most direct experiment needed to determine whether the Bruhns IgG2-asymmetry is clinically relevant in dengue.
- **Post-Dengue Syndrome thread strengthened:** Now 4 sources; Seet2007 provides first non-Cuba cohort. Cross-cohort severity-independence finding is now the strongest structural claim on this page. Short follow-up gap (Seet2007 2 months vs Garcia2009 2 years) still unresolved — a 6-month or 1-year cohort paper would bridge this.
- **NS1 mimicry / nuclear ANA gap:** The new Notable Finding flags that NS1 mimicry cannot explain nuclear IIFA positivity; epitope spreading is the implied mechanism. No paper in this wiki directly tests this — a targeted literature search for dengue + epitope spreading + nuclear antigen would be productive.
- **Bos2025 preprint status:** Ingested 2026-04-14 as preprint. Track for peer-reviewed publication; revisit mechanistic claims (rising XR EDI/II IgG as ADE driver; IgM persistence at 18M) once peer-reviewed.
- **Rising XR E-IgG mechanism gap (new):** Bos2025 shows XR EDI/II IgG rises 6–18M post-primary, challenging the classical waning ADE model. Whether these rising antibodies are functionally non-neutralising (ADE-capable) vs. cross-neutralising is unknown. A functional ADE assay study stratifying by EDI/II vs EDIII antibody titres would directly test this.
- **NS1-IgG waning → autoantibody decline (new):** If NS1-IgG wanes with t½≈2.1 years (Bos2025), the NS1-mimicry component of dengue ANA should decline on a similar curve. No study in this wiki has measured anti-platelet / anti-endothelial autoantibody titres longitudinally (acute to 18M+) to test this prediction.
- **Nicaragua geography thin (new):** Only 1 source (Bos2025 preprint). Would benefit from a peer-reviewed Nicaraguan cohort study.
- **Geography and non-ANA content remain thin:** Now 8 countries (Cuba, Thailand, Taiwan, India, Singapore, Nicaragua, Paraguay, Philippines); no Southeast Asia or Americas regional pages; vaccine and vector biology still largely derived from Guzman2016. Singapore now 2 sources (Seet2007 + Palacios2016/Chang 2007 retinal vasculitis). Broadening into these areas would balance the wiki's coverage.

- **Propagation discipline (new, post-2026-04-16 deep lint):** The recurring miss of forward propagation from source → linked target pages has been documented in feedback memory and a fix workflow added to state.md decisions. Future ingests should be checked with a forward-propagation script before completion. Until automated, every ingest should be followed by a manual audit of every wikilink in the source page's Entities/Concepts/Methods sections — particularly for secondary sources (letters, reviews) where the propagation overhead is least proportional to the source's perceived weight.

- **Dengue-MAS mechanism gap (new):** No study in this wiki directly measures anti-endothelial cell Abs by flow cytometry (Wan2012 method) in dengue-MAS patients. Morel2014's MAS cases were ANA-negative, but it is unknown whether the Wan2012-type anti-endothelial Abs were also absent or elevated. A study measuring both standard ANA and flow cytometric anti-endothelial Abs in dengue patients across the full severity spectrum (DF, DHF, MAS) would clarify whether these represent truly separate immune effector mechanisms or a continuum.

- **Morel2014 SS citation gap:** Morel2014 is not indexed on Semantic Scholar at the English-edition DOI (10.1016/j.reumae.2014.03.008). The Spanish original may be indexed under a different DOI — worth a manual check if citation count is needed. CrossRef confirms 0 citations at the English-edition DOI.
- **ELISA Inhibition Method — verify Bos2025 attribution:** Bos2025 source page lists ELISA Inhibition Method under "Methods Used." The wiki's ELISA Inhibition Method page describes a specific Garcia2009/Vazquez 2003 yellow-fever-adapted competitive assay. Whether Bos2025 used the identical protocol or a different inhibition ELISA for cross-reactivity determination could not be verified from the wiki alone — verify against raw PDF if method accuracy matters.
- **Reading Plan orphan:** `Reading Plan - ANA and Dengue Dynamics` is only linked from index.md. No content page links back to it. Minor connectivity issue; acceptable for a meta/reference document.
- **Primary-infection DHF/DSS complement mechanism gap (new):** Lin2001 establishes that IgM anti-platelet autoantibodies arise in primary DENV-3 infection and that complement-mediated platelet lysis correlates with DHF/DSS severity. No wiki source tests whether complement pathway efficiency (C3/C4 levels, C1q polymorphisms, MBL status) predicts which primary infections progress to DHF/DSS. This is the most targeted experiment implied by the Lin2001 data.
- **NS1 Protein page — possible redundant bullet (minor):** After the Lin2001 attribution rewrite of the "Autoantigenic properties" section, there may be a legacy summary-level bullet that overlaps with the new detailed block. Review NS1 Protein page for redundancy if editing the section again.
- **Thrombocytopenia bifurcation — FcγRIIa paradox unresolved (new):** Oishi2003 shows FcγRII is not required for dengue-platelet binding in secondary infection. Yet Garcia2010 shows FcγRIIa-HH genotype has OR 10.56 for DHF. The mechanism linking FcγRIIa genotype to severity must operate via ADE viral uptake in monocytes/macrophages, not platelet destruction. No study in this wiki directly tests FcγRIIa genotype effects on PAIgG levels or platelet survival in secondary infection — this is the most direct experiment to resolve the paradox.
- **PAIgG-DHF correlation gap (new):** Oishi2003 was unable to stratify by disease severity (DF vs. DHF) due to insufficient hospitalisation time to assess vascular permeability. Whether PAIgG levels predict DHF severity within secondary infection — beyond their correlation with thrombocytopenia — remains untested.
- **Philippines geography thin (new):** Only 1 source (Oishi2003). Southeast Asia is substantially under-represented; the Philippines is one of the highest-burden dengue countries and merits additional source coverage.
