# vcluster

[中文版本](./README.cn.md)

vCluster creates tenant clusters: fully isolated environments delivered as managed Kubernetes, or as the foundation for Slurm, Ray, Run:ai and inference clusters. Each gets its own API server, CRDs and RBAC, and runs on an existing cluster or standalone on bare metal. CNCF Certified Kubernetes.

[![x-cmd/install — vcluster Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/vcluster.svg)](https://x-cmd.com/install/vcluster)

## Install

```sh
x install vcluster
```

## Code insight

Total: **148,930** lines of code across **979** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 114,979 | 10,604 | 18,270 | 810 |
| Yaml | 25,653 | 948 | 1,671 | 144 |
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

- **Latest**: `v0.38.0` (2026-11-17)
- **Last commit**: 2026-11-19
- **Assets in release**: 40

## Popularity

- **Stars**: 11,394 · **Forks**: 636 · **Open issues**: 787 · **Contributors**: 178

## Totals (cumulative)

- **Releases**: 755 · **Merged PRs**: 2969 · **Open PRs**: 81 · **Closed issues**: 659 · **Open issues**: 128 · **Commits**: 4543

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-24 | 32 | 22 | 15 | 1 | 9 | 20 |
| last60d | 2026-09-24 | 49 | 38 | 30 | 4 | 19 | 42 |
| 90d | 2026-08-25 | 71 | 50 | 45 | 7 | 19 | 70 |
| last180d | 2026-05-27 | 100 | 177 | 56 | 13 | 29 | 185 |
| 360d | 2025-11-28 | 100 | 630 | 69 | 39 | 41 | 459 |
| last720d | 2024-12-03 | 100 | 1453 | 77 | 118 | 64 | 1095 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [bundle-standalone.sh](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/bundle-standalone.sh) | 4.2 KiB | `other` |
| [checksums.txt](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/checksums.txt) | 3.5 KiB | `other` |
| [checksums.txt.sigstore.json](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/checksums.txt.sigstore.json) | 9.9 KiB | `other` |
| [download-images.sh](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/download-images.sh) | 2.2 KiB | `other` |
| [images-optional.txt](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/images-optional.txt) | 214 B | `other` |
| [images-private-nodes-optional.txt](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/images-private-nodes-optional.txt) | 224 B | `other` |
| [images-private-nodes.txt](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/images-private-nodes.txt) | 188 B | `other` |
| [images.txt](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/images.txt) | 94 B | `other` |
| [install-standalone.sh](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/install-standalone.sh) | 15.8 KiB | `other` |
| [push-images.sh](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/push-images.sh) | 3.9 KiB | `other` |
| [syncer-linux-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/syncer-linux-amd64) | 111.8 MiB | `native/linux/x64` |
| [syncer-linux-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/syncer-linux-amd64.sbom) | 376.1 KiB | `native/linux/x64` |
| [syncer-linux-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/syncer-linux-arm64) | 104.0 MiB | `native/linux/arm64` |
| [syncer-linux-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/syncer-linux-arm64.sbom) | 377.5 KiB | `native/linux/arm64` |
| [values.schema.json](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/values.schema.json) | 248.7 KiB | `other` |
| [vcluster-architecture-auto-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-architecture-auto-nodes.png) | 67.8 KiB | `other` |
| [vcluster-architecture-dedicated-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-architecture-dedicated-nodes.png) | 50.3 KiB | `other` |
| [vcluster-architecture-private-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-architecture-private-nodes.png) | 64.2 KiB | `other` |
| [vcluster-architecture-shared-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-architecture-shared-nodes.png) | 31.0 KiB | `other` |
| [vcluster-architecture-standalone.png](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-architecture-standalone.png) | 39.2 KiB | `other` |
| [vcluster-darwin-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-darwin-amd64) | 101.0 MiB | `native/darwin/x64` |
| [vcluster-darwin-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-darwin-amd64.sbom) | 374.1 KiB | `native/darwin/x64` |
| [vcluster-darwin-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-darwin-arm64) | 94.7 MiB | `native/darwin/arm64` |
| [vcluster-darwin-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-darwin-arm64.sbom) | 374.1 KiB | `native/darwin/arm64` |
| [vcluster-images-k8s-1.35.txt](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-images-k8s-1.35.txt) | 125 B | `other` |
| [vcluster-images-k8s-1.36.txt](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-images-k8s-1.36.txt) | 124 B | `other` |
| [vcluster-linux-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-linux-amd64) | 98.8 MiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-linux-amd64-standalone) | 159.6 MiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone-fips](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-linux-amd64-standalone-fips) | 213.1 MiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone-fips.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-linux-amd64-standalone-fips.sbom.json) | 555.3 KiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-linux-amd64-standalone.sbom.json) | 552.2 KiB | `native/linux/x64` |
| [vcluster-linux-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-linux-amd64.sbom) | 376.9 KiB | `native/linux/x64` |
| [vcluster-linux-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-linux-arm64) | 91.9 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-linux-arm64-standalone) | 148.6 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone-fips](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-linux-arm64-standalone-fips) | 201.0 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone-fips.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-linux-arm64-standalone-fips.sbom.json) | 556.5 KiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-linux-arm64-standalone.sbom.json) | 553.3 KiB | `native/linux/arm64` |
| [vcluster-linux-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-linux-arm64.sbom) | 376.9 KiB | `native/linux/arm64` |
| [vcluster-windows-amd64.exe](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-windows-amd64.exe) | 101.1 MiB | `native/win/x64` |
| [vcluster-windows-amd64.exe.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.38.0/vcluster-windows-amd64.exe.sbom) | 379.3 KiB | `native/win/x64` |

## Distribution status

Reported by **12** distros on [repology.org](https://repology.org/project/vcluster). **4** are ✅ on the latest upstream release, **6** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `0.38.0` | ✅ latest |
| Nix unstable | `0.35.1` | ⚠️ outdated |

## Improve this data

Install metadata for vcluster lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `vcluster` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/vcluster.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261123.yml` · 2026-11-23T09:39:08Z._
