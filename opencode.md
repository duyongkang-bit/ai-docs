# OpenCode：开源AI编程助手的全新选择

## 为什么选择 OpenCode？

OpenCode 是一款 100% 开源的 AI 编程助手，它与其他同类工具的最大区别在于：不绑定任何 AI 提供商。你可以自由选择 Claude、OpenAI、Google 或本地模型，随着模型技术的发展，这种灵活性将为你节省成本并提供更优的体验。

OpenCode 由 neovim 用户和 terminal.shop 的创建者打造，专注于终端界面的极致体验，同时提供客户端-服务器架构，支持远程操作等高级功能。

## 快速安装指南

OpenCode 提供多种安装方式，满足不同平台用户的需求：

**YOLO 安装法**：只需一行命令 `curl -fsSL https://opencode.ai/install | bash`，即可完成安装。

**包管理器安装**：
- npm/bun/pnpm/yarn：`npm i -g opencode-ai@latest`
- Windows：`scoop install opencode` 或 `choco install opencode`
- macOS 和 Linux：推荐使用 `brew install anomalyco/tap/opencode`
- Arch Linux：`sudo pacman -S opencode` 或 `paru -S opencode-bin`
- 其他系统：`mise use -g opencode` 或 `nix run nixpkgs#opencode`

**桌面应用**：OpenCode 还提供 Beta 版桌面应用，支持 macOS、Windows 和 Linux 平台，可通过 releases 页面或 opencode.ai/download 下载。

## 内置智能代理

OpenCode 包含两个内置代理，可通过 Tab 键切换：

**build 代理**：默认代理，拥有完整的开发权限，适合日常开发工作。

**plan 代理**：只读代理，默认拒绝文件编辑，运行 bash 命令前会请求权限，非常适合探索陌生代码库或规划代码变更。

此外，OpenCode 还内置了一个通用子代理，用于复杂搜索和多步骤任务，可通过在消息中使用 @general 调用。

## 自定义安装目录

OpenCode 安装脚本会按照以下优先级选择安装路径：
1. $OPENCODE_INSTALL_DIR - 自定义安装目录
2. $XDG_BIN_DIR - 符合 XDG 基础目录规范的路径
3. $HOME/bin - 标准用户二进制目录（如果存在或可创建）
4. $HOME/.opencode/bin - 默认回退路径

例如，你可以通过 `OPENCODE_INSTALL_DIR=/usr/local/bin curl -fsSL https://opencode.ai/install | bash` 来自定义安装目录。

## 加入社区

如果你对 OpenCode 感兴趣，欢迎加入我们的社区 Discord 或关注 X.com，与其他开发者交流使用心得和技巧。

OpenCode，为开发者打造的开源 AI 编程助手，让你的编码效率提升到新高度！