# BRIDGE project website

Static project website for **BRIDGE: Bilevel Retrieval-Credit-Aware Agentic Reinforcement Learning**.

Website: https://jenniferquanxiao.github.io/BRIDGE/

## Preview locally

Run `python3 -m http.server 8000` in this directory and visit http://localhost:8000.

## Repository layout

Keep `index.html`, `.nojekyll`, and `public/` at the repository root. The HTML uses relative paths to the assets in `public/`.

## GitHub Pages

Publish from **main → / (root)** in Settings → Pages. GitHub Pages republishes the website after updates are pushed to `main`. The `.nojekyll` file preserves the bundled font directories.

## Update

Regenerate the static export from the original website project, then run its `scripts/export-github-pages.mjs` to prepare this deployment checkout. Review, commit, and push the changed deployment files. Local edits are not automatically pushed publicly.

This repository contains only the static website and its referenced public assets, including the downloadable original manuscript. It does not contain the application source, experiment logs, or model checkpoints. The local and standalone shareable HTML versions remain in the original project folder.
