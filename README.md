# Perks Vault

A single-file browser-based tracker for potential credit-card, subscription, and membership perks.

## Publish on GitHub Pages

1. This public repository already exists at `APEX-SOLUTIONS-LIVE/Perk-tracker`.
2. The privacy-safe `index.html` and this README have already been uploaded to the `main` branch.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, then choose `main`, `/(root)` and **Save**.
5. GitHub will show the live URL in Pages settings after a successful deployment.

For this repo `APEX-SOLUTIONS-LIVE/Perk-tracker`, the expected site URL is `https://apex-solutions-live.github.io/Perk-tracker/`. This is only a pattern, **not proof the site is published**.

## Privacy

- Do **not** commit `Passwords.csv`, exported password ZIPs, `Perks_Vault_Gmail_Starter.json`, other personal JSON/CSV backups, account lists, receipts, or any personal data to GitHub.
- This app contains no preloaded personal accounts, no external script dependencies, and no network calls to transmit imported or entered data. A strict Content Security Policy blocks network requests from the app.
- Data is stored in that browser's `localStorage`; it is **not encrypted** and does **not sync** to your other browsers/devices.
- Hosting is public, so the page and code are visible to anyone. GitHub may collect ordinary website traffic data.
- Browser storage can be cleared by the operating system, user action, or private browsing. Use **Backup & privacy → Export JSON** regularly and store backups privately.
- For safer onboarding, manually add companies instead of exporting a full password vault. If you choose an Apple password CSV export, only open it in your own trusted browser, select websites, and promptly delete both the plaintext CSV and original ZIP.
- The tool does not sign into accounts, verify memberships automatically, or run background checks. Benefit suggestions are leads, not confirmed entitlements.

## iPhone home screen

Open the live site in **Safari**, use **Share → Add to Home Screen → Add**. This is simpler than building a Shortcut. If you prefer a Shortcut, create a shortcut with a URL action pointing to the site and an Open URLs action.

## Technical

No build tools, packages, environment variables, secrets, database, or custom domain are required. The entire application is in `index.html`.