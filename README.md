# Devstroop Browser

- Status: Bootstrap; no browser implementation yet
- Initialized: 2026-10-25
- Default branch: `main`

This is the product repository for the Devstroop browser. It owns shipped source, product tests, build and release configuration, product architecture decisions, and product CI.

Research, comparative analysis, and disposable experiments live in the private workspace repository (`devstroop/browser-workspace`). Public issues here should summarize actionable work without depending on access to private material.

## Current state

- The repository contains governance documentation only.
- No engine, shell, or UI architecture has been selected.
- No build, installer, release, supported-platform statement, or update channel exists.
- No license has been granted. All rights are reserved until a license decision is recorded. Do not redistribute this repository or its contents.
- No product CI beyond the repository hygiene check exists.

These are bootstrap conditions, not product claims. See the open issues for the current decision queue.

## Intended repository responsibilities

- Product source and product tests.
- Build, packaging, signing, update, and release configuration.
- Architecture decisions needed by product contributors.
- Product security policy and dependency inventory.
- Product CI and release quality gates.

The repository structure must follow actual subsystem responsibilities. Empty placeholder modules are not created to make the repository look complete.

## Start here

1. [CONTRIBUTING.md](CONTRIBUTING.md) for the issue-first workflow and review expectations.
2. [SECURITY.md](SECURITY.md) for vulnerability reporting and the current security scope.
3. The open issues for MVP definition, engine/shell investigation, licensing, and repository governance.

## Near-term sequence

1. Decide target platforms and MVP acceptance criteria.
2. Run a time-boxed engine/shell spike; do not treat the spike as an architecture decision.
3. Record the chosen approach in an ADR in the workspace, then implement under product issues.
4. Add build, test, signing, and update CI only when there is code and a release model to verify.

## Working rules

- Every meaningful change links to an issue.
- Product changes require review and passing required checks.
- Security-sensitive changes require additional review.
- Licensing and third-party obligations must be reviewed before code is imported.
- Claims about compatibility, performance, or security require reproducible evidence and stated limitations.

## License

No license file is present, and no license is granted by publication. A license decision is required before accepting external contributions or distributing builds.
