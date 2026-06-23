# Yao Wang Academic Website

This repository hosts the academic website for Yao Wang at [wangyao1998.top](https://wangyao1998.top).

The site is built with the PRISM academic website template, Next.js, Tailwind CSS, and TypeScript. Content lives in `content/`, static assets live in `public/`, and deployment is handled by GitHub Actions to GitHub Pages.

## Local Development

Use Node.js 22 or newer.

```bash
npm install --no-package-lock
npm run dev
```

## Production Build

```bash
npm install --no-package-lock
npm run build
```

The static export is written to `out/`.

## Deployment

GitHub Actions builds and deploys the site on pushes to `main`. The custom domain is configured as `wangyao1998.top` through the repository Pages settings and the root `CNAME` file.

## Credits

This site is adapted from the PRISM academic website template by Jiale Liu and is distributed with the original MIT license.
