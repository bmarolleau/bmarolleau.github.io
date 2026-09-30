# AGENTS.md

This file provides guidance to agents when working with code in this repository.

## Stack

Jekyll 4.1.1 static site, `minima` theme, deployed to GitHub Pages at https://bmarolleau.github.io/.

## Commands

```bash
# Local dev server (required prefix — never run `jekyll` directly)
bundle exec jekyll serve

# Production build
bundle exec jekyll build
```

No test framework. No linter. No npm/node build step.

## Content conventions

- Posts live in `_posts/` and **must** follow the filename format `YYYY-MM-DD-title.md`.
- Post front matter requires `layout: post`, `title`, `date`, and `categories`.
- Page front matter uses `layout: page` (e.g. `about.markdown`) or `layout: home` for the index.
- Images go in `assets/` and are referenced as `/assets/filename.ext` (absolute path from site root).
- `_config.yml` is **not** hot-reloaded — restart `bundle exec jekyll serve` after editing it.

## Key files

| File | Purpose |
|---|---|
| `_config.yml` | Site-wide settings (title, theme, plugins) |
| `index.markdown` | Home page content (layout: home) |
| `_posts/` | Blog posts |
| `assets/` | Static images and presentations |
