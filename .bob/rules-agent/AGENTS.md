# Coding Rules

- Always prefix Jekyll commands with `bundle exec` — bare `jekyll` will use the wrong version.
- Post filenames must be `YYYY-MM-DD-slug.md` or Jekyll will ignore them silently.
- Image paths must be absolute from site root (`/assets/img.png`), not relative — relative paths break on paginated or nested URLs.
- `_config.yml` changes require a server restart; `--livereload` does not pick them up.
- No JS build step exists — do not introduce npm/node tooling without updating the Gemfile workflow.
