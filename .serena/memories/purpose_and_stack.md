# Purpose and tech stack

## Purpose
Node.js SDK for integrating Paddle Billing with server-side JavaScript applications. Package: `@paddle/paddle-node-sdk`. Supports Node, browser, Bun, Deno, workers via exports.

## Tech stack
- **Language**: TypeScript (Node >= 20)
- **Package manager**: pnpm
- **Build**: tsc (ESM + CJS + types via separate tsconfigs)
- **Testing**: Jest
- **Lint/format**: ESLint (flat config), Prettier

## Structure
- `src/` – source
- `scripts/` – build helpers (e.g. update-env-vars.js)
- `dist/` – build output (cjs, esm, types)
