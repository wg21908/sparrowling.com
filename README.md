# sparrowling.com

Sparrowling - A Linux Distribution

This repository contains starter end-user documentation for Sparrowling.

## Documentation

The static documentation site lives in `docs/` and is designed to be published
with GitHub Pages.

Starter pages:

- `docs/index.html`
- `docs/installation.html`
- `docs/security.html`
- `docs/configuration.html`
- `docs/downloads.html`

## GitHub Pages setup

The repository includes `.github/workflows/pages.yml`, which deploys the
contents of `docs/` to GitHub Pages.

In GitHub, go to:

`Settings` -> `Pages` -> `Build and deployment`

Then set the source to `GitHub Actions`.

After that, pushes to `main` that change `docs/**` will publish the docs site.
