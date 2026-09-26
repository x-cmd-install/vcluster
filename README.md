# vcluster

[中文版本](./README.cn.md)

vCluster creates tenant clusters: fully isolated environments delivered as managed Kubernetes, or as the foundation for Slurm, Ray, Run:ai and inference clusters. Each gets its own API server, CRDs and RBAC, and runs on an existing cluster or standalone on bare metal. CNCF Certified Kubernetes.

[![x-cmd/install — vcluster Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/vcluster.svg)](https://x-cmd.com/install/vcluster)

## Install

```sh
x install vcluster
```

## Code insight

Total: **144,273** lines of code across **945** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 110,526 | 10,140 | 17,678 | 779 |
| Yaml | 25,549 | 937 | 1,671 | 142 |
| Json | 6,664 | 0 | 0 | 2 |
| Pan | 757 | 0 | 34 | 9 |
| Sh | 630 | 84 | 146 | 13 |

## OpenSSF Scorecard

Overall score: **5.9 / 10**

Lowest-scoring checks:

- **Code-Review** (1/10) — Found 3/26 approved changesets -- score normalized to 1
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions

## Source

- **Upstream**: <https://github.com/loft-sh/vcluster>
- **Homepage**: <https://www.vcluster.com>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.36.3-rc.1` (2026-09-23)
- **Last commit**: 2026-09-24
- **Assets in release**: 45

## Popularity

- **Stars**: 11,317 · **Forks**: 608 · **Open issues**: 763 · **Contributors**: 171

## Totals (cumulative)

- **Releases**: 707 · **Merged PRs**: 2929 · **Open PRs**: 55 · **Closed issues**: 653 · **Open issues**: 110 · **Commits**: 4497

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-27 | 21 | 10 | 9 | 1 | 0 | 27 |
| last60d | 2026-07-28 | 41 | 33 | 21 | 3 | 6 | 79 |
| 90d | 2026-06-28 | 56 | 80 | 23 | 6 | 8 | 101 |
| last180d | 2026-03-30 | 100 | 291 | 40 | 15 | 15 | 250 |
| 360d | 2025-10-01 | 100 | 700 | 44 | 39 | 25 | 498 |
| last720d | 2024-10-06 | 100 | 1493 | 51 | 127 | 46 | 1199 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [bundle-standalone.sh](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/bundle-standalone.sh) | 4.2 KiB | `other` |
| [checksums.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/checksums.txt) | 4.0 KiB | `other` |
| [checksums.txt.sigstore.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/checksums.txt.sigstore.json) | 10.0 KiB | `other` |
| [download-images.sh](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/download-images.sh) | 2.2 KiB | `other` |
| [images-optional.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/images-optional.txt) | 535 B | `other` |
| [images-private-nodes-optional.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/images-private-nodes-optional.txt) | 224 B | `other` |
| [images-private-nodes.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/images-private-nodes.txt) | 188 B | `other` |
| [images.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/images.txt) | 94 B | `other` |
| [install-standalone.sh](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/install-standalone.sh) | 15.8 KiB | `other` |
| [push-images.sh](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/push-images.sh) | 3.9 KiB | `other` |
| [syncer-linux-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/syncer-linux-amd64) | 110.5 MiB | `native/linux/x64` |
| [syncer-linux-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/syncer-linux-amd64.sbom) | 365.0 KiB | `native/linux/x64` |
| [syncer-linux-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/syncer-linux-arm64) | 102.9 MiB | `native/linux/arm64` |
| [syncer-linux-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/syncer-linux-arm64.sbom) | 366.4 KiB | `native/linux/arm64` |
| [values.schema.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/values.schema.json) | 245.0 KiB | `other` |
| [vcluster-architecture-auto-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-architecture-auto-nodes.png) | 67.8 KiB | `other` |
| [vcluster-architecture-dedicated-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-architecture-dedicated-nodes.png) | 50.3 KiB | `other` |
| [vcluster-architecture-private-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-architecture-private-nodes.png) | 40.9 KiB | `other` |
| [vcluster-architecture-shared-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-architecture-shared-nodes.png) | 36.3 KiB | `other` |
| [vcluster-architecture-standalone.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-architecture-standalone.png) | 39.2 KiB | `other` |
| [vcluster-darwin-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-darwin-amd64) | 98.9 MiB | `native/darwin/x64` |
| [vcluster-darwin-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-darwin-amd64.sbom) | 357.4 KiB | `native/darwin/x64` |
| [vcluster-darwin-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-darwin-arm64) | 92.7 MiB | `native/darwin/arm64` |
| [vcluster-darwin-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-darwin-arm64.sbom) | 357.4 KiB | `native/darwin/arm64` |
| [vcluster-images-k8s-1.30.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-images-k8s-1.30.txt) | 124 B | `other` |
| [vcluster-images-k8s-1.31.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-images-k8s-1.31.txt) | 124 B | `other` |
| [vcluster-images-k8s-1.32.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-images-k8s-1.32.txt) | 124 B | `other` |
| [vcluster-images-k8s-1.33.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-images-k8s-1.33.txt) | 124 B | `other` |
| [vcluster-images-k8s-1.34.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-images-k8s-1.34.txt) | 123 B | `other` |
| [vcluster-images-k8s-1.35.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-images-k8s-1.35.txt) | 123 B | `other` |
| [vcluster-images-k8s-1.36.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-images-k8s-1.36.txt) | 123 B | `other` |
| [vcluster-linux-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-linux-amd64) | 96.7 MiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-linux-amd64-standalone) | 159.1 MiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone-fips](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-linux-amd64-standalone-fips) | 212.3 MiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone-fips.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-linux-amd64-standalone-fips.sbom.json) | 564.4 KiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-linux-amd64-standalone.sbom.json) | 561.3 KiB | `native/linux/x64` |
| [vcluster-linux-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-linux-amd64.sbom) | 360.2 KiB | `native/linux/x64` |
| [vcluster-linux-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-linux-arm64) | 89.9 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-linux-arm64-standalone) | 148.1 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone-fips](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-linux-arm64-standalone-fips) | 200.2 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone-fips.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-linux-arm64-standalone-fips.sbom.json) | 565.6 KiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-linux-arm64-standalone.sbom.json) | 562.4 KiB | `native/linux/arm64` |
| [vcluster-linux-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-linux-arm64.sbom) | 360.2 KiB | `native/linux/arm64` |
| [vcluster-windows-amd64.exe](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-windows-amd64.exe) | 98.9 MiB | `native/win/x64` |
| [vcluster-windows-amd64.exe.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.2/vcluster-windows-amd64.exe.sbom) | 362.5 KiB | `native/win/x64` |

## Improve this data

Install metadata for vcluster lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `vcluster` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/vcluster.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260926.yml` · 2026-09-26T05:18:42Z._
