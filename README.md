# Checkmate

A personal day-by-day checklist planner built with HTML, CSS, and vanilla JavaScript.

## Features

- Card-based checklist home: open any named checklist to see its days and completion progress
- Focus timer with focus/break modes, pause/resume, custom duration, and refresh recovery
- Nineteen themes, including Sage, Midnight, and an illustrated Bubu–Dudu theme
- AI import from pasted text, CSV, TSV, Markdown, JSON, and TXT
- Bring your own OpenAI API key; the key stays in page memory and is not saved
- Local browser storage and JSON backup export/import

## Hosting

GitHub Pages publishes the `docs/` directory from `main`. No build step is needed.

## Data

Checklists are stored in your browser, not on GitHub. Export a backup before moving to another browser or site address. AI conversion sends the submitted content directly to OpenAI and uses the API account associated with your key.

## Local checks

Run `node --test tests/*.test.mjs` before committing.
