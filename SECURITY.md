# Security Policy

- Status: Bootstrap policy
- Last reviewed: 2026-10-25

## Supported versions

No product version has been released. There is no supported release line, update channel, or security-fix commitment yet.

## Reporting a vulnerability

Use GitHub private vulnerability reporting for this repository:

https://github.com/devstroop/browser/security/advisories/new

Do not open a public issue for a suspected vulnerability, include exploit details in a public discussion, or attach private user data.

Private vulnerability reporting is enabled for this repository as of 2026-10-25. No bounty program, response-time SLA, or disclosure timeline is currently promised; those commitments require a separate decision.

## Scope

Once product code exists, this policy is intended to cover:

- The browser application and its update mechanism.
- Bundled engine/runtime components and integration code.
- Permission, navigation, download, and external-protocol handling.
- Profile, credential, cookie, and site-data storage.
- AI or agent features that can act on page content or local data.
- Build, signing, and release supply chain.

## Current security limitations

- The engine and process-isolation model are undecided.
- No sandbox, site-isolation, update-integrity, or release-signing implementation exists.
- No threat model or security test suite exists.
- Third-party license and vulnerability obligations are still being assessed.

These limitations must be resolved or explicitly accepted before any public release.
