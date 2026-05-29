# dongwei.info — Academic Portfolio

Jekyll 3.9.5 site using Minimal Mistakes 4.24.0 (remote theme), hosted on GitHub Pages.

## Dev commands

```bash
bundle exec jekyll serve          # Local dev server at localhost:4000
npm run build:js                  # Rebuild JS bundle (uglify + banner)
```

## Content structure

- `_posts/` — Publications (format: `YYYY-MM-DD-slug.md`)
- `_pages/` — Static pages (publication list, blog)
- `_data/` — Navigation and UI text config
- `_includes/` — Reusable HTML partials
- `_layouts/` — Page templates
- `_sass/` — SCSS stylesheets
- `assets/` — Images, PDFs, JS (main.min.js is the bundled output)

## Conventions

- Posts use front matter with `title`, `date`, `categories`, `tags`
- Images go in `assets/images/`; reference with `/assets/images/filename`
- JS plugins are concatenated via `npm run build:js` into `assets/js/main.min.js`
- Site config lives in `_config.yml` (requires server restart on change)
