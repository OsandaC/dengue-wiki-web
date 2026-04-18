# Wiki Commands Reference

All commands used to operate, maintain, and serve the Dengue Literature Review Wiki.

---

## Curator Commands (say to Claude)

These are spoken commands that trigger defined workflows in CLAUDE.md.

| Command | What it does |
|---------|-------------|
| `ingest [filename]` | Reads a PDF, takes git snapshot, discusses 2-3 key takeaways, creates source + all linked pages, fetches citation counts, propagates Questions Raised to state.md Watch Items |
| `ingest --fast [filename]` | Same as `ingest` but skips the discussion step — use for bulk ingests or papers whose scope is already clear |
| `lint` or `health check` | Scans all pages in folder batches (sources → entities/concepts → methods/geography → analyses) for broken links, orphans, thin pages, missing connections, contradictions |
| `update web` | Syncs wiki → Quartz content folder and rebuilds the static site |
| `wrap up` or `that's all` | Updates `state.md`, index, and log before ending the session |
| `query [question]` | Answers a question by synthesising across wiki pages; may suggest saving the answer as an analysis page |
| `add a new category for [X]` | Creates a new subfolder axis under `wiki/` and updates CLAUDE.md |
| `add a notable finding` | Appends a flagged finding directly to `Notable Findings.md` |
| `retract [AuthorYear]` | Marks a source as retracted: adds warning banner to source page, flags all linked concept/entity/method pages with inline warnings, adds Watch Item to state.md, logs the retraction |
| `correct [AuthorYear] — [note]` | Same as `retract` but for corrections rather than full retractions — preserves the source page with a correction note |
| `update highlights` | Scans all wiki pages for `==highlights==` and `%%comments%%`, then overwrites `Curator Highlights.md` with the current snapshot grouped by page |

---

## Terminal Commands

### Build & Sync

Run from the `webforshare/` folder.

**Sync wiki files and rebuild the site (one command):**
```powershell
.\sync-and-build.ps1
```

**Build only (without re-syncing):**
```powershell
npx quartz build
```

---

### Preview Locally

Serves the site locally with live-rebuild on file changes:
```powershell
npx quartz build --serve
```

Then open: http://localhost:1313

---

### First-Time Setup

Install Node.js (if not already installed):
```powershell
winget install OpenJS.NodeJS.LTS
```

Then restart your terminal, and install Quartz dependencies from the `webforshare/` folder:
```powershell
npm install
```

---

## File Locations

| Path | Purpose |
|------|---------|
| `dengue-wiki/wiki/` | Source markdown files (edit here) |
| `webforshare/content/` | Synced copy for Quartz (do not edit directly) |
| `webforshare/public/` | Built static site (upload this to host) |
| `webforshare/sync-and-build.ps1` | Sync + build script |
| `webforshare/quartz.config.ts` | Site title, baseUrl, theme settings |
