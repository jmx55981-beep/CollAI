CollAI Project White Paper



**Version**: v2.0

**Date**: June 23, 2026



---



## Table of Contents



1. [Project Overview](#1-project-overview)

2. [Project Origin and Development](#2-project-origin-and-development)

3. [Problems and Market Opportunities](#3-problems-and-market-opportunities)

4. [Products and Technologies](#4-products-and-technologies)

5. [Competitive Analysis](#5-competitive-analysis)

6. [Current Progress](#6-current-progress)

7. [Technical Challenges and Improvement Directions](#7-technical-challenges-and-improvement-directions)

8. [Appendix: In-depth Technical Explanation](#8-appendix-in-depth-technical-explanation)



---



## 1. Project Overview



CollAI is an **AI agent infrastructure with autonomous cognitive architecture** — not just another wrapped AI programming tool, but an AI operating system with independent cognitive cycles, self-evolution capabilities, and long-term memory.



The core bottleneck facing the current AI industry is: **All AI products remain at the level of "conversational interaction" and lack true autonomy and continuous learning capabilities**. Cursor, Copilot, and Claude Code are essentially "super auto-completion" tools that start from scratch in each conversation, with no cognitive accumulation or self-evolution.



CollAI fundamentally solves this problem. Core differences:



| Dimension | Cursor/Copilot/Claude Code | CollAI |

|-----------|----------------------------|--------|

| **Interaction Mode** | Passive response (one question, one answer) | **Autonomous cognitive cycle** with continuous thinking |

| **Memory** | Context window (limited) | **3-layer memory architecture** (169,788 persistent memories) |

| **Learning** | No learning capability | **Autonomous knowledge acquisition** + multi-stage learning pipeline |

| **Evolution** | No evolution capability | **Self-code modification** + genetic algorithm-based evolution |

| **Cognitive Architecture** | None | **7-stage cognitive cycle + simulation of 9 neurotransmitters** |

| **Deployment** | Cloud/SaaS | **Local-first**, with optional privatized deployment |



CollAI is not just another AI IDE plugin — it is an OS-layer infrastructure for the "era of autonomous AI agents".



---



## 2. Project Origin and Development



### 2.1 Origin



CollAI originated in early 2025 as a local-first AI programming assistant. However, during development, with the gradual construction of cognitive architecture, memory systems, and self-evolution capabilities, the project transcended the scope of a "programming assistant" and evolved into an AI infrastructure project with autonomous cognitive capabilities.



Current CollAI features:

- **1 complete cognitive architecture** — 7-stage cognitive cycle + consciousness model + motivation engine

- **1 long-term memory system** — 3-layer memory architecture with 169,788 persistent memories

- **1 self-evolution engine** — capable of self-modifying code and self-optimization

- **1 distributed entity system** — Prime Brain → Avatar, supporting splitting and collaboration

- **1 sandbox civilization simulator** — a simulation environment for AI autonomous training

- **1 quantitative trading system** — connected to A-share market with live trading capabilities

- **1 complete development frontend** — React + TypeScript with 50+ functional panels



### 2.2 Project Status



| Metric | Data |

|--------|------|

| Code Scale | ~3,400 Python files + ~200 TypeScript files |

| API Endpoints | ~600+ |

| Test Cases | 5,381 |

| Memory Repository | 169,788 entries |

| Evolution Cycles | 5,059 |

| Tool Calls | 5,189 |

| Runtime Duration | 18+ months of continuous operation |

| Development Team | 1 person (full-time) |



### 2.3 Core Design Philosophy



CollAI is built around several core principles:



**Local-first** — All cognitive processing is completed locally, independent of cloud services. This not only addresses enterprise data security and compliance issues but also is a prerequisite for AI autonomy — an AI that must report to the cloud is not truly autonomous.



**Cognitive Architecture > Model Capability** — CollAI does not pursue the strongest LLM; instead, it leverages cognitive architecture (memory, cycles, learning, evolution) to enable weaker models to outperform single-inference capabilities during continuous operation. The depth of architecture is more important than model parameters.



**Continuous Operation > Single Conversation** — Traditional AI tools are "use-and-leave", while CollAI is a continuously running process. This continuity enables accumulation — memory, learning, and evolution all require a time dimension.



---



## 3. Problems and Market Opportunities



### 3.1 Core Problem: AI Tools Lack a True "Cognitive Layer"



There are over 50 AI programming assistants on the market, all sharing a fatal flaw: **no memory, no learning, no autonomy**.



| Problem | Manifestation | Consequence |

|---------|---------------|-------------|

| **No Persistent Memory** | Starts from scratch in each conversation | Repeated context explanations, low efficiency |

| **No Autonomous Cycle** | Only responds to user queries | Unable to proactively identify and solve problems |

| **No Learning Capability** | Repeats past mistakes | Zero progress and accumulation |

| **No Evolution Capability** | Code cannot self-optimize | High manual maintenance costs, lack of sustainability |

| **Cloud Dependence** | Code must be uploaded to third-party servers | Enterprises hesitate to adopt (data security risks) |



### 3.2 Market Timing



Three trends converge here:



**Trend 1: Explosive Growth of AI Programming Tools**

- GitHub Copilot has over 3 million paid users

- Cursor's valuation exceeds RMB 20 billion

- Microsoft/Google/Amazon are heavily investing in AI programming

- China's AI programming market is shifting from "availability" to "quality"



**Trend 2: Paradigm Shift from "Auto-completion" to "Autonomous Agents"**

- Devin (Cognition AI) proves the feasibility of "AI engineers"

- Anthropic's computer use demonstrates AI's ability to operate computers

- The market is realizing: **The next leap is not better auto-completion, but autonomous agents**



**Trend 3: Localization/Privatization Demand in the Chinese Market**

- Compliance requirements for Chinese enterprise data to remain within borders

- Localized AI needs of state-owned enterprises and military units

- Cursor/Copilot have almost zero team support in China



---



## 4. Products and Technologies



### 4.1 Product Positioning



> **CollAI is an AI agent engine with autonomous cognitive capabilities** — it does not just answer questions, but thinks, learns, remembers, and evolves continuously like human developers.



### 4.2 Core Technology Stack



```

┌─────────────────────────────────────────────────┐

│                   Frontend (Electron)            │

│     React + TypeScript + Monaco Editor + 50 Panels│

├─────────────────────────────────────────────────┤

│               API Layer (~600 Endpoints)         │

├─────────┬─────────┬──────────┬──────────────────┤

│ Provider│ Tools   │ ReAct    │ Self-Evolution   │

│ Layer   │ System  │ Agent    │ Engine           │

│ (5 LLMs)│(55 Tools)│(1,097 LOC)│ (Self-modifying Code)│

├─────────┴─────────┴──────────┴──────────────────┤

│              Cognitive Architecture (Core Moat)  │

│  7-stage cognitive cycle + 9 neurotransmitters + 3-layer memory │

│  Consciousness model + motivation engine + autonomous engine    │

├─────────────────────────────────────────────────┤

│              Data Layer (~25 SQLite DBs)         │

│    169,788 memory entries | 5,189 tool call records │

├─────────────────────────────────────────────────┤

│              Quantitative Trading System         │

│    Tonghuashun automation + limit-up strategy + risk control │

└─────────────────────────────────────────────────┘

```



### 4.3 Core Moats



**Moat 1: Autonomous Cognitive Cycle**



This is not a "prompt engineering" trick. CollAI implements a complete cognitive cycle:



```

RECALL → THINK → PLAN → EXECUTE → ANALYZE → REFLECT → LEARN

```



Each stage is an independent asynchronous module with state passed via CycleContext. It includes:

- **DriveMechanism**: Adaptive exploration/exploitation balance based on uncertainty-driven + goal-driven behavior

- **Simulation of 9 neurotransmitters**: Dynamic regulation of cognitive behavior via dopamine/serotonin/cortisol etc.

- **Consciousness Model**: 7 levels of consciousness (NONE→INTEGRATED), 6-dimensional Bayesian self-cognition update



**This is not a wrapper — it is a cognitive architecture built from scratch.**



**Moat 2: Long-term Memory System**



```

Working Memory (12,848) → Short-term Memory (156,110) → Long-term Memory (830)

```



3-layer memory architecture based on SQLite+FTS5+SentenceTransformer:

- 90-day half-life exponential decay forgetting curve

- Dual retrieval via FTS5 full-text search + vector embedding

- Automatic memory consolidation (working→short-term→long-term)

- 169,788 entries of real operational data across 18 months



**Moat 3: Self-Evolution Capability**



CollAI can modify its own code:

- Complete cycle: introspect→analyze gaps→plan→execute→learn→reflect→test→document

- Triple safeguards: AST validation + sandbox testing + snapshot rollback

- Operational data from 5,059 evolution cycles



**Moat 4: 5-Level Provider Fallback Chain**



```

Primary Model → Backup Model → Arbitrary Enabled Provider → Memory Cache → Service Degradation Allowed

```



Independent of single LLM, with true elastic inference capabilities.



### 4.4 Capabilities Unavailable in Competitors



| Capability | Technical Barrier | Competitor Status |

|------------|-------------------|-------------------|

| Cross-session Persistent Memory | Memory consolidation algorithm + forgetting curve | None in Cursor/Copilot |

| Autonomous Cognitive Cycle | 7-stage orchestration + state transfer | Preliminary implementation in Devin only |

| Self-code Modification | AST validation + sandbox + rollback | No competitor implementation |

| Multi-Provider Elasticity | 8-level fallback chain + automatic routing | Only CollAI |

| Local-first Deployment | Full cloud independence | Cursor is cloud-dependent |

| Neurotransmitter Regulation | Dynamic simulation of 9 types | Pure academic concept, no productization |



### 4.5 Technical Debt



| Problem | Severity | Fix Cost |

|---------|----------|----------|

| baby_cognitive_service.py (8,788 LOC single file) | Critical | 2 months of refactoring |

| 253 route files mostly unreviewed manually | Critical | 3 months of audit |

| Inconsistent API paths (awakening/awakening2) | Medium | 2 weeks of unification |

| Plaintext passwords (broker_client.py) | Security | 1 day of fix |

| Numerous empty database tables and panels | Medium | Continuous cleanup |

| Coverage threshold only 30% | Medium | Long-term improvement |

| 44 subdirectories with no test coverage | Medium | 2 months of supplementation |



---



## 5. Competitive Analysis



### 5.1 Competitor Matrix



| Competitor | Core Capabilities | CollAI Differentiation |

|------------|-------------------|------------------------|

| **Cursor** | AI IDE + auto-completion | No autonomous cycle, no memory, no localization |

| **GitHub Copilot** | Auto-completion | Purely auxiliary, no autonomy |

| **Windsurf** | AI Editor | Similar to Cursor, no memory |

| **Devin** | AI Software Engineer | Cloud-only, no localization, no self-evolution |

| **Claude Code** | AI Terminal Agent | No persistent memory, no autonomous cycle |

| **Bolt.new** | Natural Language → Application | Generation-only, no maintenance |

| **Tongyi Lingma** | Alibaba-backed AI Programming | Cloud-dependent, no cognitive cycle |



### 5.2 Window of Advantage for CollAI



CollAI has a 12-18 month technical window:

- The architecture of Cursor/Copilot makes it impossible to quickly add "persistent memory" and "autonomous cycle" — this is an architectural difference, not a functional one

- Devin focuses on cloud services and cannot meet the privatization needs of Chinese enterprises

- Claude Code is a demo product of Anthropic, not a core business



### 5.3 Competitive Risks


- If OpenAI/Anthropic/Microsoft decide to build localized autonomous agents, CollAI's resources cannot compete

- If Cursor acquires or builds its own cognitive architecture, it can directly leverage its user base

- Chinese competitors (Tongyi Lingma etc.) have ecological resources from Alibaba/Baidu



---



## 6. Current Progress



### 6.1 Technologies Completed


- [x] Autonomous cognitive cycle (full implementation of 7 stages + real operational data)

- [x] 3-layer long-term memory system (169,788 entries + FTS5 + vector retrieval)

- [x] Self-evolution engine (5,059 evolution cycles)

- [x] 5 LLM Provider elastic routing (8-level fallback chain)

- [x] 55+ tool system (12 categories)

- [x] 60+ API route modules (600+ endpoints)

- [x] Complete frontend (React + TypeScript, 50+ panels)

- [x] ReAct Agent core (1,097 LOC, including validation/auto-fix/circuit breaker)

- [x] 5,381 automated tests

- [x] Three-province six-division avatar governance system (1,912 LOC)

- [x] Defense pipeline + hallucination interceptor

- [x] Consciousness model (7 levels + 6-dimensional Bayesian update)

- [x] Distributed entity system (Prime Brain → Avatar)

- [x] Consciousness upload/self-replication/civilization simulation (experimental features)



### 6.2 Pending Completion


- [ ] Productization design (ground-up UI/UX polishing)

- [ ] Cross-platform support (macOS/Linux untested currently)

- [ ] Installation experience (manual configuration required currently)

- [ ] Documentation and tutorial system

- [ ] Enterprise-level admin backend

- [ ] Technical debt cleanup

- [ ] API standardization and version management

- [ ] Security audit and compliance certification

- [ ] Community operation



---



## 7. Technical Challenges and Improvement Directions



### 7.1 Core Current Challenges



**Ambiguous Identity Positioning**



CollAI lacks a clear positioning between "AI programming tool" and "digital life form". The former has fierce market competition but clear demand; the latter has technological leadership but an immature market. This dual identity is both a source of innovation and a barrier to productization and market communication.



**Single-person Development Bottleneck**



A codebase of ~3,400 files built and maintained by one person has reached the limit of individual capacity. The core system is solid, but peripheral code quality is uneven, with a large amount of AI-generated code unreviewed in depth. The project requires more developers to enter the productization phase.



**Insufficient Productization**



While featuring numerous functions (50+ panels), there has been no systematic product design and user experience polishing. Function stacking outweighs function design, and technical depth surpasses user experience.



**Accumulated Technical Debt**

- `baby_cognitive_service.py`: 8,788 LOC single file in urgent need of refactoring and splitting

- Most of the 253 route files are unreviewed manually

- Inconsistent API path naming (e.g., `awakening`/`awakening2`)

- Plaintext credentials in some configuration files

- Test coverage threshold only 30%, with 44 subdirectories having zero test coverage



### 7.2 Improvement Roadmap



| Direction | Priority | Expected Outcome |

|-----------|----------|------------------|

| Core system refactoring (single file splitting, API unification) | P0 | Significant improvement in code maintainability |

| UI/UX productization design | P0 | From "usable" to "user-friendly" |

| Simplified installation experience (one-click installer) | P0 | Lowered usage threshold |

| Test coverage supplementation (target 60%+) | P1 | Measurable code quality |

| Cross-platform support (macOS/Linux) | P1 | Expanded user coverage |

| Documentation and tutorial system construction | P1 | Lowered barrier to community participation |

| Security audit and compliance certification | P2 | Prerequisite for enterprise customer onboarding |



---



## 8. Appendix: In-depth Technical Explanation



### 8.1 Detailed Cognitive Cycle



```

RECALL     → Retrieve relevant experiences from memory repository

THINK      → Select exploration topics via information gain scoring

PLAN       → Translate topics into specific tool calls

EXECUTE    → Execute tool calls (30s timeout, security checks)

ANALYZE    → Analyze execution results and extract patterns

REFLECT    → Detect contradictions/novelty/knowledge gaps

LEARN(GROW)→ Quality control + hallucination interception + permanent storage

```



### 8.2 Memory System Architecture



```

User Input

│

▼

Intent Router ──TEMPORAL → Timeline Query

│              ENTITY → Entity Query

│              SEMANTIC → Semantic Search

▼

3-layer Memory Hierarchy ── working (12,848) → short_term (156,110) → long_term (830)

│

▼

Memory Consolidation ── Forgetting Curve (90-day half-life) → Automatic downgrade/archiving

│

▼

Vector Index (SentenceTransformer) + FTS5 Full-text Search

```



### 8.3 Self-Evolution Engine



```

introspect → Code analysis

│

analyze gaps → Identify improvement points

│

build plan → Formulate modification plan

│

execute plan → AST validation + sandbox execution

│

learn → Learn from results

│

reflect → Evaluate effectiveness

│

generate self-tests → Generate test cases

│

self-document → Update documentation

```



### 8.4 Nervous System: Neurotransmitter System



CollAI implements dynamic simulation of 9 neurotransmitters to regulate cognitive behavior:



| Neurotransmitter | Function | Influencing Factors |

|------------------|----------|---------------------|

| Dopamine | Motivation, desire for exploration | Discovery of new knowledge, goal achievement |

| Serotonin | Stability, sense of satisfaction | Successful memory consolidation, confirmation of repeated patterns |

| Cortisol | Alertness, risk avoidance | Increased error rate, anomaly detection |

| Endorphins | Long-term commitment, patience | Completion of large-scale refactoring, continuous operation |

| Norepinephrine | Attention focus | New information impact, urgency |

| Acetylcholine | Learning rate, memory formation | Information gain, pattern novelty |

| GABA | Impulse inhibition, prudence | High-risk operations, high uncertainty |

| Glutamate | Plasticity, long-term potentiation | Repeated successful patterns, strong correlations |

| Adenosine | Fatigue, rest demand | Continuous runtime, cognitive load |



### 8.5 Deployment Architecture



```

User's Computer

│

├── Electron Frontend (React + TypeScript)

│

├── Parent Process (run_forever.py) Port 8770

│   ├── FastAPI Service Layer

│   ├── Cognitive Architecture Layer

│   ├── Memory System Layer

│   ├── Tool System Layer

│   ├── Provider Routing Layer (LLM-agnostic)

│   └── Self-Evolution Engine

│

├── Child Process (run_child.py) Port 8769

│   └── Independent Cognitive Cycle

│

└── (Optional) Quantitative Trading System Port 8753

    └── Tonghuashun Automation

```



---



*This document is based on actual code and data of the CollAI project, with technical data derived from real statistics during project operation.*
