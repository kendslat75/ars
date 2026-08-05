# Antique Radio Salvage — Astro Website

This is the production website for **https://antiqueradiosalvage.com**.

## Why Astro

Astro creates a fast static website while keeping shared items—navigation, footer, styles and page layouts—in one place. GitHub Actions automatically builds and publishes the site whenever a change is committed to `main`.

## First-time GitHub setup

1. Extract this ZIP on your computer.
2. Open the existing GitHub repository: `https://github.com/kendslat75/ars`.
3. Delete the old site files from the repository, except you may keep repository history.
4. Upload **all files and folders inside this project**, including the hidden `.github` folder.
5. Commit with the message: `Rebuild website in Astro`.
6. Open **Settings → Pages**.
7. Under **Build and deployment → Source**, choose **GitHub Actions**.
8. Open the repository's **Actions** tab and wait for “Deploy Astro site to GitHub Pages” to finish with a green check.
9. Visit `https://antiqueradiosalvage.com` and hard-refresh with Ctrl+F5.

## Important files

- `src/pages/` — page content
- `src/components/Header.astro` — navigation and top contact bar
- `src/components/Footer.astro` — footer
- `src/styles/global.css` — all site styling
- `public/images/` — website images
- `public/CNAME` — custom domain
- `.github/workflows/deploy.yml` — automatic deployment

## Contact form

The form posts to:

`https://formspree.io/f/xzepbarv`

Submissions should be forwarded by Formspree to `ken@antiqueradiosalvage.com`.

## Editing locally (optional)

Install Node.js, then run:

```bash
npm install
npm run dev
```

Build check:

```bash
npm run build
```
