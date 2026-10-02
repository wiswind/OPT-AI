<div align="center">

<img src="assets/opt-logo.png" width="132" alt="OPT Logo">

# OPT · AI Optimization Master

**让 AI 项目、记忆、任务、Runner / CI 与本地能力真正协同工作的 Windows 本地优先工作环境**

[下载 OPT](../../releases) · [快速开始](docs/GETTING-STARTED.md) · [常见问题](docs/FAQ.md) · [反馈问题](../../issues) · [交流讨论](../../discussions)

</div>

---

> **当前阶段：OPT Alpha 01 · 0.3.0-alpha.1 · 封闭内测**
>
> Alpha 01 已完成工程验收，目前主要目标不是继续堆功能，而是通过真实用户使用发现首次上手、环境兼容、任务恢复和理解成本上的问题。

## OPT 是什么

OPT 是一个 **Windows 本地优先的 AI 工作环境**。它希望解决一个很现实的问题：

> 当 AI 编程、长期记忆、GitHub、Runner、CI、本地模型和多个 Agent 越来越多时，用户不应该自己记住每个工具的状态、路径和恢复方法。

OPT 把这些能力收拢到一个统一入口，并尽量把复杂的内部状态翻译成普通用户能理解的结论和下一步。

目前主要包括：

- **项目准备**：从本地 Git 项目开始，检查 GitHub、仓库、Runner、CI 与 AI 开发准备状态。
- **任务中心**：识别任务是在运行、正常静默等待、停滞、不可达、失败还是已经完成。
- **记忆库**：发现并复用已有记忆环境，支持跨会话连续工作。
- **开发环境**：读取本机 Runner、Bridge、Workflow 路由和最近 CI 状态。
- **AI 资产**：统一管理 Skill、Rules、MCP、Agent、Knowledge 等能力资产。
- **保护与迁移**：在修改、迁移和恢复时尽量保留可回退证据。
- **续接与换新对话**：长任务或长对话出现问题时，基于最新状态安全继续，而不是盲目重来。

## 谁适合参加 Alpha 01

目前更适合：

- 经常用 ChatGPT / Codex / AI Agent 做较长开发任务的人；
- 已经在使用 GitHub，希望把本地 Runner / CI 接入 AI 工作流的人；
- 经常遇到长对话、任务停滞、上下文丢失、跨会话接续问题的人；
- 希望把 AI 记忆、规则、MCP、项目配置等放在一个本地优先环境里管理的人。

如果你只是偶尔问几个问题、没有 Git/GitHub 使用经验，Alpha 01 可能还偏早。后续版本会继续降低门槛。

## 下载

正式给测试者使用的版本会统一发布在：

**[GitHub Releases](../../releases)**

当前 Alpha 01：

- 版本：`0.3.0-alpha.1`
- 平台：Windows 10 / 11 x64
- 交付方式：免安装压缩包
- .NET / Python / Node：普通用户无需额外安装
- 代码签名：Alpha 01 暂无，因此 Windows 可能显示“未知发布者”或 SmartScreen 提示
- 自动更新：Alpha 01 暂无，每次新版本请从 Releases 获取

首次使用请看：[快速开始](docs/GETTING-STARTED.md)

## 反馈方式

我们把不同类型的反馈分开处理：

- **不会用 / 不确定是不是 Bug**：优先到 [Discussions](../../discussions) 提问。
- **功能想法 / 使用体验**：到 [Discussions](../../discussions) 交流。
- **可以稳定复现的 Bug**：使用 [Issues](../../issues) 中的 Bug 模板。
- **Windows / Runner / 环境兼容问题**：使用兼容性问题模板。
- **文档错误或看不懂**：使用文档问题模板。
- **安全漏洞**：不要公开贴 Token、日志或私有信息，请先阅读 [SECURITY.md](SECURITY.md)。

第一批 Alpha 最有价值的反馈不是“再加一个功能”，而是：

> 哪一步让你不知道发生了什么？  
> 哪一步让你不知道该点哪里？  
> 哪一步失败后你不知道怎么恢复？  
> 哪些内部概念本来不应该要求你理解？

## Alpha 01 已知限制

- 仅支持 Windows x64。
- 暂无安装器。
- 暂无代码签名。
- 暂无自动更新。
- 当前仍是封闭内测，不建议把测试包公开扩散。
- 部分开发环境能力需要 GitHub 与本地 Runner。
- 这是产品门户仓库，**不是 OPT 源码仓库，也不是开源代码仓库**。

更多说明见：[Alpha 01 内测说明](docs/ALPHA-TESTING.md)

## 关于这个仓库

`wiswind/OPT-AI` 是 OPT 的**公开产品门户**，用于：

- 产品介绍
- 下载与版本说明
- 用户文档
- FAQ / 故障排查
- Bug 反馈
- Discussions 社区交流

核心研发代码、内部 CI、设计 checkpoint 和工程问题在私有研发仓中维护，不在这里公开。

## 文档

- [快速开始](docs/GETTING-STARTED.md)
- [Alpha 01 内测说明](docs/ALPHA-TESTING.md)
- [常见问题 FAQ](docs/FAQ.md)
- [故障排查](docs/TROUBLESHOOTING.md)
- [隐私与反馈数据说明](docs/PRIVACY.md)
- [安全问题报告](SECURITY.md)
- [如何参与反馈](CONTRIBUTING.md)
- [版本记录](CHANGELOG.md)

---

<div align="center">

**OPT Alpha 01 · 先把真实工作跑通，再决定下一步做什么。**

</div>
