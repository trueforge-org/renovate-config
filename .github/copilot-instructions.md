# Copilot instructions for `trueforge-org/renovate-config`

This repository contains shared Renovate presets.

- Keep changes minimal and focused on Renovate configuration files (`*.json`, `*.json5`).
- Preserve existing schema declarations and JSON/JSON5 formatting style in each file.
- Reuse existing preset fragments under `.github/renovate/**` through `extends` when possible instead of duplicating rules.
- Do not remove existing package rules or ignore rules unless the task explicitly requires it.
- Always use semantic commit names for commits and PR titles (e.g., `feat: ...`, `fix: ...`, `docs: ...`, `chore: ...`).
