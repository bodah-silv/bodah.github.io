# Jekyll + GitHub Pages starter

## Quick start
1) Create a **public** repo named `yourusername.github.io`.
2) Copy these files into the repo (keep folders as-is).
3) Commit & push to `main`.
4) In **Settings → Pages**, ensure the source is **GitHub Actions**.
5) The workflow in `.github/workflows/pages.yml` will build & deploy to `https://yourusername.github.io`.

## Local preview (optional)
If you have Ruby:
```bash
bundle add jekyll
bundle exec jekyll serve
```
Then visit http://localhost:4000
