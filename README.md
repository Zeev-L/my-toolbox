# 🧰 Zeev's Toolbox

A bilingual (Hebrew / English) landing page for the tools I install on a fresh machine, plus a live view of my public GitHub repositories.

**Live:** https://zeev-l.github.io/my-toolbox/

## What's inside
- **Tools tab** — a card per tool I install (from my setup doc), each with a description, platform badges, a link to its repo, a one-click **Copy install prompt** button (copies the exact text to paste into Claude Code), and expandable install steps.
- **Repositories tab** — all my public repos, pulled **live** from the GitHub API (always up to date), with search and sort.

## Tech
Single static `index.html` — no build, no dependencies. Bilingual with full RTL/LTR switching, light/dark theme. Hosted on GitHub Pages.

## Run locally
Just open `index.html` in a browser, or serve the folder:
```bash
python3 -m http.server 8022
```

---
Built with [Claude Code](https://claude.com/claude-code).
