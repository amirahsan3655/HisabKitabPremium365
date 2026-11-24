# Hisab Kitab HK 2.0

Personal finance tracker (PWA) — income, expenses, budget, goals, debts, bills, wallets, subscriptions, multi-currency, PIN lock, themes, reports.

## What's new in HK 2.0
- Multiple wallets / accounts manager
- Subscriptions tracker
- Debt payoff planner (snowball & avalanche)
- Category budget alerts on dashboard
- Bill due browser notifications
- Spending heatmap (last ~6 weeks)
- Savings challenges
- Custom categories
- Bank CSV import templates
- Family share code (local snapshot export/import)
- Weekly WhatsApp-ready summary
- Editable exchange rates
- Full theme list (89 themes)

## Files
- `index.html` — main app
- `style.css` — styles + themes
- `script.js` — application logic
- `sw.js` — service worker (offline / PWA)
- `manifest.webmanifest` — installable app
- `version.json` — `2.0`

## Publish
1. Upload this whole folder (HTTPS required for PWA)
2. Netlify Drop / GitHub Pages / Vercel / Cloudflare Pages
3. Users: Settings → Check update after you deploy a new build

## Data
- Stored in browser localStorage (private by design)
- Use Backup from Profile / Settings
- Encrypted backup available in Power tools

## HK 2.0 tools
Settings → **HK 2.0 tools** dropdown, or Settings → Power tools:
Wallets, Subscriptions, Debt planner, Heatmap, Challenge, Categories, CSV templates, Family share, Weekly summary, Rates, Bill notifications.
