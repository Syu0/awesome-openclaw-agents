# 🦞 Awesome OpenClaw Agents

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Stars](https://img.shields.io/github/stars/mergisi/awesome-openclaw-agents?style=social)](https://github.com/mergisi/awesome-openclaw-agents)

> A curated collection of AI agent templates, MCP servers, tools, and resources for the OpenClaw ecosystem. Every template is a copy-paste ready SOUL.md file.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,100:7C3AED&height=180&section=header&text=%F0%9F%A6%9E%20Awesome%20OpenClaw%20Agents&fontSize=36&fontColor=ffffff&fontAlignY=35" width="100%"/>
</p>

<div align="center">

**Don't want to set up manually?**

[**Deploy any agent with Docker + Telegram in 5 minutes →**](https://crewclaw.com/create-agent)

CrewClaw packages your SOUL.md with Dockerfile, Telegram bot, and deployment config. No code required.

</div>

---

<div align="center">

**If this repo saved you time, consider supporting the work:**

<a href="https://github.com/sponsors/mergisi">
  <img src="https://img.shields.io/badge/Sponsor-%E2%9D%A4-ea4aaa?style=for-the-badge&logo=github-sponsors&logoColor=white" alt="Sponsor" />
</a>

New templates every month, MCP integrations, guides, and compatibility updates. Even $1/mo helps.

</div>

---

## Contents

- [Agent Templates](#agent-templates)
  - [Productivity](#productivity)
  - [Development](#development)
  - [Marketing & Content](#marketing--content)
  - [Business](#business)
  - [Personal](#personal)
- [MCP Servers](#mcp-servers)
- [Integrations](#integrations)
- [Tools](#tools)
- [Tutorials & Guides](#tutorials--guides)
- [Community](#community)

---

## Agent Templates

Ready-to-use SOUL.md templates for your AI agents. Copy the SOUL.md, register with `openclaw agents add`, and start the gateway.

```bash
# Quick start with any template
git clone https://github.com/mergisi/awesome-openclaw-agents.git
openclaw agents add my-agent --workspace ./awesome-openclaw-agents/agents/productivity/orion
openclaw gateway start
```

### Productivity

| Agent | Description | SOUL.md | Deploy |
|-------|-------------|---------|--------|
| [🎯 Orion](agents/productivity/orion/) | Task coordinator and project manager | [View](agents/productivity/orion/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent/project-manager-soul-md) |
| [📊 Pulse](agents/productivity/metrics/) | Analytics dashboard agent (Mixpanel, Stripe, GA4) | [View](agents/productivity/metrics/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent) |
| [🧍 Standup](agents/productivity/daily-standup/) | Daily standup collector and team summarizer | [View](agents/productivity/daily-standup/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent) |
| [📧 Inbox](agents/productivity/inbox-zero/) | Email triage, response drafting, daily digest | [View](agents/productivity/inbox-zero/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent) |
| [📝 Minutes](agents/productivity/meeting-notes/) | Meeting summarizer and action item tracker | [View](agents/productivity/meeting-notes/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent) |

### Development

| Agent | Description | SOUL.md | Deploy |
|-------|-------------|---------|--------|
| [🔎 Lens](agents/development/code-reviewer/) | PR review, security scanning, quality assessment | [View](agents/development/code-reviewer/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent/code-reviewer-soul-md) |
| [📖 Scribe](agents/development/docs-writer/) | README, API docs, and code documentation generator | [View](agents/development/docs-writer/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent/technical-writer-soul-md) |
| [🐛 Trace](agents/development/bug-hunter/) | Error analysis, root cause investigation, debugging | [View](agents/development/bug-hunter/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent) |
| [🧪 Probe](agents/development/api-tester/) | API endpoint testing, health checks, performance | [View](agents/development/api-tester/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent) |
| [📋 Log](agents/development/changelog/) | Auto-changelog from git commits, release notes | [View](agents/development/changelog/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent) |

### Marketing & Content

| Agent | Description | SOUL.md | Deploy |
|-------|-------------|---------|--------|
| [✍️ Echo](agents/marketing/echo/) | Content writer for blogs, social, emails | [View](agents/marketing/echo/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent/content-writer-soul-md) |
| [📱 Buzz](agents/marketing/social-media/) | Social media manager for Twitter, LinkedIn, threads | [View](agents/marketing/social-media/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent/social-media-manager-soul-md) |
| [🔍 Rank](agents/marketing/seo-writer/) | SEO content writer with keyword research from GSC | [View](agents/marketing/seo-writer/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent/seo-specialist-soul-md) |
| [📬 Digest](agents/marketing/newsletter/) | Weekly newsletter curator and email writer | [View](agents/marketing/newsletter/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent) |
| [🔭 Scout](agents/marketing/competitor-watch/) | Competitor monitoring, pricing intel, market analysis | [View](agents/marketing/competitor-watch/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent) |

### Business

| Agent | Description | SOUL.md | Deploy |
|-------|-------------|---------|--------|
| [📊 Radar](agents/business/radar/) | Data analyst and insights generator | [View](agents/business/radar/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent/data-analyst-soul-md) |
| [🎧 Compass](agents/business/customer-support/) | Support ticket triage, response drafting, escalation | [View](agents/business/customer-support/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent/customer-support-soul-md) |
| [💼 Pipeline](agents/business/sales-assistant/) | Lead scoring, outreach drafting, pipeline reports | [View](agents/business/sales-assistant/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent/sales-representative-soul-md) |
| [💰 Ledger](agents/business/invoice-tracker/) | Payment monitoring, invoice tracking, MRR reports | [View](agents/business/invoice-tracker/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent) |
| [🔮 Sentinel](agents/business/churn-predictor/) | Churn risk scoring, retention actions, re-engagement | [View](agents/business/churn-predictor/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent) |

### Personal

| Agent | Description | SOUL.md | Deploy |
|-------|-------------|---------|--------|
| [📅 Atlas](agents/personal/daily-planner/) | Daily schedule optimizer, morning plans, evening reviews | [View](agents/personal/daily-planner/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent) |
| [📚 Scroll](agents/personal/reading-digest/) | Article summarizer, weekly reading digest, Notion sync | [View](agents/personal/reading-digest/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent) |
| [💪 Iron](agents/personal/fitness-coach/) | Workout planner, nutrition tracker, progress reports | [View](agents/personal/fitness-coach/SOUL.md) | [Deploy →](https://crewclaw.com/create-agent/fitness-coach-soul-md) |

---

## Quick Deploy with CrewClaw

Don't want to configure manually? [CrewClaw](https://crewclaw.com/create-agent) generates a complete deployment package for any agent:

```
Your CrewClaw package includes:
├── agents/your-agent/SOUL.md    # Agent configuration
├── Dockerfile                    # Container setup
├── docker-compose.yml            # One-command deploy
├── bot.js                        # Telegram bot (grammy)
├── .env.example                  # API keys template
├── package.json                  # Dependencies
└── README.md                     # Setup instructions
```

**Single agent: $9** | **Team of 3 agents: $19** | **Free: Copy SOUL.md only**

[Create your agent →](https://crewclaw.com/create-agent)

---

## MCP Servers

Model Context Protocol servers to extend agent capabilities.

### Official

| Server | Description | Install |
|--------|-------------|---------|
| [@anthropic/mcp-server-fetch](https://github.com/anthropics/mcp-server-fetch) | Web fetching and browsing | `npx -y @anthropic/mcp-server-fetch` |
| [@anthropic/mcp-server-filesystem](https://github.com/anthropics/mcp-server-filesystem) | File system access | `npx -y @anthropic/mcp-server-filesystem` |

### Community

| Server | Description |
|--------|-------------|
| mcp-notion | Notion integration |
| mcp-google-calendar | Google Calendar access |
| mcp-github | GitHub operations |
| mcp-slack | Slack messaging |
| mcp-postgres | PostgreSQL queries |
| mcp-stripe | Stripe payments |
| mcp-shopify | Shopify store management |
| mcp-twitter | Twitter/X posting |
| mcp-discord | Discord bot integration |
| mcp-linear | Linear issue tracking |

---

## Integrations

Connect your agents to external services.

### Messaging

- **Telegram** - Chat with agents via Telegram (built-in to OpenClaw)
- **Slack** - Slack workspace connection (built-in to OpenClaw)
- **Discord** - Discord server bot (built-in to OpenClaw)
- **Email** - Email channel (built-in to OpenClaw)

### Automation

- **n8n** - n8n integration nodes
- **GitHub Actions** - CI/CD integration
- **Cron / pm2 / systemd** - Always-on agent scheduling

---

## Tools

Utilities and helpers for working with OpenClaw.

| Tool | Description |
|------|-------------|
| [openclaw CLI](https://crewclaw.com/blog/openclaw-cli-commands-reference) | Official CLI - complete command reference |
| agent-validator | Validate SOUL.md syntax |
| mcp-tester | Test MCP server connections |

---

## Tutorials & Guides

Learn how to build and deploy agents.

### Getting Started

- [What is OpenClaw?](https://crewclaw.com/blog/what-is-openclaw-ai-agent-framework) - Complete guide to the framework
- [Create Your First Agent](https://crewclaw.com/blog/how-to-create-ai-agent-openclaw) - No code required
- [OpenClaw Setup Guide 2026](https://crewclaw.com/blog/openclaw-setup-guide-2026) - Install, configure, run
- [SOUL.md Templates](https://crewclaw.com/blog/soul-md-examples-templates) - 10 ready-to-use examples

### Multi-Agent & Orchestration

- [Multi-Agent Setup Guide](https://crewclaw.com/blog/openclaw-multi-agent-setup-guide) - Run multiple agents together
- [Agent-to-Agent Communication](https://crewclaw.com/blog/openclaw-agent-to-agent-communication) - How agents collaborate
- [Build an AI Team](https://crewclaw.com/blog/build-ai-team-workflows) - Workflows that run autonomously

### Integrations & Automation

- [Slack & Telegram Integration](https://crewclaw.com/blog/openclaw-slack-telegram-integration) - Connect to messaging channels
- [Run with Ollama](https://crewclaw.com/blog/openclaw-ollama-local-agents) - Free local AI agents
- [Automation Guide](https://crewclaw.com/blog/openclaw-automation-guide) - Build 24/7 workflows
- [CLI Commands Reference](https://crewclaw.com/blog/openclaw-cli-commands-reference) - Complete cheat sheet

### Comparisons

- [OpenClaw vs LangChain](https://crewclaw.com/blog/openclaw-vs-langchain) - Framework comparison
- [OpenClaw vs AutoGPT](https://crewclaw.com/blog/openclaw-vs-autogpt) - Key differences
- [OpenClaw vs CrewAI](https://crewclaw.com/blog/openclaw-vs-crewai) - Which is better?

---

## Community

### Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md).

#### How to Add an Agent

1. Fork this repository
2. Create folder: `agents/[category]/[agent-name]/`
3. Add `SOUL.md` and `README.md`
4. Submit a Pull Request

#### Agent Template

```markdown
# Agent Name

Brief description of what this agent does.

## Use Cases

- Use case 1
- Use case 2

## Setup

openclaw agents add agent-name --workspace ./agents/agent-name

## Example Prompts

- "Example prompt 1"
- "Example prompt 2"
```

---

## Related Projects

- [🦀 CrewClaw](https://crewclaw.com) - Deploy and orchestrate AI agents as a team. No code required.
- [OpenClaw](https://github.com/openclaw) - Official OpenClaw repository
- [Anthropic MCP](https://github.com/anthropics/mcp) - Model Context Protocol

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=mergisi/awesome-openclaw-agents&type=Date)](https://star-history.com/#mergisi/awesome-openclaw-agents&Date)

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.

---

<p align="center">
  Made with 🦞 by the OpenClaw Community
  <br/>
  <a href="https://crewclaw.com/create-agent">Deploy your agent with CrewClaw →</a>
</p>
