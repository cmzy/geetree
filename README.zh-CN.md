<p align="center"><img src=".github/media/logo.svg" width="96" alt="GeeTree"></p>

<h1 align="center">GeeTree</h1>

<h3 align="center">纯 GPU 渲染的<br>专业 Git 客户端。</h3>

<p align="center">为超大仓库设计。百万提交，直接秒开。</p>

<p align="center">
  <a href="https://github.com/cmzy/geetree/releases/latest"><img src="https://img.shields.io/github/v/release/cmzy/geetree?label=release&color=3b82f6" alt="Latest release"></a>
  <img src="https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Linux-555" alt="macOS | Windows | Linux">
  <img src="https://img.shields.io/badge/built%20with-Rust%20%2B%20GPUI-b7410e" alt="Rust + GPUI">
</p>

<p align="center">
  <a href="#下载"><b>下载</b></a> ·
  <a href="https://geetree.app/">官网</a> ·
  <a href="https://github.com/cmzy/geetree/releases">全部版本</a> ·
  <a href="https://github.com/cmzy/geetree/issues">问题反馈</a> ·
  <a href="README.md">English</a>
</p>

<p align="center"><a href="https://geetree.app/"><img src=".github/media/demo.gif" alt="GeeTree 打开 150 万个提交的仓库并搜索的演示" width="100%"></a></p>

<table align="center"><tr><td align="center"><h3>150 万</h3><sub>个提交，直接秒开</sub></td><td align="center"><h3>0.5 s</h3><sub>第一屏提交上屏</sub></td><td align="center"><h3>77 ms</h3><sub>全量搜索 150 万个提交</sub></td><td align="center"><h3>3 平台</h3><sub>macOS · Windows · Linux</sub></td></tr></table>

## 为超大仓库设计

**百万提交，直接秒开。** 150 万个提交，半秒上屏。边加载边滚动、搜索、跳转。

<picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/big-dark.gif"><img src=".github/media/big-light.gif" alt="打开 150 万个提交的仓库，边加载边滚动，并跳到最早的提交" width="100%"></picture>

## 专业级 diff、提交、合并，媲美 JetBrains

并排 diff、按块暂存、三方合并、blame，任意版本随意对比。

<picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/commit-dark.gif"><img src=".github/media/commit-light.gif" alt="提交页：按块暂存与并排 diff" width="100%"></picture>

<table>
<tr><td width="50%" align="center" valign="top"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/compare-dark.jpg"><img src=".github/media/compare-light.jpg" alt="对比窗口：两个版本之间的文件与提交"></picture><br><sub>对比</sub></td><td width="50%" align="center" valign="top"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/merge-dark.jpg"><img src=".github/media/merge-light.jpg" alt="合并对话框"></picture><br><sub>合并</sub></td></tr>
</table>

## 与 Zed 同样的技术栈

Rust + GPUI，纯 GPU 渲染，丝滑滚动。

<picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/scroll-dark.gif"><img src=".github/media/scroll-light.gif" alt="在 150 万个提交的历史中快速滚动" width="100%"></picture>

<table><tr><td><b>Rust</b></td><td>原生代码，没有浏览器，没有垃圾回收停顿。</td></tr><tr><td><b>GPUI</b></td><td>Zed 编辑器的 UI 框架，纯 GPU 渲染，百万行滚动依旧丝滑。</td></tr></table>

## 原生开发，超大仓库也能秒搜

150 万个提交，毫秒级搜索。提交信息、作者、路径，每个提交的 diff 也能搜。

<picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/search-dark.gif"><img src=".github/media/search-light.gif" alt="搜索提交信息与 diff 内容" width="100%"></picture>

<table>
<tr><td width="100%" align="center" valign="top"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/author-dark.jpg"><img src=".github/media/author-light.jpg" alt="搜索的作者筛选，带每位作者的提交数"></picture><br><sub>按作者筛选</sub></td></tr>
</table>

## 完整的高级工作流

交互式 rebase、工作树、stash、Git Flow、多标签页、内置终端、⌘K 命令面板。

<picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/rebase-dark.gif"><img src=".github/media/rebase-light.gif" alt="交互式 rebase 编辑器" width="100%"></picture>

<table>
<tr><td width="33%" align="center" valign="top"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/palette-dark.jpg"><img src=".github/media/palette-light.jpg" alt="⌘K 命令面板"></picture><br><sub>命令面板</sub></td><td width="33%" align="center" valign="top"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/refs-dark.jpg"><img src=".github/media/refs-light.jpg" alt="分支、标签、stash 与工作树"></picture><br><sub>引用</sub></td><td width="33%" align="center" valign="top"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/home-dark.jpg"><img src=".github/media/home-light.jpg" alt="首页：多个仓库与各自状态"></picture><br><sub>首页</sub></td></tr>
</table>

### 更多界面

<table>
<tr><td width="33%" align="center" valign="top"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/push-dark.jpg"><img src=".github/media/push-light.jpg" alt="推送对话框"></picture><br><sub>推送</sub></td><td width="33%" align="center" valign="top"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/pull-dark.jpg"><img src=".github/media/pull-light.jpg" alt="拉取对话框"></picture><br><sub>拉取</sub></td><td width="33%" align="center" valign="top"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/worktrees-dark.jpg"><img src=".github/media/worktrees-light.jpg" alt="工作树"></picture><br><sub>工作树</sub></td></tr>
<tr><td width="33%" align="center" valign="top"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/terminal-dark.jpg"><img src=".github/media/terminal-light.jpg" alt="内置终端"></picture><br><sub>终端</sub></td><td width="33%" align="center" valign="top"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/git-flow-dark.jpg"><img src=".github/media/git-flow-light.jpg" alt="Git Flow"></picture><br><sub>Git Flow</sub></td><td width="33%" align="center" valign="top"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/media/preferences-dark.jpg"><img src=".github/media/preferences-light.jpg" alt="偏好设置"></picture><br><sub>偏好设置</sub></td></tr>
</table>

## 下载

macOS、Windows、Linux，一个应用全搞定。所有平台都需要 git 2.30 或更新版本。

| 平台 | 下载 | 系统要求 |
|---|---|---|
| **macOS** | [Apple 芯片](https://github.com/cmzy/geetree/releases/latest/download/GeeTree_aarch64.dmg) · [Intel](https://github.com/cmzy/geetree/releases/latest/download/GeeTree_x64.dmg) | macOS 12 及以上 |
| **Windows** | [安装程序](https://github.com/cmzy/geetree/releases/latest/download/GeeTree_x64-setup.exe)（x64） | Windows 10 1809 及以上 |
| **Linux** | [AppImage](https://github.com/cmzy/geetree/releases/latest/download/GeeTree_x86_64.AppImage) · [.deb](https://github.com/cmzy/geetree/releases/latest/download/GeeTree_amd64.deb)（x64） | glibc 2.35 及以上，Wayland 或 X11 |

**macOS**：用 [Homebrew](https://brew.sh) 安装（自动选择芯片），或打开 `.dmg`，把 GeeTree 拖进「应用程序」。应用已经过 Apple 签名与公证。

```sh
brew install --cask cmzy/tap/geetree
```

**Windows**：运行安装程序即可，装到当前用户，不需要管理员权限。还没有 git 的话：`winget install Git.Git`

**Linux**：AppImage 加上执行权限后直接运行；deb 用系统的包管理器安装（自动装上 git）。

```sh
chmod +x GeeTree_x86_64.AppImage && ./GeeTree_x86_64.AppImage
# 或者
sudo apt install ./GeeTree_amd64.deb
```

每个版本都附带 `SHA256SUMS` 用于校验下载的文件；有新版本时 GeeTree 会自动更新。[全部版本 →](https://github.com/cmzy/geetree/releases)

## 问题反馈

遇到问题或想要新功能？请提交 [Issue](https://github.com/cmzy/geetree/issues)。

---

<p align="center"><b>在你最大的仓库上试试。</b><br><a href="#下载">下载</a> · <a href="https://geetree.app/">geetree.app</a></p>

<p align="center"><sub>本仓库用于发布 GeeTree 的安装包和收集反馈，不包含源代码。</sub></p>
