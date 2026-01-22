# Contributing to Awesome Beeper

Thank you for your interest in contributing! This document explains how to contribute to this community-driven Beeper documentation project.

## Ways to Contribute

### 💬 Share a Discovery (Easiest)

Found a cool trick, workaround, or undocumented feature? Share it in [GitHub Discussions](https://github.com/robertogogoni/awesome-beeper/discussions)!

1. Go to [Discussions → Tips & Discoveries](https://github.com/robertogogoni/awesome-beeper/discussions/new?category=tips-discoveries)
2. Fill out the template
3. Submit!

Popular discoveries get promoted to the main documentation with full credit.

### 📝 Improve Documentation (PR)

Want to add or fix documentation directly?

1. Fork this repository
2. Create a branch: `git checkout -b my-improvement`
3. Make your changes
4. Submit a Pull Request

### 🐛 Report Issues

Found an error or outdated information? [Open an Issue](https://github.com/robertogogoni/awesome-beeper/issues/new).

---

## Documentation Guidelines

### Source Tags

Every piece of information should have a source tag:

| Tag | When to Use |
|-----|-------------|
| `[official]` | From Beeper team, official docs, or release notes |
| `[community]` | Tested and verified by community members |
| `[unverified]` | Reported but not yet confirmed |

### Reference Format

Use footnote-style references:

```markdown
Voice transcription uses Whisper AI [^1] and works offline on Apple Silicon [^2].

### References
[^1]: [Beeper Desktop v4.2.0 Release Notes](https://...)
[^2]: [@tulir in Developer Community](https://...) - 2026-01-15
```

### Changelog Entry Format

```markdown
## v4.2.0 - 2026-01-15

`[official]`

### Added
- Feature description [^1]

### Fixed
- Bug fix description [^2]

### Community Notes
`[community]` Additional tips from users [^3]

### References
[^1]: [Source](url)
```

---

## Code of Conduct

- Be respectful and constructive
- Give credit to original sources
- Don't share private/confidential information
- When in doubt, tag as `[unverified]`

---

## Questions?

Open a [Discussion in General](https://github.com/robertogogoni/awesome-beeper/discussions/new?category=general) and we'll help!
