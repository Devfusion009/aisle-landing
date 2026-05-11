# aisle-landing

Marketing landing page for **Verse AI by Moovehub**. Next.js 16 (App Router) configured for static export.

## Develop

```bash
npm install
npm run dev
```

Dev server runs at http://localhost:3000.

## Build

```bash
npm run build
```

`next.config.ts` sets `output: 'export'`, so the build emits a fully static site to `out/` — drop those files behind any static host (S3, Nginx, Cloudflare Pages, etc.). No Node runtime is needed to serve it.
