# Vasloria — website

This vault is published with [Quartz 5](https://quartz.jzhao.xyz). The Quartz project lives in the hidden `.quartz/` folder and reads the Markdown files in this vault directly.

## Preview locally (updates as you edit)

```powershell
npm run dev
```

Then open <http://localhost:8080>. Leave the command running while you write in Obsidian; every save rebuilds the site and refreshes the browser automatically.

## Build the static site

```powershell
npm run build
```

The finished site is written to `.quartz/public/`.

## Publish

Push to `main` and the GitHub Actions workflow in `.github/workflows/deploy.yml` builds and deploys the site to GitHub Pages.

One-time setup in the repository: **Settings → Pages → Build and deployment → Source: GitHub Actions**.

The site will be at <https://stonepaw90.github.io/Draw-Steel-Notes/>. If that address changes, update `baseUrl` in `.quartz/quartz.config.yaml`.

## Configuration

- Site settings: `.quartz/quartz.config.yaml`
- Ignored folders: `md/` (an older export) and `obs.html/` are excluded from the site. Add more patterns under `configuration.ignorePatterns`.
- The home page is `index.md` in this folder.

## First-time setup on another machine

```powershell
cd .quartz
npm install
cd ..
npm run dev
```
