# Release notes: 2026-05-25 — github-description-seo

**Status:** Ready for review  
**Repo:** li-langverse/li-std-math  
**Author:** agent (WP-A4)

## Summary (one sentence)

Replace template GitHub description with HPC spatial-math blurb; README tagline + `.github/repo-description`.

## Agent continuation (required)

1. Read: `.github/repo-description`.
2. Run: `gh repo view li-langverse/li-std-math --json description`.
3. Then: numerics/API work on `main`.
4. Blocked on: WP-H2 — **none**.

## Changed (specific)

- `.github/repo-description`, `README.md`, `CHANGELOG.md`.

## Not changed (scope fence)

- `src/` math APIs, `lic` codegen, physics benches — **not** touched.
- LICENSE SPDX sweep — WP-H2.
- `li-std-core` — separate repo.

## Breaking changes

None.

## Security

N/A.

## Performance

N/A.

## Downstream

N/A.
