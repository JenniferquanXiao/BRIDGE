# BRIDGE project website

Static project website for BRIDGE, a bilevel learning framework for training retrievers and LLM agents with retrieval-aware credit assignment.

## Preview locally

Run `python3 -m http.server 8000` in this directory and visit http://localhost:8000.

## Repository layout

Keep `index.html`, `.nojekyll`, and `public/` at the repository root. The HTML uses relative paths to the assets in `public/`.

## Publish when ready

Keep GitHub Pages disabled during private preparation. When ready to publish, make the repository public, then select Settings → Pages → Deploy from a branch → main → / (root).

## Update

Regenerate the static export from the original website project, then replace this repository’s `index.html` and `public/` with the generated files. This repository contains the deployment files, not the application source.
