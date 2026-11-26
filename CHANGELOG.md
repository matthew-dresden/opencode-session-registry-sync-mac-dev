# Changelog

## [1.1.0] - 2026-11-26

### Maintenance

- add automerge workflow (mirrored from opencode-cross-session-messaging estate template)

## [1.0.1] - 2026-11-23

## [1.0.0] - 2026-11-22

### Added

- extract the session-registry-sync opencode plugin into a standalone repository (registration sync, rename trail, find_session name lookup, file-inbox watcher)
- standard estate plugin pipeline: PR CI jobs wired 1:1 to npm targets, push-to-main validation with release PR, tag-release on release commits
- secret-enforcement kit: .githooks (pre-commit, pre-push, scan_diff.py), security.yml with gitleaks 8.30.1, check-tarball leak gates
