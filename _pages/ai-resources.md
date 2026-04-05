---
layout: page
title: AI Resources
permalink: /ai-resources/
---

### Generative AI Systems Stack

**LLMs / Foundation Models**

- [OpenAI](https://openai.com) — GPT-5.4, GPT-5.3, o3-pro
- [Anthropic](https://www.anthropic.com) — Claude Opus 4.6, Sonnet 4.6
- [Google Gemini](https://deepmind.google/technologies/gemini/) — Gemini 3.1 Pro, Gemini 3.1 Flash
- [Meta Llama](https://llama.meta.com) — Llama 4 (Maverick, Scout)
- [DeepSeek](https://www.deepseek.com) — DeepSeek R1, DeepSeek-V3
- [Mistral](https://mistral.ai) — Mistral Large 3, Mistral Small 4
- [xAI](https://x.ai) — Grok 4.20
- [Qwen](https://qwenlm.github.io) — Qwen 3.6-Plus

**AI Frameworks**

- [LangChain](https://www.langchain.com) — LLM orchestration and chaining
- [LlamaIndex](https://www.llamaindex.ai) — Data-centric RAG and document processing
- [Haystack](https://haystack.deepset.ai) — Production RAG and search pipelines
- [Microsoft Agent Framework](https://learn.microsoft.com/en-us/agent-framework/) — Unified SDK (successor to Semantic Kernel + AutoGen)
- [Mastra](https://mastra.ai) — TypeScript-first AI agent framework

**AI Coding Assistants**

- [Cursor](https://www.cursor.com) — AI-native code editor with Background Agents
- [GitHub Copilot](https://github.com/features/copilot) — Inline code completion and chat
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) — CLI-based agentic coding assistant
- [Windsurf](https://codeium.com/windsurf) — AI IDE with agentic flows
- [OpenAI Codex](https://openai.com/codex/) — Cloud-based agentic coding with parallel worktrees
- [Devin](https://devin.ai) — Autonomous AI software engineer
- [Amazon Kiro](https://kiro.dev) — Spec-driven AI IDE

**Text Embeddings**

- [OpenAI Embeddings](https://platform.openai.com/docs/guides/embeddings) — text-embedding-3-large
- [Cohere Embed 4](https://cohere.com/embed) — Multimodal (text + images)
- [Voyage AI](https://www.voyageai.com) — Voyage 4, MoE architecture (acquired by MongoDB)
- [Gemini Embedding](https://ai.google.dev/gemini-api/docs/embeddings) — Multimodal including native audio
- [Mistral Embed](https://docs.mistral.ai/capabilities/embeddings/) — Retrieval-optimized, lowest cost

**Vector Databases**

- [Pinecone](https://www.pinecone.io) — Fully managed, serverless
- [Weaviate](https://weaviate.io) — Open-source with hybrid search
- [Qdrant](https://qdrant.tech) — High-performance, Rust-based
- [Chroma](https://www.trychroma.com) — Lightweight, developer-friendly
- [Milvus](https://milvus.io) — Billion-scale vector search, hot/cold tiering
- [pgvector](https://github.com/pgvector/pgvector) — PostgreSQL extension

**RAG (Retrieval-Augmented Generation)**

- Hybrid RAG — Dense vector + sparse keyword search (production baseline)
- Agentic RAG — Autonomous plan-retrieve-reason loops
- Graph RAG — Knowledge graph layer for multi-hop reasoning
- [LlamaIndex Workflows](https://docs.llamaindex.ai/en/stable/module_guides/workflow/) — Event-driven RAG pipelines
- [LangChain LCEL](https://python.langchain.com/docs/concepts/lcel/) — Chain-based RAG orchestration

**AI Agents**

- [LangGraph](https://www.langchain.com/langgraph) — Stateful multi-actor workflows
- [CrewAI](https://www.crewai.com) — Role-based multi-agent collaboration
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) — Production-grade agent orchestration
- [Claude Agent SDK](https://github.com/anthropics/claude-agent-sdk-python) — Tool-use agents with constitutional safety
- [Google ADK](https://google.github.io/adk-docs/) — Agent Development Kit (Python, Java, Go, TS)
- [AG2](https://github.com/ag2ai/ag2) — Community fork of AutoGen, multi-agent conversations
- [Smolagents](https://github.com/huggingface/smolagents) — Hugging Face's lightweight agent framework

**Model Context Protocol (MCP)**

- [MCP Specification](https://modelcontextprotocol.io) — Open standard for connecting AI to tools and data
- [MCP Servers](https://github.com/modelcontextprotocol/servers) — 10,000+ community servers
- [Agentic AI Foundation](https://agenticaifoundation.org) — Linux Foundation governance (Anthropic, OpenAI, Google, Microsoft)

**LLM Serving / Inference**

- [vLLM](https://github.com/vllm-project/vllm) — PagedAttention, high-throughput serving
- [SGLang](https://github.com/sgl-project/sglang) — Zero-overhead batch scheduler, fastest on benchmarks
- [Ollama](https://ollama.com) — Local model serving with Apple MLX support
- [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) — NVIDIA-optimized inference
- [TGI](https://github.com/huggingface/text-generation-inference) — Hugging Face's production inference server
- [LiteLLM](https://github.com/BerriAI/litellm) — AI gateway/proxy for 100+ LLMs in OpenAI format

**Fine-Tuning**

- [Unsloth](https://github.com/unslothai/unsloth) — 2-12x faster fine-tuning, 80% less memory
- [Axolotl](https://github.com/axolotl-ai-cloud/axolotl) — Multi-GPU, supports LoRA/QLoRA/SFT/RLHF/GRPO
- [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) — GUI-first, 100+ model support, no-code fine-tuning
- [TRL](https://github.com/huggingface/trl) — Hugging Face RL-based alignment (GRPO, PPO, DPO)
- [Torchtune](https://github.com/pytorch/torchtune) — PyTorch-native, deep customization
- [PEFT](https://github.com/huggingface/peft) — Parameter-efficient methods (LoRA, QLoRA, adapters)

**Guardrails / Safety**

- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) — NVIDIA's open-source safety toolkit
- [Guardrails AI](https://github.com/guardrails-ai/guardrails) — Output validation and structuring
- [Llama Guard](https://ai.meta.com/research/publications/llama-guard-llm-based-input-output-safeguard-for-human-ai-conversations/) — LLM-based content classification

**LLM Monitoring / Observability**

- [Langfuse](https://langfuse.com) — Open-source LLM observability (acquired by ClickHouse)
- [LangSmith](https://www.langchain.com/langsmith) — Tracing, cost, and latency tracking
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) — Open-source drift and bias monitoring
- [Weights & Biases Weave](https://wandb.ai/site/weave) — Multi-agent execution traces
- [AgentOps](https://www.agentops.ai) — Agentic workflow monitoring

**Evaluation and Testing**

- [RAGAS](https://github.com/explodinggradients/ragas) — RAG-specific evaluation (faithfulness, relevancy, recall)
- [DeepEval](https://github.com/confident-ai/deepeval) — 14+ targeted metrics, Pytest-like LLM testing
- [PromptFoo](https://www.promptfoo.dev) — Red teaming, security testing, and CI/CD integration
- [OpenAI Evals](https://github.com/openai/evals) — Open-source evaluation framework
