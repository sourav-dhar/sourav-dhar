<a href="https://sourav-dhar.github.io">
  <img src="./banner.svg" alt="Sourav Dhar, AI Engineer. Foundation models, inference and production agents." width="100%">
</a>

<p>
  <a href="https://sourav-dhar.github.io"><b>Portfolio</b></a> &nbsp;|&nbsp;
  <a href="https://www.linkedin.com/in/sourav-dhar-ai-engineer/"><b>LinkedIn</b></a> &nbsp;|&nbsp;
  <a href="mailto:dharsourav03@gmail.com"><b>dharsourav03@gmail.com</b></a>
</p>

I train models, serve them, and ship the agents that run on them. I'm a key contributor to a **120B-parameter mixture-of-experts foundation model** being built at The School of AI (ERA V5). Before that I led compliance analytics (AI/ML) at **TerraPay**, a cross-border payments network, and was Lead Data Analyst at **India Post Payments Bank**.

### Models: training, inference and serving

| | |
|---|---|
| **120B MoE foundation model** | Pretraining a mixture-of-experts model from scratch with The School of AI's ERA V5 programme. Key contributor across the data pipeline, evaluation and benchmarking, post-training (SFT, RL-based alignment) and model serving. |
| **Training and fine-tuning** | Transformers trained from scratch; open-weight LLMs fine-tuned for domain tasks; distributed training (5D parallelism). |
| **Attention ablation** | MHA vs MQA vs GQA vs MLA in small language models, benchmarked on compute and quality on RunPod GPUs. |
| **Serving** | vLLM and SGLang with continuous batching, PagedAttention, prefix caching and tensor / expert parallelism; AWQ, GPTQ, GGUF and FP8 quantization; speculative decoding and TTFT / throughput tuning. |

### Agents in production

| | |
|---|---|
| **Enterprise knowledge assistant** | RAG across onboarding, legal, compliance and sales documents with ACL/JWT pre-filtering, hybrid search and re-ranking. **8 departments**, **60%+ faster** query resolution. |
| **TxQuery AI** | LangGraph multi-agent customer support, connected to Freshdesk through MCP, streaming over SSE. |
| **AML transaction graph** | Production Cypher analytics on a Neo4j graph of **107M nodes / 199M relationships**. |
| **AML fraud detection** | XGBoost model that cut false positives by **35%**. |

The TerraPay work is company code, so it's private. The [portfolio](https://sourav-dhar.github.io) has the write-ups, and I'm happy to walk through any of the architectures.

### Stack

**Training** PyTorch, mixture-of-experts, data pipelines, SFT and RL post-training, evals and benchmarks, distributed training &nbsp;
**Serving** vLLM, SGLang, PagedAttention, AWQ / GPTQ / GGUF, speculative decoding, FastAPI, Docker &nbsp;
**Agents** LangGraph, LangChain, MCP, Claude Agent SDK, Google ADK &nbsp;
**Retrieval** pgvector, hybrid search, re-ranking, Neo4j / GraphRAG &nbsp;
**Evals and observability** Langfuse, DeepEval, Opik, Guardrails AI
