# Trading Journal Repo Instructions

## Project overview
- This project is a flat, vanilla HTML/CSS/JavaScript app.
- Main marketing page: `index.html`
- Main application page: `app.html`
- Netlify config: `netlify.toml`
- There is no framework, bundler, or package manager.
- Do not migrate this project to React, Next.js, Vite, or any other framework unless explicitly asked.

## Current architecture
- UI and business logic currently live mostly inside `app.html`
- Supabase auth and cloud sync are already implemented
- localStorage is still used as offline/local fallback
- README may be outdated; prefer the actual implementation in `app.html`

## Rules
- Preserve the existing design language and layout unless explicitly asked to redesign
- Keep changes minimal and focused
- Do not break offline mode
- Do not remove Supabase integration
- Do not rename files or routes unless necessary
- Do not introduce a build system
- Before making changes, first inspect the relevant existing code paths

## What good looks like
- Changes should work in the current vanilla setup
- Existing pages must keep functioning
- Auth flow must still work
- Local storage fallback must still work
- Cloud sync must still work
- Explain exactly which files were changed and why

## Preferred workflow
- First analyze
- Then change only one feature at a time
- Keep diffs small and reviewable
- If logic is duplicated, refactor carefully without changing behavior
