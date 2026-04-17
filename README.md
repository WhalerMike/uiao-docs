# uiao-docs — moved to WhalerMike/uiao

> **This repository has moved.** All `uiao-docs` content now lives under
> [`docs/`](https://github.com/WhalerMike/uiao/tree/main/docs) in the
> consolidated monorepo [`WhalerMike/uiao`](https://github.com/WhalerMike/uiao).
>
> The move happened on 2026-04-17. Full history was preserved via
> `git subtree`. No content was lost — only the URL changed.

## Where to go

| Old location | New location |
|---|---|
| `uiao-docs/` repo root | [`uiao/docs/`](https://github.com/WhalerMike/uiao/tree/main/docs) |
| `uiao-docs/docs/` (Quarto `.qmd` canon) | [`uiao/docs/docs/`](https://github.com/WhalerMike/uiao/tree/main/docs/docs) |
| `uiao-docs/data/` (YAML schemas) | [`uiao/docs/data/`](https://github.com/WhalerMike/uiao/tree/main/docs/data) |
| `uiao-docs/_quarto.yml` | [`uiao/docs/_quarto.yml`](https://github.com/WhalerMike/uiao/blob/main/docs/_quarto.yml) |
| Narrative series | [`uiao/docs/narrative/`](https://github.com/WhalerMike/uiao/tree/main/docs/narrative) |
| Live site (Quarto, GitHub Pages) | Served from [`WhalerMike/uiao`](https://github.com/WhalerMike/uiao) once Pages source is configured |
| Issue tracker | [`uiao/issues`](https://github.com/WhalerMike/uiao/issues) |

## Why consolidated

Four repositories (`uiao-core`, `uiao-docs`, `uiao-gos`, `uiao-impl`)
were merged into a single governance substrate with schema-anchored
canon, drift detection, and unified CI. See
**[ADR-028](https://github.com/WhalerMike/uiao/blob/main/core/canon/adr/adr-028-monorepo-consolidation-gos-integration.md)**
in the new repo for the authoritative rationale.

## This repo is now read-only

No new commits will land here. File issues and open PRs against
[`WhalerMike/uiao`](https://github.com/WhalerMike/uiao).
