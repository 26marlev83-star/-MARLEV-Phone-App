MARLEV Trading Command Center Build 7 — installable web app.

DEPLOYMENT:
1. Create a NEW public GitHub repository (suggested: marlev-phone-app). Do not use the private trading backend repository.
2. Upload all five files from this ZIP to the repository ROOT (not inside a folder): index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png.
3. Repository Settings > Pages > Deploy from a branch > main > /(root) > Save.
4. Wait for the Pages URL, open it in Android Chrome, menu > Add to Home screen > Install.

SECURITY: Public GitHub Pages makes frontend source public. No API keys or personal data should be committed. This app only uses locally imported data and local browser storage; no live data feed, notifications, or orders. Local browser data may not transfer from the old downloaded HTML file to the hosted site: export/import a backup if needed. Service worker caches only app shell, not CSV or user data.
