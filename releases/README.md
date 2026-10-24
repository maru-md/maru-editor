# Release notes

One file per release: `releases/<version>.md`. Maru uses [semantic versioning](https://semver.org) — before 1.0, new features bump the minor number and fixes bump the patch number.

These files are the single source for the release notes on GitHub Releases, on https://maru.md/changelog and in its RSS feed (https://maru.md/changelog/rss.xml).

## Format

```markdown
---
version: 0.2.0
date: 2026-10-24
title: One line that says what this release is about
draft: true        # optional — drafts are not published
---

A short paragraph for people who read nothing else.

### New
- …

### Improved
- …

### Fixed
- …

### Notes
- Anything you must know before updating: data moves, things that stop working, one-time steps.
```

Use only the sections you need, in that order. Write for people who use Maru, not for the people who build it — say what changed for them, not which files changed.
