# How Automation Works

> This document explains how awesome-beeper stays up-to-date.

---

## Overview

This repository uses GitHub Actions to automatically track Beeper ecosystem changes:

```
┌─────────────────────────────────────────┐
│  Daily: official-updates.yml            │
│  • Fetches GitHub releases              │
│  • Fetches npm versions                 │
│  • Compares with previous snapshot      │
│  • Creates PR if changes found          │
└─────────────────────────────────────────┘

┌─────────────────────────────────────────┐
│  Weekly: community-digest.yml           │
│  • Fetches popular Discussions          │
│  • Creates digest Issue for curation    │
└─────────────────────────────────────────┘
```

---

## Sources Tracked

| Source | Type | Frequency |
|--------|------|-----------|
| beeper/bridge-manager | GitHub Releases | Daily |
| @beeper/desktop-api | npm Registry | Daily |
| GitHub Discussions | Community | Weekly |

---

## Human Curation

Automation creates PRs, but humans:
- Add context ("What this means")
- Verify tags (`[official]`, `[community]`, `[unverified]`)
- Promote valuable community discoveries

---

## Scripts

Located in `/scripts`:
- `official-updates.ts` - Fetches official releases
- `community-digest.ts` - Creates weekly digest
- `lib/` - Shared utilities

---

## Contributing to Automation

See [CONTRIBUTING.md](../CONTRIBUTING.md) or open an Issue.
