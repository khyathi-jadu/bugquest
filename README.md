# BugQuest

**Every Bug Has a Story.** BugQuest is a self-contained, browser-based debugging mystery demo. Investigate fictional incidents, inspect evidence, track hypotheses and notes, reveal hints, edit starter code, and record learning progress.

## Run it

Open `index.html` in a modern browser. No build step, account, server, or package installation is required. Progress, notes, code edits, hints, and hypotheses are saved in that browser's local storage.

## About the demo runner

This standalone edition does **not** execute submitted code. The console labels every result as simulated and explains that it cannot verify a fix. Submitting a case records a learning completion and awards the case XP; it does not assert that the edited solution passed tests. Reference explanations are shown as learning material after the case is marked complete.

## Included

- Dashboard with local progress and an empty first-run experience
- Eight searchable and filterable fictional cases
- Responsive investigation workspace with editable Python starter code
- Evidence panels, progressive hints, autosaved notes, and editable/deletable hypotheses
- Local XP, completion history, and achievement milestones
- Optional light theme and reduced-motion support

## Production direction

A production release should move challenge definitions, reference solutions, hidden tests, scoring, and guest identity to a FastAPI service backed by SQLite/SQLAlchemy. Connect a sandbox provider such as Judge0 for isolated execution. Until that backend and provider exist, this edition deliberately remains a clearly labeled demo and keeps progress in the local browser.

## Project

Portfolio prototype for `bugquest` — an evidence-led programming mystery and debugging platform.

MIT License.
