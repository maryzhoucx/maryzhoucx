# Hi there, this is maryzhoucx

Exploring self-hosted tools, AI agents, and small automation projects. I keep notes on what I actually try and run.

## 🔥 热门推荐

> 每天发现的热门项目，每日更新。

<!-- TRENDING:START -->
- [anthropics/claude-code](https://github.com/anthropics/claude-code) — ★154565，住在终端里的 AI 编程助手，能读懂代码库并直接动手写代码、跑测试
- [browser-use/jev-ultrafast](https://github.com/browser-use/jev-ultrafast) — ★24181，主打最快、最便宜的网页智能体，能自动操作浏览器完成网页任务
- [storytold/pdfcraft](https://github.com/storytold/pdfcraft) — ★19570，用纯 Rust 从零写的开源 PDF 阅读器和编辑器，轻快可本地运行
- [gogs/gogs](https://github.com/gogs/gogs) — ★47917，轻量易装的自托管 Git 服务，自己搭一个私有的代码托管站
- [appsmithorg/appsmith](https://github.com/appsmithorg/appsmith) — ★41159，低代码平台，拖拖拽拽加接数据库和 API 就能搭出管理后台和内部工具
- [Droid-Deck/DroidDeck](https://github.com/Droid-Deck/DroidDeck) — ★17901，把 SteamOS 的游戏主机体验带到安卓设备上，适合掌机式游玩
<!-- TRENDING:END -->

热门区每天两次随热门汇总同步更新（约 09:52 / 21:52 美东）。

## 🛠️ 我常用的工具

> 只写实际用过、本地已验证的工具。

- **微信桥（自托管）**：通过 ClawBot / iLink 桥接 WeChat，处理 1-1 文字消息；2026-11-04 实测状态为 polling，收发队列为空，登录已绑定。
- **Microsoft Rewards 脚本**：[TheNetsky/Microsoft-Rewards-Script](https://github.com/TheNetsky/Microsoft-Rewards-Script)，本地已安装并配每日自动运行，用于小号自动完成每日任务。
- **REA 静态分析（本地 CLI）**：[morluto/rea](https://github.com/morluto/rea) 的 rea-agents 6.8.0，本地装在 custom-connectors/custom.rea/node_modules/.bin/rea（不在 PATH）；2026-11-04 实测 --version 返回 6.8.0，并对一个单文件 JS 测试程序跑通 analyze-javascript-application，返回完整证据记录（evidence_id ev_25d1ff54…）。只做 JS/Electron 静态分析，不承诺原生反编译（本机未装 Hopper/Ghidra/IDA）。
