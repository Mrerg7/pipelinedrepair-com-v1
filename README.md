# pipelinedrepair.com

Premium single-name acquisition site for **pipelinedrepair.com**. Astro 7 + Tailwind CSS 4, deployed as **Cloudflare Workers Static Assets** (free plan, no adapter).

## Stack

- Astro 7 (static output)
- Tailwind CSS 4 via `@tailwindcss/vite`
- `@astrojs/sitemap`
- Existing Cloudflare Images emblem (reused, not replaced)
- Open Graph, Twitter card, JSON-LD (Organization, WebSite, Product/Offer)
- `robots.txt`, generated sitemap, canonical URL
- `public/_headers` for basic security headers

## Local development

```bash
npm install
npm run dev
```

## Build & deploy

```bash
npm run build
npm run deploy
```

`wrangler.toml` stays assets-only:

```toml
[assets]
directory = "./dist"
```

Production: https://pipelinedrepair.com

Inquiries: sales@desertrich.com

Price is a private offer. Do not publish a number on the page.

## Changelog

See [CHANGELOG.md](./CHANGELOG.md).
