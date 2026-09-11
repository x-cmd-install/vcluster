# vcluster

[中文版本](./README.cn.md)

vCluster creates tenant clusters: fully isolated environments delivered as managed Kubernetes, or as the foundation for Slurm, Ray, Run:ai and inference clusters. Each gets its own API server, CRDs and RBAC, and runs on an existing cluster or standalone on bare metal. CNCF Certified Kubernetes.

![vcluster](https://repo.x-cmd.io/vcluster.svg)

## Install

```sh
x install vcluster
```

## Code insight

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

## Source

- **Upstream**: <https://github.com/loft-sh/vcluster>
- **Homepage**: <https://www.vcluster.com>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.37.1-rc.1` (2026-09-08)
- **Last commit**: 2026-09-02
- **Assets in release**: 26

## Popularity

- **Stars**: 11,298 · **Forks**: 598 · **Open issues**: 763 · **Contributors**: 171

## Totals (cumulative)

- **Releases**: 701 · **Merged PRs**: 2924 · **Open PRs**: 50 · **Closed issues**: 653 · **Open issues**: 110 · **Commits**: 4473

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 19 | 10 | 15 | 2 | 3 | 36 |
| last60d | 2026-07-13 | 44 | 50 | 17 | 4 | 8 | 65 |
| 90d | 2026-06-13 | 65 | 92 | 19 | 7 | 11 | 88 |
| last180d | 2026-03-15 | 100 | 323 | 36 | 16 | 19 | 247 |
| 360d | 2025-09-16 | 100 | 723 | 39 | 40 | 25 | 494 |
| last720d | 2024-09-21 | 100 | 1513 | 46 | 132 | 46 | 1212 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [bundle-standalone.sh](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/bundle-standalone.sh) | 4.2 KiB | `other` |
| [checksums.txt](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/checksums.txt) | 2.8 KiB | `other` |
| [checksums.txt.pem](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/checksums.txt.pem) | 3.2 KiB | `other` |
| [checksums.txt.sig](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/checksums.txt.sig) | 96 B | `other` |
| [images-private-nodes-optional.txt](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/images-private-nodes-optional.txt) | 224 B | `other` |
| [images-private-nodes.txt](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/images-private-nodes.txt) | 188 B | `other` |
| [install-standalone.sh](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/install-standalone.sh) | 14.2 KiB | `other` |
| [syncer-linux-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/syncer-linux-amd64) | 109.3 MiB | `native/linux/x64` |
| [syncer-linux-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/syncer-linux-amd64.sbom) | 364.0 KiB | `native/linux/x64` |
| [syncer-linux-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/syncer-linux-arm64) | 101.7 MiB | `native/linux/arm64` |
| [syncer-linux-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/syncer-linux-arm64.sbom) | 365.5 KiB | `native/linux/arm64` |
| [values.schema.json](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/values.schema.json) | 223.9 KiB | `other` |
| [vcluster-darwin-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/vcluster-darwin-amd64) | 98.2 MiB | `native/darwin/x64` |
| [vcluster-darwin-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/vcluster-darwin-amd64.sbom) | 356.5 KiB | `native/darwin/x64` |
| [vcluster-darwin-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/vcluster-darwin-arm64) | 92.1 MiB | `native/darwin/arm64` |
| [vcluster-darwin-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/vcluster-darwin-arm64.sbom) | 356.5 KiB | `native/darwin/arm64` |
| [vcluster-linux-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/vcluster-linux-amd64) | 96.1 MiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/vcluster-linux-amd64-standalone) | 156.7 MiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone-fips](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/vcluster-linux-amd64-standalone-fips) | 209.6 MiB | `native/linux/x64` |
| [vcluster-linux-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/vcluster-linux-amd64.sbom) | 359.2 KiB | `native/linux/x64` |
| [vcluster-linux-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/vcluster-linux-arm64) | 89.3 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/vcluster-linux-arm64-standalone) | 145.9 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone-fips](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/vcluster-linux-arm64-standalone-fips) | 197.7 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/vcluster-linux-arm64.sbom) | 359.2 KiB | `native/linux/arm64` |
| [vcluster-windows-amd64.exe](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/vcluster-windows-amd64.exe) | 98.3 MiB | `native/win/x64` |
| [vcluster-windows-amd64.exe.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.36.1/vcluster-windows-amd64.exe.sbom) | 361.5 KiB | `native/win/x64` |

## Distribution status

Reported by **12** distros on [repology.org](https://repology.org/project/vcluster). **4** are ✅ on the latest upstream release, **6** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `0.36.1` | ✅ latest |
| Nix unstable | `0.35.1` | ⚠️ outdated |

## Improve this data

Install metadata for vcluster lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `vcluster` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/vcluster.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260911.yml` · 2026-09-11T05:10:02Z._
