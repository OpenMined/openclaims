# OpenClaims

A public registry of verified AI evaluation claims.

Live at [openclaims.global](https://openclaims.global). Today the site is a single placeholder page in `public/`.

## Deploy

Every push to `main` deploys `public/` to the Cloudflare Pages project `openclaims` (`.github/workflows/deploy.yml`). The Cloudflare token is read from 1Password at run time by the OpenMined CI service account; nothing deploys from a laptop.
