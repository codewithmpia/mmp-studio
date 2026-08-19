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
| **Notaro** | 100% offline invoicing & quote app for freelancers and small businesses. | [App Store](https://apps.apple.com/app/notaro/id6802968660) | [Google Play](https://play.google.com/store/apps/details?id=com.mmp.notaro) |

## Live pages

Served at `https://<account>.github.io/mmp-studio/` (replace `<account>` with the
GitHub account/organization name once the repo is pushed):

- Notaro — landing: `/notaro/`
- Notaro — Privacy Policy: `/notaro/privacy.html`
- Notaro — Terms of Service (EULA): `/notaro/terms.html`

> The `/notaro/privacy.html` URL is the one to provide in App Store Connect and
> Google Play Console as the app's privacy policy link.

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
