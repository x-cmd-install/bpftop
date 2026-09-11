# bpftop

[中文版本](./README.cn.md)

bpftop provides a dynamic real-time view of running eBPF programs. It displays the average runtime, events per second, and estimated total CPU % for each program.

![bpftop](https://repo.x-cmd.io/bpftop.svg)

## Install

```sh
x install bpftop
```

## Code insight

Total: **99,424** lines of code across **13** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| CHeader | 97,464 | 4,669 | 12,835 | 4 |
| Rust | 1,691 | 133 | 207 | 6 |
| Sh | 180 | 22 | 42 | 1 |
| Nix | 36 | 6 | 6 | 1 |
| C | 28 | 0 | 10 | 1 |

## Source

- **Upstream**: <https://github.com/Netflix/bpftop>
- **Homepage**: <https://bpftop.sh>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.9.0` (2026-05-02)
- **Last commit**: 2026-07-29
- **Assets in release**: 2

## Popularity

- **Stars**: 2,705 · **Forks**: 129 · **Open issues**: 30 · **Contributors**: 17

## Totals (cumulative)

- **Releases**: 17 · **Merged PRs**: 164 · **Open PRs**: 1 · **Closed issues**: 26 · **Open issues**: 4 · **Commits**: 277

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-15 | 2 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-16 | 2 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-21 | 5 | 0 | 0 | 0 | 0 | 0 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [bpftop-aarch64-unknown-linux-gnu](https://github.com/Netflix/bpftop/releases/download/v0.9.0/bpftop-aarch64-unknown-linux-gnu) | 2.5 MiB | `native/linux/arm64/glibc` |
| [bpftop-x86_64-unknown-linux-gnu](https://github.com/Netflix/bpftop/releases/download/v0.9.0/bpftop-x86_64-unknown-linux-gnu) | 2.5 MiB | `native/linux/x64/glibc` |

## Distribution status

Reported by **56** distros on [repology.org](https://repology.org/project/bpftop). **12** are ✅ on the latest upstream release, **29** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
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

## Improve this data

Install metadata for bpftop lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `bpftop` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/bpftop.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260911.yml` · 2026-09-11T18:57:02Z._
