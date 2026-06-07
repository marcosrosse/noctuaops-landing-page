# CLAUDE.md

This file guides Claude Code when working in **pages**. Platform-wide context lives in the docs hub
(`docs-podhive.io`, https://codeberg.org/mrosse/docs-podhive.io) — see its `architecture/repo-map.md`.

## What this repo is

A static HTML landing page for **owl-reporter**. A single `index.html`, served from the `pages`
branch.

> **Not production.** Nothing serious depends on this; keep it simple.

## Working rules

- It's one static file — no build step, no framework, no dependencies.
- Don't introduce a toolchain (bundler, generator) without approval.
- Don't delete files without approval.
