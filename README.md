# Hi there, this is maryzhoucx

Exploring self-hosted tools, AI agents, and small automation projects. I keep notes on what I actually try and run.

## 🔥 热门推荐

> 每天发现的热门项目，每日更新。

<!-- TRENDING:START -->
- [career-ops-hq/career-ops](https://github.com/career-ops-hq/career-ops) — ★82016，开源 AI 求职助手：扫描招聘网站、按简历给岗位打分、定制 ATS 友好简历与求职信，还能做面试准备
- [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) — ★70382，LLM 驱动的多市场股票智能分析系统：多源行情、实时新闻、决策看板与自动推送，支持零成本定时运行
- [codewhale-hq/Codewhale](https://github.com/codewhale-hq/Codewhale) — ★41179，用 Rust 编写的开源终端编程 Agent，支持任意大模型厂商，可多 Agent 协同
- [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) — ★36157，面向复杂软件工程任务的 DeepSeek 编程 Agent，在终端内完成编码工作
- [Twigpine/openclaude](https://github.com/Twigpine/openclaude) — ★34338，随处运行、支持任意模型的开源 Agent 命令行工具
- [googleworkspace/cli](https://github.com/googleworkspace/cli) — ★32264，Google 官方出品的 Workspace 命令行工具，一条命令操作 Drive、Gmail、日历、表格等
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
- **2026-11-11**：Microsoft Rewards 每日跑分 +150 分，余额 1835 → 1985 分；移动端每日任务 3 项 +30、每日一句 +5、月度精选 2 项 +20、签到 +15、阅读 10 篇 +30、桌面搜索 +50（日志 [RUN-END]，运行时长 21.4 分钟）。
- **2026-11-11**：微信桥过去 24 小时上游 RemoteProtocolError 14 次、轮询重启 10 次，均自动恢复；登录有效、无消息积压（2026-11-11 14:49 UTC status.py 实测）。
- **2026-11-12**：Microsoft Rewards 每日跑分 +670 分，余额 1985 → 2655 分；移动端每日任务 3 项 +50、每日一句 +5、月度精选 2 项 +20、签到 +15、阅读 10 篇 +30、桌面搜索 10 次 +50、奖励领取 +500（日志 [RUN-END]，运行时长 21.8 分钟）。
- **2026-11-12**：微信桥过去 24 小时上游 RemoteProtocolError 18 次、轮询重启 13 次，均自动恢复；登录有效、无消息积压（2026-11-12 14:34 UTC status.py 实测，桥日志按 2026-11-11 14:49 UTC 起 24 小时窗口精确计数）。
- **2026-11-13**：Microsoft Rewards 每日跑分 +310 分，余额 2655 → 2965 分；移动端每日任务 +130、签到 +50、阅读 10 篇 +30、奖励领取 +100；桌面搜索因上游响应流错误 0/100 未计分（日志逐条核实；[RUN-END] 末尾余额读取失败显示 0，实际以逐条日志为准，运行时长 13.0 分钟）。
- **2026-11-13**：微信桥过去 24 小时上游 RemoteProtocolError 15 次、轮询重启 12 次，均自动恢复；登录有效、无消息积压（2026-11-13 14:34 UTC status.py 实测，桥日志按 2026-11-12 14:49 UTC 起 24 小时窗口精确计数）。
