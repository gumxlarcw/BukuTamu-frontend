# BukuTamu-frontend — archived

This repository has been consolidated into [gumxlarcw/bukutamu](https://github.com/gumxlarcw/bukutamu) as `frontend/`.

Full commit history is preserved there under the `frontend/` prefix via `git subtree`. Run `git log -- frontend/` in the monorepo to see the original commits.

This repo is now read-only. New work happens in the monorepo.

## Migration date

2026-05-16

## Why the consolidation

- Single source of truth for the three buku-tamu components (backend / frontend / kiosk print)
- One `git pull` to update all parts
- Aligns disk layout with naming (everything under `/var/www/html/bukutamu/`)
- Both backend and frontend commit histories preserved via `git subtree`
