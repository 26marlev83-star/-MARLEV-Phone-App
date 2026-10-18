MARLEV Trading Command Center — Build 9 PRIVATE CONNECTOR PREVIEW

This is a SEPARATE TEST BUILD based on your uploaded Build 8.

INCLUDED: index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png, README.txt

WHAT CHANGED
- New private connector preview on the Data tab.
- Only the endpoint address is stored; never enter keys, tokens, passwords, or signed URLs.
- Future authenticated service must implement login/session cookies, HTTPS, credentialed CORS and legally authorized CSV delivery.
- A failed private sync leaves existing candles untouched.
- Existing CSV importer, scanner, risk settings, plans and JSON backup retained.
- Corrected stale Build 5 safety text.
- Updated service-worker cache to Build 9.

NOT YET IMPLEMENTED
- No authenticated backend or provider redistribution authorization has been established.
- No real-time exchange verification, push alerts, scheduled background updates or order execution.
- Do not treat scores as buy/sell signals.

INSTALLATION / TESTING
1. Keep Build 8 and your downloaded JSON backup.
2. Test Build 9 separately before uploading to your existing GitHub Pages repository.
3. If later deploying over Build 8, upload the six files to the existing repository root with unchanged filenames, then refresh/reopen the PWA.
4. Do NOT enter your EODHD API token in any app field.
5. Existing local records use the same storage key, but browser origin/storage changes can make them unavailable; retain your backup.
