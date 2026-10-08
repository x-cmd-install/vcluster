# vcluster

[English version](./README.md)

vCluster creates tenant clusters: fully isolated environments delivered as managed Kubernetes, or as the foundation for Slurm, Ray, Run:ai and inference clusters. Each gets its own API server, CRDs and RBAC, and runs on an existing cluster or standalone on bare metal. CNCF Certified Kubernetes.

[![x-cmd/install — vcluster Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/vcluster.svg?lang=zh)](https://x-cmd.com/install/vcluster)

## 安装

```sh
x install vcluster
```

## 代码洞察

合计: **145,147** 行代码（覆盖前 5 种语言、共 **950** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 111,403 | 10,227 | 17,837 | 784 |
| Yaml | 25,546 | 937 | 1,671 | 142 |
| Json | 6,664 | 0 | 0 | 2 |
| Pan | 757 | 0 | 34 | 9 |
| Sh | 630 | 84 | 146 | 13 |

## OpenSSF Scorecard 评分

总评分: **5.8 / 10**

评分最低的几项:

- **Code-Review** (0/10) — Found 1/30 approved changesets -- score normalized to 0
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## 源代码

- **上游仓库**: <https://github.com/loft-sh/vcluster>
- **官网**: <https://www.vcluster.com>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.38.0-alpha.1` (2026-10-05)
- **最近提交**: 2026-10-05
- **Release 含资产**: 45 个

## 流行度

- **Star**: 11,335 · **Fork**: 612 · **开放 issue**: 765 · **贡献者**: 171

## 累计统计

- **发布数**: 712 · **已合并 PR**: 2929 · **开放 PR**: 62 · **已关闭 issue**: 654 · **开放 issue**: 111 · **提交数**: 4502

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-08 | 15 | 5 | 15 | 1 | 1 | 18 |
| last60d | 2026-08-09 | 30 | 16 | 28 | 3 | 5 | 69 |
| 90d | 2026-07-10 | 55 | 61 | 30 | 6 | 9 | 96 |
| last180d | 2026-04-11 | 100 | 235 | 44 | 13 | 13 | 214 |
| 360d | 2025-10-13 | 100 | 682 | 51 | 39 | 25 | 484 |
| last720d | 2024-10-18 | 100 | 1465 | 58 | 123 | 47 | 1147 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
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

## 改进这些数据

vcluster 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `vcluster` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/vcluster.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261008.yml` · 2026-10-08T06:29:28Z._
