# D365 Commerce CRT Reference Docs

Published documentation site for Commerce Runtime (CRT) request handlers, triggers, request types, and assembly inventory.

## Live Site

- https://fraga.github.io/d365-commerce-crt-reference-docs/

## Start Points

- [Start Here](index.md)
- [Domain Index](by-domain/index.md)
- [Request Type Index](by-request-type/index.md)
- [Handler Index](by-handler/index.md)
- [Assembly Inventory](assemblies.md)

## What This Repo Publishes

- SDK version captured in this build: `9.56.26056.3`
- Generated reference pages for request types, handlers, and domains
- Machine-readable catalog in `catalog.json`

## Source Of Truth

- Main source repository: https://github.com/fraga/d365-commerce-crt-reference
- This repository is published from the source repo's `docs/` subtree.

## Update Model

- Regenerate docs in the source repo.
- Publish with `git subtree push --prefix docs docs-origin main`.
