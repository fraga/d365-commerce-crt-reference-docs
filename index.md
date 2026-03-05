# CRT Extension Point Guide

SDK Version: `10.13.23228.2`
Generated from: `sdk`

## Start Here

1. Pick your business area in [Domain Index](by-domain/index.md).
2. Open a request type page in [Request Type Index](by-request-type/index.md).
3. Open concrete implementations in [Handler Index](by-handler/index.md).
4. Check assembly coverage in [Assembly Inventory](assemblies.md).

## Requirement-to-Entrypoint Flow

1. Requirement mentions business concept (cart, customer, tax): start in `by-domain/`.
2. Requirement mentions API/request name: start in `by-request-type/`.
3. Requirement mentions existing class/assembly: start in `by-handler/`.
4. Validate request neighbors: use the handler page's `Neighboring Triggers` section.

## Catalog Summary

| Item | Count |
|------|-------|
| Assemblies | 140 |
| Handlers | 577 |
| Triggers | 77 |
| Request Types | 1561 |
