MARLEV Trading Command Center — Build 10 PRIVATE CONNECTOR CLIENT
Build 10 is an incremental update from the user's Build 9 GitHub source.
CHANGED: Private endpoint auto-check on app opening, returning online, or foregrounding.
CHANGED: New valid private CSV data refreshes the daily scan and reports latest per-symbol dates.
UNCHANGED: Existing localStorage data, manual CSV imports, trade plans, public legacy sync, and manual trade execution.
IMPORTANT: This is CLIENT ONLY. It does NOT deploy an authenticated server, grant a login session, access private GitHub Actions artifacts, or provide live quotes. Cross-site cookie blocking may prevent browser-session authentication.
SECURITY: Never put EODHD keys, personal access tokens, or passwords in the app or public GitHub repository. A future private backend must handle authentication, CORS, data licensing, and authorization.
DEPLOY: Backup app data first. Upload six root files to existing GitHub Pages repository. Avoid deployment until ready to test. Roll back from Build 9 backup if needed.
