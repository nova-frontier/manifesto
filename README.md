<img src="https://raw.githubusercontent.com/nova-frontier/.github/main/profile/assets/groundstate-banner.svg" alt="GROUNDSTATE" width="100%">

# GROUNDSTATE · 基态

**让智能接受现实的约束，让研究留下可检验的证据。**

本仓库是组织的研究总纲、协作约定与路线图入口。我们研究具身智能、群体智能与多智能体协作，尝试把模型能力连接到可测量、可复现、可解释的系统行为。

“基态”是一种工程隐喻：回到能量、通信、身体、工作流和规则这些基础条件。它不是对系统已经达到最优状态的宣称。

## 从哪里开始

1. 阅读 [RFC-001 · 研究与工程约定](rfcs/RFC-001.md)。
2. 选择一个研究节点，运行其演示和测试。
3. 从 [路线图](ROADMAP.md) 认领一个小工作包。
4. 用 [证据记录模板](templates/evidence-record.md) 保存输入、过程、结果和限制。

## 五个节点

| 层 | 名称 | 工作对象 | 当前交付 |
|---|---|---|---|
| L1 | [瓦特与比特](https://github.com/nova-frontier/watt-to-token-bench) | 能量与算力 | 功率积分、测量协议、合成 CSV |
| L2 | [香农港](https://github.com/nova-frontier/edge-swarm-protocol) | 受限通信 | 带宽、时延、丢包与中断的合成信道探针 |
| L3 | [第七自由度](https://github.com/nova-frontier/embodied-field-notes) | 身体与现场 | 试验记录检查、失败复盘模板 |
| L4 | [像素人间](https://github.com/nova-frontier/mundane-agent-kits) | 工作流 | 尝试预算、异常与回退的离线事件回放 |
| L5 | [权重之上](https://github.com/nova-frontier/agentic-order-spec) | 来源与规则 | 组件元数据清单、复核记录 |

五个视角协同而非固定流水线；按具体问题选用。节点不等于成员名册，也不代表学校或机构的正式合作关系。

## 当前状态

**初始化 / v0.1。** 已提供五个标准库 Python 起步工具、示例、单元测试与 CI 配置。这些工具验证局部算术、输入结构或控制分支；它们尚不构成经过硬件验证的具身系统、完整多智能体协议或生产级 Agent 框架。

没有公开的实测基准、节能比例、成功率或生产部署结论。合成、仿真、回放和实测应分别标记；未知就是未知。

## 我们如何协作

以 Issue 描述问题，以 PR 提交可复查的改动，以 RFC 讨论跨节点约定。认领基于自愿，身份与公开范围由成员自行决定。贡献代码、复现、测量、文档、设计和规则分析都可以从小问题开始。

<img src="https://raw.githubusercontent.com/nova-frontier/.github/main/profile/assets/04-notebook-and-machine.jpg" alt="机械手研究笔记的 AI 概念视觉" width="760">

*AI 生成概念视觉，不是历史科学家真迹、团队手稿或实验记录。 [来源说明](https://github.com/nova-frontier/.github/blob/main/profile/assets/PROVENANCE.md)*

[组织主页](https://github.com/nova-frontier) · [路线图](ROADMAP.md) · [贡献约定](https://github.com/nova-frontier/.github/blob/main/CONTRIBUTING.md) · [MIT](LICENSE)
