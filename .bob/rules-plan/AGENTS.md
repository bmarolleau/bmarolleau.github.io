# Architecture Constraints

- Static Jekyll site — all "dynamic" behaviour must be client-side JS or handled by a third-party service.
- Deployed via GitHub Pages: unsupported Jekyll plugins (anything not on the [GitHub Pages whitelist](https://pages.github.com/versions/)) will silently fail in production even if they work locally.
- Theme is `minima` — to override layouts or includes, copy the relevant file from the gem into `_layouts/` or `_includes/` at the repo root; do not patch the gem.
- `baseurl` is set to `""` in `_config.yml` — keep it empty for GitHub Pages user/org sites (repo sites need a non-empty baseurl).
