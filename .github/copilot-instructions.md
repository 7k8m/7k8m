# Copilot Instructions

## Build, test, and lint

This repository does not contain build, test, or lint tooling. There is no package manifest, CI workflow, or automated test suite, so there is no single-test command to run.

## High-level architecture

- `README.md` is the primary artifact. The repository functions as a personal profile/portfolio page rather than an application codebase.
- `5734680.png` is a local image asset referenced from `README.md`. If the image is renamed, moved, or replaced, update the markdown reference with it.
- There is no source tree, runtime, or generated output directory to keep in sync.

## Key conventions

- Keep edits centered on `README.md` content and the image asset it references.
- Preserve the current content structure: grouped sections with nested markdown bullet lists for personal works, involved works, other activities, and social links.
- Keep outbound links inline within list items. Some entries intentionally include a primary project link plus a secondary link in parentheses on the same line.
- Prefer surgical content updates over broad rewrites unless the user explicitly asks for a reorganization or copy edit across the whole profile.
