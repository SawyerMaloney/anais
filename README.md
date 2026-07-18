# Anais

A little website, built with [Jekyll](https://jekyllrb.com) and hosted on GitHub Pages.

## Run locally

You'll need Ruby + Bundler. Then:

```bash
bundle install      # first time only
bundle exec jekyll serve
```

Site shows up at http://127.0.0.1:4000/anais/

## Deploy

1. Push this repo to GitHub (name the repo `anais`, or rename to `username.github.io` for a user site).
2. In the repo: **Settings → Pages → Source = Deploy from a branch → branch `main` / root**.
3. GitHub builds it automatically with Jekyll. Live in ~1 min at `https://<your-username>.github.io/anais`.

## Edit content

- `index.md` — the home page
- `about.md` — about page (linked in the nav)
- `_posts/` — drop in dated Markdown files for blog posts, e.g. `2026-07-17-hello.md`

Made with ♥ for Anais.
