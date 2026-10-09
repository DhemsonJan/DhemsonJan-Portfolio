# DhemsonJan Portfolio — Dashboard

The public dashboard front end for Dhemson Jan P. Tubod's portfolio. Built with
React and Vite.

This repo contains only the browser app. All content comes from the API, which
lives in the companion [Admin-Portfolio](https://github.com/DhemsonJan/Admin-Portfolio)
repository and is served from the same Supabase Postgres + Storage backend.

## Quick start

```bash
npm install
npm run dev
```

## Connecting to the API

The client calls `${VITE_API_BASE}/api/*` (same origin when the variable is
empty). To point a deployed dashboard at a hosted API, set the build-time
variable:

```
VITE_API_BASE=https://your-api-origin
```