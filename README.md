# MMP Studio

Marketing websites and legal pages for the applications published by **MMP Studio**,
hosted with **GitHub Pages**.

Each app lives in its own folder (a self-contained static site: landing page,
Privacy Policy and Terms of Service / EULA). All pages use **relative links** and
**self-hosted fonts**, so every site works from any sub-path with no external
dependencies.

## Apps

| App | Description | App Store | Google Play |
|-----|-------------|-----------|-------------|
| **Notaro** | 100% offline invoicing & quote app for freelancers and small businesses. | [App Store](https://apps.apple.com/fr/app/notaro-devis-factures/id6802968660) | _Coming soon_ |
| **Skanzo** | 100% offline barcode scanner & stock inventory app for shops and warehouses. | [App Store](https://apps.apple.com/fr/app/skanzo-inventaire-scan/id6804024920) | _Coming soon_ |
| **LeafPulse** | 100% offline smart plant care journal & calculated watering reminders. | [App Store](https://apps.apple.com/fr/app/leafpulse-arrosage-plantes/id6805659559) | _Coming soon_ |
| **ChronoPace** | 100% offline haptic, audio & visual running cadence metronome (SPM). | [App Store](https://apps.apple.com/fr/app/chronopace-cadence-running/id6806511004) | _Coming soon_ |
| **TeleStudio** | 100% offline 4K 60 FPS studio teleprompter with AI voice tracking & Duo Remote. | [App Store](https://apps.apple.com/app/telestudio/id6742398511) | _Coming soon_ |


## Live pages

Served at `https://<account>.github.io/mmp-studio/` (replace `<account>` with the
GitHub account/organization name once the repo is pushed):

- Notaro — landing: `/notaro/`
- Notaro — Privacy Policy: `/notaro/privacy.html`
- Notaro — Terms of Service (EULA): `/notaro/terms.html`
- Skanzo — landing: `/skanzo/`
- Skanzo — Privacy Policy: `/skanzo/privacy.html`
- Skanzo — Terms of Service (EULA): `/skanzo/terms.html`
- LeafPulse — Privacy Policy: `/leafpulse/privacy.html`
- LeafPulse — Terms of Service (EULA): `/leafpulse/terms.html`
- ChronoPace — landing: `/chronopace/`
- ChronoPace — Privacy Policy: `/chronopace/privacy.html`
- ChronoPace — Terms of Service (EULA): `/chronopace/terms.html`
- TeleStudio — landing: `/telestudio/`
- TeleStudio — Privacy Policy: `/telestudio/privacy.html`
- TeleStudio — Terms of Service (EULA): `/telestudio/terms.html`
- TeleStudio — Support: `/telestudio/support.html`

> The `/notaro/privacy.html`, `/skanzo/privacy.html`, `/leafpulse/privacy.html`, `/chronopace/privacy.html`, and
> `/telestudio/privacy.html` URLs are the ones to provide in App Store Connect and Google
> Play Console as each app's privacy policy link.

## Deploying

GitHub Pages is served from the `main` branch, root folder (`/`):

1. **Settings → Pages → Source:** Branch `main`, folder `/ (root)`.
2. The site goes live at `https://<account>.github.io/mmp-studio/` within ~1 minute.

## Adding a new app

1. Create a folder named after the app (e.g. `myapp/`).
2. Add `index.html` (+ optional `privacy.html`, `terms.html`) and assets inside it.
3. Use **relative paths only** (`./…`) so the site works under its sub-path.
4. Add a row to the **Apps** table above.

## License

Proprietary — see [`LICENSE`](./LICENSE). All content and brand assets are
© 2026 MMP Studio, all rights reserved.
