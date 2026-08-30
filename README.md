# sparrowling.com

Sparrowling - A Linux Distribution

This repository contains starter end-user documentation for Sparrowling configured with the Jekyll theme [`pages-themes/minimal`](https://github.com/pages-themes/minimal).

## Documentation

The documentation site lives in `docs/` and is processed with Jekyll for GitHub Pages.

Starter pages:

- `docs/index.md`
- `docs/installation.md`
- `docs/security.md`
- `docs/configuration.md`
- `docs/downloads.md`

Theme configuration lives in `_config.yml` (and `docs/_config.yml`) using `theme: pages-themes/minimal`.

## GitHub Pages setup

The repository includes `.github/workflows/pages.yml`, which builds the site using `actions/jekyll-build-pages` and deploys it to GitHub Pages.

In GitHub, go to:

`Settings` -> `Pages` -> `Build and deployment`

Then set the source to `GitHub Actions`.

After that, pushes to `main` that change `docs/**` or `_config.yml` will publish the updated documentation site.
