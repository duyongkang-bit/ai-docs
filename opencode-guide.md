# OpenCode：开发者的AI编程利器

最近我测试了几十款AI编程工具，最终还是选择了OpenCode。我有三个必须使用OpenCode的理由：

1. 100%开源，无拘无束
2. 多平台支持，安装简单
3. 内置双代理，功能强大

OpenCode是一款真正为开发者打造的AI编程工具，它不仅功能强大，而且完全开源，这意味着你可以自由定制和扩展它的功能。今天我就来详细介绍一下OpenCode的安装和使用方法，让你快速上手这个开发者的AI编程利器。

## 安装指南：多种方式任你选

安装OpenCode的方式非常多，无论你使用什么操作系统，都能找到适合你的安装方法：

### YOLO安装法
最简单的方法就是使用官方提供的一键安装脚本：
```bash
curl -fsSL https://opencode.ai/install | bash
```

### 包管理器安装
如果你喜欢使用包管理器，OpenCode也支持多种包管理工具：
- npm：`npm i -g opencode-ai@latest`（也支持bun/pnpm/yarn）
- Windows：`scoop install opencode` 或 `choco install opencode`
- macOS和Linux：`brew install anomalyco/tap/opencode`（推荐，更新最及时）
- Arch Linux：`sudo pacman -S opencode`（稳定版）或 `paru -S opencode-bin`（AUR最新版）
- 其他系统：`mise use -g opencode` 或 `nix run nixpkgs#opencode`

### 桌面应用（BETA）
OpenCode也提供了桌面应用版本，支持macOS、Windows和Linux：
- macOS（Apple Silicon）：opencode-desktop-darwin-aarch64.dmg
- macOS（Intel）：opencode-desktop-darwin-x64.dmg
- Windows：opencode-desktop-windows-x64.exe
- Linux：.deb、.rpm或AppImage

你也可以通过包管理器安装桌面版：
- macOS：`brew install --cask opencode-desktop`
- Windows：`scoop bucket add extras; scoop install extras/opencode-desktop`

## 核心功能：双代理助力开发

OpenCode内置了两个强大的代理，你可以通过Tab键在它们之间切换：

### build代理
- 默认代理，拥有完全访问权限
- 适合开发工作，可编辑文件、运行命令
- 为日常开发提供全方位支持

### plan代理
- 只读代理，专注于分析和代码探索
- 默认拒绝文件编辑
- 运行bash命令前会请求权限
- 非常适合探索陌生代码库或规划变更

此外，OpenCode还包含一个通用子代理，用于复杂搜索和多步骤任务，你可以在消息中使用@general来调用它。

## 平台支持与灵活性

OpenCode的一大优势是它的平台支持和灵活性：

### 安装目录自定义
安装脚本会按照以下优先级顺序选择安装路径：
1. $OPENCODE_INSTALL_DIR - 自定义安装目录
2. $XDG_BIN_DIR - 符合XDG Base Directory规范的路径
3. $HOME/bin - 标准用户二进制目录（如果存在或可创建）
4. $HOME/.opencode/bin - 默认回退路径

你可以通过环境变量来自定义安装目录，例如：
```bash
OPENCODE_INSTALL_DIR=/usr/local/bin curl -fsSL https://opencode.ai/install | bash
```

### 模型无关性
OpenCode不绑定任何特定的AI模型提供商，你可以使用Claude、OpenAI、Google或甚至本地模型。这种模型无关性确保了你可以根据自己的需求和预算选择最合适的模型。

### 客户端/服务器架构
OpenCode采用客户端/服务器架构，这意味着你可以在电脑上运行OpenCode，同时从移动应用远程控制它。终端TUI前端只是众多可能的客户端之一。

## 结语：开发者的AI编程新选择

OpenCode是一款真正为开发者着想的AI编程工具，它的开源特性、多平台支持、强大的代理功能以及灵活的架构设计，使其成为开发者的理想选择。

如果你还在使用传统的编程工具，或者对现有的AI编程助手不满意，不妨试试OpenCode。它不仅能提高你的编程效率，还能为你带来全新的开发体验。

加入OpenCode社区，与其他开发者一起探索AI编程的无限可能！

---

**提示：** 安装前请移除0.1.x之前的旧版本，以确保最佳体验。

**社区链接：** Discord | X.com