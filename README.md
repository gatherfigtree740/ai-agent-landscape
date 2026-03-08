# AI Agent Landscape

<p align="center">
  <strong>A sharp, curated directory of the AI agent ecosystem.</strong><br/>
  Compare coding agents, browser agents, research agents, workflow agents, and personal assistants in one place.
</p>

<p align="center">
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-categories">Categories</a> •
  <a href="#-comparison-snapshot">Comparison Snapshot</a> •
  <a href="#-contributing">Contributing</a>
</p>

---

## Why this exists

The AI agent space is exploding, but discovery is still messy:
- lists are stale
- comparisons are shallow
- pricing and open-source status are often unclear
- it is hard to know what to use for a specific job

**AI Agent Landscape** is meant to be the practical map:
- curated, not bloated
- opinionated, not empty marketing copy
- useful to developers, operators, founders, and tinkerers

## ⚡ Quick Start

Use this repo to answer three questions fast:
1. **What category of agent do I actually need?**
2. **Which tools are open source vs closed?**
3. **Which tools are best for my use case right now?**

Start here:
- Want coding help? See [Coding Agents](#coding-agents)
- Want web automation? See [Browser Agents](#browser-agents)
- Want research help? See [Research Agents](#research-agents)
- Want personal assistance or ops automation? See [Personal Assistants](#personal-assistants) and [Workflow Agents](#workflow-agents)

## 📊 Comparison Snapshot

| Tool | Category | Open Source | Best For | Notes |
|------|----------|-------------|----------|-------|
| OpenHands | Coding Agent | Yes | autonomous coding tasks | strong OSS mindshare |
| Codex CLI | Coding Agent | No | code generation and edits | useful for direct coding loops |
| Claude Code | Coding Agent | No | large refactors and repo reasoning | strong architectural work |
| Cursor Agent | Coding Agent | No | IDE-native dev workflows | very popular with app devs |
| OpenClaw | Personal Assistant / Agent Runtime | Yes | cross-channel assistant workflows | broad tool + device orchestration |
| Browser Use | Browser Agent | Yes | browser automation | strong OSS visibility |
| Goose | General Agent | Yes | extensible local agent workflows | dev-focused open source project |
| AutoGen | Agent Framework | Yes | multi-agent orchestration | framework, not turnkey product |
| CrewAI | Agent Framework | Yes | workflow-style multi-agent systems | popular among builders |
| LangGraph | Agent Framework | Yes | graph-based agent systems | strong for controlled flows |

> This is the starter table. The repo will expand category-by-category with sharper criteria and better sourcing.

## 🗂 Categories

### Coding Agents
Tools focused on writing, editing, refactoring, reviewing, or debugging code.

Current examples:
- Claude Code
- Codex CLI
- Cursor Agent
- OpenHands
- Aider
- Goose

### Browser Agents
Tools that act on websites and web apps.

Current examples:
- Browser Use
- OpenAI Operator-style systems
- Playwright-based agent wrappers
- OpenClaw browser automation flows

### Research Agents
Tools optimized for web search, synthesis, literature scans, or structured investigation.

Current examples:
- Perplexity-style research flows
- Deep research products
- agentic research wrappers on top of LLM APIs

### Workflow Agents
Tools that connect apps, APIs, documents, and automations.

Current examples:
- CrewAI automations
- LangGraph production flows
- n8n agent workflows
- MCP-connected task runners

### Personal Assistants
Agents that manage messages, notes, calendar, tasks, files, and devices.

Current examples:
- OpenClaw
- local desktop assistants
- messaging-native assistants

### Agent Frameworks
Building blocks for developers who want to create custom agents.

Current examples:
- AutoGen
- CrewAI
- LangGraph
- Semantic Kernel
- PydanticAI

## 🧠 What makes an agent interesting?

Each entry should eventually answer:
- What does it actually do well?
- Who is it for?
- Is it open source or closed?
- How hard is setup?
- Does it run locally, in the cloud, or both?
- Does it support tools, memory, workflows, browser control, coding, or MCP?

## 🏗 Repo Structure

```text
.
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── data/
│   ├── agents.csv
│   └── categories.md
└── .github/
    └── ISSUE_TEMPLATE/
```

## 🛣 Roadmap

- [x] Ship initial public repo structure
- [ ] Add 50+ curated agent entries
- [ ] Add better comparison tables by category
- [ ] Add pricing / hosting / OSS metadata columns
- [ ] Add contribution workflow for new submissions
- [ ] Add generated website or docs view
- [ ] Add changelog and weekly update cadence

## 🤝 Contributing

Contributions are welcome, especially if you can help with:
- missing tools
- outdated pricing or licensing info
- better categorization
- corrections to feature claims
- sharper use-case guidance

See [CONTRIBUTING.md](./CONTRIBUTING.md).

## ⭐ Star this repo

If this saves you time, helps you pick tools faster, or gives you a cleaner view of the agent ecosystem, drop a star.

## License

MIT
