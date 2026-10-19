POCKET LEDGER — iPHONE / INSTALLABLE WEB APP

Files in this folder:
- index.html: the tracker app
- manifest.webmanifest: app name and install settings
- sw.js: offline caching after first load
- icons/: app icons for iPhone and browsers

IMPORTANT
The app needs to be served from an HTTPS website to install as a Home Screen web app and use its offline caching. Do not open index.html only as a local file and expect service workers to work.

Easy free route (GitHub Pages):
1. Create/sign in to a GitHub account.
2. Create a NEW PUBLIC repository named pocket-ledger-app.
3. Upload all files from this folder to the repository root (index.html must be at the root; include manifest.webmanifest, sw.js, and the icons folder).
4. In the repository, open Settings → Pages.
5. Under Build and deployment, choose Deploy from a branch, branch main, folder /(root), then Save.
6. Wait for the published website URL to appear on the Pages screen. GitHub Pages publishes the app code publicly. The app code contains no transactions; do NOT upload your private expense backup JSON or CSV file to GitHub.
7. On your iPhone, open the published URL in Safari. Tap Share → Add to Home Screen. If shown, enable Open as Web App, then tap Add.
8. Open Pocket Ledger from the new Home Screen icon and use that same icon consistently. Add a test transaction, close and reopen it to confirm storage works, then set up your real records.

PRIVACY AND BACKUPS
Transactions are stored locally in the browser/web app on that device and are not sent to the hosting service. They do not automatically sync between your iPhone and computer. In Settings & backups, export JSON regularly. Keep that backup private. If you clear website data or remove/reset the web app, local records may be lost. Importing a JSON backup into another device can transfer your data manually.

AI NOTE
Quick text entry uses an on-device lightweight parser, not a connected AI model. It costs nothing but can misread ambiguous descriptions; review every suggested entry before saving.
