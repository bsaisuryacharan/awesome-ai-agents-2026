<div align="center">

![](img/ARUNAGIRINATHAN-K.png)

# Awesome AI Agents 2026

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/ARUNAGIRINATHAN-K/awesome-ai-agents?style=social)](https://github.com/ARUNAGIRINATHAN-K/awesome-ai-agents/stargazers)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Last Commit](https://img.shields.io/github/last-commit/ARUNAGIRINATHAN-K/awesome-ai-agents)](https://github.com/ARUNAGIRINATHAN-K/awesome-ai-agents/commits/main)
[![Tools Listed](https://img.shields.io/badge/tools_listed-173%2B-blue?style=flat-square)]()
[![License: CC0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg?style=flat-square)](LICENSE)

*The most comprehensive, structured guide to AI agent frameworks, tools, and resources.*  
*Updated weekly. Compared side-by-side. Built for developers who ship.*

**[Explore the Stack](#contents) • [Read the Docs](#contributing) • [Submit a Tool](https://github.com/ARUNAGIRINATHAN-K/awesome-ai-agents/issues/new)**

</div>

## Contents

- [Orchestration Frameworks](#orchestration-frameworks)
- [Coding Agents](#coding-agents)
- [Memory and Context](#memory-and-context)
- [Multi-Agent Systems](#multi-agent-systems)
- [Agent Communication Protocols](#agent-communication-protocols)
- [Browser and Computer Use Agents](#browser-and-computer-use-agents)
- [Agent Tooling and Infrastructure](#agent-tooling-and-infrastructure)
- [Low and No-Code Builders](#low-and-no-code-builders)
- [Voice and Multimodal Agents](#voice-and-multimodal-agents)
- [Safety Guardrails and Observability](#safety-guardrails-and-observability)
- [Agent Interfaces and UIs](#agent-interfaces-and-uis)
- [Agent Deployment and Hosting](#agent-deployment-and-hosting)
- [Agent Evaluation and Benchmarks](#agent-evaluation-and-benchmarks)
- [Learning Resources](#learning-resources)
- [Agent Communication](#agent-communication)
- [Data Pipeline and Workflow](#data-pipeline-and-workflow)
- [Secure Execution Environments](#secure-execution-environments)
- [Changelog](#changelog)
- [Star History](#star-history)

## Orchestration Frameworks

- [Agency Swarm](https://github.com/VRSEN/agency-swarm) - Orchestrates multi-agent systems built on the OpenAI Assistants API with role-based collaboration (🏷️ `Python` `OpenAI` `SDK`).
- [Agno](https://github.com/agno-agi/agno) - Multi-agent framework with a runtime and control plane for managing agent deployments at scale (`Python` `FastAPI` `Cloud`) (🏷️ `Python` `FastAPI` `Cloud`).
- [AutoGen](https://github.com/microsoft/autogen) - Event-driven multi-agent framework merged with Semantic Kernel for production workflows (🏷️ `Python` `Semantic Kernel` `SDK`).
- [CopilotKit](https://github.com/CopilotKit/CopilotKit) - The open-source AI copilot platform for React, allowing developers to embed custom AI agents directly into their applications (🏷️ `TypeScript` `React` `SDK`).
- [CrewAI](https://github.com/crewAIInc/crewAI) - Role-playing agent orchestration for collaborative agent teams (🏷️ `Python` `LangChain` `SDK`).
- [DSPy](https://github.com/stanfordnlp/dspy) - Programmatically optimizes LLM prompts and chains using machine learning instead of manual prompt engineering (🏷️ `Python` `Stanford` `SDK`).
- [Google ADK](https://github.com/google/adk-python) - Modular agent dev kit integrating Gemini and Vertex AI natively (🏷️ `Python` `Vertex AI` `SDK`).
- [Haystack](https://github.com/deepset-ai/haystack) - Production-ready AI orchestration framework focused on building customizable LLM applications and RAG pipelines (🏷️ `Python` `RAG` `SDK`).
- [LangGraph](https://github.com/langchain-ai/langgraph) - Enterprise framework for stateful, graph-based agent workflows (🏷️ `Python` `LangChain` `SDK`).
- [Letta](https://github.com/letta-ai/letta) - Formerly MemGPT. Stateful agents with built-in long-term memory and a REST API server (🏷️ `Python` `REST` `SDK`).
- [LlamaIndex](https://github.com/run-llama/llama_index) - The leading framework for connecting LLMs to your data, with powerful indexing and retrieval capabilities (🏷️ `Python` `RAG` `SDK`).
- [Mastra](https://github.com/mastra-ai/mastra) - Opinionated TypeScript framework with RAG, observability, and MCP support built in (🏷️ `TypeScript` `Next.js` `SDK`).
- [Modus](https://github.com/hypermodeinc/modus) - Serverless framework for high-throughput agent workloads with minimal cold starts (🏷️ `WebAssembly` `Hypermode` `Serverless`).
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - Lightweight multi-agent SDK with tracing and guardrails from OpenAI (🏷️ `Python` `OpenAI` `SDK`).
- [Open-AutoGLM](https://github.com/zai-org/Open-AutoGLM) - Open-source phone agent model and framework for building mobile device automation agents (🏷️ `Python` `Mobile` `SDK`).
- [PraisonAI](https://github.com/MervinPraison/PraisonAI) - Production multi-agent framework with self-reflection, MCP integration, and workflow automation (🏷️ `Python` `Multi-Agent` `CLI`).
- [PydanticAI](https://github.com/pydantic/pydantic-ai) - Type-safe agent framework from the Pydantic team with a FastAPI-style developer experience (🏷️ `Python` `Pydantic` `SDK`).
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Microsoft enterprise SDK for Python, C#, and Java with modular plugins, memory, and goal planning (🏷️ `C#` `Microsoft` `SDK`).
- [Smolagents](https://github.com/huggingface/smolagents) - Hugging Face code-first framework where agents write and execute Python instead of JSON tool calls (🏷️ `Python` `Hugging Face` `SDK`).
- [Strands Agents SDK](https://github.com/strands-agents/sdk-python) - AWS model-driven agent SDK with native Bedrock integration (🏷️ `Python` `AWS Bedrock` `SDK`).
- [Vercel AI SDK](https://github.com/vercel/ai) - Streaming-first primitives for AI UIs with React Server Components and edge runtime support (🏷️ `TypeScript` `Next.js` `SDK`).
- [VoltAgent](https://github.com/voltagent/voltagent) - TypeScript agent framework with built-in observability and a self-improving context engine (🏷️ `TypeScript` `React` `SDK`).

## Coding Agents

- [Aider](https://github.com/Aider-AI/aider) - Terminal-first pair programmer that edits code in local repos, preserves Git history, and supports multi-file changes (🏷️ `Python` `CLI` `Local`).
- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) - Mature autonomous agent platform with Forge framework and public benchmarks for evaluating agent capabilities (🏷️ `Python` `Forge` `CLI`).
- [Claude Code](https://github.com/anthropics/claude-code) - Terminal-first agentic coding tool with multi-file edits, test running, and Git operations baked in (🏷️ `TypeScript` `CLI` `Local`).
- [Cline](https://github.com/cline/cline) - Autonomous coding agent in your IDE that creates/edits files, runs commands, and uses the browser with permission-gated steps (🏷️ `TypeScript` `VS Code` `IDE`).
- [Codex CLI](https://github.com/openai/codex) - OpenAI's lightweight, open-source terminal coding agent with fast execution and strong benchmark scores (🏷️ `Python` `CLI` `Local`).
- [Codex-CLI](https://github.com/microsoft/Codex-CLI) - CLI tool that turns natural language commands into Bash, ZShell, and PowerShell equivalents (🏷️ `C#` `CLI` `Local`).
- [Continue](https://github.com/continuedev/continue) - Source-controlled AI checks enforceable in CI, powered by the open-source Continue CLI (🏷️ `TypeScript` `VS Code` `IDE`).
- [Cursor](https://cursor.com) - AI-native IDE (VS Code fork) with deep codebase awareness, multi-file refactoring, and agentic workflows (🏷️ `TypeScript` `Electron` `Desktop`).
- [Devika](https://github.com/stitionai/devika) - Open-source AI software engineer that understands high-level instructions and writes full-featured code autonomously (🏷️ `Python` `Docker` `Web`).
- [Devin](https://devin.ai) - Fully autonomous AI software engineer that plans, codes, tests, and deploys in a cloud sandbox (🏷️ `Cloud` `Web` `SaaS`).
- [gemini-cli](https://github.com/google-gemini/gemini-cli) - Open-source AI agent that brings the power of Gemini directly into your terminal (🏷️ `Go` `CLI` `Local`).
- [Goose](https://github.com/aaif-goose/goose) - Open-source extensible AI agent that goes beyond code suggestions, installs, executes, edits, and tests with any LLM (🏷️ `Rust` `CLI` `Local`).
- [Open Interpreter](https://github.com/openinterpreter/open-interpreter) - Execute code locally via natural-language model instructions with a ChatGPT-like interface (🏷️ `Python` `CLI` `Local`).
- [opencode](https://github.com/anomalyco/opencode) - Open-source coding agent available as a desktop application with a visual interface (🏷️ `TypeScript` `Electron` `Desktop`).
- [OpenHands](https://github.com/OpenHands/OpenHands) - AI-driven development platform that writes, tests, and deploys code autonomously (🏷️ `Python` `Docker` `Web`).
- [SWE-agent](https://github.com/SWE-agent/SWE-agent) - Takes a GitHub issue and tries to automatically fix it. Also used for cybersecurity and competitive coding (🏷️ `Python` `Docker` `CLI`).
- [TaskWeaver](https://github.com/microsoft/TaskWeaver) - A code-first agent framework from Microsoft for seamlessly planning and executing data analytics tasks (🏷️ `Python` `Jupyter` `CLI`).
- [Windsurf](https://windsurf.com) - AI-native IDE with Cascade agent for multi-step autonomous tasks and team workflows (🏷️ `TypeScript` `Electron` `Desktop`).

## Memory and Context

- [Acontext](https://github.com/memodb-io/Acontext) - Manages agent skills and long-term memory as a layered data structure for persistent context (🏷️ `Python` `SDK` `Local`).
- [Chroma](https://github.com/chroma-core/chroma) - Lightweight, embeddable vector store for building memory-augmented AI agents with fast semantic retrieval (🏷️ `Python` `TypeScript` `SDK`).
- [cognee](https://github.com/topoteretes/cognee) - Knowledge engine for AI agent memory, set up in 6 lines of code with graph-based knowledge extraction (🏷️ `Python` `Neo4j` `SDK`).
- [Cortex Memory](https://github.com/prem-research/cortex) - Full-stack solution for agent memory covering extraction, vector search, and optimization (🏷️ `Python` `Vector DB` `SDK`).
- [graphiti](https://github.com/getzep/graphiti) - Build real-time knowledge graphs for AI agents with automatic entity extraction and linking (🏷️ `Python` `Knowledge Graph` `SDK`).
- [LanceDB](https://github.com/lancedb/lancedb) - Serverless vector search database embedded directly in the agent process with no infrastructure needed (🏷️ `Rust` `Python` `SDK`).
- [Langmem](https://github.com/langchain-ai/langmem) - Helps agents learn and adapt from their interactions over time with persistent memory (🏷️ `Python` `LangChain` `SDK`).
- [Mem0](https://github.com/mem0ai/mem0) - Memory layer for AI applications with long-term, short-term, and semantic memory extraction (🏷️ `Python` `Vector` `Cloud`).
- [Memvid](https://github.com/memvid/memvid) - Replace complex RAG pipelines with a serverless, single-file memory layer for instant retrieval (🏷️ `Python` `Multimodal` `SDK`).
- [Milvus](https://github.com/milvus-io/milvus) - Scales vector search to billions of embeddings for large-scale agent knowledge bases (🏷️ `Go` `Python` `Platform`).
- [Motorhead](https://github.com/getmetal/motorhead) - Manages conversation context windows for agents with automatic background summarization (🏷️ `Rust` `Python` `SDK`).
- [Qdrant](https://github.com/qdrant/qdrant) - High-performance vector similarity search engine with rich payload filtering for agent memory (🏷️ `Rust` `Python` `SDK`).
- [SimpleMem](https://github.com/aiming-lab/SimpleMem) - Efficient lifelong memory for LLM agents supporting both text and multimodal inputs (🏷️ `Python` `SDK` `Local`).
- [Supermemory](https://github.com/supermemoryai/supermemory) - Extremely fast and scalable memory engine and API designed for the AI era (🏷️ `TypeScript` `Vector DB` `Web`).
- [Weaviate](https://github.com/weaviate/weaviate) - Stores and searches vector embeddings with hybrid keyword and semantic retrieval for agent knowledge (🏷️ `Go` `Python` `Platform`).
- [Zep](https://github.com/getzep/zep) - Enriches agent long-term memory with automatic summarization, entity extraction, and search (🏷️ `Python` `TypeScript` `SDK`).

## Multi-Agent Systems

- [AgentVerse](https://github.com/OpenBMB/AgentVerse) - Framework for building custom multi-agent environments to accomplish collaborative tasks (🏷️ `Python` `Benchmark` `SDK`).
- [EvoAgentX](https://github.com/EvoAgentX/EvoAgentX) - Evaluates and evolves agentic workflows over time using automatic optimization (🏷️ `Python` `Optimization` `SDK`).
- [Hivemoot](https://github.com/hivemoot/hivemoot) - Autonomous agent teams that collaboratively build software on GitHub (🏷️ `Python` `GitHub` `SDK`).
- [MetaGPT](https://github.com/FoundationAgents/MetaGPT) - Simulates a full software company workflow from requirements to PRs using role-playing agents (🏷️ `Python` `Role-Playing` `SDK`).
- [Swarm](https://github.com/openai/swarm) - Lightweight framework for agent handoffs, context variables, and function calling patterns from OpenAI (🏷️ `Python` `OpenAI` `SDK`).
- [Swarms Framework](https://github.com/kyegomez/swarms) - Multi-agent orchestration for production use cases with scalability and reliability at its core (🏷️ `Python` `Production` `SDK`).


## Agent Communication Protocols

The protocol layer that enables agents to discover tools, communicate with each other, and interoperate across ecosystems.

| Protocol | Purpose             | Creator   | Status   |
| -------- | ------------------- | --------- | -------- |
| MCP      | Agent-to-tool       | Anthropic | Standard |
| A2A      | Agent-to-agent      | Google    | Growing  |
| ACP      | Agent communication | IBM/BeeAI | Early    |

### MCP (Model Context Protocol)

- [Arcade AI](https://github.com/ArcadeAI/arcade-mcp) - Tool-use platform with authentication, authorization, and logging for agent-tool interactions (🏷️ `Python` `Cloud` `API`).
- [Composio](https://github.com/ComposioHQ/composio) - Integration platform with 250+ pre-built tool connectors for AI agents and LLMs (🏷️ `TypeScript` `Cloud` `API`).
- [Docker MCP](https://github.com/docker/docker-mcp) - Docker's MCP gateway CLI plugin for running MCP servers in isolated containers (🏷️ `Go` `Docker` `CLI`).
- [MCP Registry](https://github.com/modelcontextprotocol) - Official Model Context Protocol specification and server implementations for standardized tool access (🏷️ `JSON` `Standard` `Registry`).
- [Toolhouse](https://toolhouse.ai) - Cloud-hosted tool infrastructure for agents with optimized execution and low-latency access (🏷️ `Python` `Cloud` `API`).
- [Zapier MCP Server](https://zapier.com/mcp) - Connect agents to 7,000+ app integrations via MCP, powered by Zapier's automation platform (🏷️ `Cloud` `Zapier` `API`).

### A2A (Agent-to-Agent Protocol)

- [A2A Protocol](https://github.com/google/A2A) - Google's open protocol enabling AI agents to communicate, collaborate, and delegate tasks across frameworks (🏷️ `Protobuf` `Standard` `RPC`).

## Browser and Computer Use Agents

- [AgentQL](https://github.com/tinyfish-io/agentql) - AI-powered web scraping and automation with a semantic query language for page elements (🏷️ `Python` `Playwright` `SDK`).
- [Browser Use](https://github.com/browser-use/browser-use) - Open-source framework to let LLMs navigate and interact with any website programmatically (🏷️ `Python` `Playwright` `SDK`).
- [LaVague](https://github.com/lavague-ai/LaVague) - Large Action Model framework to turn natural language instructions into browser automation (🏷️ `Python` `Selenium` `SDK`).
- [Skyvern](https://github.com/Skyvern-AI/skyvern) - Automate browser-based workflows with computer vision and LLMs, no brittle selectors needed (🏷️ `Python` `Playwright` `Cloud`).
- [Stagehand](https://github.com/browserbase/stagehand) - AI web browsing framework built on Playwright with natural-language selectors and actions (🏷️ `TypeScript` `Playwright` `SDK`).

## Agent Tooling and Infrastructure

Sandboxes, web scrapers, browser automation, and networking layers that agents depend on.

- [AgentDock](https://github.com/agentdock/agentdock) - Framework for building and deploying production-ready AI agents with composable node architecture (🏷️ `Python` `Docker` `Platform`).
- [Crawl4AI](https://github.com/unclecode/crawl4ai) - Extracts structured data from web pages using LLM-friendly output formats optimized for agent ingestion (🏷️ `Python` `Playwright` `SDK`).
- [Docling](https://github.com/docling-project/docling) - Parses PDFs, DOCX, and slides into structured text with deep layout understanding for document agents (🏷️ `Python` `PDF` `SDK`).
- [E2B](https://github.com/e2b-dev/e2b) - Cloud sandboxes for AI agents to run code securely in isolated environments (🏷️ `TypeScript` `Cloud` `Sandbox`).
- [Engram](https://github.com/kwstx/engram_translator) - Universal bridge for multi-protocol AI agent systems with automated semantic mapping (🏷️ `Python` `Networking` `SDK`).
- [Firecrawl](https://github.com/firecrawl/firecrawl) - Web scraping API built for LLMs that converts websites to clean, structured markdown (🏷️ `TypeScript` `Cloud` `API`).
- [Jina Reader](https://github.com/jina-ai/reader) - Converts any URL to LLM-ready clean text via a simple API prefix for agent ingestion (🏷️ `TypeScript` `Cloud` `API`).
- [LlamaParse](https://github.com/run-llama/llama_cloud_services) - GenAI-native document parser designed to extract complex tables and layouts for RAG pipelines (🏷️ `Python` `Cloud` `API`).
- [Marker](https://github.com/datalab-to/marker) - Converts PDF documents to markdown with high accuracy for tables, equations, and figures (🏷️ `Python` `PDF` `CLI`).
- [Notte](https://github.com/nottelabs/notte) - Browser automation engine optimized for production AI pipelines (🏷️ `Python` `Browser` `SDK`).
- [Pilot Protocol](https://github.com/TeoSlayer/pilotprotocol) - Networking stack for distributed agent systems with encrypted tunnels (🏷️ `Go` `Networking` `SDK`).
- [Playwright](https://github.com/microsoft/playwright) - Automates Chromium, Firefox, and WebKit browsers with a single cross-language API for agent-driven testing (🏷️ `TypeScript` `Python` `SDK`).
- [ScrapeGraphAI](https://github.com/ScrapeGraphAI/Scrapegraph-ai) - Python web-scraping library that uses LLMs to build intelligent scraping pipelines from natural-language instructions (🏷️ `Python` `LangChain` `SDK`).
- [Surya](https://github.com/datalab-to/surya) - Runs OCR and layout detection on documents in 90+ languages for multilingual document agents (🏷️ `Python` `PDF` `CLI`).
- [Tavily](https://github.com/tavily-ai/tavily-python) - Search API purpose-built for LLM agents providing real-time, accurate web data with source citations (🏷️ `Python` `Cloud` `API`).
- [Unstructured](https://github.com/Unstructured-IO/unstructured) - Ingests and preprocesses documents across 25+ file types for downstream LLM and agent pipelines (🏷️ `Python` `Pipeline` `SDK`).

## Low and No-Code Builders

- [AgentGPT](https://github.com/reworkd/AgentGPT) - Deploy AI agents in the browser with zero local setup required (🏷️ `TypeScript` `Next.js` `Web`).
- [Dify](https://github.com/langgenius/dify) - Open-source LLM app development platform with visual workflow builder and RAG orchestration (🏷️ `Python` `FastAPI` `Web`).
- [Flowise](https://github.com/FlowiseAI/Flowise) - Open-source drag-and-drop UI to build customized LLM flows, RAG pipelines, and agent systems (🏷️ `TypeScript` `React` `Web`).
- [Langflow](https://github.com/langflow-ai/langflow) - Visual drag-and-drop builder for LLM workflows, RAG agents, and multi-step pipelines (🏷️ `Python` `FastAPI` `Web`).
- [Wordware](https://wordware.ai) - Web-hosted IDE where domain experts collaborate with AI engineers to build agent workflows (🏷️ `TypeScript` `Next.js` `Web`).

## Voice and Multimodal Agents

- [Agentset](https://github.com/agentset-ai/agentset) - Production RAG platform with reasoning, hybrid search, and full multimodal support (🏷️ `Python` `Multimodal` `Platform`).
- [LiveKit Agents](https://github.com/livekit/agents) - Framework for building real-time, multimodal AI agents with voice, video, and data channels (🏷️ `Python` `LiveKit` `SDK`).
- [Pipecat](https://github.com/pipecat-ai/pipecat) - Open-source framework for voice and multimodal conversational AI with streaming pipelines (🏷️ `Python` `WebRTC` `SDK`).
- [Vapi](https://github.com/VapiAI/server-sdk-python) - Platform for building voice AI agents with low-latency speech-to-speech capabilities (🏷️ `Python` `Cloud` `API`).

## Safety Guardrails and Observability

- [Agent OS](https://github.com/buildermethods/agent-os) - Kernel architecture for governing autonomous AI agents with policy enforcement (🏷️ `Python` `Policy` `SDK`).
- [AgentDoG](https://github.com/AI45Lab/AgentDoG) - Diagnostic guardrails that analyze full agent execution trajectories to detect instruction hijacking and tool misuse (🏷️ `Python` `Diagnostics` `SDK`).
- [AgentGuard](https://github.com/cyberark/agent-guard) - Runtime observability and guardrails for AI agents with loop detection and anomaly alerts (🏷️ `Python` `CyberArk` `SDK`).
- [APort Agent Guardrails](https://github.com/aporthq/aport-agent-guardrails) - Pre-action authorization plugin for agent frameworks with policy-based access control (🏷️ `Python` `Authorization` `SDK`).
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) - Open-source observability platform built on OpenTelemetry for tracing, evaluating, and debugging AI agents (🏷️ `Python` `OpenTelemetry` `Platform`).
- [DriftGuard](https://github.com/sujal-maheshwari2004/DriftGuard) - Semantic memory guardrails using causal graphs to prevent agents from repeating past failures (🏷️ `Python` `Memory` `SDK`).
- [Laminar](https://github.com/lmnr-ai/lmnr) - Open-source observability and analytics platform purpose-built for the full lifecycle of AI agents (🏷️ `Rust` `Observability` `Platform`).
- [Langfuse](https://github.com/langfuse/langfuse) - Open-source LLM observability platform for tracing, prompt versioning, and LLM-as-a-judge evaluations (🏷️ `TypeScript` `Next.js` `Platform`).
- [Logfire](https://github.com/pydantic/logfire) - Python-native observability from the Pydantic team with deep integration for high-performance agent monitoring (🏷️ `Python` `Pydantic` `Platform`).
- [Orchard Kit](https://github.com/OrchardHarmonics/orchard-kit) - Modules for agent runtime security, self-audit trails, and collective cognition patterns (🏷️ `Python` `Security` `SDK`).

## Agent Interfaces and UIs

Frontend workspaces and chat interfaces with built-in agent plugins and tool-use capabilities.

- [LobeChat](https://github.com/lobehub/lobe-chat) - Modern, open-source AI chat framework with a massive plugin ecosystem for autonomous agent capabilities (🏷️ `TypeScript` `Next.js` `Web`).
- [OpenWebUI](https://github.com/open-webui/open-webui) - Extensible local AI interface with built-in RAG, tool use, and support for multi-agent workflows (🏷️ `TypeScript` `Svelte` `Web`).

## Agent Deployment and Hosting

- [AWS Bedrock AgentCore](https://github.com/awslabs/agentcore-samples) - Managed AWS infrastructure for Bedrock-based agents with compliance, scaling, and monitoring built in (🏷️ `TypeScript` `AWS` `Platform`).
- [Modal](https://github.com/modal-labs/modal-client) - Serverless GPU compute purpose-built for AI workloads with fast cold starts and Python-native deployment (🏷️ `Python` `Serverless` `Cloud`).
- [Northflank](https://northflank.com/) - Full-stack platform with GPU orchestration, Git-based CI/CD, and bring-your-own-cloud support (🏷️ `Kubernetes` `Cloud` `Platform`).
- [Railway](https://railway.com/) - One-click deploy from GitHub with persistent volumes and databases for stateful agent deployments (🏷️ `Nix` `Cloud` `Platform`).
- [Trigger.dev](https://github.com/triggerdotdev/trigger.dev) - Background job platform with cron, webhook, and event triggers purpose-built for long-running agent tasks (🏷️ `TypeScript` `Serverless` `Cloud`).

## Agent Evaluation and Benchmarks

- [AgentBench](https://github.com/THUDM/AgentBench) - Comprehensive benchmark for evaluating LLMs as agents across 8 distinct environments (🏷️ `Python` `Benchmark` `SDK`).
- [GAIA Benchmark](https://huggingface.co/papers/2311.12983) - Benchmark for General AI Assistants measuring real-world reasoning and tool use (🏷️ `JSON` `Benchmark` `Dataset`).
- [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) - Framework for evaluating large language models with composable tasks and scoring (🏷️ `Python` `Evaluation` `SDK`).
- [SWE-bench](https://github.com/SWE-bench/SWE-bench) - Benchmark for evaluating LLMs on real-world software engineering tasks from GitHub issues (🏷️ `Python` `Docker` `Benchmark`).

## Learning Resources

- [AI Agents in LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/) - Short course on building production agents with LangGraph by Andrew Ng's platform (🏷️ `Course` `DeepLearning.ai` `Web`).
- [AgentBench: Evaluating LLMs as Agents](https://arxiv.org/abs/2309.07864) - The benchmark paper for evaluating LLMs as agents across diverse environments (🏷️ `Paper` `ArXiv` `PDF`).
- [Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents) - Anthropic's guide on agent design patterns, evaluation strategies, and production best practices (🏷️ `Guide` `Anthropic` `Web`).
- [LATS: Language Agent Tree Search](https://github.com/lapisrocks/LanguageAgentTreeSearch) - Combines Monte Carlo tree search with LLM reasoning for complex multi-step planning tasks (🏷️ `Paper` `Python` `Research`).
- [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) - Deep breakdown of LLM-powered agent components: planning, memory, and tool use (🏷️ `Blog` `Weng` `Web`).
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) - Community-maintained guide covering prompt engineering techniques and agent strategies (🏷️ `Guide` `DAIR` `Web`).
- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) - The foundational paper behind the ReAct prompting pattern used in most agent frameworks (🏷️ `Paper` `ArXiv` `PDF`).
- [Reflexion](https://github.com/noahshinn/reflexion) - Research framework letting agents learn from past mistakes via iterative verbal self-reflection loops (🏷️ `Paper` `Python` `Research`).
- [Tree of Thoughts](https://github.com/princeton-nlp/tree-of-thought-llm) - Explores multiple parallel reasoning paths before committing to a final answer for complex problems (🏷️ `Paper` `Python` `Research`).

> **Deep dives:** [patterns/react-pattern.md](patterns/react-pattern.md) • [patterns/plan-and-execute.md](patterns/plan-and-execute.md) • [patterns/reflection-loop.md](patterns/reflection-loop.md) • [patterns/multi-agent.md](patterns/multi-agent.md) • [workflows/multi-step-reasoning.md](workflows/multi-step-reasoning.md)

## Agent Communication

Capabilities that let agents send messages, notifications, and reports across channels.

- [Apprise](https://github.com/caronc/apprise) - Sends agent notifications to 100+ services including Slack, Discord, and email from a single Python interface (🏷️ `Python` `Multi-Channel` `SDK`).
- [Discord.py](https://github.com/Rapptz/discord.py) - Lets agents interact with Discord channels and servers for team-facing real-time communication (🏷️ `Python` `Discord` `SDK`).
- [FastAPI-Mail](https://github.com/sabuhish/fastapi-mail) - Adds async email sending to FastAPI-based agent services with SMTP and OAuth2 support (🏷️ `Python` `FastAPI` `SDK`).
- [Novu](https://github.com/novuhq/novu) - Routes agent notifications across email, SMS, push, and chat from a unified API and workflow engine (🏷️ `TypeScript` `Python` `Platform`).
- [Ntfy](https://github.com/binwiederhier/ntfy) - Pushes real-time agent notifications to phones and desktops via a dead-simple HTTP API (🏷️ `Go` `Self-hosted` `API`).
- [Resend](https://github.com/resend/resend-node) - Sends transactional emails from agent workflows with a clean, developer-first API (🏷️ `TypeScript` `Cloud` `API`).
- [Slack Bolt](https://github.com/slackapi/bolt-python) - Enables agents to send, receive, and react to Slack messages with event-driven listeners (🏷️ `Python` `Slack` `SDK`).
- [Twilio](https://github.com/twilio/twilio-python) - Sends SMS and voice calls from agent workflows to any phone number worldwide (🏷️ `Python` `Cloud` `API`).

## Data Pipeline and Workflow

Frameworks for orchestrating data transformations and long-running agent-driven workflows.

- [Burr](https://github.com/dagworks-inc/burr) - Tracks and manages multi-step agent state machines with built-in observability and persistence (🏷️ `Python` `StateGraph` `SDK`).
- [Dagster](https://github.com/dagster-io/dagster) - Manages data assets and pipelines with built-in lineage tracking for data-intensive agent systems (🏷️ `Python` `Pipeline` `Platform`).
- [GPT Researcher](https://github.com/assafelovic/gpt-researcher) - Conducts multi-source autonomous web research and produces cited, structured long-form reports (🏷️ `Python` `LangChain` `Web`).
- [Hamilton](https://github.com/DAGWorks-Inc/hamilton) - Defines modular data transformations as Python functions wired automatically into a DAG for agent pipelines (🏷️ `Python` `DAG` `SDK`).
- [Prefect](https://github.com/PrefectHQ/prefect) - Orchestrates agent workflows and data pipelines with retries, caching, and built-in observability (🏷️ `Python` `Pipeline` `Platform`).
- [STORM](https://github.com/stanford-oval/storm) - Generates Wikipedia-style long-form articles by autonomously researching and synthesizing multiple sources (🏷️ `Python` `Stanford` `Research`).

> **Deep dives:** [workflows/data-pipeline.md](workflows/data-pipeline.md) • [workflows/research-agent.md](workflows/research-agent.md)

## Secure Execution Environments

Infrastructure for running agent-generated code safely in isolated, sandboxed, or serverless environments.

> 💡 **Quick Decision Guide:**
>  - **Fastest hosted sandbox:** E2B, Daytona
>  - **Self-hosted VM isolation:** Firecracker, Kata Containers, gVisor
>  - **Container-based:** Docker, Podman, Sysbox
>  - **Serverless:** AWS Lambda, Google Cloud Run, Cloudflare Workers

| Tool                | Isolation          | Cold Start | Languages              |
| ------------------- | ------------------ | ---------- | ---------------------- |
| E2B                 | VM (Firecracker)   | ~300ms     | Python, TS, Go         |
| Daytona             | Container/VM       | ~2s        | Python, TS, Go         |
| Firecracker         | microVM            | ~125ms     | REST API               |
| Docker              | Namespace+cgroup   | ~500ms     | All                    |
| AWS Lambda          | Firecracker VM     | ~200ms     | Python, TS, Go         |
| Cloudflare Workers  | V8 isolate         | ~0ms       | TS, Rust (WebAssembly) |

- [AWS Lambda](https://github.com/aws/aws-lambda-python-runtime-interface-client) - Serverless function runtime with Firecracker isolation for executing short-lived agent tasks at scale (🏷️ `Python` `AWS` `Serverless`).
- [Cloudflare Workers](https://github.com/cloudflare/workers-sdk) - Ultra-low-latency V8-isolate serverless runtime at the edge for lightweight agent task execution (🏷️ `TypeScript` `Cloudflare` `Serverless`).
- [CodeSandbox SDK](https://github.com/codesandbox/codesandbox-sdk) - Provides forked, snapshotted microVM environments for real-time collaborative agent code execution (🏷️ `TypeScript` `Python` `SDK`).
- [Daytona](https://github.com/daytonaio/daytona) - Self-hostable git-based developer environment manager for sandboxed agent code execution with fast provisioning (🏷️ `Python` `TypeScript` `Platform`).
- [Docker](https://github.com/moby/moby) - Standard container runtime providing namespace and cgroup isolation for packaging and running agent workloads (🏷️ `Go` `Docker` `Platform`).
- [Firecracker](https://github.com/firecracker-microvm/firecracker) - Lightweight microVM technology with 125ms boot time used by AWS Lambda and E2B under the hood (🏷️ `Rust` `AWS` `Infrastructure`).
- [Google Cloud Run](https://github.com/GoogleCloudPlatform/cloud-run-samples) - Fully managed serverless platform with gVisor isolation for running stateless agent containers at scale (🏷️ `Python` `GCP` `Serverless`).
- [gVisor](https://github.com/google/gvisor) - User-space kernel that intercepts syscalls to provide VM-level security with container-level overhead (🏷️ `Go` `Google` `Infrastructure`).
- [Kata Containers](https://github.com/kata-containers/kata-containers) - Combines VM-level security with the developer experience of containers using lightweight VMs (🏷️ `Go` `OCI` `Infrastructure`).
- [Podman](https://github.com/containers/podman) - Daemonless, rootless container engine ideal for running untrusted agent-generated code securely (🏷️ `Go` `Rootless` `CLI`).
- [Sysbox](https://github.com/nestybox/sysbox) - Enhanced container runtime that enables Docker-in-Docker securely for nested agent execution environments (🏷️ `Go` `Docker` `Infrastructure`).

> **Deep dives:** [environments/sandboxes.md](environments/sandboxes.md) • [environments/vms.md](environments/vms.md) • [environments/containers.md](environments/containers.md) • [environments/serverless.md](environments/serverless.md)


## Changelog

See [CHANGELOG.md](CHANGELOG.md) for the full update history.

## Contributing

Your contributions are what keep this list useful. Read [Contributing.md](Contributing.md) for the entry format, inclusion criteria, and style guide.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ARUNAGIRINATHAN-K/awesome-ai-agents&type=Date)](https://star-history.com/#ARUNAGIRINATHAN-K/awesome-ai-agents&Date)
