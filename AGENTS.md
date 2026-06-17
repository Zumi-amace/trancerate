# Project Guidance

This repository hosts a single-page GitHub Pages app.

## App

- Main file: `index.html`
- Static icons: `apple-touch-icon.png`, `favicon-32.png`
- Deployment target: GitHub Pages from the `main` branch root.

## Editing Rules

- Keep the app static and client-only unless the user explicitly asks for a backend.
- Do not hard-code real API keys, tokens, or personal secrets.
- Preserve the Anthropic API-key input flow for public GitHub Pages usage.
- Keep Japanese UI text natural and avoid mojibake.
- Prefer focused edits in `index.html`; avoid broad rewrites unless the user asks for a redesign.

## Verification

- Check that embedded JavaScript parses before finishing.
- For UI changes, inspect mobile layout assumptions because this app is used from iPhone home-screen shortcuts.
- After changes are merged to `main`, GitHub Pages should update automatically.
