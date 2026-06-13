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

| # | Title | Venue | Year | Tag | Paper | Code |
|---|-------|-------|------|-----|-------|------|
| 1 | **Large Language Model-Brained GUI Agents: A Survey** | arXiv | 2024 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2404.11213) | [GitHub](https://github.com/vyokky/LLM-Brained-GUI-Agents-Survey) |
| 2 | **A Survey on (M)LLM-Based GUI Agents** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2411.12399) | — |
| 3 | **LLM-Powered GUI Agents in Phone Automation: Surveying Progress and Prospects** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2504.19838) | — |
| 4 | **Large Model Agents: State-of-the-Art, Cooperation Paradigms, Security and Privacy, and Future Trends** | arXiv | 2024 | 📖 Reference | [Paper](https://arxiv.org/abs/2409.14457) | — |

---

## Benchmarks & Evaluation

> Standardized environments and datasets for evaluating GUI agents.

| # | Title | Venue | Year | Tag | Paper | Code |
|---|-------|-------|------|-----|-------|------|
| 5 | **OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments** | arXiv | 2024 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2404.07972) | [GitHub](https://github.com/xlang-ai/OSWorld) |
| 6 | **WebArena: A Realistic Web Environment for Building Autonomous Agents** | ICLR 2024 | 2023 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2307.13854) | [GitHub](https://github.com/webarena-dev/webarena) |
| 7 | **Mind2Web: Towards a Generalist Agent for the Web** | NeurIPS 2023 | 2023 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2306.06070) | [GitHub](https://github.com/OSU-NLP-Group/Mind2Web) |
| 8 | **GPT-4V(ision) is a Generalist Web Agent, if Grounded** | ICLR 2024 | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2401.01319) | [GitHub](https://github.com/OSU-NLP-Group/SeeAct) |
| 9 | **WorkArena: How Capable are Web Agents at Solving Common Knowledge Work Tasks?** | ICML 2024 | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2403.07718) | [GitHub](https://github.com/ServiceNow/WorkArena) |
| 10 | **WebChoreArena: Evaluating Web Browsing Agents on Realistic Tedious Web Tasks** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2506.01952) | — |
| 11 | **UI-Vision: A Desktop-centric GUI Benchmark for Visual Perception and Interaction** | ICML 2025 | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2503.15661) | — |
| 12 | **OSUniverse: Benchmark for Multimodal GUI-Navigation AI Agents** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2505.03570) | — |
| 13 | **SCUBA: Salesforce Computer Use Benchmark** | OpenReview | 2025 | 📈 Emerging | [OpenReview](https://openreview.net) | — |
| 14 | **WebLINX: Real-World Website Navigation with Multi-Turn Dialogue** | ICLR 2024 | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2402.05930) | [GitHub](https://github.com/McGill-NLP/weblinx) |
| 15 | **UIExplorer Benchmark: Toward Autonomous UI Exploration** | ICML 2025 Workshop | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2506.17779) | — |
| 16 | **AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents** | arXiv | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2405.14573) | [GitHub](https://github.com/google-research/android_world) |
| 17 | **BrowserGym: A Unified Environment for Web Agent Research** | arXiv | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2406.11716) | [GitHub](https://github.com/ServiceNow/BrowserGym) |

---

## GUI Grounding

> Techniques for localizing and interacting with UI elements from screenshots.

| # | Title | Venue | Year | Tag | Paper | Code |
|---|-------|-------|------|-----|-------|------|
| 18 | **SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents** | ACL 2024 | 2024 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2401.10935) | [GitHub](https://github.com/njucckevin/SeeClick) |
| 19 | **CogAgent: A Visual Language Model for GUI Agents** | CVPR 2024 (Highlight) | 2023 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2312.08914) | [GitHub](https://github.com/THUDM/CogAgent) |
| 20 | **Aguvis: Unified Pure Vision Agents for Autonomous GUI Interaction** | ICML 2025 | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2412.04454) | — |
| 21 | **UI-E21-Synth: Advancing GUI Grounding with Large-Scale Instruction Synthesis** | ACL 2025 Findings | 2025 | 📈 Emerging | [Paper](https://doi.org/10.18653/v1/2025.findings-acl.1152) | — |

---

## End-to-End GUI Agents

> Models that directly perceive screenshots and execute actions without intermediate structured representations.

| # | Title | Venue | Year | Tag | Paper | Code |
|---|-------|-------|------|-----|-------|------|
| 22 | **UI-TARS: Pioneering Automated GUI Interaction with Native Agents** | arXiv | 2025 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2501.12326) | — |
| 23 | **ShowUI: One Vision-Language-Action Model for Generalist GUI Agent** | OpenReview | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2411.17465) | [GitHub](https://github.com/showlab/ShowUI) |
| 24 | **Ferret-UI Lite: Lessons from Building Small On-Device GUI Agents** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2509.26539) | — |
| 25 | **TinyClick: Single-Turn Agent for Empowering GUI Automation** | arXiv | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2409.01396) | — |
| 26 | **ScreenLLM: Stateful Screen Schema for Efficient Action Understanding and Prediction** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2503.20978) | — |

---

## Planning & Reasoning

> Advanced reasoning, tree search, verification, and self-reflection mechanisms for GUI agents.

| # | Title | Venue | Year | Tag | Paper | Code |
|---|-------|-------|------|-----|-------|------|
| 27 | **Agent Alpha: Tree Search Unifying Generation, Exploration and Evaluation for Computer-Use Agents** | arXiv | 2026 | 📈 Emerging | [Paper](https://arxiv.org/abs/2602.02995) | — |
| 28 | **GUI-Reflection: Empowering Multimodal GUI Models with Self-Reflection Behavior** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2506.08012) | — |
| 29 | **V-Droid: Advancing Mobile GUI Agents: A Verifier-Driven Approach** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2503.15937) | — |
| 30 | **STEVE: A Step Verification Pipeline for Computer-use Agent Training** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2503.12532) | — |
| 31 | **OS-Kairos: Adaptive Interaction for MLLM-Powered GUI Agents** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2503.16465) | — |
| 32 | **DigiRL: Training In-The-Wild Device-Control Agents with Autonomous Reinforcement Learning** | NeurIPS 2024 | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2406.11896) | — |

---

## Multi-Agent Systems

> Architectures where multiple specialized agents collaborate on GUI tasks.

| # | Title | Venue | Year | Tag | Paper | Code |
|---|-------|-------|------|-----|-------|------|
| 33 | **UFO2: The Desktop AgentOS** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2504.14603) | [GitHub](https://github.com/microsoft/UFO) |
| 34 | **Agentic Lybic: Multi-Agent Execution System with Tiered Reasoning and Orchestration** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2509.11067) | — |
| 35 | **COLA: A Scalable Multi-Agent Framework For Windows UI Task Automation** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2503.09263) | — |
| 36 | **MGA: Memory-Driven GUI Agent for Observation-Centric Interaction** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2510.24168) | — |
| 37 | **CollabUIAgents: Advancing Language Multi-Agent Learning with Credit Re-Assignment** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2502.14496) | — |
| 38 | **Magentic-One: A Generalist Multi-Agent System for Solving Complex Tasks** | arXiv | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2411.04468) | — |

---

## Mobile GUI Agents

> Agents specialized for smartphone and tablet interfaces.

| # | Title | Venue | Year | Tag | Paper | Code |
|---|-------|-------|------|-----|-------|------|
| 39 | **AppAgent: Multimodal Agents as Smartphone Users** | arXiv | 2023 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2312.13771) | [GitHub](https://github.com/mnotgod96/AppAgent) |
| 40 | **AutoDroid: Task Automation in Real-World Android and Web Apps with LLM-based Agents** | arXiv | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2308.15272) | — |
| 41 | **Mobile-Agent: Multimodal Mobile Device Agent** | arXiv | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2401.16158) | [GitHub](https://github.com/X-PLUG/MobileAgent) |
| 42 | **Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration** | arXiv | 2024 | 📈 Emerging | [Paper](https://arxiv.org/abs/2406.01014) | [GitHub](https://github.com/X-PLUG/MobileAgent) |

---

## Data Generation & Training

> Methods for generating training data and novel training paradigms for GUI agents.

| # | Title | Venue | Year | Tag | Paper | Code |
|---|-------|-------|------|-----|-------|------|
| 43 | **GUIrilla: A Scalable Framework for Automated Desktop UI Exploration** | arXiv | 2025 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2510.16051) | — |
| 44 | **ScribeAgent: Towards Specialized Web Agents Using Production-Scale Workflow Data** | arXiv | 2024 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2411.15004) | — |

---

## Applications

> Domain-specific applications of GUI agents in industry and specialized tasks.

| # | Title | Venue | Year | Tag | Paper | Code |
|---|-------|-------|------|-----|-------|------|
| 45 | **InfraMind: A Novel Exploration-based GUI Agentic Framework for Mission-critical Industrial Management** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2509.13704) | — |
| 46 | **SmartAgent: Chain-of-User-Thought for Embodied Personalized Agent in Cyber World** | arXiv | 2024 | 📈 Emerging | [Paper](https://arxiv.org/abs/2412.07472) | — |
| 47 | **gem5 Co-Pilot: AI Assistant Agent for Architectural Design Space Exploration** | arXiv | 2025 | 📈 Emerging | [Paper](https://arxiv.org/abs/2510.19577) | — |

---

## Related Agent Foundations

> Foundational agent architectures and frameworks that influence GUI agent design.

| # | Title | Venue | Year | Tag | Paper | Code |
|---|-------|-------|------|-----|-------|------|
| 48 | **Voyager: An Open-Ended Embodied Agent with Large Language Models** | NeurIPS 2023 | 2023 | 🔥 Landmark | [Paper](https://arxiv.org/abs/2305.16291) | [GitHub](https://github.com/MineDojo/Voyager) |
| 49 | **AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation** | arXiv | 2023 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2308.08155) | [GitHub](https://github.com/microsoft/autogen) |
| 50 | **MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework** | ICLR 2024 | 2023 | ⭐ Recommended | [Paper](https://arxiv.org/abs/2308.00352) | [GitHub](https://github.com/geekan/MetaGPT) |
| 51 | **CAMEL: Communicative Agents for "Mind" Exploration of Large Language Model Society** | NeurIPS 2023 | 2023 | 📖 Reference | [Paper](https://arxiv.org/abs/2303.17760) | [GitHub](https://github.com/camel-ai/camel) |
| 52 | **Avenir-Web: Human-Experience-Imitating Multimodal Web Agents with Mixture of Grounding Experts** | arXiv | 2026 | 📈 Emerging | [Paper](https://arxiv.org/abs/2602.02468) | — |
| 53 | **Software Engineering Using Autonomous Agents: Are We There Yet?** | ASE 2023 | 2023 | 📖 Reference | [Paper](https://doi.org/10.1109/ASE56229.2023.00174) | — |
| 54 | **Claude Computer Use** | Technical Report | 2024 | ⭐ Recommended | [Blog](https://www.anthropic.com/news/3-5-sonnet-computer-use) | — |
| 55 | **OpenAI Operator** | Technical Report | 2025 | ⭐ Recommended | [Blog](https://openai.com/index/introducing-operator/) | — |

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
