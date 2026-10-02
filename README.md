# Cash Ledger (PWA)

Offline cash ledger. Data is stored on the device (localStorage), nothing is sent anywhere.

## Publish on GitHub Pages
1. Create a new repo and upload everything in this folder (keep the `icons/` folder).
2. Repo Settings > Pages > Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`.
3. Open `https://<your-username>.github.io/<repo>/` on your phone.

## Install
- Android (Chrome): menu > Install app.
- iPhone (Safari): Share > Add to Home Screen.

After changing files, bump `CACHE` in `sw.js` (e.g. `cash-ledger-v2`) so installed copies update.
