# Haven Note

**让每一个想法，都有安放之处。**

Haven Note 是一款本地优先的笔记应用。你可以直接编辑 `.hd` 和 Markdown 文件，也可以在同一个工作空间里管理便签、知识库与日常任务。

## 可以用它做什么

- **写笔记**：使用富文本编辑器、多文档侧栏和大纲整理内容；直接打开文件并自动保存。
- **整理知识**：创建多个知识库，全文搜索笔记，并通过知识集合和关系图谱发现关联。
- **记录日常**：用便签捕捉想法，使用任务看板跟进计划，导入账单整理收支。
- **保存重要信息**：独立密码本会加密条目，并在闲置后自动锁定。

功能会随版本变化，请以实际安装包为准。

## 下载

以下安装包均为**不含账号登录模块的纯本地预发布版**，没有云同步。macOS、Windows 和 Android 提供 `0.1.1-alpha.1` 测试包。

| 平台 | 版本 | 下载安装包 |
| --- | --- | --- |
| macOS · Apple Silicon（M 系列芯片） | 0.1.1-alpha.1 · 2026-10-08 重打包 | [arm64 DMG](https://github.com/GlazeChou/haven-note/releases/download/v0.1.1-alpha.1-local/Haven-Note-Local-0.1.1-alpha.1-macOS-arm64-r2.dmg) |
| macOS · Intel | 0.1.1-alpha.1 · 2026-10-08 重打包 | [x64 DMG](https://github.com/GlazeChou/haven-note/releases/download/v0.1.1-alpha.1-local/Haven-Note-Local-0.1.1-alpha.1-macOS-x64-r2.dmg) |
| Windows · x64 | 0.1.1-alpha.1 | [Windows 安装程序 EXE](https://github.com/GlazeChou/haven-note/releases/download/v0.1.1-alpha.1-local/Haven-Note-Local-0.1.1-alpha.1-Windows-x64-setup.exe) |
| Android · 6.0 及以上 | 0.1.1-alpha.1（调试签名） | [Android APK](https://github.com/GlazeChou/haven-note/releases/download/v0.1.1-alpha.1-local/Haven-Note-Local-0.1.1-alpha.1-Android-debug.apk) |

`alpha.1` 是早期测试版本号，不表示比此前的 `0.1.1-RC1` 更成熟。2026 年 10 月 8 日重打包的 macOS 版本加入离线 Mermaid、PlantUML 和表格预览资源；请下载上表中带 `r2` 的安装包。此前的 [macOS RC1 安装包](https://github.com/GlazeChou/haven-note/releases/tag/v0.1.1-RC1-local-macos)、[Windows RC1 安装包](https://github.com/GlazeChou/haven-note/releases/tag/v0.1.1-RC1-local-windows) 和 [Android 0.1.0 调试包](https://github.com/GlazeChou/haven-note/releases/tag/v0.1.0-local-android-debug) 仍可下载。

**iOS：**本地只有未签名的归档，不能直接安装到 iPhone 或 iPad，目前没有可下载的纯本地版安装包。

macOS 首次打开可能受到系统阻止；Android 包使用调试签名，仅供测试，若已安装其他签名的同包名应用，可能需要先备份数据再处理安装冲突。安装前请阅读 [0.1.1-alpha.1 发布说明](https://github.com/GlazeChou/haven-note/releases/tag/v0.1.1-alpha.1-local)，并为重要数据保留备份。

Release 页面中的 Source code（zip / tar.gz）由 GitHub 自动生成，是仓库源码快照，不是安装包。后续版本请查看 [全部 Releases](https://github.com/GlazeChou/haven-note/releases)。

## 反馈与建议

欢迎通过 [GitHub Issues](https://github.com/GlazeChou/haven-note/issues/new/choose) 报告问题或提出建议。提交前请先[搜索已有反馈](https://github.com/GlazeChou/haven-note/issues)，避免重复；选择对应模板，写明使用的平台、应用版本、重现步骤和预期结果。截图或日志可以帮助定位问题。

**请勿在公开 Issue 中提交密码、密钥、个人笔记、账单、数据库或其他敏感信息。**

## 数据说明

Haven Note 以本地优先方式工作：直接打开的 `.hd` 和 Markdown 文件保存在原位置。当前没有云同步或主密码找回功能。测试阶段请为重要数据自行保留备份，尤其不要把密码本作为唯一副本。

---

本仓库用于发布 Haven Note 安装包、更新说明，以及收集用户反馈。
