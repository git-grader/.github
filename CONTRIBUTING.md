# Contributing to GitGrader

Thanks for helping make programming assessment reliable and transparent.

## Quick start

1. **Discuss first** for anything non-trivial: open an issue describing the
   problem before writing code
2. **Fork and branch**: `feat/<topic>`, `fix/<topic>`, or `docs/<topic>`
3. **Keep PRs focused**: one concern per pull request
4. **Write it down**: user-visible changes need docs; behaviour changes need tests

## Commit style

- Present tense, imperative: `add runner timeout config`
- Reference issues where relevant: `fix submission dedup (#42)`

## Pull requests

- Fill in the PR template — what changed, why, and how it was verified
- CI must be green before review
- A maintainer review is required to merge

## Brand assets

The visual identity is locked. Any PR touching `brand/01_logo/**` or
`brand/02_color/**` in the [brand repository](https://github.com/git-grader/brand)
fails CI unless a maintainer adds the `brand-approved` label. Regenerate
assets only through the scripted pipeline (`scripts/`), never by hand-editing
generated files.

## Questions?

See [SUPPORT.md](SUPPORT.md).
