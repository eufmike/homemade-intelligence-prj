# AGENTS.md — Shared Project Management

Instructions for AI coding assistants working on shared project management assets:
architecture decisions, methodology documentation, issue templates, and project governance.

## Scope

This repo holds shared project management resources for the Homemade Intelligence platform.
It is collaborator-visible. Do not commit private notes or personal configuration here.

## References layout

```text
references/
  adr/            ← Architecture Decision Records (MADRs)
  methodology.md  ← Analytical methodology overview
```

## Conventions

- All documents follow the Markdown formatting rules in `../hmintel-prj-eufmike/.github/instructions/markdown.instructions.md`.
- ADR filenames: `NNNN-short-title.md` (zero-padded 4-digit index).
- Do not add private notes, API keys, or personal configuration to this repo.

## Quick reference

```bash
# View all ADRs
ls references/adr/
```
