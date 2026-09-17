# vcluster

[English version](./README.md)

vCluster creates tenant clusters: fully isolated environments delivered as managed Kubernetes, or as the foundation for Slurm, Ray, Run:ai and inference clusters. Each gets its own API server, CRDs and RBAC, and runs on an existing cluster or standalone on bare metal. CNCF Certified Kubernetes.

![vcluster](https://repo.x-cmd.io/vcluster.svg?lang=zh)

## 安装

```sh
x install vcluster
```

## 代码洞察

合计: **140,507** 行代码（覆盖前 5 种语言、共 **921** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 107,594 | 9,829 | 17,240 | 759 |
| Yaml | 24,727 | 912 | 1,670 | 138 |
| Json | 6,655 | 0 | 0 | 2 |
| Pan | 754 | 0 | 32 | 9 |
| Sh | 630 | 84 | 146 | 13 |

## OpenSSF Scorecard 评分

总评分: **6.1 / 10**

评分最低的几项:

- **Code-Review** (1/10) — Found 3/26 approved changesets -- score normalized to 1
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## 源代码

- **上游仓库**: <https://github.com/loft-sh/vcluster>
- **官网**: <https://www.vcluster.com>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.37.1` (2026-09-14)
- **最近提交**: 2026-09-02
- **Release 含资产**: 45 个

## 流行度

- **Star**: 11,303 · **Fork**: 603 · **开放 issue**: 763 · **贡献者**: 171

## 累计统计

- **发布数**: 704 · **已合并 PR**: 2924 · **开放 PR**: 56 · **已关闭 issue**: 653 · **开放 issue**: 110 · **提交数**: 4473

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-18 | 22 | 9 | 21 | 2 | 3 | 24 |
| last60d | 2026-07-19 | 43 | 43 | 24 | 4 | 7 | 58 |
| 90d | 2026-06-19 | 63 | 79 | 25 | 7 | 10 | 80 |
| last180d | 2026-03-21 | 100 | 309 | 42 | 16 | 19 | 238 |
| 360d | 2025-09-22 | 100 | 713 | 45 | 39 | 25 | 486 |
| last720d | 2024-09-27 | 100 | 1497 | 52 | 130 | 46 | 1197 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [bundle-standalone.sh](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/bundle-standalone.sh) | 4.2 KiB | `other` |
| [checksums.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/checksums.txt) | 4.0 KiB | `other` |
| [checksums.txt.sigstore.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/checksums.txt.sigstore.json) | 10.1 KiB | `other` |
| [download-images.sh](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/download-images.sh) | 2.2 KiB | `other` |
| [images-optional.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/images-optional.txt) | 535 B | `other` |
| [images-private-nodes-optional.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/images-private-nodes-optional.txt) | 224 B | `other` |
| [images-private-nodes.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/images-private-nodes.txt) | 188 B | `other` |
| [images.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/images.txt) | 94 B | `other` |
| [install-standalone.sh](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/install-standalone.sh) | 15.8 KiB | `other` |
| [push-images.sh](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/push-images.sh) | 3.9 KiB | `other` |
| [syncer-linux-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/syncer-linux-amd64) | 110.5 MiB | `native/linux/x64` |
| [syncer-linux-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/syncer-linux-amd64.sbom) | 365.0 KiB | `native/linux/x64` |
| [syncer-linux-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/syncer-linux-arm64) | 102.9 MiB | `native/linux/arm64` |
| [syncer-linux-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/syncer-linux-arm64.sbom) | 366.4 KiB | `native/linux/arm64` |
| [values.schema.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/values.schema.json) | 245.0 KiB | `other` |
| [vcluster-architecture-auto-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-architecture-auto-nodes.png) | 67.8 KiB | `other` |
| [vcluster-architecture-dedicated-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-architecture-dedicated-nodes.png) | 50.3 KiB | `other` |
| [vcluster-architecture-private-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-architecture-private-nodes.png) | 40.9 KiB | `other` |
| [vcluster-architecture-shared-nodes.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-architecture-shared-nodes.png) | 36.3 KiB | `other` |
| [vcluster-architecture-standalone.png](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-architecture-standalone.png) | 39.2 KiB | `other` |
| [vcluster-darwin-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-darwin-amd64) | 98.9 MiB | `native/darwin/x64` |
| [vcluster-darwin-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-darwin-amd64.sbom) | 357.4 KiB | `native/darwin/x64` |
| [vcluster-darwin-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-darwin-arm64) | 92.7 MiB | `native/darwin/arm64` |
| [vcluster-darwin-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-darwin-arm64.sbom) | 357.4 KiB | `native/darwin/arm64` |
| [vcluster-images-k8s-1.30.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-images-k8s-1.30.txt) | 124 B | `other` |
| [vcluster-images-k8s-1.31.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-images-k8s-1.31.txt) | 124 B | `other` |
| [vcluster-images-k8s-1.32.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-images-k8s-1.32.txt) | 124 B | `other` |
| [vcluster-images-k8s-1.33.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-images-k8s-1.33.txt) | 124 B | `other` |
| [vcluster-images-k8s-1.34.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-images-k8s-1.34.txt) | 123 B | `other` |
| [vcluster-images-k8s-1.35.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-images-k8s-1.35.txt) | 123 B | `other` |
| [vcluster-images-k8s-1.36.txt](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-images-k8s-1.36.txt) | 123 B | `other` |
| [vcluster-linux-amd64](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-linux-amd64) | 96.7 MiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-linux-amd64-standalone) | 158.6 MiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone-fips](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-linux-amd64-standalone-fips) | 211.6 MiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone-fips.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-linux-amd64-standalone-fips.sbom.json) | 564.4 KiB | `native/linux/x64` |
| [vcluster-linux-amd64-standalone.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-linux-amd64-standalone.sbom.json) | 561.3 KiB | `native/linux/x64` |
| [vcluster-linux-amd64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-linux-amd64.sbom) | 360.2 KiB | `native/linux/x64` |
| [vcluster-linux-arm64](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-linux-arm64) | 89.9 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-linux-arm64-standalone) | 147.7 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone-fips](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-linux-arm64-standalone-fips) | 199.6 MiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone-fips.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-linux-arm64-standalone-fips.sbom.json) | 565.6 KiB | `native/linux/arm64` |
| [vcluster-linux-arm64-standalone.sbom.json](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-linux-arm64-standalone.sbom.json) | 562.4 KiB | `native/linux/arm64` |
| [vcluster-linux-arm64.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-linux-arm64.sbom) | 360.2 KiB | `native/linux/arm64` |
| [vcluster-windows-amd64.exe](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-windows-amd64.exe) | 98.9 MiB | `native/win/x64` |
| [vcluster-windows-amd64.exe.sbom](https://github.com/loft-sh/vcluster/releases/download/v0.37.1/vcluster-windows-amd64.exe.sbom) | 362.5 KiB | `native/win/x64` |

## 改进这些数据

vcluster 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `vcluster` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/vcluster.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260917.yml` · 2026-09-17T05:54:03Z._
