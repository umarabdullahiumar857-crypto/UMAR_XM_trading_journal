UMAR XM™ Trading Journal V3
===========================

FILES
- index.html: upgraded mobile-first journal
- manifest.webmanifest: installable PWA metadata
- sw.js: offline cache
- icon-192.png and icon-512.png: clean app icons

FEATURES
- Redesigned mobile-first dashboard
- Net P/L, win rate, total trades, average planned R:R, gross profit/loss, profit factor, best trade
- Trade history, search, result filter, CSV export
- Trade entry/exit prices and APA + SMC notes
- Local storage, JSON backup/restore, optional chart screenshot
- PWA manifest and offline caching
- Attempts to migrate existing V1 trades from localStorage key umar_xm_trading_journal_v1

IMPORTANT
- This version DOES NOT automatically connect to MT5. MT5 Android does not expose a standard direct interface for a normal website to read trades.
- Records are saved locally in the browser/device. Cloud sync is not included in this ZIP.
- Keep a JSON backup before replacing your deployed files.
- To update the existing GitHub Pages site, upload/replace index.html, manifest.webmanifest, sw.js, icon-192.png, and icon-512.png in the existing repository. Keep the repository and Pages URL unchanged.
- After deployment, open the site in Chrome and refresh. If an old version remains, close the installed app, clear that site's cached files or wait for service worker update, then reopen.
