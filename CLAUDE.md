# slack-company-research

See README.md for what this is and how to run it.

## Workflow

Tier: lean
Base branch: master
Checks: `npm run build`

- `npm run build` = `tsc` (typecheck). TODO: `npm test` is a placeholder that always fails; add a real test runner.

Used by the user-level `/start` → `/build` → `/ship` commands. `Tier: off` opts this repo out.
