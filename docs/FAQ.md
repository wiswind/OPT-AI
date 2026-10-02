# 常见问题 FAQ

## OPT 是开源软件吗？

目前不是。

这个 Public 仓库是产品介绍、下载、文档和反馈入口，并不包含 OPT 核心源码，也没有开放源代码许可证。

## OPT Alpha 01 收费吗？

Alpha 01 当前用于封闭内测。是否以及如何商业化，会在真实用户验证之后再确定正式方案。

## 支持 macOS / Linux 吗？

Alpha 01 目前仅支持 Windows x64。

## Windows 10 可以吗？

Alpha 01 目标平台包括 Windows 10 / 11 x64。

如果出现系统版本兼容问题，请使用兼容性 Issue 模板反馈。

## 需要自己装 .NET、Python 或 Node.js 吗？

普通 Alpha 01 用户不需要为了运行 OPT 单独安装这些运行时。

某些被 OPT 管理的外部开发工具自身可能有独立依赖，这与 OPT 主程序运行要求不是一回事。

## 为什么 EXE 还叫 OPTAssetLite.exe？

这是 Alpha 01 沿用的历史内部文件名。

产品品牌已经统一为 **OPT · AI Optimization Master**。为了避免在第一个真实用户版本前为了改名引入新的兼容风险，文件名暂时保留。

## 为什么 Windows 提示未知发布者？

Alpha 01 暂无代码签名。

因此 Windows 可能显示未知发布者或 SmartScreen 提示。请只从本仓库 Releases 下载。

## OPT 会自动更新吗？

Alpha 01 暂无自动更新。

新版本发布后，需要重新从 Releases 下载。

## 我没有 GitHub，可以用吗？

OPT 的一部分本地能力可以独立理解，但 Alpha 01 的项目开发主路径与 GitHub / Runner / CI 集成较深。

如果完全没有 Git/GitHub 使用经验，当前 Alpha 可能还偏早。

## Runner 是什么？我必须理解吗？

不应该要求你深入理解。

Alpha 01 会尽量把它翻译成“当前机器是否具备执行能力、哪里需要修复”。如果你发现自己必须研究一堆 Runner 内部概念才能继续，这本身就是值得反馈的问题。

## 什么是 expected silence？

有些任务运行时会有一段时间没有输出，但这是正常等待，不代表任务已经卡死。

OPT 会尝试区分正常静默与真正停滞，减少用户因为“看起来没动静”而重复启动任务。

## 遇到问题应该发 Issue 还是 Discussion？

如果你还不确定是不是 Bug：**Discussion**。

如果能稳定复现、明显属于产品错误：**Issue**。

功能建议和开放讨论也优先放 Discussion。

## 可以直接给仓库提 Pull Request 吗？

目前不接受外部源码贡献。

这个仓库主要用于文档、发行和反馈。核心研发在私有工程仓完成。
