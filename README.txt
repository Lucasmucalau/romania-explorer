ROMANIA EXPLORER – PWA (hosting-ready)

This package is a Progressive Web App (PWA) that can be installed on iPhone and Android after it is published on HTTPS.

CONTENTS
- index.html: application
- manifest.json: install metadata
- sw.js: offline cache/service worker
- icon-192.png and icon-512.png: app icons

INSTALL ON IPHONE (after publishing)
1. Open the published HTTPS website in Safari.
2. Tap Share.
3. Select Add to Home Screen.
4. Tap Add. Launch it from the new home-screen icon.

INSTALL ON ANDROID (after publishing)
1. Open the HTTPS website in Chrome.
2. Use the browser menu and choose Install app or Add to Home screen.

PUBLISH WITH GITHUB PAGES (free)
1. Create a GitHub account if needed.
2. Create a new public repository named romania-explorer.
3. Upload all files in this folder to the repository root (not the ZIP itself).
4. In repository Settings > Pages, set Build and deployment to Deploy from a branch.
5. Select branch main and folder /(root), then Save.
6. Wait for GitHub Pages to provide the HTTPS site URL.
7. Open that URL on your phone and install using the instructions above.

DATA AND PRIVACY
- Visits, notes, ratings, and photos are stored locally in the browser/device.
- Export backups regularly from the app.
- The included directory is currently a starter dataset and is not yet the complete verified 319 urban localities.
- CSV import format: header row "oras,judet", then rows, e.g. "Reșița,Caraș-Severin".
- The next dataset update should use the official SIRUTA/INS list and verify the 319 urban localities (103 municipalities including Bucharest + 216 towns).

This is a static app: no account or backend is required for the current local-save version.
