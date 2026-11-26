# vcluster

[English version](./README.md)

vCluster creates tenant clusters: fully isolated environments delivered as managed Kubernetes, or as the foundation for Slurm, Ray, Run:ai and inference clusters. Each gets its own API server, CRDs and RBAC, and runs on an existing cluster or standalone on bare metal. CNCF Certified Kubernetes.

[![x-cmd/install — vcluster Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/vcluster.svg?lang=zh)](https://x-cmd.com/install/vcluster)

## 安装

```sh
x install vcluster
```

## 代码洞察

合计: **152,049** 行代码（覆盖前 5 种语言、共 **998** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 117,675 | 10,851 | 18,623 | 827 |
| Yaml | 26,022 | 948 | 1,683 | 146 |
| Json | 6,738 | 0 | 0 | 2 |
| Pan | 811 | 0 | 38 | 9 |
| Sh | 656 | 91 | 155 | 14 |

## OpenSSF Scorecard 评分

总评分: **6.2 / 10**

评分最低的几项:

- **Code-Review** (0/10) — Found 2/30 approved changesets -- score normalized to 0
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## 源代码

- **上游仓库**: <https://github.com/loft-sh/vcluster>
- **官网**: <https://www.vcluster.com>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.38.0` (2026-11-17)
- **最近提交**: 2026-11-25
- **Release 含资产**: 40 个

## 流行度

- **Star**: 11,410 · **Fork**: 636 · **开放 issue**: 789 · **贡献者**: 180

## 累计统计

- **发布数**: 755 · **已合并 PR**: 2971 · **开放 PR**: 82 · **已关闭 issue**: 659 · **开放 issue**: 130 · **提交数**: 4549

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-27 | 32 | 24 | 14 | 1 | 9 | 26 |
| last60d | 2026-09-27 | 48 | 40 | 31 | 4 | 21 | 48 |
| 90d | 2026-08-28 | 66 | 49 | 37 | 6 | 21 | 76 |
| last180d | 2026-05-30 | 100 | 171 | 56 | 13 | 31 | 191 |
| 360d | 2025-12-01 | 100 | 629 | 70 | 38 | 43 | 465 |
| last720d | 2024-12-06 | 100 | 1446 | 78 | 117 | 66 | 1090 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
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

## 改进这些数据

vcluster 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `vcluster` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/vcluster.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261126.yml` · 2026-11-26T08:43:23Z._
