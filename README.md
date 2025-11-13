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

**Example**: Installing `maestro-backend` loads 5 Python/FastAPI agents, 2 development commands, and makes 6 skills available for production-grade backend development.

## Quick Start

### Step 1: Add the Marketplace

Add this marketplace to Claude Code:

```bash
/plugin marketplace add raushan-dj/agents
```

This makes all 21 plugins available for installation, but **does not load any agents or tools** into your context.

### Step 2: Install Plugins

Browse available plugins:

```bash
/plugin
```

Install the plugins you need:

```bash
# Essential development plugins
/plugin install maestro-backend             # FastAPI/Python with 6 specialized skills
/plugin install degreed-fe-workspace        # Angular 19 with 8 specialized skills
/plugin install fullstack-ecommerce-app     # Node.js + React + React Native fullstack
/plugin install react-ecommerce-development # React e-commerce with 4 specialized skills
/plugin install jira-bugfix-analyzer        # JIRA bug analysis for .NET
/plugin install jira-bugfix-implementer     # Automated bug fix implementation

# Infrastructure & operations
/plugin install kubernetes-operations       # K8s with 4 deployment skills
/plugin install cloud-infrastructure        # AWS/Azure/GCP with 4 cloud skills

# AI & ML
/plugin install machine-learning-ops        # ML pipelines and MLOps
/plugin install agent-orchestration         # Multi-agent system optimization

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

### Agent Skills (31 skills across 8 plugins)

Specialized knowledge packages following Anthropic's progressive disclosure architecture:

**Backend Development:**
- **Maestro Backend** (6 skills): PRD parsing, task breakdown, code pattern analysis, Python testing, async patterns, performance optimization
- **Degreed Frontend** (8 skills): PRD parsing, task breakdown, component pattern analysis, Angular patterns, RxJS, testing, accessibility, performance

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

### Key Plugin Highlights

**Production-Ready Development:**
- **maestro-backend**: FastAPI backend with 3-loop code review and PRD-driven development
- **degreed-fe-workspace**: Angular 19 with component reuse enforcement and WCAG 2.1 AA compliance
- **jira-bugfix-analyzer**: Automated JIRA bug analysis with similar PR research
- **jira-bugfix-implementer**: Automated bug fix implementation with testing

**Infrastructure & Cloud:**
- **kubernetes-operations**: K8s manifests, Helm charts, and GitOps workflows
- **cloud-infrastructure**: Multi-cloud architecture with Terraform and cost optimization

**AI & Machine Learning:**
- **machine-learning-ops**: ML pipelines, model deployment, and MLOps automation
- **agent-orchestration**: Multi-agent system optimization

## Popular Use Cases

### Backend Feature Development with PRD

```bash
/maestro-backend:backend-feature
```

Comprehensive FastAPI backend development with:
- PRD parsing and task breakdown
- 3-loop code review and fix cycles
- Python testing patterns and async optimization
- Final validation before deployment

### Frontend Feature Development

```bash
/degreed-fe-workspace:frontend-feature
```

Angular 19 development with:
- Component reuse enforcement
- WCAG 2.1 AA accessibility compliance
- RxJS patterns and state management
- Nx monorepo integration

### JIRA Bug Analysis and Implementation

```bash
/jira-bugfix-analyzer:analyze-jira <JIRA-ID>
/jira-bugfix-implementer:implement-fix
```

Automated bug fixing workflow:
- Product-repo mapping and similar PR research
- Comprehensive fix suggestions
- Automated implementation with testing
- PR creation with detailed documentation

### Kubernetes and Cloud Infrastructure

```bash
"Create production Kubernetes deployment with Helm chart and GitOps"
```

Uses kubernetes-architect agent with 4 specialized skills for production-grade configs.

[→ View complete usage guide](docs/usage.md)

## Plugin Categories

**9 categories, 21 plugins:**

- 🎨 **Development** (7) - maestro-backend, degreed-fe-workspace, fullstack-ecommerce-app, react-ecommerce-development, frontend-mobile, code-documentation, code-refactoring
- 🔄 **Workflows** (1) - git-pr-workflows
- 🔍 **Quality** (2) - code-review-ai, codebase-cleanup
- 🐛 **Bug Fixing** (2) - jira-bugfix-analyzer, jira-bugfix-implementer
- 🤖 **AI & ML** (2) - agent-orchestration, machine-learning-ops
- 📊 **Data** (1) - data-engineering
- ☁️ **Infrastructure** (2) - kubernetes-operations, cloud-infrastructure
- ⚡ **Performance** (1) - application-performance
- 🔒 **Security** (1) - security-compliance
- 📢 **Marketing** (2) - seo-technical-optimization, seo-analysis-monitoring

[→ View complete plugin catalog](docs/plugins.md)

## Architecture Highlights

### Specialized Design

- **Focused plugins** - Each plugin targets specific development workflows
- **Production-ready** - Built for FastAPI, Angular 19, Node.js fullstack, React e-commerce, .NET, Kubernetes, and cloud platforms
- **Comprehensive coverage** - 63 agents, 30 commands, 32 skills across 21 plugins
- **Enterprise-grade** - 3-loop code review, accessibility compliance, payment verification, and automated testing

### Progressive Disclosure (Skills)

Three-tier architecture for token efficiency:
1. **Metadata** - Name and activation criteria (always loaded)
2. **Instructions** - Core guidance (loaded when activated)
3. **Resources** - Examples and templates (loaded on demand)

### Repository Structure

```
claude-agents/
├── .claude-plugin/
│   └── marketplace.json          # 21 plugins
├── plugins/
│   ├── maestro-backend/
│   │   ├── agents/               # 5 Python/FastAPI experts
│   │   ├── commands/             # 2 development commands
│   │   └── skills/               # 6 specialized skills
│   ├── degreed-fe-workspace/
│   │   ├── agents/               # 5 Angular/TypeScript experts
│   │   ├── commands/             # 2 development commands
│   │   └── skills/               # 8 specialized skills
│   ├── fullstack-ecommerce-app/
│   │   ├── agents/               # 5 Node.js/React/RN experts
│   │   ├── commands/             # 2 fullstack commands
│   │   └── skills/               # 1 integration skill
│   ├── react-ecommerce-development/
│   │   ├── agents/               # 4 React/e-commerce experts
│   │   ├── commands/             # 2 e-commerce commands
│   │   └── skills/               # 4 specialized skills
│   ├── kubernetes-operations/
│   │   ├── agents/               # K8s architect
│   │   └── skills/               # 4 K8s skills
│   └── ... (14 more plugins)
├── docs/                          # Comprehensive documentation
└── README.md                      # This file
```

[→ View architecture details](docs/architecture.md)

## Contributing

To add new agents, skills, or commands:

1. Identify or create the appropriate plugin directory in `plugins/`
2. Create `.md` files in the appropriate subdirectory:
   - `agents/` - For specialized agents
   - `commands/` - For tools and workflows
   - `skills/` - For modular knowledge packages
3. Follow naming conventions (lowercase, hyphen-separated)
4. Write clear activation criteria and comprehensive content
5. Update the plugin definition in `.claude-plugin/marketplace.json`

See [Architecture Documentation](docs/architecture.md) for detailed guidelines.

## Resources

### Documentation
- [Claude Code Documentation](https://docs.claude.com/en/docs/claude-code/overview)
- [Plugins Guide](https://docs.claude.com/en/docs/claude-code/plugins)
- [Subagents Guide](https://docs.claude.com/en/docs/claude-code/sub-agents)
- [Agent Skills Guide](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview)
- [Slash Commands Reference](https://docs.claude.com/en/docs/claude-code/slash-commands)

### This Repository
- [Plugin Reference](docs/plugins.md)
- [Agent Reference](docs/agents.md)
- [Agent Skills Guide](docs/agent-skills.md)
- [Usage Guide](docs/usage.md)
- [Architecture](docs/architecture.md)

## License

MIT License - see [LICENSE](LICENSE) file for details.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=raushan-dj/agents&type=date&legend=top-left)](https://www.star-history.com/#raushan-dj/agents&type=date&legend=top-left)
