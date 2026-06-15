# Python & Rust AI/ML Engineer

*by Thomas Cherickal · The Digital Futurist*

---

## The Transition

For six years, I was a trained developer who worked as a writer.

500+ articles across HackerNoon, Medium, Substack, Hashnode — and my canonical home at thomascherickal.com. I explained Generative AI, Quantum Computing, and emerging technologies to audiences who needed clarity.

But something was missing.

You can write about systems. You can analyze architecture. You can critique trade-offs. But until you sit down and actually *build*, you're describing terrain you've never walked.

So I transitioned.

And here's what that looks like: I bring the clarity of a writer into production code. Rigorous thinking. Zero tolerance for hand-waving. The ability to name what things are. And the understanding that the best code is code your team can reason about and extend.

---

## What I Build

### SLMs and LLMs — Production Infrastructure

Small Language Models and Large Language Models are the backbone of the AI stack right now.

SLMs run on edge devices, serve real-time inference, and handle tasks that don't need frontier model complexity. LLMs handle reasoning, multi-step planning, and the hard problems.

Both need infrastructure.

**In Python:** RAG pipelines that retrieve the right context. Agentic frameworks using OpenFang and MCP protocols. Fine-tuning systems for knowledge distillation. Local model deployment stacks. Prompt engineering as code — testing, versioning, optimization.

**In Rust:** Token streaming engines for real-time responses. Inference schedulers that handle concurrent requests without melting. Embedding pipelines. Quantization tooling. Hardware acceleration layers.

The work is unglamorous: vector tuning, fallback strategies, cost optimization, context-window management. But this is where systems actually work or fail.

### AI Ecosystem Infrastructure

The AI stack is being rewritten.

Not just the models. The entire infrastructure that makes models useful.

**In Python:** Request routing across model providers. Response caching. Token accounting. Monitoring and observability. Integration with vector databases, retrieval systems, external APIs.

**In Rust:** The performance layer. Low-latency inference orchestration. Batch processing pipelines. Memory-efficient model loading and swapping. Concurrent request handling that scales.

Both languages work together here. Python handles the logic. Rust handles the speed.

The goal is simple: build systems that are fast, correct, and don't require me to maintain them forever.

---

## The Discipline

I build with Test-Driven Development as default.

100% code coverage is the target. Not because numbers look good in dashboards — they don't. But because every line represents a decision about correctness. If I haven't tested it, I don't understand it.

The code ships with docstrings, type hints, architecture decisions recorded. SOLID principles. Modular design. Someone will read this six months from now. They should understand it without me.

### AI-Assisted Development

I work alongside Claude Code, GitHub Copilot, Google Antigravity, and emerging IDE tools.

Not as a crutch.

As a thought partner.

These tools surface patterns. They catch boilerplate. They let me spend less time on scaffolding and more time on the hard problems: correctness, performance, maintainability.

But the design is mine. The testing is mine. The responsibility for what ships is mine.

---

## What I'm Building

> [!NOTE]
> **All repositories listed below are upcoming open-source releases.**

### Q3 2026 releases (5 projects)
- **slm-inference-engine** [Rust] — High-performance Rust library for local SLM inference on CPU-only hardware. Optimized for 2–8 GB RAM targets with streaming support.
- **ai-career-toolkit** [Python] — Python scripts, prompts, and automation tools accompanying the *RECRUITED* book — NotebookLM workflows, resume AI analysis, LinkedIn audit scripts.
- **quantum-ai-experiments** [Python] — Research notebooks exploring QAI intersections — Qiskit, Q#, Quantinuum stack experiments, and quantum threat modeling for blockchain systems.
- **digital-futurist-site** [HTML/CSS] — Open-source GitHub Pages site with JSON-LD schema, SEO metadata, dark-mode design, and cross-platform social integration.
- **rust-llm-router** [Rust] — Zero-latency request router for multi-provider LLM APIs with automatic failover, rate-limit awareness, and cost-optimized model selection.

### Q4 2026 releases (5 projects)
- **vector-forge** [Rust] — High-performance SIMD-accelerated vector operations library for embedding pipelines — cosine similarity, HNSW indexing, and ANN search.
- **ai-cli** [Rust] — Terminal-native AI assistant built in Rust — streaming completions, tool-calling, local model support via llama.cpp bindings, and custom plugins.
- **neural-bench** [Python] — Automated benchmarking suite for local LLM inference — latency, throughput, TTFT, and quality metrics with auto hardware detection.
- **agent-memory-kit** [Python] — Long-term episodic and semantic memory layer for AI agents using LanceDB and Nomic embeddings — pluggable into LangChain or LlamaIndex.
- **slm-distiller** [Python] — An ultra-efficient distillation and low-rank adaptation (LoRA) pipeline for fine-tuning 1B-4B parameter SLMs on consumer GPUs.

### Q1 2027 releases (5 projects)
- **prompt-optimizer** [Python] — Self-correcting prompt engineering and evaluation framework designed specifically to maximize reasoning capability in local Gemma models.
- **rust-rag-engine** [Rust] — A lightning-fast, zero-dependency RAG indexer and query engine written in Rust, featuring native markdown parsing and chunking optimization.
- **slm-wasm-chat** [Rust] — WebAssembly-optimized local SLM inference runner allowing quantized Gemma models to run client-side in the browser via WebGPU acceleration.
- **local-model-dashboard** [Web] — Vibrant, responsive client-side dashboard for monitoring local LLM instances (Ollama, LM Studio) with real-time charts, metrics, and memory logs.
- **gemma-playground** [Web] — A web-based interactive prompt playground and chat interface built for testing local SLM system prompts, settings, and structured output formatting.

These are not toys. They're systems I want to work well.

---

## What I'm Bringing to Your Team

**Translation between domains.** I've spent years explaining complex systems to non-specialists. That skill applies to code too. I can help your team understand what a system does without drowning it in implementation details.

**Clarity without dumbing down.** Not every problem needs a sophisticated solution. When it does, I can explain why and what we gain by adding complexity.

**Rigorous thinking.** Six years of writing taught me that technical complexity is never an excuse for unclear communication.

**Partnership, not heroics.** My goal is to build something good, help your team own it, and move forward. You succeed when you don't need me to maintain the codebase forever. That's the goal.

---

## Where to Find Me

- **GitHub:** github.com/thomascherickal — upcoming repositories as they go public
- **LinkedIn:** linkedin.com/in/thomascherickal — technical thoughts and updates
- **Portfolio:** thomascherickal.github.io — open infrastructure and projects
- **Canonical home:** thomascherickal.com — long-form technical writing
- **Consulting:** topmate.io/thomascherickal — 1-on-1 for teams evaluating AI infrastructure
- **Newsletter:** thomascherickal.kit.com — weekly updates on GenAI and emerging tech
- **Digital products:** thomascherickal.gumroad.com — frameworks and playbooks
- **Community:** patreon.com/thomascherickal — exclusive technical content

---

## Let's Work

I'm interested in roles where:

- The systems are real and serve actual users.
- Your team values clarity and maintainability alongside performance.
- You're working on problems that will matter in five years.
- Async-first, distributed teams work fine.

Contract or full-time both work.

Connect on LinkedIn if you want to talk about what you're building.

Looking forward.

---

© 2026 Thomas Cherickal · The Digital Futurist · Chennai, India 🇮🇳