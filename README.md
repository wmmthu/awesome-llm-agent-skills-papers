# Awesome LLM Agent Skills Papers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of papers, blog posts, and systems on **skills for LLM agents** — reusable, named capability units that an agent can store, retrieve, compose, and improve over time — together with closely adjacent research on tool use, function calling, procedural memory, and skill induction.

**Scope.** Entries here treat *skills* as first-class artifacts (Anthropic-style skill folders, Voyager-style code skill libraries, learned options, induced procedures, retrievable prompts, callable tools). General LLM-agent work that does not put a skill abstraction at the center is mostly out of scope and lives in other awesome-lists.

**Format.** One line per entry, chronological within each section (oldest → newest):

```
- **Title** — First Author et al. *Venue Year*. [paper](url) [code](url)
```

Contributions welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).

## Contents

- [Surveys & Position Papers](#surveys--position-papers)
- [Skill Definition & Formats](#skill-definition--formats)
- [Skill Acquisition & Induction](#skill-acquisition--induction)
- [Skill Curation & Learning](#skill-curation--learning)
- [Skill Retrieval & Selection](#skill-retrieval--selection)
- [Skill Composition & Reuse](#skill-composition--reuse)
- [Tool Use & Function Calling](#tool-use--function-calling)
- [Procedural Memory & Lifelong Learning](#procedural-memory--lifelong-learning)
- [Benchmarks & Evaluation](#benchmarks--evaluation)
- [Systems & Frameworks](#systems--frameworks)
- [Blogs & Engineering Notes](#blogs--engineering-notes)
- [Contributing](#contributing)
- [License](#license)

## Surveys & Position Papers

- **Agent Skills for Large Language Models: Architecture, Acquisition, Security, and the Path Forward** — Xu and Yan. *arXiv 2026*. [paper](https://arxiv.org/abs/2602.12430)
- **Externalization in LLM Agents: A Unified Review of Memory, Skills, Protocols and Harness Engineering** — Zhou et al. *arXiv 2026*. [paper](https://arxiv.org/abs/2604.08224)

## Skill Definition & Formats

- **Agent Skills Enable a New Class of Realistic and Trivially Simple Prompt Injections** — Schmotz et al. *arXiv 2025*. [paper](https://arxiv.org/abs/2510.26328)
- **Agent Skills Open Standard** — Anthropic. *2025*. [site](https://agentskills.io)
- **Agent Skills in the Wild: An Empirical Study of Security Vulnerabilities at Scale** — Liu et al. *arXiv 2026*. [paper](https://arxiv.org/abs/2601.10338)
- **Malicious Agent Skills in the Wild: A Large-Scale Security Empirical Study** — Liu et al. *arXiv 2026*. [paper](https://arxiv.org/abs/2602.06547)

## Skill Acquisition & Induction

- **Code as Policies: Language Model Programs for Embodied Control** — Liang et al. *arXiv 2022*. [paper](https://arxiv.org/abs/2209.07753)
- **Voyager: An Open-Ended Embodied Agent with Large Language Models** — Wang et al. *arXiv 2023*. [paper](https://arxiv.org/abs/2305.16291) [code](https://github.com/MineDojo/Voyager)
- **Eureka: Human-Level Reward Design via Coding Large Language Models** — Ma et al. *ICLR 2024*. [paper](https://arxiv.org/abs/2310.12931) [code](https://github.com/eureka-research/Eureka)
- **SEAgent: Self-Evolving Computer Use Agent with Autonomous Learning from Experience** — Sun et al. *arXiv 2025*. [paper](https://arxiv.org/abs/2508.04700) [code](https://github.com/SunzeY/SEAgent)
- **CUA-Skill: Develop Skills for Computer Using Agent** — Chen et al. *arXiv 2026*. [paper](https://arxiv.org/abs/2601.21123)
- **Improving Interactive In-Context Learning from Natural Language Feedback** — Klissarov et al. *arXiv 2026*. [paper](https://arxiv.org/abs/2602.16066)
- **From Context to Skills: Can Language Models Learn from Context Skillfully?** — Si et al. *arXiv 2026*. [paper](https://arxiv.org/abs/2604.27660) [code](https://github.com/S1s-Z/Ctx2Skill)

## Skill Curation & Learning

- **Reinforcement Learning for Self-Improving Agent with Skill Library** — Wang et al. *arXiv 2025*. [paper](https://arxiv.org/abs/2512.17102)
- **SKILL0: In-Context Agentic Reinforcement Learning for Skill Internalization** — Lu et al. *arXiv 2026*. [paper](https://arxiv.org/abs/2604.02268) [code](https://github.com/ZJU-REAL/SkillZero)
- **SkillX: Automatically Constructing Skill Knowledge Bases for Agents** — Wang et al. *arXiv 2026*. [paper](https://arxiv.org/abs/2604.04804)
- **Skill1: Unified Evolution of Skill-Augmented Agents via Reinforcement Learning** — Shi et al. *arXiv 2026*. [paper](https://arxiv.org/abs/2605.06130)
- **SkillOS: Learning Skill Curation for Self-Evolving Agents** — Ouyang et al. *arXiv 2026*. [paper](https://arxiv.org/abs/2605.06614)

## Skill Retrieval & Selection

- _Contributions welcome._

## Skill Composition & Reuse

- **ReAct: Synergizing Reasoning and Acting in Language Models** — Yao et al. *ICLR 2023*. [paper](https://arxiv.org/abs/2210.03629) [code](https://github.com/ysymyth/ReAct)
- **Reflexion: Language Agents with Verbal Reinforcement Learning** — Shinn et al. *arXiv 2023*. [paper](https://arxiv.org/abs/2303.11366)
- **When Single-Agent with Skills Replace Multi-Agent Systems and When They Fail** — Li. *arXiv 2026*. [paper](https://arxiv.org/abs/2601.04748)
- **Agentic Proposing: Enhancing Large Language Model Reasoning via Compositional Skill Synthesis** — Jiao et al. *arXiv 2026*. [paper](https://arxiv.org/abs/2602.03279)

## Tool Use & Function Calling

- **Toolformer: Language Models Can Teach Themselves to Use Tools** — Schick et al. *arXiv 2023*. [paper](https://arxiv.org/abs/2302.04761)
- **CREATOR: Tool Creation for Disentangling Abstract and Concrete Reasoning of Large Language Models** — Qian et al. *Findings of EMNLP 2024*. [paper](https://arxiv.org/abs/2305.14318)
- **Gorilla: Large Language Model Connected with Massive APIs** — Patil et al. *arXiv 2023*. [paper](https://arxiv.org/abs/2305.15334) [code](https://github.com/ShishirPatil/gorilla)
- **Large Language Models as Tool Makers** — Cai et al. *arXiv 2023*. [paper](https://arxiv.org/abs/2305.17126) [code](https://github.com/ctlllll/LLM-ToolMaker)
- **ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs** — Qin et al. *arXiv 2023*. [paper](https://arxiv.org/abs/2307.16789) [code](https://github.com/OpenBMB/ToolBench)
- **Tool Learning with Large Language Models: A Survey** — Qu et al. *arXiv 2024*. [paper](https://arxiv.org/abs/2405.17935)

## Procedural Memory & Lifelong Learning

- _Contributions welcome._

## Benchmarks & Evaluation

- _Contributions welcome._

## Systems & Frameworks

- **AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation** — Wu et al. *arXiv 2023*. [paper](https://arxiv.org/abs/2308.08155) [code](https://github.com/microsoft/autogen)
- **MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework** — Hong et al. *arXiv 2023*. [paper](https://arxiv.org/abs/2308.00352) [code](https://github.com/geekan/MetaGPT)

## Blogs & Engineering Notes

- **Introducing Agent Skills** — Anthropic. *Oct 2025*. [blog](https://claude.com/blog/skills)

## Contributing

PRs adding papers, fixing venue/year metadata, or filling empty sections are very welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) first — it covers the entry format, the chronological ordering rule, and the PR checklist.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, the contributors to this list have waived all copyright and related rights to the **list itself** under [CC0 1.0](LICENSE). Cited papers, blog posts, and code repositories retain their own licenses.
