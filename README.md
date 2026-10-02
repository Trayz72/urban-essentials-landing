# Urban Essentials — Landing Page Demo

A standalone, static landing page for Urban Essentials — no Shopify, no backend,
no environment variables. Built to be deployed anywhere in minutes for demo purposes.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

Outputs a fully static site to `dist/`.

## Deploy on Render

1. Push this repo to GitHub (already done if you're reading this from the repo).
2. On [Render](https://render.com), click **New → Static Site**.
3. Connect this GitHub repo.
4. Settings:
   - **Build Command:** `npm install && npm run build`
   - **Publish Directory:** `dist`
5. Deploy — Render gives you a live `*.onrender.com` URL automatically.

No environment variables or backend services are required.
