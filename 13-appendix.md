# Chapter 13: Appendix

[中文版](13-appendix-zh.md)

---

## Table of Contents

1. [Source Document Index](#source-document-index)
2. [Academic Research Papers](#academic-research-papers)
3. [Open Source Projects](#open-source-projects)
4. [Security Resources](#security-resources)
5. [Glossary (EN-ZH)](#glossary-en-zh)
6. [Changelog](#changelog)

---

## Source Document Index

This tutorial is based on the following source documents from the `ai-engineering/prompt-engineering` directory:

### Core Guide

| Document | Path | Description |
|----------|------|-------------|
| **Prompt Engineering Guide** | `ai-engineering/prompt-engineering/guide.md` | Comprehensive guide covering all prompting techniques from Zero-Shot to advanced Agent systems |

### Framework Analysis Documents

| Document | Path | Description |
|----------|------|-------------|
| **Frameworks Analysis** | `ai-engineering/prompt-engineering/frameworks-analysis-en.md` | Cross-framework comparison and pattern analysis |
| **Claude Code Analysis** | `ai-engineering/prompt-engineering/claude-code/claude-code-prompt-analysis.md` | Deep dive into Claude Code's system prompt design |

### oh-my-openagent Documentation

| Document | Path | Description |
|----------|------|-------------|
| **README** | `ai-engineering/prompt-engineering/oh-my-openagent/README.md` | Project overview and architecture |
| **Learning Path** | `ai-engineering/prompt-engineering/oh-my-openagent/00-学习路径.md` | Structured learning guide |
| **Quick Start** | `ai-engineering/prompt-engineering/oh-my-openagent/01-快速开始.md` | Getting started guide |
| **Documentation Guide** | `ai-engineering/prompt-engineering/oh-my-openagent/02-文档使用指南.md` | How to use the documentation |
| **Index** | `ai-engineering/prompt-engineering/oh-my-openagent/index.md` | Complete index of all components |
| **Architecture Overview** | `ai-engineering/prompt-engineering/oh-my-openagent/architecture-overview.md` | System architecture |
| **Dependency Graph** | `ai-engineering/prompt-engineering/oh-my-openagent/dependency-graph.md` | Component dependencies |
| **Prompt Assembly Flow** | `ai-engineering/prompt-engineering/oh-my-openagent/prompt-assembly-flow.md` | How prompts are assembled |
| **File Loading Mechanism** | `ai-engineering/prompt-engineering/oh-my-openagent/file-loading-mechanism.md` | File loading system |
| **Agent Factory Pattern** | `ai-engineering/prompt-engineering/oh-my-openagent/agent-factory-pattern.md` | Agent creation patterns |

### Agent Prompts (oh-my-openagent)

| Agent | Analysis | English Prompt | Chinese Prompt |
|-------|----------|----------------|----------------|
| **Explore** | `agents/explore.analysis.md` | `agents/explore.en.md` | `agents/explore.zh.md` |
| **Librarian** | `agents/librarian.analysis.md` | `agents/librarian.en.md` | `agents/librarian.zh.md` |
| **Oracle** | `agents/oracle.analysis.md` | `agents/oracle.en.md` | `agents/oracle.zh.md` |
| **Metis** | `agents/metis.analysis.md` | `agents/metis.en.md` | `agents/metis.zh.md` |
| **Momus** | `agents/momus.analysis.md` | `agents/momus.en.md` | `agents/momus.zh.md` |

### Sisyphus Prompts (oh-my-openagent)

| Variant | Analysis | English | Chinese |
|---------|----------|---------|---------|
| **Main** | `sisyphus/main.analysis.md` | `sisyphus/main.en.md` | `sisyphus/main.zh.md` |
| **Default** | `sisyphus/default.analysis.md` | `sisyphus/default.en.md` | `sisyphus/default.zh.md` |
| **Gemini** | `sisyphus/gemini.analysis.md` | `sisyphus/gemini.en.md` | `sisyphus/gemini.zh.md` |
| **GPT-5-4** | `sisyphus/gpt-5-4.analysis.md` | `sisyphus/gpt-5-4.en.md` | `sisyphus/gpt-5-4.zh.md` |

### Prometheus Prompts (oh-my-openagent)

| Component | Analysis | English | Chinese |
|-----------|----------|---------|---------|
| **System Prompt** | `prometheus/system-prompt.analysis.md` | `prometheus/system-prompt.en.md` | `prometheus/system-prompt.zh.md` |
| **Identity Constraints** | `prometheus/identity-constraints.analysis.md` | `prometheus/identity-constraints.en.md` | `prometheus/identity-constraints.zh.md` |
| **Interview Mode** | `prometheus/interview-mode.analysis.md` | `prometheus/interview-mode.en.md` | `prometheus/interview-mode.zh.md` |
| **Plan Generation** | `prometheus/plan-generation.analysis.md` | `prometheus/plan-generation.en.md` | `prometheus/plan-generation.zh.md` |
| **High Accuracy Mode** | `prometheus/high-accuracy-mode.analysis.md` | `prometheus/high-accuracy-mode.en.md` | `prometheus/high-accuracy-mode.zh.md` |
| **Plan Template** | `prometheus/plan-template.analysis.md` | `prometheus/plan-template.en.md` | `prometheus/plan-template.zh.md` |
| **Behavioral Summary** | `prometheus/behavioral-summary.analysis.md` | `prometheus/behavioral-summary.en.md` | `prometheus/behavioral-summary.zh.md` |
| **GPT Variant** | `prometheus/gpt.analysis.md` | `prometheus/gpt.en.md` | `prometheus/gpt.zh.md` |
| **Gemini Variant** | `prometheus/gemini.analysis.md` | `prometheus/gemini.en.md` | `prometheus/gemini.zh.md` |

### Atlas Prompts (oh-my-openagent)

| Variant | Analysis | English | Chinese |
|---------|----------|---------|---------|
| **Default** | `atlas/default.analysis.md` | `atlas/default.en.md` | `atlas/default.zh.md` |
| **Gemini** | `atlas/gemini.analysis.md` | `atlas/gemini.en.md` | `atlas/gemini.zh.md` |
| **GPT** | `atlas/gpt.analysis.md` | `atlas/gpt.en.md` | `atlas/gpt.zh.md` |

### Dynamic Builder (oh-my-openagent)

| Document | Path | Description |
|----------|------|-------------|
| **Main Analysis** | `dynamic-builder/main.analysis.md` | Dynamic prompt builder analysis |
| **English** | `dynamic-builder/main.en.md` | English version |
| **Chinese** | `dynamic-builder/main.zh.md` | Chinese version |

### oh-my-codex Documentation

| Document | Path | Description |
|----------|------|-------------|
| **README** | `ai-engineering/prompt-engineering/oh-my-codex/README.md` | Project overview |
| **Navigation** | `ai-engineering/prompt-engineering/oh-my-codex/NAVIGATION.md` | Navigation guide |
| **Architecture Overview** | `ai-engineering/prompt-engineering/oh-my-codex/architecture/overview.md` | System architecture |
| **Core Modules** | `ai-engineering/prompt-engineering/oh-my-codex/architecture/core-modules.md` | Core module documentation |
| **Tech Stack** | `ai-engineering/prompt-engineering/oh-my-codex/architecture/tech-stack.md` | Technology stack |
| **Embedded Prompts** | `ai-engineering/prompt-engineering/oh-my-codex/embedded-prompts/analysis.md` | Embedded prompt analysis |
| **Agent Overview** | `ai-engineering/prompt-engineering/oh-my-codex/agents/overview.md` | Agent system overview |
| **Agent Definitions** | `ai-engineering/prompt-engineering/oh-my-codex/agents/definitions.md` | Agent definitions |
| **Agent Mapping** | `ai-engineering/prompt-engineering/oh-my-codex/agents/mapping.md` | Agent mapping |
| **Collaboration** | `ai-engineering/prompt-engineering/oh-my-codex/agents/collaboration.md` | Agent collaboration patterns |
| **AGENTS Analysis** | `ai-engineering/prompt-engineering/oh-my-codex/agents/AGENTS-analysis.md` | AGENTS.md analysis |

### oh-my-codex Prompts

| Prompt | Analysis | Translated | Original |
|--------|----------|------------|----------|
| **Dependency Expert** | `prompts/dependency-expert/analysis.md` | `prompts/dependency-expert/translated.md` | `prompts/dependency-expert/original.md` |
| **Vision** | `prompts/vision/analysis.md` | `prompts/vision/translated.md` | `prompts/vision/original.md` |
| **Debugger** | `prompts/debugger/analysis.md` | `prompts/debugger/translated.md` | `prompts/debugger/original.md` |
| **Code Reviewer** | - | - | `prompts/code-reviewer/original.md` |

---

## Academic Research Papers

### Foundational Papers

| Paper | Authors | Year | arXiv Link | Description |
|-------|---------|------|------------|-------------|
| **Chain-of-Thought Prompting Elicits Reasoning in Large Language Models** | Wei et al. | 2022 | [arXiv:2201.11903](https://arxiv.org/abs/2201.11903) | Introduced CoT prompting, showing that step-by-step reasoning dramatically improves LLM performance on complex tasks |
| **Large Language Models are Zero-Shot Reasoners** | Kojima et al. | 2022 | [arXiv:2205.11916](https://arxiv.org/abs/2205.11916) | Demonstrated that simple phrases like "Let's think step by step" can trigger reasoning without examples |
| **ReAct: Synergizing Reasoning and Acting in Language Models** | Yao et al. | 2022 | [arXiv:2210.03629](https://arxiv.org/abs/2210.03629) | Combined reasoning and action in an iterative loop, enabling agents to use tools and external knowledge |
| **Tree of Thoughts: Deliberate Problem Solving with Large Language Models** | Yao et al. | 2023 | [arXiv:2305.10601](https://arxiv.org/abs/2305.10601) | Extended CoT to tree-structured reasoning with backtracking and exploration |
| **Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks** | Lewis et al. | 2021 | [arXiv:2005.11401](https://arxiv.org/pdf/2005.11401.pdf) | Introduced RAG, combining retrieval with generation for more accurate, up-to-date responses |
| **Self-Consistency Improves Chain of Thought Reasoning in Language Models** | Wang et al. | 2022 | [arXiv:2203.11171](https://arxiv.org/abs/2203.11171) | Showed that voting across multiple reasoning paths improves accuracy |
| **Reflexion: Self-Reflective Agents** | Shinn et al. | 2023 | [arXiv:2303.11366](https://arxiv.org/abs/2303.11366) | Introduced self-critique and iterative improvement for agent performance |
| **Rethinking the Role of Demonstrations: What Makes In-Context Learning Work?** | Min et al. | 2022 | [arXiv:2202.12837](https://arxiv.org/abs/2202.12837) | Analyzed Few-Shot prompting, finding that format matters more than label accuracy |
| **Meta Prompting: A New Approach to Task Abstraction** | Zhang et al. | 2024 | - | Theoretical foundation for Meta Prompting techniques |

### Security Research

| Paper | Authors | Year | Link | Description |
|-------|---------|------|------|-------------|
| **Not What You've Signed Up For: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection** | Greshake et al. | 2023 | [arXiv](https://arxiv.org/abs/2302.12173) | Demonstrated indirect prompt injection attacks through external data sources |
| **Prompt Injection Attack Against LLM-Integrated Applications** | Perez & Ribeiro | 2022 | [arXiv](https://arxiv.org/abs/2306.05499) | Systematic analysis of prompt injection vulnerabilities |
| **Defending Against Instruction-Based Attacks** | - | 2023 | - | Defense strategies against instruction override attacks |
| **Jailbroken: How Does LLM Safety Training Fail?** | Wei et al. | 2023 | [arXiv](https://arxiv.org/abs/2307.02483) | Analysis of jailbreak techniques and safety training limitations |

### Agent Systems Research

| Paper | Authors | Year | Link | Description |
|-------|---------|------|------|-------------|
| **Generative Agents: Interactive Simulacra of Human Behavior** | Park et al. | 2023 | [arXiv](https://arxiv.org/abs/2304.03442) | Simulated human behavior with memory, reflection, and planning |
| **CAMEL: Communicative Agents for "Mind" Exploration of Large Scale Language Model Society** | Li et al. | 2023 | [arXiv](https://arxiv.org/abs/2303.17760) | Multi-agent collaboration framework |
| **AutoGPT: An Autonomous GPT-4 Experiment** | - | 2023 | [GitHub](https://github.com/Significant-Gravitas/AutoGPT) | Popularized autonomous agent systems |
| **BabyAGI** | Nakajima | 2023 | [GitHub](https://github.com/yoheinakajima/babyagi) | Task-driven autonomous agent with OpenAI API |

---

## Open Source Projects

### Agent Frameworks

| Project | Link | Description | Language |
|---------|------|-------------|----------|
| **AutoGPT** | [GitHub](https://github.com/Significant-Gravitas/AutoGPT) | Autonomous GPT-4 agent that can pursue goals independently | Python |
| **CrewAI** | [GitHub](https://github.com/crewAIInc/crewAI) | Framework for orchestrating role-playing, autonomous AI agents | Python |
| **Claude Code** | [GitHub](https://github.com/anthropics/claude-code) | Anthropic's official CLI tool for Claude with sophisticated prompting | TypeScript |
| **oh-my-codex** | [GitHub](https://github.com/Yeachan-Heo/oh-my-codex) | Multi-agent orchestration layer for OpenAI Codex CLI | TypeScript |
| **oh-my-openagent** | Internal | Plugin system for OpenCode with 11 built-in agents and dynamic prompt assembly | TypeScript |
| **OpenClaw** | [GitHub](https://github.com/openclaw/openclaw) | Customizable AI coding assistant with modular prompt system | TypeScript |
| **AutoGen** | [GitHub](https://github.com/microsoft/autogen) | Microsoft's multi-agent conversation framework | Python |
| **LangChain** | [GitHub](https://github.com/langchain-ai/langchain) | Framework for building applications with LLMs through composability | Python/TypeScript |
| **LlamaIndex** | [GitHub](https://github.com/run-llama/llama_index) | Data framework for LLM applications with RAG capabilities | Python |

### Security Tools

| Project | Link | Description | Language |
|---------|------|-------------|----------|
| **LLM Guard** | [GitHub](https://github.com/protectai/llm-guard) | Security toolkit for LLM interactions with input/output scanners | Python |
| **NeMo Guardrails** | [GitHub](https://github.com/NVIDIA/NeMo-Guardrails) | NVIDIA's toolkit for adding programmable guardrails to LLM-based conversational systems | Python |
| **Rebuff** | [GitHub](https://github.com/protectai/rebuff) | Prompt injection detection framework | Python |
| **Promptmap** | [GitHub](https://github.com/utkusen/promptmap) | Automated prompt injection testing tool | Python |

### Prompt Management

| Project | Link | Description | Language |
|---------|------|-------------|----------|
| **Promptflow** | [GitHub](https://github.com/microsoft/promptflow) | Microsoft's tool for streamlining LLM-based AI development | Python |
| **Pezzo** | [GitHub](https://github.com/pezzolabs/pezzo) | Open-source LLM operations platform with prompt management | TypeScript |
| **Langfuse** | [GitHub](https://github.com/langfuse/langfuse) | Open-source LLM engineering platform with observability | TypeScript |

---

## Security Resources

### Security Frameworks

| Resource | Link | Description |
|----------|------|-------------|
| **OWASP Top 10 for LLM Applications** | [Website](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | Comprehensive security framework for LLM applications |
| **OWASP ASI 2026** | [Website](https://www.trydeepteam.com/docs/frameworks-owasp-top-10-for-agentic-applications) | Extended framework for Agentic AI systems |
| **redteams.ai Prompt Hardening** | [Website](https://redteams.ai/topics/defense-mitigation/prompt-hardening-patterns) | Collection of prompt hardening patterns |
| **AI Incident Database** | [Website](https://incidentdatabase.ai/) | Database of AI-related security incidents |

### Security Guidelines

| Resource | Description |
|----------|-------------|
| **NIST AI Risk Management Framework** | US National Institute of Standards and Technology framework for AI risk management |
| **ISO/IEC 23053:2022** | Framework for AI systems using ML |
| **MITRE ATLAS** | Adversarial Threat Landscape for Artificial-Intelligence Systems |

### Security Communities

| Community | Link | Description |
|-----------|------|-------------|
| **OWASP LLM Security** | [Website](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | Open Web Application Security Project LLM working group |
| **AI Village** | [Website](https://aivillage.org/) | DEF CON community for AI security research |
| **MLSecOps** | [Website](https://mlsecops.org/) | Community for ML security operations |

---

## Glossary (EN-ZH)

### Core Concepts

| English | Chinese | Definition |
|---------|---------|------------|
| **Prompt** | 提示词 | The input text provided to a language model to elicit a desired response |
| **Prompt Engineering** | 提示工程 | The practice of designing and optimizing prompts to improve LLM performance |
| **Zero-Shot Prompting** | 零样本提示 | Providing instructions without examples, relying on the model's pre-trained knowledge |
| **Few-Shot Prompting** | 少样本提示 | Providing a few examples in the prompt to guide the model's behavior |
| **Meta Prompting** | 元提示 | Focusing on task structure and syntax rather than specific content |
| **Chain-of-Thought (CoT)** | 思维链 | Guiding the model to generate intermediate reasoning steps before the final answer |
| **Tree of Thoughts (ToT)** | 思维树 | Exploring multiple reasoning paths in a tree structure with backtracking |
| **Self-Consistency** | 自一致性 | Generating multiple answers and selecting the most frequent one |
| **Reflexion** | 自我反思 | Self-critique and iterative improvement of model outputs |

### Agent Systems

| English | Chinese | Definition |
|---------|---------|------------|
| **Agent** | 智能体 | An AI system that can perceive its environment and take actions to achieve goals |
| **ReAct** | 推理+行动 | Framework combining reasoning and action in an iterative loop |
| **Multi-Agent System** | 多智能体系统 | System with multiple AI agents collaborating to solve complex tasks |
| **Leader-Worker Pattern** | 领导者-工作者模式 | Hierarchical collaboration where Leaders coordinate and Workers execute |
| **Sub-Agent** | 子智能体 | Specialized agent spawned by a parent agent for specific tasks |
| **Orchestration** | 编排 | Coordinating multiple agents or components to work together |
| **Tool Use** | 工具使用 | Agent's ability to call external tools or APIs |
| **RAG (Retrieval Augmented Generation)** | 检索增强生成 | Combining retrieval from external knowledge with text generation |

### Context Engineering

| English | Chinese | Definition |
|---------|---------|------------|
| **Context Engineering** | 上下文工程 | Designing and optimizing the contextual information provided to AI agents |
| **System Prompt** | 系统提示词 | The foundational prompt that establishes agent identity and behavior |
| **Context Window** | 上下文窗口 | The maximum amount of text a model can process in a single request |
| **Token** | 令牌 | The basic unit of text processing in LLMs (roughly 0.75 words per token) |
| **Context Hierarchy** | 上下文层级 | Organized layers of context: System, Task, Tool, Memory |
| **Bootstrap Files** | 引导文件 | Configuration files automatically injected into context (AGENTS.md, SOUL.md, etc.) |
| **Dynamic Prompt Building** | 动态提示构建 | Assembling prompts at runtime based on context |

### Security

| English | Chinese | Definition |
|---------|---------|------------|
| **Prompt Injection** | 提示注入 | Attack that manipulates input to override or bypass system instructions |
| **Jailbreak** | 越狱 | Techniques to bypass model safety restrictions |
| **Direct Injection** | 直接注入 | Attack where malicious instructions are embedded directly in user input |
| **Indirect Injection** | 间接注入 | Attack through external data sources like web pages or documents |
| **Instruction Hierarchy** | 指令层级 | Defining priority levels for different instruction sources |
| **Canary Token** | 金丝雀令牌 | Unique embedded marker to detect prompt leaks |
| **Defense in Depth** | 纵深防御 | Multi-layered security strategy |
| **Input Sanitization** | 输入清理 | Filtering and cleaning user input to remove dangerous patterns |
| **Output Filtering** | 输出过滤 | Checking model responses for sensitive information leaks |

### Technical Terms

| English | Chinese | Definition |
|---------|---------|------------|
| **LLM (Large Language Model)** | 大语言模型 | AI model trained on vast text data to understand and generate human language |
| **Temperature** | 温度 | Parameter controlling randomness in model outputs (0 = deterministic, higher = more random) |
| **Hallucination** | 幻觉 | Model generating plausible-sounding but false or ungrounded information |
| **Embedding** | 嵌入 | Numerical representation of text in a high-dimensional vector space |
| **Vector Database** | 向量数据库 | Database optimized for storing and querying high-dimensional vectors |
| **Fine-tuning** | 微调 | Further training a pre-trained model on specific data |
| **Few-Shot Learning** | 少样本学习 | Learning from a small number of examples |
| **In-Context Learning** | 上下文学习 | Learning from examples provided within the prompt |
| **Structured Output** | 结构化输出 | Enforcing specific response formats like JSON or XML |
| **Prompt Chaining** | 提示链 | Breaking complex tasks into sequential subtasks |

### Framework-Specific

| English | Chinese | Definition |
|---------|---------|------------|
| **Skill** | 技能 | Modular, on-demand capability that can be loaded at runtime |
| **Pipeline** | 流水线 | Structured workflow with defined stages |
| **Five-Stage Pipeline** | 五阶段流水线 | Plan → PRD → Execute → Verify → Fix workflow |
| **Prompt Mode** | 提示模式 | Different context configurations (full, minimal, none) |
| **Truncation** | 截断 | Limiting context size by cutting off content |
| **Delegation** | 委派 | Assigning tasks to sub-agents |

---

## Changelog

### Version 1.0.0 (2025-04-14)

**Initial Release**

- Complete 13-chapter tutorial covering Prompt Engineering from basics to expert level
- Based on 2024-2025 research and production practices
- Includes all major techniques: Zero-Shot, Few-Shot, CoT, ToT, ReAct, RAG
- Comprehensive framework analysis: AutoGPT, CrewAI, Claude Code, oh-my-codex, oh-my-openagent, OpenClaw
- Security and defense chapter with OWASP LLM Top 10 coverage
- Production practices and case studies
- Template library and cheatsheet for quick reference

**Chapters Added:**
- Chapter 1: Introduction
- Chapter 2: Basic Prompting
- Chapter 3: Reasoning Enhancement
- Chapter 4: Agents & Tools
- Chapter 5: Context Engineering
- Chapter 6: Framework Analysis
- Chapter 7: Security & Defense
- Chapter 8: Production Practices
- Chapter 9: Advanced Topics
- Chapter 10: Case Studies
- Chapter 11: Template Library
- Chapter 12: Cheatsheet
- Chapter 13: Appendix (this document)

**Key Features:**
- Bilingual support (English and Chinese)
- Mermaid diagrams for visual explanations
- Production-ready code examples
- Academic paper references with arXiv links
- Comprehensive glossary
- Security best practices

---

## How to Contribute

This tutorial is a living document. To suggest improvements:

1. **Report Issues**: Found an error or outdated information? Please report it.
2. **Suggest Additions**: New papers, frameworks, or techniques to include?
3. **Improve Translations**: Help improve the Chinese translations.
4. **Share Examples**: Real-world case studies are always welcome.

---

## License

This tutorial is provided for educational purposes. Source code examples are provided under MIT license where applicable.

---

## Acknowledgments

This tutorial builds upon the work of countless researchers and open-source contributors:

- **Research Community**: Wei et al., Yao et al., Lewis et al., and many others
- **Open Source Projects**: AutoGPT, CrewAI, LangChain, and the broader AI community
- **Security Researchers**: OWASP LLM team, redteams.ai, and security practitioners
- **Framework Developers**: Anthropic, OpenAI, and independent developers

Special thanks to all who have shared their knowledge and made this field accessible.

---

*Last Updated: April 14, 2025*

*For the latest version, check the repository at `/home/yuexiaoliang/projects/docs/prompt-engineering-learning/`*
