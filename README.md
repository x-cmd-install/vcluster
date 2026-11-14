# vcluster

[中文版本](./README.cn.md)

vCluster creates tenant clusters: fully isolated environments delivered as managed Kubernetes, or as the foundation for Slurm, Ray, Run:ai and inference clusters. Each gets its own API server, CRDs and RBAC, and runs on an existing cluster or standalone on bare metal. CNCF Certified Kubernetes.

[![x-cmd/install — vcluster Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/vcluster.svg)](https://x-cmd.com/install/vcluster)

## Install

```sh
x install vcluster
```

## Code insight

Total: **148,048** lines of code across **977** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 114,107 | 10,528 | 18,179 | 808 |
| Yaml | 25,643 | 948 | 1,671 | 144 |
| Json | 6,738 | 0 | 0 | 2 |
| Pan | 757 | 0 | 34 | 9 |
| Sh | 656 | 91 | 155 | 14 |

## OpenSSF Scorecard

Overall score: **6.2 / 10**

Lowest-scoring checks:

- **Code-Review** (0/10) — Found 1/30 approved changesets -- score normalized to 0
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## Source

- **Upstream**: <https://github.com/loft-sh/vcluster>
- **Homepage**: <https://www.vcluster.com>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.37.7` (2026-11-10)
- **Last commit**: 2026-11-13
- **Assets in release**: 40

## Popularity

- **Stars**: 11,378 · **Forks**: 630 · **Open issues**: 786 · **Contributors**: 177

## Totals (cumulative)

- **Releases**: 753 · **Merged PRs**: 2964 · **Open PRs**: 81 · **Closed issues**: 658 · **Open issues**: 128 · **Commits**: 4539

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-15 | 40 | 27 | 22 | 0 | 15 | 25 |
| last60d | 2026-09-15 | 49 | 38 | 30 | 3 | 19 | 53 |
| 90d | 2026-08-16 | 71 | 48 | 46 | 7 | 21 | 96 |
| last180d | 2026-05-18 | 100 | 181 | 58 | 14 | 29 | 194 |
| 360d | 2025-11-19 | 100 | 634 | 70 | 38 | 41 | 462 |
| last720d | 2024-11-24 | 100 | 1458 | 77 | 121 | 64 | 1108 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [bundle-standalone.sh](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/bundle-standalone.sh) | 4.2 KiB | `other` |
| [checksums.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/checksums.txt) | 3.5 KiB | `other` |
| [checksums.txt.sigstore.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/checksums.txt.sigstore.json) | 10.1 KiB | `other` |
| [download-images.sh](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/download-images.sh) | 2.2 KiB | `other` |
| [images-optional.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/images-optional.txt) | 214 B | `other` |
| [images-private-nodes-optional.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/images-private-nodes-optional.txt) | 224 B | `other` |
| [images-private-nodes.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/images-private-nodes.txt) | 188 B | `other` |
| [images.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/images.txt) | 94 B | `other` |
| [install-standalone.sh](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/install-standalone.sh) | 15.8 KiB | `other` |
| [push-images.sh](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/push-images.sh) | 3.9 KiB | `other` |
| [syncer-linux-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/syncer-linux-amd64) | 110.4 MiB | `native/linux/x64` |
| [syncer-linux-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/syncer-linux-amd64.sbom) | 365.0 KiB | `native/linux/x64` |
| [syncer-linux-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/syncer-linux-arm64) | 102.8 MiB | `native/linux/arm64` |
| [syncer-linux-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/syncer-linux-arm64.sbom) | 366.4 KiB | `native/linux/arm64` |
| [values.schema.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/values.schema.json) | 246.5 KiB | `other` |
| [vcluster-architecture-auto-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-architecture-auto-nodes.png) | 67.8 KiB | `other` |
| [vcluster-architecture-dedicated-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-architecture-dedicated-nodes.png) | 50.3 KiB | `other` |
| [vcluster-architecture-private-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-architecture-private-nodes.png) | 40.9 KiB | `other` |
| [vcluster-architecture-shared-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-architecture-shared-nodes.png) | 36.3 KiB | `other` |
| [vcluster-architecture-standalone.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-architecture-standalone.png) | 39.2 KiB | `other` |
| [vcluster-darwin-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-darwin-amd64) | 98.9 MiB | `native/darwin/x64` |
| [vcluster-darwin-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-darwin-amd64.sbom) | 357.4 KiB | `native/darwin/x64` |
| [vcluster-darwin-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-darwin-arm64) | 92.8 MiB | `native/darwin/arm64` |
| [vcluster-darwin-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-darwin-arm64.sbom) | 357.4 KiB | `native/darwin/arm64` |
| [vcluster-images-k8s-1.35.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-images-k8s-1.35.txt) | 125 B | `other` |
| [vcluster-images-k8s-1.36.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-images-k8s-1.36.txt) | 124 B | `other` |
| [vcluster-linux-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-linux-amd64) | 96.7 MiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-linux-amd64-standalone) | 159.0 MiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone-fips](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-linux-amd64-standalone-fips) | 212.4 MiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone-fips.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-linux-amd64-standalone-fips.sbom.json) | 564.5 KiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-linux-amd64-standalone.sbom.json) | 561.3 KiB | `native/linux/x64` |
| [vcluster-linux-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-linux-amd64.sbom) | 360.2 KiB | `native/linux/x64` |
| [vcluster-linux-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-linux-arm64) | 90.0 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-linux-arm64-standalone) | 148.0 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone-fips](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-linux-arm64-standalone-fips) | 200.4 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone-fips.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-linux-arm64-standalone-fips.sbom.json) | 565.6 KiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-linux-arm64-standalone.sbom.json) | 562.4 KiB | `native/linux/arm64` |
| [vcluster-linux-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-linux-arm64.sbom) | 360.2 KiB | `native/linux/arm64` |
| [vcluster-windows-amd64.exe](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-windows-amd64.exe) | 99.0 MiB | `native/win/x64` |
| [vcluster-windows-amd64.exe.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.6/vcluster-windows-amd64.exe.sbom) | 362.5 KiB | `native/win/x64` |

## Distribution status

Reported by **12** distros on [repology.org](https://repology.org/project/vcluster). **4** are ✅ on the latest upstream release, **6** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `0.37.6` | ✅ latest |
| Nix unstable | `0.35.1` | ⚠️ outdated |

## Improve this data

Install metadata for vcluster lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `vcluster` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/vcluster.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261114.yml` · 2026-11-14T07:12:20Z._
