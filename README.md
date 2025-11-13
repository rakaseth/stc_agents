# Claude Code Plugins: Orchestration and Automation

> **⚡ Updated for Sonnet 4.5 & Haiku 4.5** — All agents optimized for latest models with hybrid orchestration
>
> **🎯 Agent Skills Enabled** — 27 specialized skills extend Claude's capabilities across plugins with progressive disclosure

A comprehensive production-ready system combining **63 specialized AI agents**, **30 development commands**, **32 agent skills** organized into **21 focused, single-purpose plugins** for [Claude Code](https://docs.claude.com/en/docs/claude-code/overview).

## Overview

This unified repository provides everything needed for intelligent automation and multi-agent orchestration across modern software development:

- **21 Focused Plugins** - Specialized plugins for backend, frontend, fullstack e-commerce, DevOps, SEO, and full-stack development
- **63 Specialized Agents** - Domain experts with deep knowledge across FastAPI, Angular, React, Node.js, React Native, .NET, e-commerce, Kubernetes, cloud infrastructure, ML operations, and SEO
- **32 Agent Skills** - Modular knowledge packages with progressive disclosure for specialized expertise
- **30 Development Commands** - Optimized commands for feature development, code review, testing, and workflow automation

### Key Features

- **Specialized Plugin Architecture**: 21 focused plugins covering critical development workflows
- **Comprehensive Agents**: 63 specialized agents for backend, frontend, fullstack, e-commerce, infrastructure, and business needs
- **Agent Skills**: 32 specialized skills with progressive disclosure for token efficiency
- **Development Commands**: 30 commands for feature development, testing, and automation
- **Production-Ready**: Designed for FastAPI, Angular 19, React, Node.js, React Native, .NET, Kubernetes, and cloud infrastructure

### How It Works

Each plugin is completely isolated with its own agents, commands, and skills:

- **Install only what you need** - Each plugin loads only its specific agents, commands, and skills
- **Minimal token usage** - No unnecessary resources loaded into context
- **Mix and match** - Compose multiple plugins for complex workflows
- **Clear boundaries** - Each plugin has a single, focused purpose
- **Progressive disclosure** - Skills load knowledge only when activated



## Quick Start

### Step 1: Add the Marketplace

Add this marketplace to Claude Code:

```bash
/plugin marketplace add rakaseth/stc_agents
```

This makes all plugins available for installation, but **does not load any agents or tools** into your context.

### Step 2: Install Plugins

Browse available plugins:

```bash
/plugin
```

Install the plugins you need:

```bash
# Essential development plugins
           # FastAPI/Python with 6 specialized skills
/plugin install fullstack-ecommerce-app # React e-commerce with 4 specialized skills

# SEO & Marketing
/plugin install seo-technical-optimization  # Technical SEO
/plugin install seo-analysis-monitoring     # Content analysis and monitoring
```

Each installed plugin loads **only its specific agents, commands, and skills** into Claude's context.

## Documentation

### Core Guides

- **[Plugin Reference](docs/plugins.md)** - Complete catalog of all 63 plugins
- **[Agent Reference](docs/agents.md)** - All 85 agents organized by category
- **[Agent Skills](docs/agent-skills.md)** - 47 specialized skills with progressive disclosure
- **[Usage Guide](docs/usage.md)** - Commands, workflows, and best practices
- **[Architecture](docs/architecture.md)** - Design principles and patterns

### Quick Links

- [Installation](#quick-start) - Get started in 2 steps
- [Essential Plugins](docs/plugins.md#quick-start---essential-plugins) - Top plugins for immediate productivity
- [Command Reference](docs/usage.md#command-reference-by-category) - All slash commands organized by category
- [Multi-Agent Workflows](docs/usage.md#multi-agent-workflow-examples) - Pre-configured orchestration examples
- [Model Configuration](docs/agents.md#model-configuration) - Haiku/Sonnet hybrid orchestration

## What's New


Specialized knowledge packages following Anthropic's progressive disclosure architecture:

**E-commerce Development:**
- **React E-commerce** (4 skills): React e-commerce patterns, payment verification, cart state management, product catalog optimization

**Infrastructure & DevOps:**
- **Kubernetes** (4 skills): manifests, Helm charts, GitOps, security policies
- **Cloud Infrastructure** (4 skills): Terraform, multi-cloud, hybrid networking, cost optimization

**Bug Fix Automation:**
- **JIRA Bugfix** (4 skills): JIRA integration, coding standards, .NET testing

**Machine Learning:**
- **ML Operations** (1 skill): ML pipeline workflow

[→ View complete skills documentation](docs/agent-skills.md)


### Kubernetes and Cloud Infrastructure

```bash
"Create production Kubernetes deployment with Helm chart and GitOps"
```

Uses kubernetes-architect agent with 4 specialized skills for production-grade configs.

[→ View complete usage guide](docs/usage.md)


## License

MIT License - see [LICENSE](LICENSE) file for details.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=raushan-dj/agents&type=date&legend=top-left)](https://www.star-history.com/#raushan-dj/agents&type=date&legend=top-left)
