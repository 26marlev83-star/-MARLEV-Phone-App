MARLEV Trading Command Center — Build 8

Upload all six files to the existing public GitHub Pages repository root. Preserve filenames. App shell updates via service worker.

Automatic sync: Data tab > Automatic CSV sync > enter PUBLIC HTTPS CSV URL without any secrets, save, then Sync now. Endpoint must support CORS and CSV columns Symbol,Date,Open,High,Low,Close,Volume with >=50 rows per symbol. App checks when opened, returned to foreground, or online. No background jobs or push notifications.

No endpoint is bundled: configure a validated source and ensure legal data redistribution. Do NOT publish API keys, trading records, or credentials. Private GitHub Actions artifact URLs do not work as public CORS CSV endpoints.

All existing data uses the same localStorage key; export a backup before updating. Existing plans/scans remain in place. The app never places orders.
