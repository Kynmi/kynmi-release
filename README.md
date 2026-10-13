<p align="center">
    <img src="./icon.png" width="96" height="96" alt="Kynmi 图标" />
</p>

<h1 align="center">Kynmi · 知言</h1>

<p align="center"><strong>理解话中意，表达心中想。</strong></p>

Kynmi 是面向 macOS 的个人 AI 沟通助手，结合对话上下文分析可能的意图，并辅助多语言表达。

本仓库只用于分发安装包、校验和与版本说明。目前尚未发布正式版本。

## 下载安装

在 [Releases](https://github.com/Kynmi/kynmi-release/releases) 选择版本。当前分发架构为 **macOS arm64（Apple Silicon）**。

- **DMG：** 打开 `Kynmi-<版本>-mac-arm64.dmg`，将 Kynmi 拖入 Applications。
- **ZIP：** 解压 `Kynmi-<版本>-mac-arm64.zip`，将 Kynmi.app 放入 Applications。
- **SHA256SUMS：** 下载到安装包所在目录，运行 `shasum -a 256 -c SHA256SUMS` 核对文件。

正式发布流程包含 Developer ID 签名、Apple 公证与应用验收。GitHub Actions 的未签名预览产物不作为本仓库的正式 Release 发布。

## 开始使用

打开 Kynmi，在「设置 → AI 模型」配置自己的模型与 API Key。添加对方消息，再输入自己的想法，查看候选表达和对话分析。

会话默认保存在本机；主动生成或分析时，当前会话上下文会发送给你所配置的模型服务。候选回复由你确认、复制和发送。
