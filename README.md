<p align="center"><img src="assets/product/haven-note-app-icon.png" alt="灵栖图标" width="76"></p>
<h1 align="center">Haven Note · 灵栖</h1>
<p align="center"><strong>让每一份积累，都成为你的资产。</strong></p>
<p align="center">在自己的设备上创作、整理、使用知识，也让重要的日常各有归处。</p>
<p align="center"><a href="#下载">下载体验</a> · <a href="https://note.liuli88.com/">官方网站</a> · <a href="docs/guides/README.md">上手指南</a> · <a href="https://github.com/GlazeChou/haven-note/issues">反馈建议</a></p>

Haven Note 是一款**本地优先的个人数字资产管理工具**，为重视数字自主、持续创作和长期积累的人而设计。它适合经常处理文档、源码和创作素材的技术创作者与内容创作者，也能安放你的便签、计划、密码和账本。

## 从灵感到成果，在一个空间完成

```mermaid
flowchart LR
    A[随手记录<br/>便签 · 文档] --> B[自由创作<br/>文字 · 图形 · 白板]
    B --> C[整理积累<br/>知识库 · 关联]
    C --> D[再次使用<br/>检索 · AI]
    D --> E[推动行动<br/>任务 · 导出 · 发布]
```

- **内容主权｜你的内容，不再寄居于平台。** 直接打开的文档保存在本地原位置；格式和存放位置清晰可见，方便用自己的方式管理、备份和迁移。
- **自由形态创作｜一处起笔，让想法自由成形。** 在一篇文档里组合文字、表格、思维导图、流程图和白板。
- **跨端续写｜换一块屏幕，接着完成你的事。** 在支持的桌面和移动版本中继续处理笔记、TXT 和源码等文本文档；局域网同步可按需开启。
- **行动智能｜让 AI 从“给建议”，走向“帮你做”。** 通过受控接口，让 AI 查询、创建和修改受支持的文档内容，再由你检查结果。
- **知识复利｜让每一次记录，成为下一次创造的起点。** 用知识库、搜索和笔记关联找回已有积累，并在配置相应能力后用于 AI 工作流。

查看[笔记与知识资产卖点](docs/product/笔记与知识资产宣传卖点.md)，了解这五个方向的完整文案与适用边界。

### 你可以这样使用

| 创作一篇作品 | 解决一个技术问题 |
| --- | --- |
| 在便签里留下灵感，用文档写作、画图和排版；完成后导出或进入发布流程，再把资料收入知识库。 | 打开本地 TXT、源码或桌面端的 SSH 远程文本，记录排查过程、画出方案，再用任务推进并把经验留在知识库。 |

## 不止笔记，日常也各有归处

| 🗒️ 便签 · 桌面灵感站 | ✅ 任务 · 时间掌控力 |
| --- | --- |
| **让重要的事留在眼前，不藏在窗口后面。** 随手记录，把便签钉在桌面。 | **少一点内耗，多一点完成。** 安排时间与优先级，看清任务进度。 |

| 🔐 密钥箱 · 数字身份的归处 | 📊 账本 · 轻记账，深洞察 |
| --- | --- |
| **把密码收好，把记忆还给自己。** 集中管理账号、密码和密钥。 | **不用天天记，也能月月心中有数。** 导入支付宝、微信账单，回看收支与预算。 |

查看[日常资产卖点](docs/product/日常资产宣传卖点.md)。

## 下载

当前提供 **0.1.1-alpha.7 预发布测试版**。[官网](https://note.liuli88.com/#download)会按发布渠道展示对应平台的最新可用下载入口。

### 桌面端

| 平台 | 安装包 | 下载 |
| --- | --- | --- |
| macOS · Apple Silicon（M 系列） | 已签名、公证并装订票据的 arm64 DMG | [下载 DMG](https://github.com/GlazeChou/haven-note/releases/download/v0.1.1-alpha.7-local/Haven-Note_0.1.1-alpha.7_macOS-arm64.dmg) |
| macOS · Intel | 已签名、公证并装订票据的 x64 DMG | [从官网下载 DMG](https://noteapi.liuli88.com/api/v1/public/releases/artifacts/f23e6b51-41dd-4c8f-b232-2e1aca1faa92/content) |
| Windows · x64 | 未签名的安装程序 EXE | [下载 EXE](https://github.com/GlazeChou/haven-note/releases/download/v0.1.1-alpha.7-local/Haven-Note_0.1.1-alpha.7_Windows-x64-setup.exe) |
| Linux · ARM64 | 以官网已发布版本为准 | [查看官网下载区](https://note.liuli88.com/#download) |

### 移动端

用手机扫描二维码，或打开对应链接：

| 平台 | 下载方式 | 扫码下载 |
| --- | --- | --- |
| Android · ARM64 | [从官网下载 APK](https://noteapi.liuli88.com/api/v1/public/releases/artifacts/d1b1d4f3-52f1-4579-9585-a8115aa13804/content)（versionCode 13，沿用 Alpha 调试签名） | <a href="https://noteapi.liuli88.com/api/v1/public/releases/artifacts/d1b1d4f3-52f1-4579-9585-a8115aa13804/content"><img src="assets/downloads/android-alpha7-qr.png" alt="灵栖 Android alpha.7 APK 下载二维码" width="160"></a> |
| iOS · iPhone / iPad | [通过 Apple TestFlight 安装](https://testflight.apple.com/join/8fzXa7f9)（build 18） | <a href="https://testflight.apple.com/join/8fzXa7f9"><img src="assets/downloads/ios-testflight-alpha7-qr.png" alt="灵栖 iOS alpha.7 TestFlight 邀请二维码" width="160"></a> |

移动端二维码按官网 alpha.7 下载入口生成，随版本更新需重新核对。iOS 不提供公开 IPA；Windows 包的构建源码提交尚未独立核实。所有 alpha 版本均处于测试阶段，升级前请备份重要数据。

查看 [alpha.7 发布说明与制品](https://github.com/GlazeChou/haven-note/releases/tag/v0.1.1-alpha.7-local)。历史版本：[alpha.6](https://github.com/GlazeChou/haven-note/releases/tag/v0.1.1-alpha.6-local)、[alpha.3](https://github.com/GlazeChou/haven-note/releases/tag/v0.1.1-alpha.3-local)、[alpha.2](https://github.com/GlazeChou/haven-note/releases/tag/v0.1.1-alpha.2-local)、[alpha.1](https://github.com/GlazeChou/haven-note/releases/tag/v0.1.1-alpha.1-local)。GitHub 自动生成的源码压缩包是源码快照，不是安装包。

## 为什么是 `.hd`：为人编辑，也为 AI 理解

`.hd` 不只是把 Markdown 换一个扩展名。它是 UTF-8 编码、结构化的 Haven Document：**标题是独立字段，正文是带类型和稳定 ID 的块树**。人可以像编辑普通文档一样排版；程序可以理解“这是标题、表格、引用还是图表”，精确找到要改的块。

| 能力 | 带来的好处 |
| --- | --- |
| **结构化内容** | 标题、段落、列表、表格和扩展块各有语义；文档既能阅读，也能被检索、索引和自动化处理。 |
| **稳定块 ID + 插件 Schema** | AI 可以按块定位内容；受支持的组件可以公开自己的可读字段和允许的操作，未知组件原样保留。 |
| **语义补丁 + 版本校验** | AI 只修改选中的标题或块；写回前核对文件版本，发现别人刚改过时拒绝覆盖。 |
| **适合 RAG 的上下文** | 可以投影出紧凑语义，并按敏感级别筛选可索引内容；不必把整份 JSON 当成一段无差别的文本。 |
| **文件优先、跨平台** | `.hd` 可直接打开、原地保存和归档；文档格式不因 Windows、macOS、Android 或 iOS 而改变。 |

```mermaid
flowchart LR
    A[自然编辑器<br/>文字 · 表格 · 图表 · 组件] --> B[.hd 本地文件<br/>独立标题 · 结构化块 · 稳定 ID]
    B --> C[阅读与跨设备同步]
    B --> D[搜索 / 知识库 / RAG]
    B --> E[MCP / CLI]
    E --> F[查询块 → 语义修改 → 版本校验]
```

`.hd` 普通文档是**明文结构化文件**，便于迁移、版本比较和自主保存；敏感密码请放进独立的加密密钥箱。需要纯文本工作流时，可以继续使用 `.md` / `.markdown`。

## 自然编辑器：把内容组织成真正的文档

Haven Editor 是自研的结构化块编辑器。输入时可以使用 Markdown 快捷规则，也能通过工具栏和插入菜单组合内容；阅读态、大纲和代码高亮与编辑态共享同一份文档结构。

| 组件类别 | 已支持的内容 |
| --- | --- |
| **基础排版** | 段落、多级标题、有序/无序/任务列表、引用、分割线、链接、行内样式、代码块与代码复制。 |
| **内容组织** | 表格（增删行列、合并/拆分单元格）、图片、文件附件、目录、折叠块、多栏布局、提示/高亮块。 |
| **结构化字段** | 状态、日期、公式，以及人物、进度、数据字段、数据记录、数据视图和数据指标等数据组件。 |
| **媒体与可视化** | 本地或网页媒体嵌入、音视频、Mermaid / PlantUML / Flowchart 文本图、可视化流程图、思维导图、draw.io 图形和白板。 |

组件可组合在同一篇文档里，扩展块的数据仍随文档保存。不同格式、平台和安装版本对个别组件的编辑入口可能有所差异。

## Markdown、图表与可视化设计

- **Markdown 兼容**：直接打开和编辑 `.md` / `.markdown`；标题、列表、代码围栏等内容可以进入文档编辑体验。习惯写源码时也可以在仓库的文本编辑入口工作。
- **文本快速成图**：在文档中使用 Mermaid、PlantUML 和 Flowchart 图块。Mermaid 图可查看、缩放和下载图像；适合把流程、时序、关系写成便于版本管理的文本。
- **可视化绘图**：draw.io 图形工作台提供丰富的形状与模板，可绘制流程图、时序图、UML、ER、泳道图、网络拓扑等数十类设计图；独立思维导图支持思维导图、逻辑图、组织结构图、树形图、时间轴、鱼骨图等布局，也有流程图和白板块。图表作为文档内容保存，可随选中的仓库文件在设备间同步。

## 从笔记到知识库，再到 AI

- **知识组织**：多知识库、全文检索、知识集合与关系图谱；按来源整理资料，在知识库中检索并进行 RAG 问答。模型、索引和外部服务的使用由你配置，相关内容是否交给模型取决于你的设置。
- **MCP 接入**：Haven Note 提供 MCP 能力，可连接 Claude Code（CC）、Codex、DSH 等支持 MCP 的 AI 客户端。用自然语言查询文档、构思提纲、生成 Mermaid 图或修改受支持的结构化块；文件写入仍受授权、Schema 校验与版本校验约束。
- **不把文档锁在聊天里**：AI 处理的是你自己的文件和知识，生成结果可以继续在编辑器里检查、修改和保存。图形内部的每一种元素并不都支持 AI 语义编辑，复杂图形可在图形工作台继续调整。

## 本地掌控与跨设备流转

```mermaid
flowchart LR
    A[macOS 桌面端] <-->|可选局域网同步| B[Android / iOS]
    A --- C[本地文档仓库]
    B --- D[本机文档与数据]
    C -. 按所选范围同步 .- D
```

- **本地优先**：普通文档直接保存在所选仓库或原路径；数据库承担草稿恢复、索引和业务数据等职责。你可以用自己的文件管理、备份和迁移方式掌控文档。
- **局域网同步**：同一网络的设备可按密码配对，选择要同步的数据与仓库。自动同步由用户主动开启，数据在设备间传输；同步帧采用加密保护。不同平台的手动同步方式有所区别。
- **多平台使用**：桌面端覆盖 macOS、Windows 与 Linux，移动端覆盖 Android 与 iOS；安装包和局域网同步能力以对应平台的当前版本为准。
- **加密仓库**：桌面端可为仓库启用加密存储，打开时解锁；这与普通明文 `.hd` 文件、局域网传输加密是不同层次的保护。
- **加密密钥箱**：保存账号、密码、API 密钥等敏感信息，支持独立密钥箱、分类与自动锁定；密钥箱数据可在授权的局域网同步范围内跨设备流转。请妥善保管主密码和恢复材料。

## 也是一个能工作的文件空间

除笔记外，Haven Note 还提供便签、任务看板、账本与账单导入。仓库浏览器可以预览图片、PDF、Office 文档和电子书等文件；文本入口可编辑 `.txt`、JSON、HTML、CSS、JavaScript、TypeScript、Python、Rust、Shell 等常见源码和配置文件，并提供语法高亮、适用格式的整理以及多行文本操作。

### 笔记仓库可处理的文本格式

| 类型 | 文件格式与常见文件名 | 打开方式 |
| --- | --- | --- |
| 笔记与纯文本 | `.hd`、`.md`、`.markdown`、`.txt` | `.hd` 和 Markdown 进入文档编辑器；`.txt` 使用纯文本编辑。 |
| 网页与前端 | `.html`、`.htm`、`.css`、`.scss`、`.sass`、`.less`、`.js`、`.jsx`、`.mjs`、`.cjs`、`.ts`、`.tsx`、`.mts`、`.cts`、`.vue`、`.svelte` | 源码编辑；HTML 还可预览。 |
| 编程语言 | `.py`、`.pyw`、`.pyi`、`.java`、`.rs`、`.go`、`.c`、`.h`、`.cc`、`.cpp`、`.cxx`、`.hh`、`.hpp`、`.hxx`、`.rb`、`.rake`、`.pl`、`.pm`、`.php`、`.phtml`、`.lua`、`.awk`、`.sql` | 源码编辑。 |
| 脚本与命令 | `.sh`、`.bash`、`.zsh`、`.ksh`、`.ps1`、`.psm1`、`.psd1`、`.bat`、`.cmd`、`.vbs`、`.wsf` | 文本或源码编辑。 |
| 数据与配置 | `.json`、`.yaml`、`.yml`、`.xml`、`.toml`、`.ini`、`.properties`、`.cfg`、`.conf`、`.nginx`、`.service`、`.timer` 等 systemd 文件 | 文本或结构化编辑；部分格式有语法高亮与格式整理。 |
| 工程文件 | `Dockerfile`、`Containerfile`、`Makefile`、`GNUmakefile`、`CMakeLists.txt`、`.dockerfile`、`.mk`、`.make`、`.cmake`、`.diff`、`.patch` | 源码编辑。 |
| 日志与常见点文件 | `.log`、`.env`、`.gitignore`、`.editorconfig`、`.gitconfig`、`.npmrc`、`.bashrc`、`.zshrc`、`.vimrc`、`.ssh/config` 等 | 按对应文本格式打开；高亮和格式整理能力因文件而异。 |

`.csv` 在仓库中以表格方式预览，桌面端可切换到文本编辑。其他未列出的本地文件不一定有专门的编辑入口；SSH 远程入口可尝试打开更多 UTF-8 文本。具体支持范围与平台差异以安装版本为准。

桌面端还可以通过 **SSH / SFTP 连接远端目录**：浏览服务器文件，打开 UTF-8 文本进行编辑，再安全写回原位置。远端非文本文件、移动端 SSH 和个别本地预览格式有各自边界，详情以当前安装版本为准。

> 功能随版本迭代；下方列出的是当前公开安装包。iOS 通过 TestFlight 分发。

## 反馈与建议

欢迎通过 [GitHub Issues](https://github.com/GlazeChou/haven-note/issues) 报告问题或提出建议。提交前请先搜索已有反馈，避免重复；写明使用的平台、应用版本、重现步骤和预期结果。截图或日志可以帮助定位问题。

**请勿在公开 Issue 中提交密码、密钥、个人笔记、账单、数据库或其他敏感信息。**

## 加入交流群

点击二维码可查看大图。QQ 扫码加入“灵栖交流群”；添加微信好友时，请备注 **灵栖**。

| QQ 群 | 微信好友 |
| --- | --- |
| 群号：**1134407602**<br><a href="assets/community/qq-group-1134407602-qr.png"><img src="assets/community/qq-group-1134407602-qr.png" alt="灵栖交流群 QQ 二维码" width="260"></a> | 添加微信好友请备注 **灵栖**。<br><a href="assets/community/wechat-lingqi-friend-qr.png"><img src="assets/community/wechat-lingqi-friend-qr.png" alt="灵栖微信好友二维码" width="260"></a> |

## 数据说明

Haven Note 以本地优先方式工作：直接打开的 `.hd` 和 Markdown 文件保存在原位置。同步能力以所安装的测试版本和应用内设置为准。测试阶段请为重要数据自行保留备份，尤其不要把密码本作为唯一副本。

---

本仓库用于发布 Haven Note 安装包、更新说明，以及收集用户反馈。
