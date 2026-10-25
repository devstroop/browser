# Contributing

- Status: Bootstrap policy; not yet enforced by branch protection
- Last reviewed: 2026-10-25

## Before contributing

The repository has no license yet. Do not assume that opening a pull request grants a license or that contributions can be merged. A maintainer must resolve the licensing decision first. Until then, treat the repository as all rights reserved.

## Issue-first workflow

1. Find or create an issue that states the problem, scope, acceptance criteria, and evidence.
2. Keep each pull request bounded to one coherent change.
3. Link the pull request to the issue it closes or advances.
4. Record known limitations and follow-up work rather than hiding them in the pull request.

Do not use a pull request to introduce unrelated unfinished work.

## Branches

Proposed branch model:

```text
main
  └── develop
        ├── feature/<issue>-short-name
        ├── fix/<issue>-short-name
        ├── research/<issue>-short-name
        └── refactor/<issue>-short-name
```

`main` is intended to be release-ready and `develop` the integration branch. Neither branch protection nor a `develop` branch exists yet; this section describes the target, not the current enforced state.

## Pull requests

A product pull request must:

- Link to one or more issues.
- State included and excluded scope.
- Include tests, documentation, migration notes, or an explanation of why they do not apply.
- State security, privacy, and licensing implications.
- Identify known limitations and follow-up issues.
- Pass the checks that are actually configured at the time of review.

One review is the minimum proposed review rule. Security-sensitive, high-risk, or architecture-wide changes need additional review.

## Evidence and claims

- Separate verified facts from inference and hypotheses.
- Include exact versions, commits, commands, and environments for technical claims.
- Do not claim compatibility or performance without a reproducible method and disclosed limitations.
- Do not commit credentials, private browsing data, customer data, or unwrapped secrets.

## Third-party code

Do not copy, vendor, link, or redistribute third-party code until:

1. The canonical source and exact revision are identified.
2. The repository, file-level, and bundled-dependency licenses are reviewed.
3. Required notices and source-offer obligations are recorded.
4. A maintainer accepts the obligation in the issue or pull request.

Open an issue for any unclear or incompatible license before importing code.

## Security

Do not report vulnerabilities in public issues. Follow [SECURITY.md](SECURITY.md).

## Commit hygiene

- Keep commits coherent and reviewable.
- Explain why the change is needed, not only what changed.
- Do not rewrite shared history without coordination.
- Do not commit generated build output unless the repository explicitly tracks it.
