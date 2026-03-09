# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

A browser-based Tic Tac Toe game built as a single self-contained HTML file (`tictactoe.html`). No build step, no dependencies, no package manager.

## Running the Project

Open directly in a browser:
```bash
open tictactoe.html
```

## Architecture

Everything lives in `tictactoe.html`:
- **HTML** — 3×3 grid of `.cell` divs, scoreboard, reset button
- **CSS** — dark theme, grid layout, win-pulse animation, all inline in `<style>`
- **JS** — game logic inline in `<script>` at the bottom; board state is a flat 9-element array, win conditions checked against `WINS` (array of index triplets)

## Git & GitHub

- Remote: `https://github.com/arnarpalltuff/tic-tac-toe` (public)
- `gh` CLI is installed at `~/bin/gh` (not on system PATH — use full path or add `~/bin` to PATH)
- Git user: `arnarpalltuff` / `arnarpalltuff@users.noreply.github.com` (configured locally)
- Commit and push after every meaningful change using clean, descriptive messages
