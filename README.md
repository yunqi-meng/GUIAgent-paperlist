# Awesome GUI Agents

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Last Updated](https://img.shields.io/badge/last%20updated-June%202026-blue)](#)

A curated and rigorously verified collection of papers, benchmarks, datasets, models, and open-source projects for **GUI Agents**, **Computer Use Agents**, **Web Agents**, and **Multimodal Interface Automation**.

> Contributions are welcome! Please submit a PR with the paper title, venue, year, and links.

---

## Contents

- [Statistics](#statistics)
- [Surveys](#surveys)
- [Benchmarks & Evaluation](#benchmarks--evaluation)
- [GUI Grounding](#gui-grounding)
- [End-to-End GUI Agents](#end-to-end-gui-agents)
- [Planning & Reasoning](#planning--reasoning)
- [Multi-Agent Systems](#multi-agent-systems)
- [Mobile GUI Agents](#mobile-gui-agents)
- [Data Generation & Training](#data-generation--training)
- [Applications](#applications)
- [Related Agent Foundations](#related-agent-foundations)
- [Open-Source Projects](#open-source-projects)
- [GUI Agent Timeline](#gui-agent-timeline)
- [Research Trends (2025-2026)](#research-trends-2025-2026)
- [Reading Guide](#reading-guide)
- [Contributing](#contributing)

---

## Statistics

| Metric | Count |
|--------|-------|
| Total Papers | 55+ |
| Benchmarks | 12+ |
| Open-Source Projects | 15+ |
| Survey Papers | 4 |
| Last Updated | June 2026 |

---

## Surveys

> Systematic reviews and surveys covering the GUI Agent landscape.

| # | Title | Venue | Year | Tag | Paper | Code | 中文摘要 |
|---|-------|-------|------|-----|-------|------|----------|
| 1 | **Large Language Model-Brained GUI Agents: A Survey** | arXiv | 2024 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2404.11213) | [GitHub](https://github.com/vyokky/LLM-Brained-GUI-Agents-Survey) | 首篇全面综述LLM驱动GUI代理的论文，系统梳理了基于大语言模型的图形界面代理架构、感知、规划与执行技术，涵盖桌面、移动端和Web场景的自动化任务 |
| 2 | **A Survey on (M)LLM-Based GUI Agents** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2411.12399) | — | 综述多模态大语言模型在GUI代理中的应用，分析视觉感知、元素定位、动作生成等关键技术，讨论数据集、评估方法及未来发展方向 |
| 3 | **LLM-Powered GUI Agents in Phone Automation: Surveying Progress and Prospects** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2504.19838) | — | 聚焦手机自动化场景，系统回顾LLM驱动的GUI代理从脚本自动化到智能自适应系统的演进，涵盖单代理/多代理框架、提示工程与训练方法 |
| 4 | **Large Model Agents: State-of-the-Art, Cooperation Paradigms, Security and Privacy, and Future Trends** | arXiv | 2024 | 📖 Reference | [Paper](https://arxiv.org/abs/2409.14457) | — | 探讨大模型驱动的通用智能代理，研究多代理自主协作范式，分析数据、计算和知识层面的协作机制及安全隐私挑战 |

---

## Benchmarks & Evaluation

> Standardized environments and datasets for evaluating GUI agents.

| # | Title | Venue | Year | Tag | Paper | Code | 中文摘要 |
|---|-------|-------|------|-----|-------|------|----------|
| 5 | **OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments** | arXiv | 2024 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2404.07972) | [GitHub](https://github.com/xlang-ai/OSWorld) | 首个真实操作系统环境基准，支持Ubuntu/Windows/macOS，包含369个跨应用任务，评估发现最强模型仅12.24%成功率，远低于人类72.36% |
| 6 | **WebArena: A Realistic Web Environment for Building Autonomous Agents** | ICLR 2024 | 2023 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2307.13854) | [GitHub](https://github.com/webarena-dev/webarena) | 构建包含电商、论坛、代码协作、内容管理四大领域的真实Web环境，提供工具和知识库，GPT-4代理端到端成功率仅14.41%，人类达78.24% |
| 7 | **Mind2Web: Towards a Generalist Agent for the Web** | NeurIPS 2023 | 2023 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2306.06070) | [GitHub](https://github.com/OSU-NLP-Group/Mind2Web) | 首个通用Web代理数据集，涵盖137个网站、31个领域、2000+开放任务，支持多样化用户交互模式，探索LLM构建通用Web代理的可行性 |
| 8 | **GPT-4V(ision) is a Generalist Web Agent, if Grounded** | ICLR 2024 | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2401.01319) | [GitHub](https://github.com/OSU-NLP-Group/SeeAct) | 证明GPT-4V具备通用Web代理潜力，提出SeeAct框架通过视觉定位实现网页操作，在真实网站上展示强大泛化能力 |
| 9 | **WorkArena: How Capable are Web Agents at Solving Common Knowledge Work Tasks?** | ICML 2024 | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2403.07718) | [GitHub](https://github.com/ServiceNow/WorkArena) | 基于ServiceNow平台构建企业知识工作任务基准，评估Web代理在真实企业场景中的能力，揭示当前模型与实际需求的差距 |
| 10 | **WebChoreArena: Evaluating Web Browsing Agents on Realistic Tedious Web Tasks** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2506.01952) | — | 评估Web浏览代理处理繁琐重复任务的能力，测试多步骤、低认知负荷的真实网页操作场景 |
| 11 | **UI-Vision: A Desktop-centric GUI Benchmark for Visual Perception and Interaction** | ICML 2025 | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2503.15661) | — | 桌面GUI视觉感知与交互基准，评估代理对界面元素的识别、定位和操作能力 |
| 12 | **OSUniverse: Benchmark for Multimodal GUI-Navigation AI Agents** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2505.03570) | — | 多模态GUI导航AI代理基准，评估代理在操作系统环境中的导航和任务完成能力 |
| 13 | **SCUBA: Salesforce Computer Use Benchmark** | OpenReview | 2025 | 📈 Emerging | [OpenReview](https://openreview.net) | — | Salesforce推出的计算机使用基准，评估AI代理在企业级CRM和业务流程自动化中的表现 |
| 14 | **WebLINX: Real-World Website Navigation with Multi-Turn Dialogue** | ICLR 2024 | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2402.05930) | [GitHub](https://github.com/McGill-NLP/weblinx) | 基于多轮对话的真实网站导航数据集，支持复杂交互场景，评估代理理解用户意图和执行多步骤任务的能力 |
| 15 | **UIExplorer Benchmark: Toward Autonomous UI Exploration** | ICML 2025 Workshop | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2506.17779) | — | 评估GUI代理自主探索用户界面的能力，测试代理在未知环境中的学习和适应能力 |
| 16 | **AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents** | arXiv | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2405.14573) | [GitHub](https://github.com/google-research/android_world) | Google推出的动态Android环境基准，支持真实应用交互，评估移动代理在开放环境中的任务自动化能力 |
| 17 | **BrowserGym: A Unified Environment for Web Agent Research** | arXiv | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2406.11716) | [GitHub](https://github.com/ServiceNow/BrowserGym) | 统一的Web代理研究环境，整合多种评估基准，提供标准化接口支持不同Web代理的对比评估 |

---

## GUI Grounding

> Techniques for localizing and interacting with UI elements from screenshots.

| # | Title | Venue | Year | Tag | Paper | Code | 中文摘要 |
|---|-------|-------|------|-----|-------|------|----------|
| 18 | **SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents** | ACL 2024 | 2024 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2401.10935) | [GitHub](https://github.com/njucckevin/SeeClick) | 提出GUI定位预训练方法，通过ScreenSpot数据集训练视觉代理精准定位界面元素，在多个GUI操作基准上取得领先性能 |
| 19 | **CogAgent: A Visual Language Model for GUI Agents** | CVPR 2024 (Highlight) | 2023 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2312.08914) | [GitHub](https://github.com/THUDM/CogAgent) | 180亿参数视觉语言模型，专门针对GUI理解优化，支持高分辨率屏幕输入，在PC和移动端GUI操作任务上表现优异 |
| 20 | **Aguvis: Unified Pure Vision Agents for Autonomous GUI Interaction** | ICML 2025 | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2412.04454) | — | 首个完全基于视觉的自主GUI交互代理，无需依赖文本表示，通过纯视觉感知实现跨平台GUI操作 |
| 21 | **UI-E21-Synth: Advancing GUI Grounding with Large-Scale Instruction Synthesis** | ACL 2025 Findings | 2025 | 📈 Emerging | [Paper](https://doi.org/10.18653/v1/2025.findings-acl.1152) | — | 通过GPT-4o大规模合成GUI指令数据，提升视觉代理的界面元素定位能力，降低人工标注成本 |

---

## End-to-End GUI Agents

> Models that directly perceive screenshots and execute actions without intermediate structured representations.

| # | Title | Venue | Year | Tag | Paper | Code | 中文摘要 |
|---|-------|-------|------|-----|-------|------|----------|
| 22 | **UI-TARS: Pioneering Automated GUI Interaction with Native Agents** | arXiv | 2025 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2501.12326) | — | 开创性的原生GUI代理，直接从截图感知并输出动作，无需中间结构化表示，在OSWorld和AndroidWorld上达到开源SOTA |
| 23 | **ShowUI: One Vision-Language-Action Model for Generalist GUI Agent** | OpenReview | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2411.17465) | [GitHub](https://github.com/showlab/ShowUI) | 42亿参数的视觉-语言-动作模型，统一处理GUI感知、理解和操作，支持跨平台通用GUI代理 |
| 24 | **Ferret-UI Lite: Lessons from Building Small On-Device GUI Agents** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2509.26539) | — | 30亿参数的轻量级端侧GUI代理，探索在移动设备上高效部署GUI自动化能力的实践经验 |
| 25 | **TinyClick: Single-Turn Agent for Empowering GUI Automation** | arXiv | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2409.01396) | — | 仅2.7亿参数的轻量GUI代理，通过单轮交互实现GUI自动化，训练仅需56 GPU小时 |
| 26 | **ScreenLLM: Stateful Screen Schema for Efficient Action Understanding and Prediction** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2503.20978) | — | 提出有状态屏幕模式表示方法，高效理解和预测用户界面动作，提升GUI代理的上下文感知能力 |

---

## Planning & Reasoning

> Advanced reasoning, tree search, verification, and self-reflection mechanisms for GUI agents.

| # | Title | Venue | Year | Tag | Paper | Code | 中文摘要 |
|---|-------|-------|------|-----|-------|------|----------|
| 27 | **Agent Alpha: Tree Search Unifying Generation, Exploration and Evaluation for Computer-Use Agents** | arXiv | 2026 | 📈 Emerging | [Paper](https://arxiv.org/abs/2602.02995) | — | 将蒙特卡洛树搜索(MCTS)应用于计算机使用代理，统一生成、探索和评估过程，显著提升复杂任务的规划能力 |
| 28 | **GUI-Reflection: Empowering Multimodal GUI Models with Self-Reflection Behavior** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2506.08012) | — | 赋予GUI模型自我反思能力，通过错误检测和纠正机制提升代理在复杂交互场景中的鲁棒性 |
| 29 | **V-Droid: Advancing Mobile GUI Agents: A Verifier-Driven Approach** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2503.15937) | — | 创新性地使用LLM作为验证器而非生成器，从候选动作中选择最优操作，在AndroidWorld上表现优异 |
| 30 | **STEVE: A Step Verification Pipeline for Computer-use Agent Training** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2503.12532) | — | 提出步骤级验证管道，利用GPT-4o验证每个操作步骤的正确性，提升代理训练质量 |
| 31 | **OS-Kairos: Adaptive Interaction for MLLM-Powered GUI Agents** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2503.16465) | — | 基于置信度的自适应交互机制，GUI代理根据不确定性动态调整交互策略，提升任务成功率 |
| 32 | **DigiRL: Training In-The-Wild Device-Control Agents with Autonomous Reinforcement Learning** | NeurIPS 2024 | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2406.11896) | — | 通过自主强化学习在真实环境中训练设备控制代理，无需人工演示数据，实现端到端策略优化 |

---

## Multi-Agent Systems

> Architectures where multiple specialized agents collaborate on GUI tasks.

| # | Title | Venue | Year | Tag | Paper | Code | 中文摘要 |
|---|-------|-------|------|-----|-------|------|----------|
| 33 | **UFO2: The Desktop AgentOS** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2504.14603) | [GitHub](https://github.com/microsoft/UFO) | 微软推出的桌面代理操作系统，采用HostAgent+AppAgent双层架构，支持跨应用任务协调和自动化执行 |
| 34 | **Agentic Lybic: Multi-Agent Execution System with Tiered Reasoning and Orchestration** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2509.11067) | — | 多代理执行系统，采用分层推理和编排机制，通过FSM驱动的代理协调实现复杂任务自动化 |
| 35 | **COLA: A Scalable Multi-Agent Framework For Windows UI Task Automation** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2503.09263) | — | 可扩展的Windows UI任务自动化框架，采用场景感知调度器和决策代理池，支持多代理协作 |
| 36 | **MGA: Memory-Driven GUI Agent for Observation-Centric Interaction** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2510.24168) | — | 基于记忆驱动的GUI代理，采用以观察为中心的交互模式，通过历史信息增强代理的上下文理解 |
| 37 | **CollabUIAgents: Advancing Language Multi-Agent Learning with Credit Re-Assignment** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2502.14496) | — | 通过信用重分配机制推进语言多代理学习，优化GUI代理协作中的奖励分配和策略更新 |
| 38 | **Magentic-One: A Generalist Multi-Agent System for Solving Complex Tasks** | arXiv | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2411.04468) | — | 通用多代理系统，通过专业化代理协作解决复杂任务，支持Web浏览、文件操作等多种场景 |

---

## Mobile GUI Agents

> Agents specialized for smartphone and tablet interfaces.

| # | Title | Venue | Year | Tag | Paper | Code | 中文摘要 |
|---|-------|-------|------|-----|-------|------|----------|
| 39 | **AppAgent: Multimodal Agents as Smartphone Users** | arXiv | 2023 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2312.13771) | [GitHub](https://github.com/mnotgod96/AppAgent) | 多模态智能手机代理，通过学习人类操作模式实现应用自动化，支持自主探索和任务执行 |
| 40 | **AutoDroid: Task Automation in Real-World Android and Web Apps with LLM-based Agents** | arXiv | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2308.15272) | — | 基于LLM的Android和Web应用任务自动化，结合应用知识和用户指令实现智能操作 |
| 41 | **Mobile-Agent: Multimodal Mobile Device Agent** | arXiv | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2401.16158) | [GitHub](https://github.com/X-PLUG/MobileAgent) | 多模态移动设备代理，通过视觉感知和语言理解实现跨应用操作，支持复杂任务规划 |
| 42 | **Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration** | arXiv | 2024 | 📈 Emerging | [Paper](https://arxiv.org/abs/2406.01014) | [GitHub](https://github.com/X-PLUG/MobileAgent) | 多代理协作的移动设备操作助手，通过有效导航机制提升复杂任务的执行效率 |

---

## Data Generation & Training

> Methods for generating training data and novel training paradigms for GUI agents.

| # | Title | Venue | Year | Tag | Paper | Code | 中文摘要 |
|---|-------|-------|------|-----|-------|------|----------|
| 43 | **GUIrilla: A Scalable Framework for Automated Desktop UI Exploration** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2510.16051) | — | 可扩展的桌面UI自动探索框架，在macOS上自动生成27K任务覆盖1.1K应用，大幅降低GUI训练数据采集成本 |
| 44 | **ScribeAgent: Towards Specialized Web Agents Using Production-Scale Workflow Data** | arXiv | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2411.15004) | — | 利用生产级工作流数据训练专业化Web代理，通过大规模真实操作日志提升代理的任务执行能力 |

---

## Applications

> Domain-specific applications of GUI agents in industry and specialized tasks.

| # | Title | Venue | Year | Tag | Paper | Code | 中文摘要 |
|---|-------|-------|------|-----|-------|------|----------|
| 45 | **InfraMind: A Novel Exploration-based GUI Agentic Framework for Mission-critical Industrial Management** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2509.13704) | — | 基于探索的GUI代理框架，专为关键工业管理任务设计，支持复杂工业系统的自动化运维 |
| 46 | **SmartAgent: Chain-of-User-Thought for Embodied Personalized Agent in Cyber World** | arXiv | 2024 | 📈 Emerging | [Paper](https://arxiv.org/abs/2412.07472) | — | 提出用户思维链方法，构建具身个性化代理，支持网络世界中的个性化任务执行 |
| 47 | **gem5 Co-Pilot: AI Assistant Agent for Architectural Design Space Exploration** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2510.19577) | — | 面向处理器架构设计空间探索的AI助手代理，辅助工程师进行架构决策和性能优化 |

---

## Related Agent Foundations

> Foundational agent architectures and frameworks that influence GUI agent design.

| # | Title | Venue | Year | Tag | Paper | Code | 中文摘要 |
|---|-------|-------|------|-----|-------|------|----------|
| 48 | **Voyager: An Open-Ended Embodied Agent with Large Language Models** | NeurIPS 2023 | 2023 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2305.16291) | [GitHub](https://github.com/MineDojo/Voyager) | 首个基于LLM的开放式具身代理，在Minecraft中通过自动课程、技能库和代码生成实现持续学习和探索 |
| 49 | **AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation** | arXiv | 2023 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2308.08155) | [GitHub](https://github.com/microsoft/autogen) | 微软推出的多代理对话框架，支持可定制的代理协作模式，简化下一代LLM应用开发 |
| 50 | **MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework** | ICLR 2024 | 2023 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2308.00352) | [GitHub](https://github.com/geekan/MetaGPT) | 元编程多代理协作框架，将人类软件开发流程编码为代理工作流，支持从需求到代码的自动化 |
| 51 | **CAMEL: Communicative Agents for "Mind" Exploration of Large Language Model Society** | NeurIPS 2023 | 2023 | 📖 Reference | [Paper](https://arxiv.org/abs/2303.17760) | [GitHub](https://github.com/camel-ai/camel) | 通信式代理框架，通过角色扮演实现LLM社会的"思维"探索，支持多代理自主协作 |
| 52 | **Avenir-Web: Human-Experience-Imitating Multimodal Web Agents with Mixture of Grounding Experts** | arXiv | 2026 | 📈 Emerging | [Paper](https://arxiv.org/abs/2602.02468) | — | 模仿人类体验的多模态Web代理，采用定位专家混合机制，提升网页理解和操作的准确性 |
| 53 | **Software Engineering Using Autonomous Agents: Are We There Yet?** | ASE 2023 | 2023 | 📖 Reference | [Paper](https://doi.org/10.1109/ASE56229.2023.00174) | — | 探讨自主代理在软件工程中的应用现状与前景，分析自动化开发的技术挑战和未来方向 |
| 54 | **Claude Computer Use** | Technical Report | 2024 | ⭐ Recommended | [Blog](https://www.anthropic.com/news/3-5-sonnet-computer-use) | — | Anthropic推出的计算机使用能力，使Claude能够直接操作桌面应用，实现GUI自动化任务 |
| 55 | **OpenAI Operator** | Technical Report | 2025 | ⭐ Recommended | [Blog](https://openai.com/index/introducing-operator/) | — | OpenAI推出的Operator代理，通过浏览器自动化执行Web任务，支持订餐、购物等日常操作 |

---

## Open-Source Projects

| Project | Description | Link |
|---------|-------------|------|
| **OSWorld** | Real computer environment benchmark for multimodal agents | [GitHub](https://github.com/xlang-ai/OSWorld) |
| **WebArena** | Realistic web environment for autonomous agent evaluation | [GitHub](https://github.com/webarena-dev/webarena) |
| **Mind2Web** | Generalist web agent dataset | [GitHub](https://github.com/OSU-NLP-Group/Mind2Web) |
| **SeeClick** | Visual GUI agent with grounding pre-training | [GitHub](https://github.com/njucckevin/SeeClick) |
| **CogAgent** | 18B visual language model for GUI understanding | [GitHub](https://github.com/THUDM/CogAgent) |
| **ShowUI** | Vision-Language-Action model for GUI agents | [GitHub](https://github.com/showlab/ShowUI) |
| **UFO** | Windows desktop AgentOS by Microsoft | [GitHub](https://github.com/microsoft/UFO) |
| **AutoGen** | Multi-agent conversation framework by Microsoft | [GitHub](https://github.com/microsoft/autogen) |
| **MetaGPT** | Multi-agent collaborative framework | [GitHub](https://github.com/geekan/MetaGPT) |
| **Voyager** | LLM-powered embodied agent in Minecraft | [GitHub](https://github.com/MineDojo/Voyager) |
| **MobileAgent** | Multimodal mobile device agent | [GitHub](https://github.com/X-PLUG/MobileAgent) |
| **AppAgent** | Multimodal smartphone agent | [GitHub](https://github.com/mnotgod96/AppAgent) |
| **BrowserGym** | Unified environment for web agent research | [GitHub](https://github.com/ServiceNow/BrowserGym) |
| **SeeAct** | Grounded web agent framework | [GitHub](https://github.com/OSU-NLP-Group/SeeAct) |
| **LLM-Brained-GUI-Agents-Survey** | Microsoft's curated paper list (continuously updated) | [GitHub](https://github.com/vyokky/LLM-Brained-GUI-Agents-Survey) |

---

## GUI Agent Timeline

```
2023
├── Voyager (May) — LLM-powered embodied agent in Minecraft
├── CAMEL (Mar) — Communicative agents framework
├── MetaGPT (Aug) — Multi-agent collaborative framework
├── AutoGen (Aug) — Multi-agent conversation framework
├── Mind2Web (Jun) — Generalist web agent dataset
├── WebArena (Jul) — Realistic web environment benchmark
├── CogAgent (Dec) — 18B visual language model for GUI
├── AppAgent (Dec) — Multimodal smartphone agent
└── SeeAct / GPT-4V as Web Agent (Dec) — Grounded web agent

2024
├── SeeClick (Jan) — GUI grounding pre-training + ScreenSpot
├── Mobile-Agent (Jan) — Multimodal mobile device agent
├── OSWorld (Apr) — Real computer environment benchmark
├── WebLINX (Feb) — Multi-turn dialogue web navigation
├── WorkArena (Mar) — Enterprise knowledge work tasks
├── DigiRL (Jun) — RL training for device control
├── Mobile-Agent-v2 (Jun) — Multi-agent mobile assistant
├── BrowserGym (Jun) — Unified web agent evaluation
├── ShowUI (Aug) — Vision-Language-Action model
├── TinyClick (Sep) — Lightweight 0.27B GUI agent
├── ScribeAgent (Sep) — Production-scale workflow data
├── Aguvis (Dec) — Unified pure vision GUI agent
├── Magentic-One (Nov) — Generalist multi-agent system
├── Claude Computer Use (Oct) — Anthropic's computer use
└── Ferret-UI Lite — On-device GUI agent

2025
├── UI-TARS (Jan) — End-to-end native GUI agent
├── GUI-Reflection — Self-reflection for GUI models
├── V-Droid — Verifier-driven mobile agent
├── UFO2 — Desktop AgentOS by Microsoft
├── Agentic Lybic — Multi-agent orchestration
├── UI-Vision — Desktop GUI benchmark
├── COLA — Multi-agent Windows automation
├── GUIrilla — Automated UI exploration at scale
├── MGA — Memory-driven GUI agent
├── CollabUIAgents — Multi-agent RL
├── STEVE — Step verification pipeline
├── OS-Kairos — Adaptive interaction
├── Avenir-Web — Web agent with grounding experts
└── OpenAI Operator (Jan) — Computer use by OpenAI

2026
└── Agent Alpha — MCTS-based computer-use agent
```

---

## Research Trends (2025-2026)

### Trend 1: Native End-to-End GUI Agents

Models that directly perceive screenshots and output actions without intermediate structured representations (HTML, accessibility trees).

**Representative Work:**
- UI-TARS — Pure screenshot input, strong performance on OSWorld and AndroidWorld
- ShowUI — Vision-Language-Action model with 4.2B parameters
- Aguvis — First fully autonomous vision-based GUI agent without closed-source models

### Trend 2: Tree Search & Advanced Planning

Moving beyond single-pass generation to deliberate search over action sequences.

**Representative Work:**
- Agent Alpha — MCTS tree search unifying generation, exploration, and evaluation
- GUI-Reflection — Self-reflection and error correction capabilities
- STEVE — Step-level verification pipeline

### Trend 3: Multi-Agent GUI Systems

Specialized agents collaborating on complex multi-application tasks.

**Representative Work:**
- UFO2 — HostAgent + AppAgent architecture for Windows
- Agentic Lybic — FSM-driven multi-agent orchestration
- COLA — Scene-aware scheduler with decision agent pool
- Magentic-One — Generalist multi-agent system

### Trend 4: Verification-Driven Agents

Using verifiers (rather than generators) to select optimal actions from candidates.

**Representative Work:**
- V-Droid — LLM as verifier, strong performance on AndroidWorld
- STEVE — GPT-4o verification of each step
- OS-Kairos — Confidence-driven adaptive interaction

### Trend 5: Lightweight & On-Device Models

Deploying GUI agents on edge devices with limited compute.

**Representative Work:**
- TinyClick — 0.27B parameters, 56 GPU hours training
- Ferret-UI Lite — 3B on-device GUI agent
- CogAgent — Optimized for high-resolution screen understanding

### Trend 6: Automated Data Generation

Scaling training data through autonomous UI exploration and synthetic generation.

**Representative Work:**
- GUIrilla — Automated macOS exploration, 27K tasks across 1.1K apps
- UI-E21-Synth — Large-scale instruction synthesis via GPT-4o
- DigiRL — Autonomous RL with in-the-wild data collection

---

## Reading Guide

### If You Have One Day (Top 10)

1. **Large Language Model-Brained GUI Agents: A Survey** — Domain overview
2. **SeeClick** — GUI grounding foundation
3. **OSWorld** — Desktop benchmark standard
4. **WebArena** — Web benchmark standard
5. **Mind2Web** — Web dataset standard
6. **UI-TARS** — Current open-source SOTA
7. **CogAgent** — High-resolution GUI understanding
8. **ShowUI** — VLA paradigm
9. **Agent Alpha** — Planning breakthrough
10. **UFO2** — System-level architecture

### By Research Direction

| Direction | Start With | Then Read |
|-----------|------------|-----------|
| GUI Grounding | SeeClick, CogAgent | Aguvis, UI-E21-Synth |
| End-to-End Models | UI-TARS, ShowUI | Ferret-UI Lite, TinyClick |
| Planning & Reasoning | Agent Alpha, GUI-Reflection | STEVE, OS-Kairos |
| Multi-Agent Systems | UFO2, Magentic-One | COLA, Agentic Lybic |
| Mobile Agents | V-Droid, AppAgent | Mobile-Agent, AutoDroid |
| Data & Training | GUIrilla, DigiRL | UI-E21-Synth, ScribeAgent |
| Benchmarks | OSWorld, WebArena | Mind2Web, WorkArena |

---

## Key Venues

| Venue | Relevance |
|-------|-----------|
| **NeurIPS / ICML / ICLR** | Core ML venues; benchmarks, agent architectures |
| **ACL / EMNLP / NAACL** | NLP venues; grounding, language understanding |
| **CVPR / ICCV / ECCV** | Vision venues; visual grounding, UI understanding |
| **CHI / UIST** | HCI venues; interaction design, usability |
| **AAAI / IJCAI** | AI venues; planning, reasoning |
| **ASE / FSE / ICSE** | SE venues; software agents, automation |

---

## Contributing

We welcome contributions! To add a paper:

1. Fork this repository
2. Add the paper to the appropriate category
3. Include: Title, Venue, Year, Tag, Paper link, Code link (if available)
4. Ensure the venue and year are verified against the official publication (check arXiv comments for conference acceptances)
5. Submit a Pull Request

**Tag Legend:**
- 🔥 **Landmark** — Foundational work that shaped the field
- ⭐ **Recommended** — High-impact, widely cited work
- 📈 **Emerging** — Recent work with promising results
- 📖 **Reference** — Useful background reading

**Verification Checklist:**
- [ ] Venue is the actual conference/journal (not just "arXiv" if accepted elsewhere)
- [ ] Year matches the publication year (not just arXiv upload date)
- [ ] Paper link points to the correct arXiv/DOI page
- [ ] Code link points to the official repository

---

## License

This project is licensed under the [MIT License](LICENSE).

---

> **Disclaimer:** This list is curated with care for accuracy. Venue information is verified against official sources (arXiv comments, conference proceedings) where possible. Papers linked via Google Scholar may require verification of the exact arXiv ID. If you find an error, please open an issue or submit a PR.
>
> **Last Updated:** June 2026
