# vcluster

[English version](./README.md)

vCluster creates tenant clusters: fully isolated environments delivered as managed Kubernetes, or as the foundation for Slurm, Ray, Run:ai and inference clusters. Each gets its own API server, CRDs and RBAC, and runs on an existing cluster or standalone on bare metal. CNCF Certified Kubernetes.

![vcluster](https://repo.x-cmd.io/vcluster.svg)

## 安装

```sh
x install vcluster
```

## 源代码

- **上游仓库**: <https://github.com/loft-sh/vcluster>
- **官网**: <https://www.vcluster.com>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.37.0` (2026-09-08)
- **最近提交**: 2026-09-02
- **Release 含资产**: 26 个
- **发布时间**: 2026-08-03T12:35:44Z

## 流行度

- **Star**: 11,296 · **Fork**: 597 · **开放 issue**: 763 · **贡献者**: 171

## 累计统计

- **发布数**: 700 · **已合并 PR**: 2924 · **开放 PR**: 50 · **已关闭 issue**: 653 · **开放 issue**: 110 · **提交数**: 4473

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 18 | 11 | 15 | 2 | 3 | 36 |
| 90d | 2026-06-12 | 66 | 92 | 19 | 7 | 11 | 88 |
| 360d | 2025-09-15 | 100 | 725 | 39 | 40 | 25 | 494 |

## 代码规模

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

## 改进这些数据

vcluster 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `vcluster` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/vcluster.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T05:21:25Z._
