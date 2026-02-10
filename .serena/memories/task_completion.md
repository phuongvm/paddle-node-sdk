# Task completion checklist

Before considering a task done:
1. Run `pnpm lint` (and `pnpm lint:fix` if needed).
2. Run `pnpm prettier:fix` if you changed code.
3. Run `pnpm test`.
4. Run `pnpm typecheck:tests`.
5. Run `pnpm build` to ensure build succeeds.
