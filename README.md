# GeeTree

English | [简体中文](#简体中文)

**A pure-GPU-rendered, professional Git client** for macOS, Windows and Linux. https://geetree.app

- Built for huge repositories: millions of commits, open in a second
- Professional diff, commit and merge, on par with JetBrains IDEs
- Rust + GPUI, the stack behind Zed: everything drawn on the GPU, smooth scrolling
- Native search that stays instant in large repositories, down to every commit's diff
- The full set of advanced workflows: interactive rebase, cherry-pick, stash, work trees, Git Flow

## Install

**macOS** (Apple silicon and Intel), with [Homebrew](https://brew.sh):

```sh
brew install --cask cmzy/tap/geetree
```

Or download the `.dmg` for your Mac's chip from [Releases](https://github.com/cmzy/geetree/releases/latest): `aarch64` for Apple silicon, `x64` for Intel. The app is signed and notarised by Apple and opens at once.

**Windows** 10 1809 or later (x64): the `-setup.exe` installer from [Releases](https://github.com/cmzy/geetree/releases/latest). It installs for the current user, no administrator rights needed.

**Linux** (x64): the `.deb` package or the `.AppImage` from [Releases](https://github.com/cmzy/geetree/releases/latest).

GeeTree uses your system's `git`, version 2.30 or later. Every release lists the files' SHA-256 sums in `SHA256SUMS`, and the app updates itself from new releases.

## Feedback

Report a bug or ask for a feature in [Issues](https://github.com/cmzy/geetree/issues).

This repository holds GeeTree's releases and issues; the source code is not published.

---

## 简体中文

**纯 GPU 渲染的专业 Git 客户端**，支持 macOS、Windows 和 Linux。https://geetree.app

- 为超大仓库设计：百万提交，直接秒开
- 专业级的 diff、提交与合并体验，媲美 JetBrains
- 与 Zed 同样的技术栈，Rust + GPUI 开发，纯 GPU 渲染，丝滑滚动
- 原生开发，大型仓库也能秒搜，每个提交的 diff 也能搜索
- 完整的高级工作流：交互式变基、拣选、贮藏、工作树、Git Flow

### 安装

**macOS**（Apple 芯片与 Intel），使用 [Homebrew](https://brew.sh)：

```sh
brew install --cask cmzy/tap/geetree
```

也可以在 [Releases](https://github.com/cmzy/geetree/releases/latest) 下载对应芯片的 `.dmg`：Apple 芯片选 `aarch64`，Intel 选 `x64`。应用已经过 Apple 签名与公证，下载后可直接打开。

**Windows** 10 1809 及以上（x64）：在 [Releases](https://github.com/cmzy/geetree/releases/latest) 下载 `-setup.exe` 安装程序，装到当前用户，不需要管理员权限。

**Linux**（x64）：在 [Releases](https://github.com/cmzy/geetree/releases/latest) 下载 `.deb` 安装包或 `.AppImage`。

GeeTree 使用系统中的 `git`，需要 2.30 及以上版本。每个版本都在 `SHA256SUMS` 中列出文件的 SHA-256 校验值；应用会从新版本自动更新。

### 反馈

在 [Issues](https://github.com/cmzy/geetree/issues) 报告问题或提出功能建议。

本仓库用于发布 GeeTree 的安装包和收集反馈，不包含源代码。
