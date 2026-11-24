# Hisab Kitab Premium

Personal finance tracker (PWA) — income, expenses, budget, goals, debts, bills, multi-currency, PIN lock, themes, reports.

## Files
- `index.html` — main app
- `style.css` — styles + themes
- `script.js` — full application logic
- `sw.js` — service worker (offline / PWA)
- `manifest.webmanifest` — installable app manifest

## How to publish (public)

### Option 1 — Netlify (easiest)
1. Go to https://app.netlify.com/drop
2. Drag this whole folder
3. Done → you get a public HTTPS link

### Option 2 — GitHub Pages
1. Create a new repo
2. Upload these 5 files to the root (or `/docs`)
3. Settings → Pages → Deploy from main branch
4. Site will be live on `https://username.github.io/repo-name/`

### Option 3 — Vercel / Cloudflare Pages
- Same: drag & drop the folder or connect Git

## Important notes
- Works fully offline after first load (service worker)
- Data stays in browser localStorage (private by design)
- Use **Backup** from Profile menu to download JSON
- HTTPS is required for install prompt + service worker
- Clear old cache if you updated files (or change version in `sw.js`)

## Version
Cache: `hisab-kitab-1.7`

Enjoy tracking your money ✨


## New in this build
- **Print / PDF report** — full statement (balance, categories, goals, transactions)
- **Download report** — HTML report file (open → Print → Save as PDF)
- **10 new Pro features** in Settings → Pro features dropdown:
  - Duplicate transaction
  - Quick date ranges (7d / 30d / month)
  - Merchant memory (autocomplete)
  - Compact list
  - Multi-select mode flag
  - Low savings-rate alert
  - Backup reminder badge
  - Strict privacy blur
  - Goal link flag
  - Heatmap hints flag


## Release notes (v337)
- Fixed quick templates (type tabs / entryType)
- Google Sign-In script only loads when Client ID is set
- Legacy optional buttons remain safe-guarded (no crash)
- Insights page render on nav
- Cache bust v337


## Power tools (Settings)
- Recurring transactions (auto apply by day)
- Split bill
- Weekly digest (Smart Insight)
- Share story card (PNG)
- Receipts gallery
- Tags analytics
- CSV export
- Setup checklist
- Keyboard shortcuts (`?`)
- Biometric availability check


## Product version
**Hisab Kitab One UI 9** (Android 17 / One UI style)
Internal: 9.0


## Version line
**HK 26.2 · Mint** — own product numbering (not One UI / iOS clone). Next: 26.3 or 27.0 · new codename.


## Version scheme
- **Current:** HK 1.7
- **While testing changes:** HK 1.8 Beta, HK 1.9 Beta, …
- **Final next major:** **HK 2**


Version **HK 1.7** shows only in Settings (update card) and What’s new / update popup — not in the app name or home brand.
