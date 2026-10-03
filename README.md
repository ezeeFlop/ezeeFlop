# Hi there 👋

I'm **Christophe Verdier**, founder & CTO of **[Sponge Theory](https://sponge-theory.ai)** and a **Forward Deployed AI Engineer (FDE)**.
I design and ship production-grade generative AI for **hospitality, retail and industry**, and I build a family of AI products that run on **your own infrastructure**: sovereign RAG, self-hosted inference, agent memory, local voice, marketing automation.

Serial tech entrepreneur (Ezeeworld, OneFirst), former **CIO of Renault F1 Team (Alpine)** through four World Championship titles. Same mindset applied to AI: performance, reliability, and shipping under real constraints.

---

## 🚀 Products: live

### 🧠 [NeoRAG](https://neo-rag.com) · Sovereign enterprise RAG platform
Turns documents into queryable knowledge, on your infrastructure. **In production at Accor for 8,000+ users**, and running structured invoice & HR extraction at E.Leclerc.
- 10 retrieval strategies (hybrid, BM25, RAPTOR, CAG, knowledge graph, agentic…), 12 chunking strategies, 6 query-rewriting techniques
- Knowledge graph (Apache AGE / Neo4j), schema-driven structured extraction, multimodal embeddings, Whisper + pyannote for audio/video
- 150+ REST endpoints, MCP server, Python SDK, n8n node, Dify & OpenWebUI integrations, Chrome extension
- **Stack:** Python 3.12 · FastAPI · PostgreSQL + pgvector + Apache AGE · Celery + Redis · MinIO/S3 · React 19 + shadcn/ui · Langfuse · Docker Swarm / AWS ECS

### ⚡ [SPT Models](https://models.sponge-theory.dev/landing/) · Self-hosted multimodal inference platform
One OpenAI-compatible API + MCP over a heterogeneous GPU fleet (NVIDIA DGX Spark, RTX, Apple Silicon): chat with tools & constrained JSON, embeddings, reranking, ASR & diarization, streaming TTS & voice cloning, image, video, music, audio-to-score, image-to-3D. Async jobs, per-key quotas, model catalogue with qualified recipes. Source code delivered to customers.
- **Stack:** Python · FastAPI · vLLM · SGLang · llama.cpp · diffusers · oMLX · headless ComfyUI · PostgreSQL · Redis · Docker Swarm + Portainer
- Product page: [sponge-theory.ai/en/digital-products/spt-models](https://sponge-theory.ai/en/digital-products/spt-models)

### 🧽 [Spongram](https://spongram.sponge-theory.dev/en/) · Persistent memory & personas for Claude Code, Claude Desktop and Codex
A second brain for coding agents: temporal knowledge graph, dated invalidation of stale facts, AST code map, personas with their own skills and memory, 3D "Cortex" explorer. Runs on your GPUs, never on a third-party cloud.
- **Editions:** Desktop (native macOS app) and Cloud (self-hosted, multi-tenant)
- **Stack:** Python · FastAPI · Graphiti · Neo4j · Tauri (Rust) · Astro · MCP plugins & `.mcpb` bundle

### 🎙️ [NeoDicta](https://neodicta.sponge-theory.ai) · Privacy-first voice dictation for macOS & Windows
Speak, it types, in any app (VS Code, Claude Code, Terminal, Cursor, Xcode…). 100% on-device, under 300 ms latency, 25 European languages with automatic detection, personal dictionary and snippets.
- **Stack:** native macOS app · Parakeet TDT 0.6B on Core ML / Apple Neural Engine · Accessibility API text injection · Next.js 16 + React 19 web

### 🔎 [AudiGEO](https://audigeo.ai) · GEO audit & AI visibility monitoring
Measures and improves how a website shows up in ChatGPT, Claude, Gemini and Perplexity answers: GEO audits, continuous monitoring, GEO content generation, REST API.
- **Stack:** Python API + async workers · multi-LLM monitoring · self-hosted on Sponge Theory infrastructure

### 📣 [Rayonne](https://rayonne.sponge-theory.dev) · AI marketing automation for software & SaaS
From marketing audit to storyboards, generated videos and multi-platform distribution (LinkedIn, YouTube, Hashnode and more), with human validation before publishing. Exposes an MCP server for agents.
- **Stack:** Python · FastAPI · React · PostgreSQL · heavy media workers · SPT Models for generation · Docker Swarm

### 📺 [ClipHaven](https://cliphaven.tv) · Video capture & streaming to Smart TVs
Capture videos from the web and watch them on your TV, with tiered subscriptions and a browser extension.
- **Clients:** Samsung Tizen · LG webOS · iOS · browser extension
- **Stack:** yt-dlp · Clerk · Stripe · Docker Swarm

---

## 🛠️ Products: in development

| Product | What it is | Stack |
|---|---|---|
| **NeoKanban** | Project management with AI meeting transcription, notes, mail actions and searchable meeting memory | FastAPI · Vite + React · macOS bridge · NeoRAG · MCP |
| **Ausculte** | AI scribe for veterinarians: consultation audio → grounded, structured clinical report | FastAPI · Vite + React · native iOS (Swift) · CrisperWhisper · pyannote · SPT Models |
| **Vocierge** | AI telephone agent taking restaurant & hotel reservations by voice | FastAPI · Vite + React |
| **Ritchy** | Voice-first desktop robot companion built on Reachy Mini | Python · on-device VAD & vision · SPT Models |

---

## 🤝 Client work
- **Agentic workflows in production** for a global hospitality group: tech lead on a multi-agent procurement (RFP) workflow on AWS Bedrock AgentCore, LangGraph, LiteLLM and Langfuse.
- **Enterprise knowledge management & executive assistants** built on NeoRAG, integrated with Microsoft 365.
- **AI for retail** with a major French retailer: structured document extraction and purchasing use cases.
- **Digitalisation & AI** for SMEs (booking platform for a diving center: React, TypeScript, Firebase, Stripe).
- Coaching data science teams on **AI-assisted development with Claude Code** (skills, plugins, MCP, multi-session workflows).

## 🧰 Stack
**Languages:** Python · TypeScript / Node.js · Swift · Rust (Tauri)
**AI:** LangGraph · LangChain · MCP · RAG · Graphiti · Whisper / Parakeet / pyannote · vLLM · SGLang · Qwen, Gemma & frontier LLMs · Langfuse · LiteLLM
**Backend & data:** FastAPI · Celery · PostgreSQL / pgvector / Apache AGE · Neo4j · Redis · MinIO
**Front & apps:** React · Next.js · Vite · Astro · native macOS & iOS · Smart TV (Tizen, webOS)
**Infra:** Docker Swarm + Portainer on our own GPU cluster · AWS (AgentCore, Bedrock, ECS) · GitLab CI/CD

## 💬 Ask me about
- Taking GenAI from POC to production in large enterprises
- Sovereign RAG and running open-weight models on your own GPUs
- Multi-agent systems, MCP and long-term agent memory

## 📫 Reach me
- 🌐 [sponge-theory.ai](https://sponge-theory.ai)
- 💼 [linkedin.com/in/cverdier](https://www.linkedin.com/in/cverdier/)
- 📧 [christophe.verdier@sponge-theory.ai](mailto:christophe.verdier@sponge-theory.ai)
- 📅 [Book a 30-min call](https://calendly.com/christophe-verdier-sponge-theory/30min)

Let's build AI that actually ships. 🚀
