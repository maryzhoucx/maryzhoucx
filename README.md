# Hi there, this is maryzhoucx

Exploring self-hosted tools, AI agents, and small automation projects. I keep notes on what I actually try and run.

## 🔥 热门推荐

> 每天发现的热门项目，每日更新。

<!-- TRENDING:START -->
- [ClickHouse/ClickHouse](https://github.com/ClickHouse/ClickHouse) — ★50738，实时分析数据库，查询海量数据快如闪电
- [photoprism/photoprism](https://github.com/photoprism/photoprism) — ★40404，带 AI 识别的自托管相册，自动分类整理照片
- [TriliumNext/Trilium](https://github.com/TriliumNext/Trilium) — ★38693，可自托管的个人知识库，层级笔记加富文本编辑
- [khoj-ai/khoj](https://github.com/khoj-ai/khoj) — ★37971，可自托管的 AI 第二大脑，能查文档、联网问答并做自动化
- [IceWhaleTech/CasaOS](https://github.com/IceWhaleTech/CasaOS) — ★37541，简单优雅的个人云系统，一台旧电脑变家庭服务器
- [langfuse/langfuse](https://github.com/langfuse/langfuse) — ★36967，开源 LLM 应用观测平台，追踪、评估并优化 AI 应用
<!-- TRENDING:END -->

## 🛠️ 我常用的工具

> 只写实际用过、本地已验证的工具。

- **微信桥（自托管）**：通过 ClawBot / iLink 桥接 WeChat，处理 1-1 文字消息；2026-11-03 实测状态为 polling，收发队列为空。
- **Microsoft Rewards 脚本**：[TheNetsky/Microsoft-Rewards-Script](https://github.com/TheNetsky/Microsoft-Rewards-Script)，本地已安装并配每日自动运行，用于小号自动完成每日任务。
- **REA 静态分析（本地 CLI）**：[morluto/rea](https://github.com/morluto/rea) 的 rea-agents 6.8.0，本地装在 custom-connectors/custom.rea/node_modules/.bin/rea（不在 PATH）；2026-11-04 实测 --version 返回 6.8.0，并对一个单文件 JS 测试程序跑通 analyze-javascript-application，返回完整证据记录（evidence_id ev_25d1ff54…）。只做 JS/Electron 静态分析，不承诺原生反编译（本机未装 Hopper/Ghidra/IDA）。
