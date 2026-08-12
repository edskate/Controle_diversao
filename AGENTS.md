# AGENTS

## Project overview

This repository is a very small static website. The main entry point is [index.html](index.html), and the project docs are minimal in [README.md](README.md).

- There is no build step, package manager, or framework setup.
- Changes should remain lightweight and easy to inspect in plain HTML.
- Prefer simple, semantic HTML over introducing libraries or tooling unless the request explicitly requires them.

## Working conventions

- Keep edits focused and minimal.
- Prefer readability and directness over abstraction.
- Preserve the existing structure of the page unless the task clearly requires a change.
- If the work adds significant user-facing functionality or a new feature area, update [README.md](README.md) to reflect it.

## Validation

Because this is a static page, validation is usually visual and lightweight:

1. Open [index.html](index.html) in a browser, or serve the folder locally.
2. If needed, run a local static server from the repository root, for example:
   - `python -m http.server 8000`
3. Confirm the page renders correctly and content changes are visible without console errors.

## Expected behavior for AI agents

- Do not assume a framework or build pipeline exists.
- Do not add npm, bundlers, or dependency-heavy setup for simple page edits.
- Keep HTML accessible and easy to maintain.
- When making content changes, prefer copy that matches the project’s casual, Brazilian Portuguese tone if present in the page.

## Files to check first

- [index.html](index.html) — primary page content and structure
- [README.md](README.md) — project-level notes and documentation
