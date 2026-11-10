# Hi there, this is maryzhoucx

Exploring self-hosted tools, AI agents, and small automation projects. I keep notes on what I actually try and run.

## 🔥 热门推荐

> 每天发现的热门项目，每日更新。

<!-- TRENDING:START -->
- [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) — ★144375，把代码库、文档、SQL、PDF 变成可查询的知识图谱，本地确定性解析、无向量库
- [stablyai/orca](https://github.com/stablyai/orca) — ★119131，用自己的订阅跑一队编程智能体（Claude Code、Codex 等），桌面、手机、远程都能用
- [paperclipai/paperclip](https://github.com/paperclipai/paperclip) — ★112269，开源的团队智能体管理应用
- [robbietilton/Compositor](https://github.com/robbietilton/Compositor) — ★18538，Mac 原生开源 Photoshop 替代品
- [storytold/filmcraft](https://github.com/storytold/filmcraft) — ★17833，纯 Rust 从零写的开源非线性视频编辑器
- [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) — ★4680，用 7 美元 ESP32 让 AI 模型操作真 iPhone，无需 Mac、开发者账号或越狱
<!-- TRENDING:END -->

热门区每天两次随热门汇总同步更新（约 09:52 / 21:52 美东）。

## 🛠️ 我常用的工具

> 只写实际用过、本地已验证的工具。

- **微信桥（自托管）**：通过 ClawBot / iLink 桥接 WeChat，处理 1-1 文字消息；2026-11-04 实测状态为 polling，收发队列为空，登录已绑定。
- **Microsoft Rewards 脚本**：[TheNetsky/Microsoft-Rewards-Script](https://github.com/TheNetsky/Microsoft-Rewards-Script)，本地已安装并配每日自动运行，用于小号自动完成每日任务。
- **REA 静态分析（本地 CLI）**：[morluto/rea](https://github.com/morluto/rea) 的 rea-agents 6.8.0，本地装在 custom-connectors/custom.rea/node_modules/.bin/rea（不在 PATH）；2026-11-04 实测 --version 返回 6.8.0，并对一个单文件 JS 测试程序跑通 analyze-javascript-application，返回完整证据记录（evidence_id ev_25d1ff54…）。只做 JS/Electron 静态分析，不承诺原生反编译（本机未装 Hopper/Ghidra/IDA）。

## 📓 实测记录

> 只记当天实际跑过、查证过的东西，数字以日志为准。

- **2026-11-10**：Microsoft Rewards 每日跑分 +175 分，余额 1660 → 1835 分；移动端每日任务、阅读 10 篇、桌面搜索 10 次均完成（日志 [RUN-END]，EXIT:0）。一项 UrlReward「A new web hero」已领取但未计分。
- **2026-11-10**：微信桥过去 24 小时上游 RemoteProtocolError 16 次、轮询重启 12 次，每次 1–2 分钟内自动恢复；登录有效、无消息积压。
