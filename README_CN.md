# Meta-Harness：AI Agent 时代的 Harness 生成、验证与演化平台

> **Meta-Harness 产品战略计划书**
>
> 关于构建 Agent 时代"生产线生成器"的产品战略文档。

## 仓库内容

| 文件 | 说明 |
|------|------|
| `Meta-Harness-Strategy-Text.pdf` | 产品战略书文字版 (~534 KB) |
| `Meta-Harness-Strategy-Deck.pdf` | 产品战略书 PPT 版 (~13 MB) |

---

## 核心判断

AI Agent 的下一阶段竞争，不只是模型能力竞争，而是 **Harness 能力竞争**。

过去两年，Coding Agent 率先爆发，原因不只是模型会写代码，而是软件工程天然拥有 repo、test、CI、diff、review、rollback 等完整工作环境。模型进入这个环境后，才从"回答问题的助手"变成了"能参与生产流程的执行主体"。

但在教育、HR、销售、运营、咨询、内容、数据分析、中小企业管理等更广泛行业中，这种结构化 Harness 并不存在。很多用户不是不需要 Agent，而是不知道如何把自己的需求、行业经验、工具、流程、记忆、质量标准和验证机制组织成一个可持续工作的 AI 系统。因此，Agent 仍然停留在"辅助人完成旧流程"的阶段，而没有真正进入各行业的主生产流程。

**Meta-Harness 要解决的正是这个问题：让 AI 自动生成适合具体任务和行业的小 Harness。**

---

## 什么是 Harness？

这里的 Harness 不是 prompt，而是一套围绕模型构建的**任务执行系统**，包括：

- **角色（Roles）** — agent 身份与职责
- **命令与工具权限（Commands & Tool Permissions）** — agent 可以做什么
- **记忆策略（Memory Strategy）** — 上下文与知识如何保留
- **工作流（Workflows）** — 分步执行流程
- **评估标准（Rubric）** — 质量评价准则
- **硬验证器（Hard Validator）** — 确定性验证（测试、schema 检查等）
- **评估用例（Eval Cases）** — 性能评估基准
- **产出物（Artifacts）** — 结构化输出模板
- **受控演化（Controlled Evolution）** — 基于真实 trace 数据的版本化改进

---

## Agent 生态的四个层级

| 层级 | 定义 | 示例 |
|------|------|------|
| **Skill** | 能力模块 | 单个工具或 API 调用 |
| **小 Harness** | 领域工作系统 | GStack、自定义 agent 工作流 |
| **大 Harness** | 完整 Agent 产品或运行环境 | Claude Code、Cursor、Devin |
| **Meta-Harness** | 生成和改进工作系统的平台 | **本项目** |

GStack 等项目已经证明，小 Harness 可以显著提升 Agent 的生产力边界；但它们仍然依赖少数既懂领域、又会操作 Claude Code / Codex / OpenCode 等工具的高手，通过 Agent 辅助反复打磨。普通业务专家即使懂行业，也很难自己造出可运行、可验证、可演化的 Harness。

---

## 产品机会

Meta-Harness 的产品机会在于，把这种"高手驱动 Agent 生成小 Harness"的个人能力，**产品化**为普通用户、业务专家和企业团队都能使用的平台能力。

用户只需要描述目标 → 系统就能生成：

1. **领域蓝图** — 问题空间的结构化描述
2. **角色结构** — 需要哪些 agent
3. **工作流** — 执行流程
4. **工具权限** — 允许执行的操作
5. **评估标准** — rubric + validator
6. **输出模板** — artifact schema

真实运行后，系统还能根据 trace、validator 失败、用户修正和专家反馈提出**版本化改进**。

---

## 对模型公司的战略价值

对于模型公司而言，Meta-Harness 不只是一个应用层工具，而是从**模型/API 层进入工作流层**的战略入口。

模型公司如果只停留在 API 层，用户关系、任务数据、行业 know-how 和企业工作流可能被上层 Agent 产品拿走；而 Meta-Harness 可以让模型公司定义：

- Pack 标准
- Runtime
- Eval 框架
- Registry
- Evolution Loop

成为 Agent 时代的**工作系统基础设施**。

---

## 产品路线图

1. **CLI 与 Developer Preview** — 验证 Pack Schema、Runtime、Validator、Trace 和成本曲线
2. **Harness Studio** — 让非技术用户通过自然语言和可视化界面创建小 Harness
3. **Harness Registry** — 让官方 Pack、社区 Pack 和认证 Pack 被发现、安装、fork、复用和改进
4. **Big Harness Composer** — 让完整 Agent 产品系统也可以被组件化生成

---

## 核心壁垒

五件事构成 Meta-Harness 的竞争壁垒：

1. **需求到蓝图**：能否把模糊需求转成清晰领域蓝图
2. **可运行可验证**：能否生成可运行、可验证的小 Harness
3. **成本可控**：能否把多 Agent 工作流成本压到日常可用
4. **安全演化**：能否从真实 trace 中安全改进 Harness
5. **数据与生态飞轮**：能否形成专家、开发者、企业和模型公司之间的数据与生态飞轮

---

## 愿景

**Meta-Harness 可能成为 Agent 时代的"生产线生成器"。**

- 模型提供智能
- Agent 提供执行
- Harness 提供工作系统
- Meta-Harness 提供生成工作系统的方法

如果这个方法成立，各行业就可能迎来自己的 **Claude Code 时刻**：教育、HR、咨询、数据分析、内容生产、企业运营和个人学习，都可以拥有经过验证、持续演化、低成本运行的 AI 工作系统。

届时，经济增长的来源不只是"现有员工效率提高"，还可能是**"更多个人和小组织获得过去只有专家团队和大公司才能调用的能力"**。

---
