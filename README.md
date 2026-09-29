# ff-fixture-deploy

A Frontier Factory fixture for milestone M6 (read-only deployments). It is a tiny site that deploys to two platforms:

- **Vercel** serves `public/` as a static site (`vercel.json`).
- **Railway** runs `npm start`, a Node HTTP server (`server.js`) that serves the same page on `$PORT`.

Branches: `main` (production) and `dev` (the integration branch). The `fixture-base` tag marks the commit that `pnpm verify` resets to before a run.
