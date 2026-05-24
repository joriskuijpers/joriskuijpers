# Bookmarks

## Core Cross-Language

### Environment and Runtime Management

#### Core Tooling

- [Homebrew](https://brew.sh/): Primary package manager for macOS and Linux workstations
- [mise](https://mise.jdx.dev/): Unified runtime/version manager for multi-language projects
- [asdf](https://asdf-vm.com/): Plugin-based version manager for many language runtimes
- [Nix](https://nixos.org/): Reproducible package and environment system
- [Devbox](https://www.jetify.com/devbox): Simpler developer UX on top of Nix environments

### Productivity and Shell Context

#### Workflow Foundations

- [Raycast](https://www.raycast.com/): Productivity launcher and command palette for macOS workflows
- [direnv](https://direnv.net/): Automatic per-directory environment variable loading

## Terminal and Shell

### Terminal Emulators

#### Interactive Terminals

- [WezTerm](https://wezfurlong.org/wezterm/): GPU-accelerated terminal with modern configuration options
- [Kitty](https://sw.kovidgoyal.net/kitty/): Fast, scriptable terminal focused on performance and features
- [Ghostty](https://ghostty.org/): Native-feeling modern terminal emulator with low latency
- [Warp](https://www.warp.dev/): Terminal with command blocks and AI-assisted workflows

### Shells and Prompting

#### Shell Experience

- [fish shell](https://fishshell.com/): Friendly interactive shell with great defaults
- [nushell](https://www.nushell.sh/): Structured shell with typed pipelines and table data
- [Starship](https://starship.rs/): Cross-shell prompt
- [Atuin](https://atuin.sh/): Shell history sync/search with encryption and cross-machine recall

### CLI Navigation and Search

#### Finder and Navigation Utilities

- [zoxide](https://github.com/ajeetdsouza/zoxide): Smarter cd
- [fzf](https://github.com/junegunn/fzf): Fuzzy finder
- [ripgrep](https://github.com/BurntSushi/ripgrep): Extremely fast search
- [fd](https://github.com/sharkdp/fd): Fast and user-friendly alternative to find

### Everyday Utilities and Multiplexing

#### Daily Command-Line Utilities

- [bat](https://github.com/sharkdp/bat): Better cat
- [eza](https://eza.rocks/): Modern ls
- [btop](https://github.com/aristocratos/btop): Interactive system monitor for CPU, memory, disk, and network
- [hyperfine](https://github.com/sharkdp/hyperfine): Command-line benchmark tool for measuring execution speed
- [just](https://just.systems/): Better makefile runner
- [watchexec](https://watchexec.github.io/): Run commands on file changes
- [tmux](https://github.com/tmux/tmux): Terminal multiplexer for persistent and split sessions

## Editors and IDEs

### Modal and Keyboard-First Editors

#### Modal Editing Stack

- [Neovim](https://neovim.io/): Extensible modal editor for keyboard-centric development
- [LazyVim](https://www.lazyvim.org/): Opinionated Neovim distribution with batteries included
- [AstroNvim](https://astronvim.com/): Modular Neovim setup with curated defaults and plugins
- [Helix](https://helix-editor.com/): Modal editor built around syntax trees and multi-cursor editing

### GUI Editors and IDE Platforms

#### General-Purpose Editors

- [Visual Studio Code](https://code.visualstudio.com/): General-purpose IDE with strong extension ecosystem
- [Zed](https://zed.dev/): High-performance collaborative code editor built in Rust

### AI-First Coding IDEs

#### AI-Native IDEs

- [Cursor](https://cursor.com/): AI-native code editor based on the VS Code experience
- [Windsurf](https://windsurf.com/): AI-focused IDE designed for high-velocity coding workflows

## Python Ecosystem

### Packaging, Environments, and Tooling

#### Package and Version Management

- [uv](https://docs.astral.sh/uv/): Extremely fast Python package and project manager
- [Poetry](https://python-poetry.org/): Dependency and packaging manager
- [PDM](https://pdm-project.org/): Modern Python package manager
- [Hatch](https://hatch.pypa.io/): Python project manager/build tool
- [pyenv](https://github.com/pyenv/pyenv): Python version manager for local and global runtimes

### Quality, Types, and CLI UX

#### Python Developer Experience

- [Ruff](https://docs.astral.sh/ruff/): Fast Python linter + formatter
- [Pyright](https://github.com/microsoft/pyright): Fast static type checker
- [Typer](https://typer.tiangolo.com/): Build CLIs from Python type hints
- [Rich](https://github.com/Textualize/rich): Beautiful terminal formatting
- [Textual](https://textual.textualize.io/): Build terminal UIs in Python

### Backend and Data Stack

#### Python Backend and Data Libraries

- [FastAPI](https://fastapi.tiangolo.com/): High-performance Python web framework for APIs
- [Litestar](https://litestar.dev/): Typed and async-first Python ASGI framework
- [Pydantic](https://docs.pydantic.dev/): Data validation and settings management via type hints
- [Polars](https://pola.rs/): Fast DataFrame library for analytical workloads
- [DuckDB](https://duckdb.org/): Analytical SQL database

### Notebooks and Orchestration

#### Interactive and Pipeline Tooling

- [JupyterLab](https://jupyter.org/): Interactive notebook and data science development environment
- [Marimo](https://marimo.io/): Reactive Python notebooks with reproducible execution model
- [Prefect](https://www.prefect.io/): Workflow orchestration platform for data and ML pipelines

## JavaScript and TypeScript

### Runtimes and Package Managers

#### JavaScript Runtime Toolchain

- [Bun](https://bun.sh/): Fast JS runtime + package manager
- [Deno](https://deno.com/): Secure JS/TS runtime
- [pnpm](https://pnpm.io/): Efficient package manager
- [nvm](https://github.com/nvm-sh/nvm): Node.js version manager for switching Node installations

### Build and Quality Tooling

#### Frontend Build Core

- [Biome](https://biomejs.dev/): Fast formatter/linter replacement
- [Vite](https://vite.dev/): Fast dev server and build tool for modern web projects

### Full-Stack Frameworks

#### Web Application Frameworks

- [Next.js](https://nextjs.org/): React framework for full-stack and SSR applications
- [Nuxt](https://nuxt.com/): Vue framework for full-stack and server-rendered applications
- [SvelteKit](https://kit.svelte.dev/): Full-stack framework for building Svelte applications
- [Astro](https://astro.build/): Content-focused web framework with island architecture

### Monorepo and Build Graph Tools

#### Workspace Orchestration

- [Turborepo](https://turbo.build/repo): High-performance monorepo build and caching toolkit
- [Nx](https://nx.dev/): Smart monorepo tooling

## Databases and Backend

### Databases and Caches

#### Data Engines

- [PostgreSQL](https://www.postgresql.org/): Production-grade relational database with rich SQL support
- [Redis](https://redis.io/): In-memory key-value store for caching, queues, and pub/sub
	- [Redis Cloud](https://redis.io/cloud/): Fully managed Redis deployment platform for production workloads
	- [Redis Search](https://redis.io/search/): Full-text and secondary-index search module for Redis datasets
	- [Redis Insight](https://redis.io/insight/): Desktop and web GUI for Redis inspection, profiling, and diagnostics
- [ClickHouse](https://clickhouse.com/): Columnar analytical database optimized for high-speed OLAP queries and large event datasets
- [Neon](https://neon.com/): Serverless Postgres with autoscaling and branching for AI-era workloads
- [Turso](https://turso.tech/): Edge SQLite platform
- [LiteFS](https://fly.io/docs/litefs/): SQLite replication

### Backend Platforms

#### Managed Backend Services

- [Supabase](https://supabase.com/): Open-source Firebase alternative
	- [Supabase Auth](https://supabase.com/auth): Authentication and authorization service with RLS-friendly JWT workflows
	- [Supabase Edge Functions](https://supabase.com/edge-functions): Globally distributed server-side TypeScript functions for backend logic
	- [Supabase Realtime](https://supabase.com/realtime): WebSocket-based realtime sync for database changes, presence, and broadcast
	- [Supabase Storage](https://supabase.com/storage): File and object storage with CDN delivery and access controls
	- [Supabase Vector](https://supabase.com/modules/vector): Vector-capable Postgres module for embeddings and semantic search
- [PocketBase](https://pocketbase.io/): Lightweight backend with embedded database and auth

### ORMs and Data Access

#### Application Data Layers

- [Prisma](https://www.prisma.io/): Modern ORM
- [Drizzle ORM](https://orm.drizzle.team/): Type-safe SQL ORM for TypeScript applications

## Containers and Infra

### Local Container Tooling

#### Local Runtime and Dev Environments

- [Colima](https://colima.run/): Lightweight Docker-compatible container runtime for macOS and Linux
- [Dev Containers](https://containers.dev/): Reproducible development environments
- [Docker](https://www.docker.com/): Container platform
	- [Docker Desktop](https://www.docker.com/products/docker-desktop/): Local development environment for building and running containers
	- [Docker Hub](https://www.docker.com/products/docker-hub/): Container registry for publishing and consuming images
	- [Docker Scout](https://www.docker.com/products/docker-scout/): Container image security and remediation insights
	- [Docker Build Cloud](https://www.docker.com/products/build-cloud/): Managed remote build acceleration for container pipelines
- [Podman](https://podman.io/): Daemonless containers
- [OrbStack](https://orbstack.dev/): Lightweight Docker/VM replacement for macOS

### Cloud and PaaS Platforms

#### Public Cloud Foundations

- [Azure](https://azure.microsoft.com/): Cloud platform for app hosting, data, and managed infrastructure services
	- [Azure Kubernetes Service](https://azure.microsoft.com/products/kubernetes-service): Managed Kubernetes control plane and worker lifecycle on Azure
	- [Azure Container Apps](https://azure.microsoft.com/products/container-apps): Serverless container platform for microservices and background jobs
	- [Azure DevOps](https://azure.microsoft.com/products/devops): Developer platform for repos, pipelines, boards, and artifact workflows
- [Azure CLI](https://learn.microsoft.com/cli/azure/): Command-line interface for provisioning and managing Azure resources
- [Google Cloud Run](https://cloud.google.com/run): Serverless container runtime with autoscaling on Google Cloud

#### Application Platforms and PaaS

- [Railway](https://railway.com/): Fast app platform with strong momentum around agent-assisted workflows
- [Vercel](https://vercel.com/): Frontend-first cloud platform and deployment workflow for web apps
	- [Vercel AI Gateway](https://vercel.com/ai-gateway): Unified gateway for accessing many AI model providers through one endpoint
	- [Vercel Agent](https://vercel.com/agent): Agent runtime for orchestrating complex AI workflows on Vercel infrastructure
	- [Vercel Blob](https://vercel.com/storage/blob): Managed object storage for runtime and build-time file uploads
	- [Vercel Observability](https://vercel.com/products/observability): Integrated observability for production performance and runtime diagnostics
	- [Vercel Web Application Firewall](https://vercel.com/security/web-application-firewall): Layer-7 protection and traffic filtering for deployed applications
- [Render](https://render.com/): Unified cloud platform for web services, workers, and managed databases
- [Heroku](https://www.heroku.com/): Established PaaS for fast app deployment with add-on ecosystem
- [DigitalOcean App Platform](https://www.digitalocean.com/products/app-platform): Simpler managed app hosting for small and mid-size teams
- [Fly.io](https://fly.io/): Edge cloud platform for deploying apps close to users
- [Coolify](https://coolify.io/): Self-hosted PaaS for managing app deployments and services

### Kubernetes and Infrastructure as Code

#### Kubernetes Tooling

- [Kubernetes](https://kubernetes.io/): Container orchestration platform for distributed systems
- [k9s](https://k9scli.io/): Terminal UI for observing and managing Kubernetes clusters
- [Helm](https://helm.sh/): Package manager for Kubernetes applications and charts

#### Infrastructure as Code and Automation

- [Terraform](https://developer.hashicorp.com/terraform): Infrastructure as code for cloud and on-prem provisioning
- [OpenTofu](https://opentofu.org/): Open-source Terraform-compatible infrastructure as code tool
- [Pulumi](https://www.pulumi.com/): Infrastructure as code in general-purpose languages with strong agent workflows
- [Ansible](https://www.ansible.com/): Agentless automation for configuration and deployment tasks

### Laravel Cloud and Deployment Stack

#### First-Party Laravel Platforms

- [Laravel Cloud](https://laravel.com/cloud): Managed Laravel platform with deploy-from-git, autoscaling, and built-in app resources
	- [Cloud Preview Environments](https://cloud.laravel.com/docs/preview-environments): Ephemeral, production-like environments for reviewing pull requests safely
- [Laravel Forge](https://laravel.com/forge): Server management and deployment platform with root access and zero-downtime deploy workflows
	- [Forge API](https://forge.laravel.com/api-documentation): Programmatic interface for automating server provisioning and deployment actions
	- [Forge CLI](https://forge.laravel.com/docs/cli): Command-line interface for managing Forge resources from terminal workflows
- [Laravel Vapor](https://vapor.laravel.com/): Serverless Laravel deployments on AWS with autoscaling workers and managed cloud primitives
	- [Vapor Documentation](https://docs.vapor.build/): Official docs for serverless deployment workflows, configuration, and operations on Vapor

#### Laravel Deployment Alternatives

- [Ploi](https://ploi.io/): Server provisioning and deployment control panel often used as a Forge alternative
- [RunCloud](https://runcloud.io/): Cloud server control panel for PHP app deployment and operations
- [ServerPilot](https://serverpilot.io/): Managed control layer for deploying and maintaining PHP applications on cloud servers

## Platform Engineering Services

### Serverless SQL and Branching Databases

#### Developer-First SQL Platforms

- [PlanetScale](https://planetscale.com/): Vitess-powered serverless MySQL and Postgres platform with branching and safe schema workflows
- [Xata](https://xata.io/): Serverless Postgres platform focused on branch-based environments and developer workflows
- [CockroachDB](https://www.cockroachlabs.com/): Distributed SQL database built for high availability and geo-scale workloads

#### Hyperscaler Managed SQL

- [Amazon Aurora](https://aws.amazon.com/rds/aurora/): Cloud-native relational database with high throughput and managed scaling
- [Google Cloud SQL](https://cloud.google.com/sql): Managed relational database service for MySQL, PostgreSQL, and SQL Server
- [Azure Database for PostgreSQL](https://azure.microsoft.com/products/postgresql): Fully managed PostgreSQL service in Azure with enterprise controls

### Object Storage and Data Access

#### Developer and S3-Compatible Storage

- [Tigris Data](https://www.tigrisdata.com/): Globally distributed S3-compatible object storage designed for modern app and AI workloads
- [Cloudflare R2](https://www.cloudflare.com/products/r2/): S3-compatible object storage with zero egress fees for internet delivery paths
- [MinIO](https://min.io/): High-performance S3-compatible object storage for self-hosted and hybrid deployments

#### Hyperscaler Object Storage

- [Amazon S3](https://aws.amazon.com/s3/): Baseline object storage platform with broad ecosystem support and storage tiers
- [Google Cloud Storage](https://cloud.google.com/storage): Durable multi-class object storage on Google Cloud infrastructure
- [Azure Blob Storage](https://azure.microsoft.com/products/storage/blobs): Microsoft object storage for archival, analytics, and application assets
- [NetApp](https://www.netapp.com/): Enterprise data infrastructure platform for unified storage across on-prem and cloud environments

### CI, Build, and Runner Acceleration

#### Build Acceleration and Pipeline Engines

- [Blacksmith](https://www.blacksmith.sh/): GitHub Actions-compatible CI runner platform focused on faster builds and better cache hit rates
- [Depot](https://depot.dev/): Remote build execution and cache acceleration platform for Docker and CI pipelines
- [Dagger](https://dagger.io/): Programmable CI engine for reproducible pipelines defined in general-purpose languages

#### General-Purpose CI/CD Platforms

- [GitHub Actions](https://github.com/features/actions): Native GitHub automation for CI/CD, release workflows, and infrastructure jobs
- [CircleCI](https://circleci.com/): Managed CI/CD platform for parallel pipelines, test orchestration, and deployment automation
- [Buildkite](https://buildkite.com/): Pipeline platform that runs jobs on your own infrastructure with cloud control plane orchestration

### Backup and Disaster Recovery

#### Developer Workspace Backup

- [Cloudback](https://cloudback.it/): SaaS backup platform for developer tools and workspaces with bring-your-own-storage support

#### Enterprise Data Protection

- [Druva](https://www.druva.com/): Cloud-native data protection platform for endpoint, SaaS, and cloud workload backups
- [Rubrik](https://www.rubrik.com/): Data security and ransomware recovery platform with policy-driven backup workflows
- [Cohesity](https://www.cohesity.com/): Data resilience and backup platform for hybrid cloud environments
- [Commvault](https://www.commvault.com/): Enterprise backup and recovery suite for large multi-cloud estates
- [Veeam](https://www.veeam.com/): Enterprise backup and recovery platform for cloud, virtualized, and on-prem environments

### Programmable Code Storage and Access

#### Machine-First Git Infrastructure

- [Code.storage](https://code.storage/): Programmable Git infrastructure for machine-scale code access, indexing, and storage workflows
- [Gerrit](https://www.gerritcodereview.com/): Git-centric code review platform often used for large-scale gated contribution workflows

#### Hosted Git APIs and Repo Platforms

- [GitHub](https://github.com/): Hosted Git platform with APIs, webhooks, and ecosystem tooling for automation-heavy workflows
	- [GitHub Advanced Security](https://github.com/security/advanced-security): Enterprise security suite for code scanning, secret detection, and supply-chain controls
	- [GitHub CodeQL](https://codeql.github.com/): Semantic code analysis engine used for advanced static vulnerability detection
	- [GitHub Secret Scanning](https://docs.github.com/en/code-security/secret-scanning/about-secret-scanning): Built-in detector for leaked credentials and exposed secrets in repositories
	- [Dependabot](https://github.com/dependabot): Automated dependency update and vulnerability remediation tooling
- [Azure Repos](https://azure.microsoft.com/products/devops/repos): Managed private Git repositories integrated with Azure DevOps workflows
- [Bitbucket](https://bitbucket.org/): Git hosting platform with Jira integration and enterprise access controls
	- [Jira](https://www.atlassian.com/software/jira): Issue and project tracking platform deeply integrated with Bitbucket workflows
	- [Confluence](https://www.atlassian.com/software/confluence): Team knowledge base and documentation platform in the Atlassian suite
	- [Atlassian Rovo](https://www.atlassian.com/rovo): AI search and agent layer across Atlassian tools and engineering workflows

### Internal Developer Platforms and Portals

#### Developer Portals and Service Catalogs

- [Backstage](https://backstage.io/): Open platform framework for building internal developer portals and software catalogs
- [Port](https://www.port.io/): Internal developer portal with golden paths and self-service workflows for platform teams
- [Cortex](https://www.cortex.io/): Service catalog and engineering intelligence platform for ownership, standards, and scorecards
- [OpsLevel](https://www.opslevel.com/): Developer portal and service maturity tooling for improving operational excellence

#### Platform Orchestration and IDP Layers

- [Humanitec](https://humanitec.com/): Platform orchestrator that separates developer workflows from infrastructure complexity
- [Qovery](https://www.qovery.com/): Internal developer platform for self-service environments on top of Kubernetes and cloud providers
- [Kratix](https://www.kratix.io/): Open-source platform framework for defining reusable promises and developer self-service APIs
- [Akuity](https://akuity.io/): Enterprise GitOps platform built around Argo for app delivery and platform automation

### Platform Security and Policy

#### Security and Compliance Platforms

- [Aikido Security](https://www.aikido.dev/): Developer-first security platform for code, cloud, containers, and runtime risk visibility
- [JFrog Platform](https://jfrog.com/): End-to-end artifact management and software supply-chain platform for enterprise delivery pipelines
	- [JFrog Xray](https://jfrog.com/xray/): Artifact and dependency security scanner with contextual vulnerability and license analysis
	- [JFrog Curation](https://jfrog.com/curation/): Package control layer for allowlisting and blocking risky open-source dependencies
- [Snyk](https://snyk.io/): Developer security platform for dependency, code, container, and IaC vulnerability management
- [Semgrep](https://semgrep.dev/): Fast static analysis and code security scanning platform with customizable rules
- [Wiz](https://www.wiz.io/): Cloud security platform for risk graphing, posture management, and runtime exposure detection

#### Policy-as-Code and Guardrails

- [Open Policy Agent](https://www.openpolicyagent.org/): General-purpose policy engine for enforcing platform and infrastructure guardrails
- [Kyverno](https://kyverno.io/): Kubernetes-native policy engine for validating, mutating, and generating configuration resources
- [Checkov](https://www.checkov.io/): IaC and cloud configuration scanning tool for policy enforcement in CI/CD pipelines

## AI and LLM Engineering

### Local Models and Interfaces

#### Local LLM Runtime Stack

- [Ollama](https://ollama.com/): Run local LLMs
- [Open WebUI](https://openwebui.com/): Self-hosted ChatGPT-style UI
- [LM Studio](https://lmstudio.ai/): Desktop app for running and testing local language models

### Agent Runtime and Workspace Infrastructure

#### Agent Runtime and Sandbox Substrates

- [Mesa](https://mesa.dev/): Versioned filesystem and checkpoint runtime for parallel AI agent execution and reviewable workflows
- [E2B](https://e2b.dev/): Secure cloud sandboxes for running AI-generated code with isolation and lifecycle controls
- [Modal](https://modal.com/): Serverless compute platform tuned for Python, AI inference, and elastic job execution
- [Val Town](https://www.val.town/): JavaScript runtime for lightweight serverless workflows and AI-assisted automation scripts

#### Agent Observability and Evaluation

- [LangSmith](https://www.langchain.com/langsmith-platform): Agent development platform for tracing, evaluation, and production debugging

### Agent Frameworks and Orchestration

#### Python-Centric Agent Frameworks

- [LangChain](https://www.langchain.com/): LLM application framework
	- [LangSmith](https://smith.langchain.com/): Agent observability, evaluation, and debugging platform for LangChain applications
	- [LangGraph Platform](https://www.langchain.com/langgraph-platform): Production runtime and control plane for deploying stateful LangGraph agents
- [LangGraph](https://www.langchain.com/langgraph): Stateful agent orchestration framework for complex control flow
- [LlamaIndex](https://www.llamaindex.ai/): Framework for retrieval-augmented generation over private data
- [Pydantic AI](https://ai.pydantic.dev/): Typed Python framework for building production agent workflows

#### TypeScript Agent Frameworks

- [Vercel AI SDK](https://ai-sdk.dev/): TypeScript SDK for building AI features and agent interactions

### Serving, Routing, and Provider Abstraction

#### Inference Serving and Gateways

- [vLLM](https://vllm.ai/): High-performance LLM serving
- [LiteLLM](https://www.litellm.ai/): Unified gateway and SDK for multiple LLM providers

#### Multi-Provider Routing

- [OpenRouter](https://openrouter.ai/): Aggregated API access across many LLM vendors

## AI Coding Agents

### Terminal and IDE Coding Agents

#### Terminal-First Agentic Coding

##### Open-Source Terminal Agents

- [OpenCode](https://opencode.ai/): Open-source AI coding agent for terminal, desktop, and IDE workflows
- [Goose](https://github.com/aaif-goose/goose): Open-source native AI agent with desktop app, CLI, and API
- [Aider](https://aider.chat/): AI pair programmer optimized for git-based coding loops
- [OpenHands](https://www.openhands.dev/): Open-source platform and SDK for autonomous coding agents at scale

##### Commercial and Hosted Terminal Agents

- [Codex CLI](https://github.com/openai/codex): OpenAI coding agent that runs locally in your terminal
- [Codex Web](https://chatgpt.com/codex): Cloud-hosted OpenAI coding agent experience for delegated tasks
- [Amp](https://ampcode.com/): Frontier-focused coding agent CLI optimized for long-running agent sessions
- [Claude Code](https://claude.ai/code): Agentic coding workflow in the terminal

#### IDE-Native Agentic Coding

- [Continue](https://www.continue.dev/): Open-source coding agent and assistant inside IDEs
- [GitHub Copilot](https://github.com/features/copilot): AI coding assistant with chat, edits, and agent capabilities
- [Cursor Cloud Agents](https://cursor.com/agents): Agent runs and automations for multi-repo and no-repo workflows
- [Zed Agentic Editing](https://zed.dev/agentic): Native-speed agent panel and delegate/review coding workflow in Zed

### AI App Builders and Prototyping

#### Prompt-to-App Builders

- [Entire](https://entire.io/): AI app builder focused on generating and iterating production-style applications from prompts
- [v0](https://v0.app/): Prompt-to-app builder with templates, repo sync, and one-click deploy flows
- [Bolt.new](https://bolt.new/): Browser-based AI app generator with instant full-stack prototyping loops
- [Lovable](https://lovable.dev/): Prompt-driven app builder for quickly shipping product-grade UIs and workflows
- [Base44](https://base44.com/): AI-native app creation environment for building SaaS-style products from ideas

#### Browser IDE and Runtime Builders

- [Replit](https://replit.com/): Collaborative cloud IDE with AI-assisted coding and deploy-from-browser experience
- [StackBlitz](https://stackblitz.com/): Instant web development runtime with browser-native coding and AI tooling

#### Visual Design-to-Production Builders

- [Builder.io](https://www.builder.io/): Visual development platform adding AI-assisted app and UI generation workflows
- [Framer AI](https://www.framer.com/ai): AI-assisted website builder integrated into Framer's design-to-publish flow

### Harnesses and Agent Workspaces

#### Agent Workspaces and Harnesses

- [SoloTerm](https://soloterm.ai/): AI harness for terminal-centric development and automation workflows
- [T3 Chat](https://t3.chat/): Theo's AI workspace/chat product popular with dev and creator communities
- [Pi](https://pi.dev/): Agent runtime platform that inspired modern plugin-based coding-agent workflows

## APIs and Testing

### API Clients and Request Tooling

#### Interactive API Clients

- [Hoppscotch](https://hoppscotch.io/): Lightweight API client for testing REST, GraphQL, and websockets
- [Bruno](https://www.usebruno.com/): Local-file-based API client built for git-friendly collaboration
- [Postman](https://www.postman.com/): Full-featured API platform for testing and documentation
- [Insomnia](https://github.com/Kong/insomnia): Popular API client with local and team-based request workflows
- [HTTPie](https://httpie.io/): Human-friendly command-line HTTP client

### Test Frameworks and Automation

#### Automated Testing Stack

- [pytest](https://pytest.org/): Python testing framework with simple, scalable test patterns
- [Playwright](https://playwright.dev/): End-to-end browser automation and testing framework
- [Vitest](https://vitest.dev/): Vite-native unit test runner for JavaScript and TypeScript

## Monitoring and Observability

### Metrics, Logs, and Tracing Foundations

#### Telemetry Foundations

- [Grafana](https://grafana.com/): Dashboard and visualization platform for metrics and logs
- [Prometheus](https://prometheus.io/): Time-series monitoring system with pull-based metrics
- [OpenTelemetry](https://opentelemetry.io/): Open standard for traces, metrics, and telemetry data
- [Better Stack](https://betterstack.com/): Unified logs, uptime, and incident monitoring platform

### Error Tracking and APM

#### Application Monitoring Platforms

- [Sentry](https://sentry.io/): Error tracking and performance monitoring for applications
	- [Sentry Performance](https://sentry.io/for/performance/): Distributed tracing and transaction performance analysis across services
	- [Sentry Session Replay](https://sentry.io/product/session-replay/): Browser session replay for debugging user-impacting issues
	- [Sentry Profiling](https://sentry.io/product/profiling/): Continuous profiling for identifying CPU hotspots and slow code paths
- [Datadog](https://www.datadoghq.com/): Widely used observability platform with strong AI/LLM telemetry coverage
	- [Datadog APM](https://www.datadoghq.com/product/apm/): Application performance monitoring with traces, flame graphs, and service maps
	- [Datadog Log Management](https://www.datadoghq.com/product/log-management/): Centralized log ingestion, indexing, and analytics workflows
	- [Datadog LLM Observability](https://www.datadoghq.com/product/llm-observability/): Monitoring for prompts, token usage, latency, and model reliability
- [Bugsnag](https://www.bugsnag.com/): Stability monitoring and crash analytics platform for web and backend systems
- [Honeybadger](https://www.honeybadger.io/): Error, uptime, and check-in monitoring for teams that want simpler APM workflows
- [New Relic](https://newrelic.com/): Full-stack observability platform for distributed systems and cloud workloads

### Laravel-Centric Monitoring

#### Laravel-Native Observability

- [Laravel Nightwatch](https://nightwatch.laravel.com/): First-party Laravel monitoring with event timelines, smart alerts, and deep framework visibility

## Security and Secrets

### Secrets and Vault Workflows

#### Secret Management Tools

- [1Password CLI](https://developer.1password.com/docs/cli/): Command-line secrets and vault access for automation
- [Bitwarden](https://bitwarden.com/): Password manager with self-host and cloud deployment options
- [age](https://age-encryption.org/): Simple modern file encryption tool
- [sops](https://getsops.io/): Encrypted file management for infrastructure and application secrets

### Scanning and Supply-Chain Hygiene

#### Security Scanners

- [Trivy](https://trivy.dev/): Security scanner for containers, dependencies, and IaC misconfigurations
- [Gitleaks](https://github.com/gitleaks/gitleaks): High-usage secret scanning tool for repos, CI, and pre-commit hooks

## Git and Collaboration

### Git Interfaces and Version Control UX

#### Git Workflow Interfaces

- [GitHub CLI](https://cli.github.com/): Terminal interface for issues, PRs, and repository workflows
- [lazygit](https://github.com/jesseduffield/lazygit): Terminal UI for faster and safer daily git operations
- [Jujutsu (jj)](https://docs.jj-vcs.dev/latest/): Modern VCS with Git interoperability and growing power-user adoption

### Commit and Quality Workflows

#### Commit Guardrails

- [pre-commit](https://pre-commit.com/): Framework for running checks before each commit
- [Conventional Commits](https://www.conventionalcommits.org/): Standard commit message format for changelog automation

## Git Forges and Decentralized Collaboration

### Self-Hosted and Sovereign Git Forges

#### Mainstream Self-Hosted Forges

- [GitLab](https://about.gitlab.com/): Full-stack source code and DevOps platform with strong self-managed deployment support
	- [GitLab Duo](https://about.gitlab.com/gitlab-duo/): AI capabilities for code suggestions, chat, and workflow automation in GitLab
	- [GitLab CI/CD](https://about.gitlab.com/solutions/continuous-integration/): Built-in pipeline engine for testing, building, and deployment automation
	- [GitLab Application Security](https://about.gitlab.com/solutions/application-security/): Integrated DevSecOps scanning for code, dependencies, and containers
- [Gitea](https://about.gitea.com/): Lightweight self-hosted Git service with low resource usage and easy administration
- [Forgejo](https://forgejo.org/): Community-governed self-hosted Git forge focused on open governance and long-term sustainability
- [OneDev](https://onedev.io/): Self-hosted Git platform with integrated CI/CD and issue tracking workflows

#### Lightweight and Niche Forges

- [Gogs](https://gogs.io/): Minimal Git service designed for simple self-hosted deployments and low operational overhead
- [SourceHut](https://sr.ht/): Minimalist developer platform with hosted and distributed workflows for email-driven collaboration
- [Phorge](https://we.phorge.it/): Community-maintained code collaboration suite continuing the Phabricator model

### Decentralized Code Collaboration

#### Federated and Peer-to-Peer Collaboration

- [Tangled](https://tangled.org/): Federated social coding platform built on AT Protocol with stacked change workflows
- [Radicle](https://radicle.dev/): Peer-to-peer code collaboration network using Git and cryptographic identity primitives

#### Distributed Version Control Systems

- [Fossil SCM](https://www.fossil-scm.org/): Distributed version control system with integrated issue tracking and wiki capabilities
- [Pijul](https://pijul.org/): Distributed patch-based version control system focused on conflict reduction and correctness
- [Mercurial](https://www.mercurial-scm.org/): Mature distributed version control system with strong performance on large repositories
- [Darcs](https://darcs.net/): Patch-oriented distributed VCS known for flexible history operations and advanced merging semantics

## Self-hosting and Homelab

### Server Platforms and Virtualization

#### Self-Hosted Infrastructure Base

- [CasaOS](https://casaos.io/): Friendly home server platform for self-hosted apps
- [Umbrel](https://umbrel.com/): Personal server OS for running home and developer services
- [Proxmox](https://www.proxmox.com/en/): Open-source virtualization platform with broad homelab and enterprise adoption
- [TrueNAS](https://www.truenas.com/): Storage-focused NAS operating system for homelab environments

### Networking and Private Access

#### Private Network Overlay

- [Tailscale](https://tailscale.com/): Zero-config mesh VPN based on WireGuard
- [Headscale](https://headscale.net/): Open-source self-hosted control plane for Tailscale networks

### Reverse Proxies and Edge Routing

#### Traffic Routing Layer

- [Caddy](https://caddyserver.com/): Web server with automatic HTTPS and straightforward configuration
- [Traefik](https://traefik.io/): Dynamic reverse proxy for containers and microservices

## Performance and Benchmarking

### Load and Traffic Testing

#### Load Generation Tools

- [wrk](https://github.com/wg/wrk): High-throughput HTTP benchmarking tool for load testing
- [k6](https://k6.io/): Developer-focused load testing framework with scripted scenarios
- [Locust](https://locust.io/): Python-based distributed user load testing framework

### Tracing and Performance Analysis

#### Performance Tracing

- [Perfetto](https://perfetto.dev/): System tracing and performance analysis platform

## Awesome Lists

### Ecosystem Curations

#### General Curated Lists

- [Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted): Curated list of free and open-source self-hostable services
- [Awesome Python](https://github.com/vinta/awesome-python): Curated collection of Python libraries, frameworks, and tools
- [Awesome Neovim](https://github.com/rockerBOO/awesome-neovim): Community-maintained list of Neovim plugins and resources

### Tooling Curations

#### Developer Tool Discovery Lists

- [Awesome CLI Apps](https://github.com/agarrharr/awesome-cli-apps): Curated set of useful command-line tools and applications
- [Awesome DevTools](https://github.com/moimikey/awesome-devtools): Curated list of productivity tools for software developers
