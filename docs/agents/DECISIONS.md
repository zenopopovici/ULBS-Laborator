# Decisions — ULBS-Laborator

<!-- graffino-agentic:begin v1 -->
> Constraints the code must obey. Status: `approved` (obey) · `proposed` (do not
> build on it) · `superseded-by <ID>` (kept to explain old code).
> Adding or changing an entry needs the user's OK (AGENTS.md → The gate).
<!-- graffino-agentic:end -->

## Index
- D-001 · Server services run in Docker

---

## D-001 · Server services run in Docker
- **Status:** approved
- **Date:** 2026-11-05
- **Rule:** Run every server service (database, API, web server, cache) in Docker, with Docker Compose. Never install one on the host.
- **Why:** The user installed Docker and chose it as the one way to run server parts of this project.
- **Rejected:** Host installs (Homebrew and similar) — not chosen.
- **Evidence:** User instruction, 2026-11-05 (Claude Code session). Docker 29.9.2 and Compose v5.6.1 are installed.
- **Source:** user · confidence high
