# erj-web-assets

Static web assets for King Jesus Ministry / El Rey Jesus, served via GitHub Pages.

## Structure

| Path | Purpose | Used by |
|---|---|---|
| `sf-login/` | Right-frame branding page for the Salesforce login screen | Salesforce Setup → My Domain → Authentication Configuration → Right Frame URL |

## GitHub Pages

This repo is published with GitHub Pages (Settings → Pages → Deploy from branch `main`, root folder).

Live URL pattern:

```
https://<account>.github.io/erj-web-assets/<folder>/
```

## Notes

- Pages in this repo are publicly accessible. Do not commit anything sensitive (credentials, API keys, internal data).
- Keep each asset self-contained (inline CSS/JS/images) where practical so pages have no external dependencies that can break.
- Changes to `main` deploy automatically within a couple of minutes.
