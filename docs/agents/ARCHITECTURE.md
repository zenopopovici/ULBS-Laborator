# Architecture — ULBS-Laborator

<!-- graffino-agentic:begin v1 -->
> How this repo is built, generated from the code at backfill and kept current by
> whoever changes the structure. The code wins: when this page is wrong, fix it.
<!-- graffino-agentic:end -->

## Overview
No application code exists yet (2026-11-05). The repo holds lint and format config
for a React app, and the agent setup. Server services will run in Docker (D-001).
Purpose: Q-001.

```text
(not drawn yet — no parts exist)
```

## Parts
| Part | Path | Responsibility | Talks to |
|---|---|---|---|

## Data flow
Not known yet.

## State and storage
| What | Where | Owner | Notes |
|---|---|---|---|

## Configuration
| Name | Where set | Used by | Notes |
|---|---|---|---|
| Prettier | `.prettierrc.json` | Prettier | PATTERN-001 |
| oxlint | `.oxlintrc.json` | oxlint | PATTERN-002 |
<!-- names only, never values -->

## Build, deploy, runtime
Not set (Q-002). Server services run in Docker Compose (D-001). See AGENTS.md sections 2 and 5.

## Boundaries
None yet.
