# DASCREATES Portfolio

A responsive React + TypeScript + Vite portfolio for Tarini Das / DASCREATES. The supplied portrait and Instagram Insights screenshot are included in `public/assets/`.

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

The production output is generated in `dist/` and can be deployed to Vercel, Netlify, Cloudflare Pages or any static host.

## Enable inquiry form

1. Create a form at [Formspree](https://formspree.io/).
2. Copy its endpoint (for example `https://formspree.io/f/xxxxxxxx`).
3. Set the environment variable `VITE_FORMSPREE_ENDPOINT` in your deployment dashboard, or create a local `.env` file based on `.env.example`.
4. Rebuild and redeploy. Until configured, the form intentionally displays a setup notice instead of pretending a message was sent.

## Before publishing

- Replace `YOUR_EMAIL@example.com` in `src/App.tsx` with the business email.
- Replace YouTube and LinkedIn `href="#"` placeholders with real profile URLs.
- Add individual Reel Insights screenshots if you want post-level evidence, and verify any timing claims separately.
- Add approved project images and detailed case-study material as available. The other project tiles are clearly presented as work summaries rather than fabricated client case studies.

## Evidence notes

The supplied account Insights image visibly reports 24,534,191 total views, 23,868,549 Instagram views, 665,642 Facebook views and 14,719,121 viewers for the selected last-90-days period. It also displays selected top Reel thumbnails at 19.8M, 1.9M and 1.4M views. The website uses those visible values and explicitly notes that individual post-level screenshots were not supplied.
