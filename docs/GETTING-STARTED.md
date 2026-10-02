# OPT Alpha 01 快速开始

这份说明只覆盖第一次使用需要知道的内容。

## 1. 下载

前往 [Releases](../../releases) 下载最新的 Alpha 01 Windows x64 压缩包。

请只使用本仓库 Releases 发布的正式测试包。

## 2. 解压

把整个 ZIP 解压到一个普通文件夹。

不要只从压缩包里单独拖出一个 EXE，因为 OPT Alpha 01 还包含配套组件。

目录中至少应看到：

```text
OPTAssetLite.exe
BrainLite.SharedConnector.exe
SHA256.txt
RELEASE-MANIFEST.json
START-HERE-ALPHA-01.txt
```

`OPTAssetLite.exe` 是 Alpha 01 仍沿用的历史内部文件名，产品名称已经统一为 **OPT · AI Optimization Master**。

## 3. 第一次启动

双击：

```text
OPTAssetLite.exe
```

Alpha 01 暂无代码签名，因此 Windows 可能提示未知发布者或 SmartScreen。

如果你拿到的包不是来自本仓库 Releases，请不要继续运行。

## 4. 准备一个项目

第一次使用时，OPT 会引导你完成项目准备。

正常路径大致是：

```text
选择本地 Git 项目
→ 检查 GitHub
→ 确认仓库
→ 检查 Runner / Bridge
→ 检查 CI
→ READY
→ 开始 AI 开发
```

不需要为了测试而主动破坏一个已经工作的 Git 或 Runner 环境。

## 5. 如果某一步失败

先看界面给出的“下一步”。

OPT Alpha 01 的一个重要目标，就是尽量避免只给内部错误码而不告诉用户怎么办。

仍无法继续时：

1. 看 [故障排查](TROUBLESHOOTING.md)。
2. 不确定是不是 Bug：到 [Discussions](../../discussions) 提问。
3. 能稳定复现：到 [Issues](../../issues) 提交 Bug。
4. 不要把 Token、密码、完整私有仓库内容贴到公开页面。

## 6. 建议第一次体验什么

不需要把所有功能点一遍。优先完成以下几件事：

- 打开 OPT；
- 准备一个真实或测试 Git 项目；
- 看懂项目当前是否 Ready；
- 看懂 Runner / CI 是否正常；
- 启动或观察一个任务；
- 关闭 OPT 后重新打开，确认上下文仍能继续；
- 如果自然遇到异常，看看你是否知道下一步怎么办。

## 7. 日志

应用异常日志默认位置：

```text
%LOCALAPPDATA%\OPTAssetLite\logs\app.log
```

提交日志前请先检查是否包含你不希望公开的信息。

如果问题涉及 Bridge / Runner，可在产品提供相应入口时附带 Support Bundle。

## 下一步

- [Alpha 01 内测说明](ALPHA-TESTING.md)
- [FAQ](FAQ.md)
- [故障排查](TROUBLESHOOTING.md)
- [隐私与反馈数据说明](PRIVACY.md)
