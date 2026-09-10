# vcluster

[中文版本](./README.cn.md)

vCluster creates tenant clusters: fully isolated environments delivered as managed Kubernetes, or as the foundation for Slurm, Ray, Run:ai and inference clusters. Each gets its own API server, CRDs and RBAC, and runs on an existing cluster or standalone on bare metal. CNCF Certified Kubernetes.

![vcluster](https://repo.x-cmd.io/vcluster.svg)

## Install

```sh
x install vcluster
```

## Source

- **Upstream**: <https://github.com/loft-sh/vcluster>
- **Homepage**: <https://www.vcluster.com>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.37.0` (2026-09-08)
- **Last commit**: 2026-09-02
- **Assets in release**: 26
- **Published**: 2026-08-03T12:35:44Z

## Popularity

- **Stars**: 11,296 · **Forks**: 597 · **Open issues**: 763 · **Contributors**: 171

## Totals (cumulative)

- **Releases**: 700 · **Merged PRs**: 2924 · **Open PRs**: 50 · **Closed issues**: 653 · **Open issues**: 110 · **Commits**: 4473

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 18 | 11 | 15 | 2 | 3 | 36 |
| 90d | 2026-06-12 | 66 | 92 | 19 | 7 | 11 | 88 |
| 360d | 2025-09-15 | 100 | 725 | 39 | 40 | 25 | 494 |

## Code size

Total: **140,507** lines of code across **921** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 107,594 | 9,829 | 17,240 | 759 |
| Yaml | 24,727 | 912 | 1,670 | 138 |
| Json | 6,655 | 0 | 0 | 2 |
| Pan | 754 | 0 | 32 | 9 |
| Sh | 630 | 84 | 146 | 13 |

## OpenSSF Scorecard

Overall score: **6.1 / 10**

Lowest-scoring checks:

- **Code-Review** (1/10) — Found 3/26 approved changesets -- score normalized to 1
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## Improve this data

Install metadata for vcluster lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `vcluster` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/edit/main/vcluster.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T05:21:25Z._
