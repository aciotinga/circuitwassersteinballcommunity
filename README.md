# Circuit Wasserstein Ball Community

Static demo site for [circuitwassersteinballcommunity.xyz](https://circuitwassersteinballcommunity.xyz), deployed on Cloudflare Pages.

- Production: https://circuitwassersteinballcommunity.pages.dev
- Custom domains: `circuitwassersteinballcommunity.xyz`, `www.circuitwassersteinballcommunity.xyz`

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
npx --yes serve .
```

## Deploy

Manual:

```bash
npx wrangler pages deploy . --project-name=circuitwassersteinballcommunity --branch=main
```

GitHub Actions (`.github/workflows/deploy-pages.yml`) deploys on push to `main` when these repository secrets are set:

- `CLOUDFLARE_API_TOKEN` — token with **Account → Cloudflare Pages → Edit**
- `CLOUDFLARE_ACCOUNT_ID` — `9f66fbed1762396be278d02bd7bf1e78`
