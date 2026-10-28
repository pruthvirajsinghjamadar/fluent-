# Fluent — deployment package

Zero-config Next.js deploy: no database, no environment variables, fully client-side.

## Deploy to Vercel (recommended)
1. Push this folder to a GitHub repo (or drag it into an existing one)
2. vercel.com/new → Import → Deploy (auto-detects Next.js — no settings needed)
3. Done: permanent HTTPS URL, mic + voice feedback work out of the box

## Deploy anywhere with Node/Bun
    bun install        # or: npm install
    bun run build      # or: npm run build
    bun run start      # serves on :3000 (NODE_ENV=production)

## Notes
- Sign-in is local-only (localStorage) — no backend required
- All progress, leaderboard "you" row, and PDF report card generate on-device
