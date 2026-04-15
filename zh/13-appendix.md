# 第 13 章：附录

> [English Version](../13-appendix.md)

---

## 源文档索引

本教程基于以下源文档编撰：

| 源文件 | 行数 | 核心内容 |
|--------|------|----------|
| `guide.md` | 990 | 基础 Prompting、推理增强、Agent、上下文工程、安全防御 |
| `frameworks-analysis-zh.md` | 867 | AutoGPT/CrewAI/Claude Code 源码级 Prompt 分析（中文） |
| `frameworks-analysis-en.md` | 867 | 同上（英文） |
| `claude-code/claude-code-prompt-analysis.md` | 682 | Claude Code 泄露系统提示词逐段分析 |
| `openclaw/openclaw-prompt-system.md` | 189 | OpenClaw 提示系统组成与配置 |
| `openclaw/openclaw-prompt-templates.md` | 474 | OpenClaw 实际提示模板中英对照 |
| `oh-my-codex/` | 109 文件 | 29 角色完整 Prompt 提取 + 架构分析 |
| `oh-my-openagent/` | 75 文件 | 11 代理三语对照文档 + 学习路径 |

---

## 学术研究论文

### 核心论文

| 论文 | 作者 | 年份 | arXiv 链接 |
|------|------|------|-----------|
| Chain-of-Thought Prompting Elicits Reasoning in Large Language Models | Wei et al. | 2022 | [arXiv:2201.11903](https://arxiv.org/abs/2201.11903) |
| ReAct: Synergizing Reasoning and Acting in Language Models | Yao et al. | 2022 | [arXiv:2210.03629](https://arxiv.org/abs/2210.03629) |
| Tree of Thoughts: Deliberate Problem Solving with Large Language Models | Yao et al. | 2023 | [arXiv:2305.10601](https://arxiv.org/abs/2305.10601) |
| Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks | Lewis et al. | 2021 | [arXiv:2005.11401](https://arxiv.org/pdf/2005.11401.pdf) |
| Large Language Models are Zero-Shot Reasoners | Kojima et al. | 2022 | [arXiv:2205.11916](https://arxiv.org/abs/2205.11916) |
| Self-Consistency Improves Chain of Thought Reasoning in Language Models | Wang et al. | 2022 | [arXiv:2203.11171](https://arxiv.org/abs/2203.11171) |
| Reflexion: Self-Reflective Agents | Shinn et al. | 2023 | [arXiv:2303.11366](https://arxiv.org/abs/2303.11366) |

---

## 开源项目

### 多代理框架

| 项目 | 链接 | 说明 |
|------|------|------|
| AutoGPT | https://github.com/Significant-Gravitas/AutoGPT | 自主 GPT-4 实验框架 |
| CrewAI | https://github.com/crewAIInc/crewAI | 多代理编排框架 |
| Claude Code | https://github.com/anthropics/claude-code | Anthropic 官方编码助手 |
| oh-my-codex | https://github.com/Yeachan-Heo/oh-my-codex | OpenAI Codex CLI 多代理层 |
| oh-my-openagent | https://github.com/Yeachan-Heo/oh-my-openagent | OpenCode 多代理插件 |
| OpenClaw | https://github.com/openclaw/openclaw | 个人 AI 助手框架 |

### 安全工具

| 项目 | 链接 | 说明 |
|------|------|------|
| LLM Guard | https://github.com/protectai/llm-guard | LLM 输入输出安全扫描 |
| NeMo Guardrails | https://github.com/NVIDIA/NeMo-Guardrails | 对话系统安全护栏 |
| Guardrails AI | https://github.com/guardrails-ai/guardrails | 结构化输出验证 |

---

## 安全资源

### OWASP LLM Top 10

https://owasp.org/www-project-top-10-for-large-language-model-applications/

### 安全研究

| 资源 | 链接 |
|------|------|
| Prompt Injection 防御指南 | https://learnprompting.org/docs/prompt_hacking/defensive_measures |
| LLM 安全最佳实践 | https://cloud.google.com/blog/products/ai-machine-learning/mitigating-prompt-injection-attacks |
| AI 红队测试 | https://www.anthropic.com/research/red-teaming-for-generative-ai |

---

## 术语表（Glossary）

| 英文 | 中文 | 说明 |
|------|------|------|
| Prompt Engineering | 提示工程 | 设计和优化输入提示以获得更好输出的技术 |
| Zero-Shot | 零样本 | 无需示例直接推理 |
| Few-Shot | 少样本 | 提供少量示例进行推理 |
| Chain-of-Thought (CoT) | 思维链 | 引导模型逐步推理的技术 |
| Tree of Thoughts (ToT) | 思维树 | 多路径探索的推理方法 |
| ReAct | 推理+行动 | 结合推理和行动的框架 |
| RAG | 检索增强生成 | 结合外部知识检索的生成方法 |
| Agent | 代理 | 能自主执行任务的 AI 系统 |
| Prompt Injection | 提示注入 | 恶意操纵模型输入的攻击 |
| Jailbreak | 越狱 | 绕过模型安全限制的行为 |
| Context Window | 上下文窗口 | 模型能处理的最大输入长度 |
| Token | 令牌 | 模型处理的基本文本单位 |
| Temperature | 温度 | 控制输出随机性的参数 |
| System Prompt | 系统提示 | 定义模型行为的初始指令 |
| Multi-Agent | 多代理 | 多个 AI 代理协作的系统 |
| Skills | 技能 | 预定义的工作流或能力模块 |
| Orchestration | 编排 | 协调多个组件或代理的过程 |
| Defense-in-Depth | 纵深防御 | 多层安全防御策略 |
| Observability | 可观测性 | 监控和调试系统的能力 |
| Structured Output | 结构化输出 | 按特定格式（JSON/XML）输出 |

---

## 版本更新记录

### v1.0.1 (2026-04-15)
- 日期同步更新：2026-04-14 → 2026-04-15

---

### v1.0.0 (2026-04-15)
- 初始版本发布
- 包含 13 章完整教程（中英双语）
- 覆盖基础到高级全部内容
- 包含 5 个实战案例
- 包含 15+ 可复用模板

---

*本附录持续更新，如有遗漏请提交反馈。*
