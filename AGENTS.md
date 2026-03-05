# Repository Guidelines

## Purpose

- This repository publishes the generated documentation site for `d365-commerce-crt-reference`.
- Treat this repo primarily as a publish target, not the source of parsing logic.

## Source Of Truth

- Source repository: `https://github.com/fraga/d365-commerce-crt-reference`.
- If a change affects generated content, update the source repo and republish.

## Repository Layout

- `index.md`: landing page for requirement-to-entrypoint navigation.
- `by-domain/`: domain-oriented navigation pages.
- `by-request-type/`: per-request-type reference pages.
- `by-handler/`: per-handler reference pages.
- `catalog.json`: machine-readable catalog.
- `_config.yml` and `assets/css/style.scss`: GitHub Pages presentation settings.

## Editing Guidelines

- Do not hand-edit generated reference pages if the change should survive republish.
- Preferred path: change the source repo generator or source docs subtree, then republish.
- Repo-level presentation files may also be managed from the source repo's `docs/` subtree.

## Publish Workflow

- Generate docs from the source repo.
- Push the subtree with `git subtree push --prefix docs docs-origin main`.
