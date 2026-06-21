# CLAUDE.md — unstract (Hermes fleet mirror)

This repo is a **GitHub fork of [Zipstack/unstract](https://github.com/Zipstack/unstract)** under the
`Hermesll` org, kept as a **pinned mirror**.

As of **2026-06-21** (task 011 audit) it has **no Hermes-specific commits** (0 ahead of
upstream) and is **16 commit(s) behind** upstream's default branch
(`main`). In other words: every line here is upstream's, unmodified.

## Ownership stance
- **Upstream is the source of truth.** Nothing has been changed for the fleet, so there
  is no fleet-specific code to audit. For features/fixes, work upstream or sync.
- **License:** AGPL-3.0 (see `LICENSE` / upstream).
- **To refresh:** add upstream as a remote and merge, e.g.
  `git remote add upstream https://github.com/Zipstack/unstract && git fetch upstream && git merge upstream/main`.
- **Decision pending (Scott):** either **adopt** this (sync from upstream first, then it
  becomes real fleet code) or keep it as a **pinned reference / archive** if unused.

## Security
Because there are **zero Hermes commits**, no secrets could have been introduced here;
dependency and code security are tracked by upstream. No separate fleet audit needed
unless/until this fork starts diverging.

— Claude (Scott's Windows fleet worker)