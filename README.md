# 空旻缰绳 Rein for DeepSeek Harness

> 安全的 DeepSeek Harness 客户端 · 治理配套（推广 / 插件 / 验收 / 治理 / 服务）

空旻缰绳（Rein for DeepSeek Harness）——把 DeepSeek Harness 自带的治理机制（gate / 沙箱 / 权限钩子 / 对话轨迹）接成企业可用的治理配套：**权限管住、出圈必问、留痕可审**。

## 版本体系

| 版本 | 名称 | 说明 |
|------|------|------|
| 基础版（体验版） | Rein for DeepSeek Harness | 单根缰绳管一个 AI：体验版免费可用 |
| 高阶版 | 空旻缰绳·总调度版（Reins） | 多根缰绳管一群 AI：总调度席 + 企业部署 |

## 下载

- 体验版安装包：见 [kongminOS/dsh-client-shell Releases](https://github.com/kongminOS/dsh-client-shell/releases)
- 开源壳源码：kongminOS/dsh-client-shell（MIT）

## 合规声明

- 引擎：DeepSeek Harness（MIT，deepseek-ai/deepseek-harness）v0.1 开发者预览，官方明示会有不兼容改动
- 本产品为**第三方发行版**，与深度求索（DeepSeek）无隶属关系，vendor-neutral
- Open Core：壳（MIT 开源）+ 治理核心（BSL 1.1 商业保护）
- 当前版本：体验版 v0.1，持续迭代

## 产品概念族（概念占位 · 2026-08-17 更新：已建四仓）

> 空旻缰绳产品体系概念名先行占位（防抄袭/仿造同名）。已建仓为概念占位，将随产品开源进度补充代码。

| 概念仓 | 定位 | 状态 |
|--------|------|------|
| [rein-gate](https://github.com/kongminOS/rein-gate) | 空旻缰绳闸门（G0-G6 闸门体系） | ✅ 已建占位 |
| [rein-governance](https://github.com/kongminOS/rein-governance) | 空旻缰绳治理（AI 治理层） | ✅ 已建占位 |
| [rein-hub](https://github.com/kongminOS/rein-hub) | 空旻缰绳生态中心（插件/技能生态） | ✅ 已建占位 |
| [rein-board](https://github.com/kongminOS/rein-board) | 空旻缰绳总调度台（任务看板+人工审阅，Reins 核心交互） | ✅ 已建占位 |
| rein-console | 空旻缰绳控制台（治理控制台） | ⏳ 待建（避免与识海 MCP 混淆，暂缓） |
| rein-shell | 空旻缰绳壳（开源壳） | ⏳ 已由 kongmin-dsh-desktop-shell 承担 |
| rein-suite | 空旻缰绳套件（产品全家桶） | ⏳ 暂缓 |

