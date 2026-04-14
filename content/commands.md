# Wiki Commands Reference

All commands used to operate, maintain, and serve the Dengue Literature Review Wiki.

---

## Curator Commands (say to Claude)

These are spoken commands that trigger defined workflows in CLAUDE.md.

| Command | What it does |
|---------|-------------|
| `ingest [filename]` | Reads a PDF from `raw/`, discusses key takeaways, creates source + all linked pages, fetches citation counts |
| `lint` or `health check` | Scans all pages for broken links, orphans, thin pages, missing connections, contradictions |
| `update web` | Syncs wiki → Quartz content folder and rebuilds the static site |
| `wrap up` or `that's all` | Updates `state.md`, index, and log before ending the session |
| `query [question]` | Answers a question by synthesising across wiki pages; may suggest saving the answer as an analysis page |
| `add a new category for [X]` | Creates a new subfolder axis under `wiki/` and updates CLAUDE.md |
| `add a notable finding` | Appends a flagged finding directly to `Notable Findings.md` |

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

Serves the site on port 8888 with live-rebuild on file changes:
```powershell
npx quartz build --serve --port 8888
```

Then open: http://localhost:8888

---

### Expose to Public via Cloudflare Tunnel

Requires `cloudflared` installed. Run **while the local server is running**:
```powershell
cloudflared tunnel --url http://localhost:8888
```

Cloudflare will print a temporary public URL (e.g. `https://abc-xyz.trycloudflare.com`).

**Typical workflow for sharing:**
```powershell
# Terminal 1 — start local server
cd "C:/Users/user/Documents/Claude/Literature Review Dengue/webforshare"
npx quartz build --serve --port 8888

# Terminal 2 — open tunnel
cloudflared tunnel --url http://localhost:8888
```

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
