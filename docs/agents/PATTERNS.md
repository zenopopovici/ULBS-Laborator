# Patterns — ULBS-Laborator

<!-- graffino-agentic:begin v1 -->
> How we build things here. Copy only `approved` entries. `candidate` = seen once or
> not yet confirmed; agents add these freely. Promotion needs the user's OK.
<!-- graffino-agentic:end -->

## Index
- PATTERN-001 · Prettier format: no semicolons, single quotes · approved
- PATTERN-002 · oxlint with React rules · approved

---

## PATTERN-001 · Prettier format: no semicolons, single quotes
- **Status:** approved
- **Use when:** You write or change any file Prettier formats (JS, TS, JSX, JSON, Markdown).
- **How:** Run Prettier with the repo config. Do not add semicolons. Use single quotes. `dist`, `node_modules` and `package-lock.json` are skipped.
- **Example:** `.prettierrc.json:2`, `.prettierignore:1`
- **Why:** One format keeps diffs small and reviews about content.
- **Source:** code · confidence high

## PATTERN-002 · oxlint with React rules
- **Status:** approved
- **Use when:** You write React components or hooks.
- **How:** Lint with oxlint (plugins `react`, `oxc`). `react/rules-of-hooks` is an error. Export only components from a component file (constants are allowed).
- **Example:** `.oxlintrc.json:3-7`
- **Why:** Hook-order bugs break at runtime; mixed exports break fast refresh.
- **Source:** code · confidence high
