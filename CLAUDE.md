# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project status

This repository is a bare scaffold — there is no implementation yet. `cine_visas/__init__.py` is empty, `tests/` and `requirements.txt` are empty, and no build, lint, or test tooling is configured. Do not assume any of these exist until you (or the user) add them; check the current state of the repo before relying on prior context.

## Goal

Per [README.md](README.md): cross-reference 80 years of French cinema exploitation visas ("visas d'exploitation cinématographique") with TMDB (The Movie Database) data.

## Layout

- `cine_visas/` — the Python package (currently empty).
- `data/` — data directory; only `data/processed/` exists so far (empty, tracked via `.gitkeep`).
- `tests/` — empty, reserved for tests.
- `.claude/skills/`, `.github/workflows/` — present but empty.

Since there is no established structure for data ingestion, TMDB API access, or visa-record parsing yet, the first real implementation work should propose and confirm an approach (e.g. where raw vs. processed data lives, how TMDB API credentials are supplied, what the CLI/library surface looks like) before writing code.
