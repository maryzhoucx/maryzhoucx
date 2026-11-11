# Hi there, this is maryzhoucx

Exploring self-hosted tools, AI agents, and small automation projects. I keep notes on what I actually try and run.

## 🔥 热门推荐

> 每天发现的热门项目，每日更新。

<!-- TRENDING:START -->
- [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) — ★113319，给编程智能体注入审美：艺术指导、参考图与浏览器检查，告别千篇一律的 AI 风格界面
- [tt-a1i/archify](https://github.com/tt-a1i/archify) — ★95567，把想法、计划或代码库一键变成精美的交互式架构图
- [Egonex-AI/Understand-Anything](https://github.com/Egonex-AI/Understand-Anything) — ★92042，把任意代码变成可探索、可提问的交互式知识图谱
- [cheaper-inference/OmniRoute](https://github.com/cheaper-inference/OmniRoute) — ★86455，免费开源 AI 网关：一个接口接入 375 家服务商、1400+ 模型，自动切换、节省 token
- [rtk-ai/rtk](https://github.com/rtk-ai/rtk) — ★86213，单文件 Rust 二进制代理，常见开发命令可省 60–90% 的 LLM token
- [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) — ★82627，写 HTML 就能渲染视频，专为 AI 智能体打造的视频生成工具
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
