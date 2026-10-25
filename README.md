# facundosarina.github.io

Personal site — legal operations and process automation.

Live at **https://facundosarina.github.io**

## Contents

- `/` — who I am and what I have built
- `/deadline-control/` — case study: automating procedural deadline control for a labour-law firm,
  reading the Buenos Aires judiciary's filing portal. 404 cases audited, 11 overdue obligations
  surfaced.

## Running it

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # static output in dist/
```

Built with [Astro](https://astro.build). No client-side JavaScript, no external fonts, no tracking:
every page is static HTML and inline CSS, light and dark.

Deployed to GitHub Pages on every push to `main` (see `.github/workflows/deploy.yml`).
