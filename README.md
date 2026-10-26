# GianniLee.github.io

Jian Lee's personal academic site, built on [al-folio](https://github.com/alshedivat/al-folio).

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000/.

## Content

- `_pages/about.md` — bio, shown on the home page
- `_data/cv.yml` — CV / experience / education
- `_projects/` — one file per project
- `_news/` — short announcements shown on the home page
- `_bibliography/papers.bib` — publications (BibTeX)
- `_data/socials.yml` — email / GitHub / LinkedIn

## Deploy

Pushing to `main` runs [.github/workflows/deploy.yml](.github/workflows/deploy.yml), which builds the site and pushes the result to the `gh-pages` branch. In the repo's Settings → Pages, set the source to "Deploy from a branch" → `gh-pages` → `/ (root)`.
