# Registration Report — GitHub Pages

Interactive registration dashboard for May 11 – Jun 4, 2026.

**Tabs:** Overview | Asia & Oceania | Americas | Middle & Eastern Europe | Swiss MU

## Deployment

1. Create a GitHub repository (or use an existing one).
2. Push the contents of this folder to the `main` branch (or a `gh-pages` branch).
3. In your repo settings, go to **Settings > Pages** and set the source to the branch you pushed to.
4. The report will be live at `https://<your-username>.github.io/<repo-name>/`.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The full interactive report (self-contained, no external dependencies except Chart.js CDN) |
| `.nojekyll` | Tells GitHub Pages to skip Jekyll processing |
| `README.md` | This file |

## Quick Deploy Commands

```bash
cd github-pages-package
git init
git add .
git commit -m "Deploy Registration Report v8"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Then enable GitHub Pages in your repository settings.
