# bpftop

[English version](./README.md)

bpftop provides a dynamic real-time view of running eBPF programs. It displays the average runtime, events per second, and estimated total CPU % for each program.

![bpftop](https://repo.x-cmd.io/bpftop.svg?lang=zh)

## 安装

```sh
x install bpftop
```

## 代码洞察

合计: **99,424** 行代码（覆盖前 5 种语言、共 **13** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| CHeader | 97,464 | 4,669 | 12,835 | 4 |
| Rust | 1,691 | 133 | 207 | 6 |
| Sh | 180 | 22 | 42 | 1 |
| Nix | 36 | 6 | 6 | 1 |
| C | 28 | 0 | 10 | 1 |

## 源代码

- **上游仓库**: <https://github.com/Netflix/bpftop>
- **官网**: <https://bpftop.sh>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.9.0` (2026-05-02)
- **最近提交**: 2026-07-29
- **Release 含资产**: 2 个

## 流行度

- **Star**: 2,705 · **Fork**: 129 · **开放 issue**: 30 · **贡献者**: 17

## 累计统计

- **发布数**: 17 · **已合并 PR**: 164 · **开放 PR**: 1 · **已关闭 issue**: 26 · **开放 issue**: 4 · **提交数**: 277

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-15 | 2 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-16 | 2 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-21 | 5 | 0 | 0 | 0 | 0 | 0 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [bpftop-aarch64-unknown-linux-gnu](https://github.com/Netflix/bpftop/releases/download/v0.9.0/bpftop-aarch64-unknown-linux-gnu) | 2.5 MiB | `native/linux/arm64/glibc` |
| [bpftop-x86_64-unknown-linux-gnu](https://github.com/Netflix/bpftop/releases/download/v0.9.0/bpftop-x86_64-unknown-linux-gnu) | 2.5 MiB | `native/linux/x64/glibc` |

## 发行版状态

在 [repology.org](https://repology.org/project/bpftop) 上共有 **56** 个发行版报告此项目。**12** 个 ✅ 已是最新上游版本，**29** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Debian unstable | `0.9.0.9.g5a67ec0` | ignored |
| Debian 14 | `0.9.0.8.g4c7c8c1` | ignored |
| Debian 13 | `0.5.2.20.gc23a822` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `0.7.1.4.gd579e4e` | ⚠️ outdated |
| Arch | `0.8.0` | ⚠️ outdated |
| Homebrew | `HEAD` | 🔄 rolling |
| Fedora rawhide | `0.9.0` | ✅ latest |
| Nix unstable | `0.9.0` | ✅ latest |
| Void | `0.9.0` | ✅ latest |
| Alpine edge | `0.9.0` | ✅ latest |
| openSUSE Tumbleweed | `0.7.1` | ⚠️ outdated |

## 改进这些数据

bpftop 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `bpftop` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/bpftop.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260911.yml` · 2026-09-11T05:58:59Z._
