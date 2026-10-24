# Nexso Vault legal site

Static pages (no build step): `index.html`, `privacy.html`, `terms.html`, `delete-account.html`, `style.css`.
`privacy.html` and `terms.html` are generated from `docs/PRIVACY_POLICY.md` and `docs/TERMS_OF_SERVICE.md`; after legal review, update the HTML to match.

## Host it in 3 steps
1. **Finish content:** make sure the support@nexsolabs.com mailbox is monitored.
2. **Deploy this folder** (publish directory `web/legal`, no build command):
   - GitHub Pages: push the repo, Settings, Pages, deploy from a branch/GitHub Action serving `web/legal`; or
   - Cloudflare Pages / Netlify: connect the repo, build command empty, output directory `web/legal`.
3. **Check the URLs** load over HTTPS without login, then paste them into Play Console.

## URLs for Play Console (published at nexsolabs.github.io/nexsovault-legal)
| Play Console field | URL |
|---|---|
| Store listing / App content, Privacy policy | `https://nexsolabs.github.io/nexsovault-legal/privacy.html` |
| App content, Data safety, Account deletion URL | `https://nexsolabs.github.io/nexsovault-legal/delete-account.html` |
| Terms (optional, store listing website / in-app link) | `https://nexsolabs.github.io/nexsovault-legal/terms.html` |
