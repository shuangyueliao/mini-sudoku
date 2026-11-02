# Mini Sudoku — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Classic sudoku for everyone: 4x4, 6x6 or 9x9 grids, Easy/Medium/Hard. Every
puzzle is generated fresh with exactly one solution. Pencil notes, timer,
best times. (168 characters — under the 200 limit)

## Details

- Genre: Puzzle / Board / Casual
- Controls: Mouse / Touch (tap a cell, tap a number). Keyboard: 1-9 type,
  arrows move, Backspace erase, N toggles pencil notes, M mutes.
- Features: 3 grid sizes x 3 difficulties, guaranteed unique solutions
  (backtracking generator with solution-counter pruning), conflict/mistake
  highlighting, same-number hints, pencil notes, timer and mistake counter,
  per-mode best times (localStorage), mute, single-file HTML5 (no external
  assets), works offline once loaded.
- Tech: Vanilla JavaScript, Canvas, WebAudio. No frameworks, no tracking,
  no external links.

## Tags

sudoku, puzzle, logic, numbers, board, casual, brain, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (board and UI scale from 320px phones to desktop, touch + keyboard)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png (1280×800)

## GameDistribution
- Upload mini-sudoku-gd.zip (contains index.html only); the loader injects
  the GD SDK automatically on gamedistribution / gd.games domains.

## itch.io
- Upload zip (mini-sudoku-itch.zip), mark "This file is playable in browser",
  entry file: index.html, kind: html.
- Pricing: $0 (donations optional)
