# Copilot Instructions - Docker Infrastructure

Scope: This repository only (my-dashboard-docker).

## Stack
- Docker Compose, nginx, MySQL bootstrap.

## Rules
- Keep compose configuration valid and deterministic.
- Prefer health checks that reflect real readiness.
- Keep nginx routes explicit and consistent with backend service routes.
- Do not hardcode secrets; use environment-driven configuration.

## Quality
- Validate compose after changes: docker compose config.
- Verify critical routes through nginx after proxy changes.
