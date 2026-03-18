# OpenCode：开源AI编程助手的全新选择

这两年我试过了各种AI编程工具，最终我选择了OpenCode。我有三个必须使用OpenCode的理由：

1. 100%开源，不绑定任何AI提供商
2. 安装简单，多种平台支持
3. 内置智能代理，功能强大

OpenCode的最大优势就是完全开源，不绑定任何AI提供商。你可以自由选择Claude、OpenAI、Google或本地模型，随着模型技术的发展，这种灵活性将为你节省成本并提供更优的体验。

同时OpenCode由neovim用户和terminal.shop的创建者打造，专注于终端界面的极致体验，同时提供客户端-服务器架构，支持远程操作等高级功能。

## 快速安装指南

OpenCode提供多种安装方式，满足不同平台用户的需求：

**YOLO安装法**：只需一行命令 `curl -fsSL https://opencode.ai/install | bash`，即可完成安装。

**包管理器安装**：
- npm/bun/pnpm/yarn：`npm i -g opencode-ai@latest`
- Windows：`scoop install opencode` 或 `choco install opencode`
- macOS和Linux：推荐使用 `brew install anomalyco/tap/opencode`
- Arch Linux：`sudo pacman -S opencode` 或 `paru -S opencode-bin`
- 其他系统：`mise use -g opencode` 或 `nix run nixpkgs#opencode`

**桌面应用**：OpenCode还提供Beta版桌面应用，支持macOS、Windows和Linux平台，可通过releases页面或opencode.ai/download下载。

## 内置智能代理

OpenCode包含两个内置代理，可通过Tab键切换：

**build代理**：默认代理，拥有完整的开发权限，适合日常开发工作。

**plan代理**：只读代理，默认拒绝文件编辑，运行bash命令前会请求权限，非常适合探索陌生代码库或规划代码变更。

此外，OpenCode还内置了一个通用子代理，用于复杂搜索和多步骤任务，可通过在消息中使用@general调用。

## 自定义安装目录

OpenCode安装脚本会按照以下优先级选择安装路径：
1. $OPENCODE_INSTALL_DIR - 自定义安装目录
2. $XDG_BIN_DIR - 符合XDG基础目录规范的路径
3. $HOME/bin - 标准用户二进制目录（如果存在或可创建）
4. $HOME/.opencode/bin - 默认回退路径

例如，你可以通过 `OPENCODE_INSTALL_DIR=/usr/local/bin curl -fsSL https://opencode.ai/install | bash` 来自定义安装目录。

## 加入社区

如果你对OpenCode感兴趣，欢迎加入我们的社区Discord或关注X.com，与其他开发者交流使用心得和技巧。

OpenCode，为开发者打造的开源AI编程助手，让你的编码效率提升到新高度！