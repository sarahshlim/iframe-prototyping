# iframe-prototyping

Static HTML/CSS/JS prototypes for OLI Torus **Webpage** blocks.

This repo is used to prototype and revise interactive accounting learning activities before they are finalized for implementation.

## Main prototype files

- `reflect4.html` — original / baseline transaction sequencer
- `reflect4_sarah.html` — revised working version of the transaction sequencer
- `entity-diagram.html` — entity boundary diagram
- `entity-diagram-prompts.html` — Stuff, Rights, and Promises + writing prompts
- `homework.html` — homework / related page
- `reflect4_rick.html` — Rick’s original design reference

## Shared files

- `shared.css` — shared styling
- `shared.js` — shared logic/helpers
- `config.js` — configuration values
- image files (`.png`) — supporting visuals for activities

## Current working branch

- Main working branch for prototype revisions: `sarah-activity-edits`

## GitHub Pages preview

This repo is published through GitHub Pages.

Repo root:
- `https://sarahshlim.github.io/iframe-prototyping/`

Prototype pages:
- `https://sarahshlim.github.io/iframe-prototyping/reflect4.html`
- `https://sarahshlim.github.io/iframe-prototyping/reflect4_sarah.html`
- `https://sarahshlim.github.io/iframe-prototyping/entity-diagram.html`
- `https://sarahshlim.github.io/iframe-prototyping/entity-diagram-prompts.html`
- `https://sarahshlim.github.io/iframe-prototyping/homework.html`

## Notes on workflow

- `reflect4_sarah.html` is the main sandbox for design/content/layout revisions.
- `reflect4.html` should remain as a stable baseline reference unless intentional changes are needed.
- Most visual/layout revisions should be made in:
  - `reflect4_sarah.html`
  - `shared.css` (only when a shared styling change is necessary)
- Avoid changing `shared.js` or `config.js` unless the change truly requires logic updates.

## Purpose of the Transaction Sequencer prototype ('System in Action: Simple Case' activity)

The goal of the transaction-sequencer activity is to help learners see the architecture of financial statements:

- the two balance sheets are snapshots of financial position at different dates
- the three flow statements (Statement of Changes in Equities, Cash Flow Statement, Income Statement) decompose the difference between the two balance sheets
- the Statement of Changes in Equities explains the full change in equities
- the Cash Flow Statement explains the full change in cash
- the Income Statement explains net income, which is one part of the change in equities

`https://sarahshlim.github.io/iframe-prototyping/reflect4_sarah.html`

## Status

This repo contains working prototypes and iterative revisions. Some files may be experimental or in progress.
