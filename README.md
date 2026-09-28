# YouTube Music Generator

A React + TypeScript + Vite web project for experimenting with music-generation workflows aimed at YouTube creators.

## Local development

```bash
npm ci
npm run dev
```

## Validation

```bash
npm run lint
npm run build
```

## Static deployment

The project includes a `gh-pages` deployment script and an explicit GitHub Pages homepage in `package.json`. CI validates the production build before changes are merged.

## Change Log

### 2026-09-28 03:39 Europe/Vienna (CEST) — CI / Portfolio / Maintenance
- Replaced the generic Vite template README with project-specific documentation.
- Added automated `npm ci`, lint and production-build validation for pull requests and `main` pushes.
- Documented the existing GitHub Pages deployment target.

> The timestamp uses the verified Europe/Vienna minute in which the change set's draft PR was created.
