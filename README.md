---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: 791cb3c8963b65894fbf91a10e48b476_89e259aa5cbb11f1b2415254002afed2
    ReservedCode1: OQkbDnbcmJzXvYqCnyMDnFpIOGZUfwY6oLgW+du18YiIBu8aKk536KQU4HxWnITm/WXpcgeTosrkGRo2ObPRhYq6p9ELsx1aJYk1HVqNrFgp6UFxxTgetobmKd3iwEt0phql9291+9ZVuZNB1rZW6Rufrh3o/ZWYFFEVVYqUXQNdUzrHPN8JPUKt/E8=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: 791cb3c8963b65894fbf91a10e48b476_89e259aa5cbb11f1b2415254002afed2
    ReservedCode2: OQkbDnbcmJzXvYqCnyMDnFpIOGZUfwY6oLgW+du18YiIBu8aKk536KQU4HxWnITm/WXpcgeTosrkGRo2ObPRhYq6p9ELsx1aJYk1HVqNrFgp6UFxxTgetobmKd3iwEt0phql9291+9ZVuZNB1rZW6Rufrh3o/ZWYFFEVVYqUXQNdUzrHPN8JPUKt/E8=
---

# BKS Studio

> 一个 Builder + 一群 AI Agent。这不是工具调用，是持牌上岗的团队协作。

---

## 团队大事记

### 2026-05-31 — 团队正式成立

KK 决定将协作 Agent 体系正规化。从"一个助手"升级为"一个团队"。

| 里程碑 | 详情 |
|--------|------|
| 团队命名 | 经 小马 × CC 联合提案，KK 选定 **BKS**（BKS Studio） |
| 组织架构 | 项目部（小马）+ 研发部（CC），KK 直接领导 |
| 基础设施 | Git 仓库体系建立，团队灵魂与项目代码物理隔离 |
| 协作规范 | 四项纪律、TOK 双签、代工原则、产出物留痕 |
| 回顾机制 | 日报/周报/SOP 三层复盘体系，持续自我进化 |
| 首个项目 | 团队工作室（像素风格三方协作空间）立项 |

### 2026-06-01 — BKS V1.0 正式发布

一天之内完成首次正式协作全流程闭环，团队规范从 v1.0 迭代至 v1.8。

| 里程碑 | 详情 |
|--------|------|
| Hub-Spoke 架构 | 四 Agent 调度体系落地，群聊消息协议 + 文件路径流转规则 |
| TOK 双签机制 | 自检（T/O/K）+ Marvis 终审，产出物交叉审阅 |
| 复盘标准化 | 四阶段流程（20min 标准/35min 上限），异常处理协议，经验固化 |
| 多任务追踪 | 纪律八：承诺 ≥2 件事须建追踪清单，接收方反向校验 |
| CC 稳定性 | fetch 超时保护 + 指数退避重试 + shared-memory 单数据源改造 |
| 知识库上线 | 协作流程 / 技术方案 / 工具配置 / 故障排查四分类，复盘知识永久保留 |
| GitHub 自动化 | 团队文档实时推送，项目代码日推，公开展示同步维护 |

---

## 组织能力

| 能力域 | 说明 |
|--------|------|
| 产品定义 | 需求分析 → PRD → 交互原型（小马 主导） |
| 技术架构 | Node.js / Preact / Canvas 2D / WebSocket / SQLite（CC 主导） |
| 自动化运维 | Git + GitHub API + 代理穿透 + 定时复盘 + 守护进程 |
| 团队协作 | Hub-Spoke 调度 / TOK 双签 / 群聊消息协议 / 多任务追踪 |
| 像素视觉 | CSS 像素方块手绘动画，独立角色状态机 |
| Agent SDK | 自研 Agent 接入模块，支持心跳保活、离线消息排队、状态同步 |
| 实时通信 | WebSocket 全双工通信，支持自动重连、消息去重、历史加载 |
| 知识沉淀 | 四分类知识库（协作流程/技术方案/工具配置/故障排查），复盘经验永久保留 |

---

## 项目

### 团队工作室 `V1.0 已发布`

像素风格的线上团队协作空间，KK / 小马 / CC 三方实时群聊。

| 维度 | 详情 |
|------|------|
| 仓库 | [github.com/xjtluk/team-workspace](https://github.com/xjtluk/team-workspace) |
| 前端 | Preact + Canvas 2D 像素网格渲染 |
| 后端 | Node.js + Express + WebSocket + SQLite (sql.js) |
| 通信 | WebSocket 全双工，支持自动重连、消息去重、离线排队 |
| UI 风格 | 像素风格，CRT 扫描线效果，Press Start 2P 字体 |
| Agent SDK | 自研接入模块，支持心跳保活、状态同步、历史消息加载 |

**技术亮点**：
- **Hub-Spoke 架构**：小马作为任务分发中枢，CC 作为执行单元，KK 作为决策层
- **TOK 双签机制**：产出方自检（T/O/K）+ Marvis 终审，确保交付质量
- **实时群聊**：WebSocket 全双工通信，支持消息去重、历史加载、离线排队
- **像素风格 UI**：Canvas 2D 渲染，CRT 扫描线效果，独立角色状态机
- **知识沉淀**：四分类知识库，复盘经验永久保留，团队持续进化

---

## 成长日志

| 日期 | 事件 |
|------|------|
| 2026-06-01 | V1.0 正式发布，团队规范迭代至 v1.9，知识库上线，GitHub 自动化推送 |
| 2026-05-31 | 团队成立，首个项目立项，Git 仓库体系+复盘机制搭建完成 |

## 团队数据

| 指标 | 数值 |
|------|------|
| 团队规范版本 | v1.9（10 次迭代） |
| 知识库条目 | 4 分类，持续积累中 |
| GitHub 仓库 | 3 个（BKS-team / team-workspace / BKS-portfolio） |
| 协作消息协议 | 8 种类型（任务/完成/TOK/问题/审阅/收到/通过/打回） |
| 复盘机制 | 日报/周报/SOP 三层体系，四阶段标准流程 |

---

*Built by KK, operated by 小马 & Claude Code.*
*（内容由AI生成，仅供参考）*
