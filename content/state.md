---
type: meta
updated: 2026-04-14
---



# Wiki State

Persistent operational context for the dengue literature review. Read this at the start of every session. Update it after every session.

---

## Current Focus

- Primary research thread: **autoimmunity in dengue / ANA dynamics** — the comprehensive literature review ([[ANA and Dengue - A Literature Review]]) is now complete. The thread is substantially developed; remaining gaps are (1) the acute-to-chronic ANA trajectory on HEp-2, (2) whether NS1 shares homology with nuclear antigens, (3) FcγRIIa-ANA correlation. Bos2025 (preprint, ingested 2026-04-14) provides the first kinetic data contextualising gap #1 indirectly: NS1-IgG waning (t½≈2.1y) suggests the NS1-mimicry component of ANA declines early, leaving the epitope-spreading component as the more durable contributor at 2 years (Garcia2009). The ANA trajectory on HEp-2 post-dengue (the acute-to-chronic decline) remains unmeasured in any wiki source.
- Secondary thread: **asymptomatic vs. symptomatic dengue** — host genetics (FcγRIIa), immune signatures, and what distinguishes silent from clinical infection. Only 2 sources (Garcia2010, Sungnak2025); under-developed relative to the autoimmunity thread.

## Queue

Papers waiting to be ingested (add new entries at the top):

*(none currently queued)*

**Bos2025 ingested 2026-04-14** — removed from queue.
**Li2018 ingested 2026-04-13** — removed from queue.
**Seet2007 ingested 2026-04-13** — removed from queue.

## Decisions

Structural and workflow decisions with rationale. Append-only.

### [2026-04-14] Bos2025 preprint ingested with explicit preprint warnings
**Decision:** Ingested Bos2025 (medRxiv preprint, doi: 10.1101/2025.08.11.25333449) with prominent PREPRINT warnings in the source page, all updated concept/entity pages, and the Notable Findings entry. Citation counts are 0/0 as expected for an unreviewed preprint.
**Rationale:** The paper contains the most detailed longitudinal antibody kinetics data in the wiki and fills important gaps (XR E-IgG trajectories, NS1-IgG waning kinetics, Nicaragua geography). However, preprint findings require explicit caveating because they have not undergone peer review. Mechanistic claims derived from these kinetics (especially ADE risk reframing) are treated as hypotheses, not established findings.

### [2026-04-14] "update web" workflow added; commands.md created; Cloudflare port set to 1330
**Decision:** Added `update web` as a curator command in CLAUDE.md — triggers sync-and-build.ps1 via Bash. Created `wiki/commands.md` as a permanent reference for all curator and terminal commands. Quartz preview and Cloudflare tunnel use port 1330 (`npx quartz build --serve --port 1330` + `cloudflared tunnel --url http://localhost:1330`). baseUrl in quartz.config.ts updated to localhost:1330.
**Rationale:** Curator needed a single-command web update workflow and a durable reference for all operational commands. Cloudflare tunnel enables public sharing without a permanent hosting provider.
**How to apply:** When curator says "update web", run sync-and-build.ps1 and report result.

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

- **Thin entity pages:** DENV-1, DENV-3, E Protein, Aedes albopictus, CYD-TDV, Wolbachia — all have only 1 source each
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
- **Geography and non-ANA content remain thin:** Only 4 countries; no Southeast Asia or Americas regional pages; vaccine and vector biology still largely derived from Guzman2016. Broadening into these areas would balance the wiki's coverage.
