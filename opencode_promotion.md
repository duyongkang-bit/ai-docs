# OpenCode：程序员的AI编码助手新选择

最近我试用了一款叫OpenCode的AI编码工具，用了一段时间后，我发现它可能会成为程序员的新宠。今天就来跟大家聊聊这款工具的几个亮点。

## 安装超简单，多平台支持

OpenCode的安装方式可以说是我见过最丰富的了，不管你用什么系统，都能找到适合的安装方法。

最简单的就是一行命令搞定：`curl -fsSL https://opencode.ai/install | bash`，这是跨平台的通用安装方式。

如果你习惯用包管理器，也有多种选择：
- npm用户：`npm i -g opencode-ai@latest`
- Windows用户：`scoop install opencode` 或 `choco install opencode`
- macOS和Linux用户：`brew install anomalyco/tap/opencode`（推荐，更新最快）
- Arch Linux用户：`sudo pacman -S opencode` 或 `paru -S opencode-bin`

甚至还有桌面应用版本，支持macOS、Windows和Linux，直接从官网下载安装包即可。

## 双Agent设计，满足不同场景需求

OpenCode内置了两个Agent，用Tab键就能切换：

**build Agent**：默认的全功能Agent，适合日常开发工作，拥有完整的文件编辑和命令执行权限。

**plan Agent**：只读模式的Agent，专注于代码分析和探索。默认拒绝文件编辑，执行bash命令前会先询问，非常适合探索不熟悉的代码库或规划改动。

除此之外，还有一个通用子Agent，用于复杂搜索和多步骤任务，可以通过在消息中使用@general来调用。

## 开源、灵活、终端友好

OpenCode的几个核心优势让它在众多AI编码工具中脱颖而出：

1. **100%开源**：完全透明，社区驱动，不用担心闭源工具的限制。

2. **不绑定任何AI提供商**：虽然推荐使用OpenCode Zen提供的模型，但也可以与Claude、OpenAI、Google甚至本地模型配合使用，真正做到了提供商无关。

3. **开箱即用的LSP支持**：内置语言服务器协议支持，代码补全、跳转等功能一应俱全。

4. **专注于终端体验**：由neovim用户和terminal.shop的创建者打造，将终端的可能性发挥到极致。

5. **客户端/服务器架构**：这意味着你可以在电脑上运行OpenCode，然后从移动应用远程控制它，终端界面只是众多可能的客户端之一。

## 配置灵活，高度可定制

OpenCode的安装脚本会按照优先级选择安装目录：
- $OPENCODE_INSTALL_DIR - 自定义安装目录
- $XDG_BIN_DIR - 符合XDG Base Directory规范的路径
- $HOME/bin - 标准用户二进制目录（如果存在或可创建）
- $HOME/.opencode/bin - 默认回退路径

这让你可以根据自己的喜好和系统环境来决定安装位置，非常灵活。

## 总结

OpenCode给我的感觉是一款真正为程序员设计的AI工具，它不仅功能强大，而且使用方式灵活多样，完全符合开发者的工作习惯。无论是快速安装、多平台支持，还是双Agent设计、开源架构，都体现了它的专业性和对开发者需求的深刻理解。

如果你正在寻找一款能够提升编码效率的AI助手，不妨试试OpenCode，相信它会给你带来惊喜。

加入OpenCode社区：Discord | X.com