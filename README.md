# AI Engineer Roadmap — Verified Course Path

16 steps · all 53 phases covered · ~184 hours (~10–11 weeks at 2–3 hrs/day) · Total cost ≈ ₹1,098 (two Udemy courses at Indian pricing; everything else free with real certificates).

Each step below is checked off as completed, with a deadline set 2 days after the previous step (starting 2026-09-24).

## Checklist

- [ ] **1. Python, NumPy/Pandas, EDA** (Phases 1, 2) — Deadline: 2026-09-24
  Python syntax, functions, lists, dicts; Pandas DataFrames, indexing, groupby, merge, missing-data; matplotlib/seaborn charts; loading CSVs; EDA workflow.
  Course: [Kaggle: Python](https://www.kaggle.com/learn/python) + [Pandas](https://www.kaggle.com/learn/pandas) + [Data Visualization](https://www.kaggle.com/learn/data-visualization) — Free, ~6 days

- [ ] **2. Math for ML** (Phase 3) — NEW — Deadline: 2026-09-26
  Linear algebra: vectors, matrix multiplication, dot/cosine similarity, eigenvectors. Probability: distributions, Bayes' theorem, expectation. Calculus: derivatives, gradients, chain rule (backprop math).
  Course: freeCodeCamp: College Algebra with Python + 3Blue1Brown: Essence of Linear Algebra (YouTube) — Free, ~5 days

- [ ] **3. Classical ML, ML fundamentals** (Phases 4, 5) — Deadline: 2026-09-28
  Regression (linear/logistic), decision trees, random forests, XGBoost, k-NN, k-means; scikit-learn workflow; train/val/test split; over/underfitting; precision, recall, F1, ROC-AUC; hyperparameter tuning; error analysis.
  Course: Kaggle: Intro to ML + Intermediate ML — Free, ~3 days

- [ ] **4. Neural nets + PyTorch** (Phases 6, 7) — PyTorch added — Deadline: 2026-09-30
  MLPs, activations (ReLU/softmax), backprop, cross-entropy/MSE loss, SGD/Adam. PyTorch: tensors, autograd, nn.Module, Dataset/DataLoader, training loops, GPU/CUDA, checkpoints, fine-tuning a pretrained model.
  Course: Kaggle: Intro to Deep Learning + Udemy: PyTorch for Deep Learning — Daniel Bourke (4.7★) — ₹549, ~18 days

- [ ] **5. Async Python, Pydantic, FastAPI** (Phase 1 advanced) — Deadline: 2026-10-02
  async/await, asyncio, HTTP clients (httpx); Pydantic models & validation; FastAPI routing, request/response models, dependency injection; SQLAlchemy ORM; OAuth2 + JWT auth; testing; deploying an async AI backend.
  Course: Udemy: The Complete FastAPI Course with OAuth & JWT — ₹549, ~2 days

- [ ] **6. Transformers, tokenization, embeddings, LLMs** (Phases 8–11) — Deadline: 2026-10-04
  Self-attention & multi-head attention; positional encoding; encoder/decoder blocks. BPE, WordPiece, SentencePiece, token counting. Embedding models, cosine similarity, semantic search. LLM pretraining, instruction tuning, sampling (temperature, top-p), model selection.
  Course: Hugging Face: LLM Course — Free (chapter certs), ~6 days

- [ ] **7. Fine-tuning + inference/serving** (Phases 38–41) — EXPANDED — Deadline: 2026-10-06
  SFT, LoRA, QLoRA, PEFT library; dataset prep; DPO preference alignment; evaluating fine-tuned models. Inference: KV cache, batching, quantization (INT8/INT4, GPTQ, AWQ). vLLM: continuous batching, PagedAttention; benchmarking; hosting an open-source LLM.
  Course: HF: smol-course + DeepLearning.AI: Fast & Efficient LLM Inference with vLLM — Free, ~5 days

- [ ] **8. Prompt engineering, structured outputs, LLM APIs** (Phases 12–14) — Deadline: 2026-10-08
  System vs user prompts, few-shot/CoT prompting, prompt templates; JSON schema, function/tool-calling APIs, Pydantic validation, constrained decoding; Claude, OpenAI, HF APIs; streaming; rate limits & backoff; multi-provider fallback.
  Course: Anthropic Academy: Claude Platform 101 + AI Fluency — Free, ~3 days

- [ ] **9. LangChain + LangGraph** (Phase 29) — NEW — Deadline: 2026-10-10
  LangChain: chains, prompts, output parsers, memory, document loaders, LCEL. LangGraph: graph-based agent orchestration, state machines, conditional branches, checkpointing, parallel tool execution, human-in-the-loop nodes.
  Course: DeepLearning.AI: LangChain for LLM App Development + AI Agents in LangGraph — Free videos (no free cert), ~2 days

- [ ] **10. RAG — full stack** (Phases 15–22, 44) — Deadline: 2026-10-12
  Chunking strategies; embedding pipelines; vector DBs (pgvector, Qdrant, FAISS, Pinecone); top-k retrieval; metadata filtering; hybrid search (BM25 + vector); reranking (cross-encoders); query rewriting, HyDE, parent-child; knowledge graphs & GraphRAG; RAG eval (recall, faithfulness, RAGAS).
  Course: Neo4j GraphAcademy: GenAI & RAG Certification — Free, ~4 days

- [ ] **11. Agents — full stack** (Phases 23–27, 30, 31, 33) — Deadline: 2026-10-14
  Tool-calling loops, agent state; ReAct (reason-act-observe), planning, task decomposition; working/episodic/semantic memory; context selection, compression, budgeting; safe tool design; smolagents, LlamaIndex; delegation & handoffs; multi-agent supervisors; approval gates; trajectory evaluation.
  Course: Hugging Face: AI Agents Course — Free (2 certs), ~8 days

- [ ] **12. MCP + agent reliability** (Phases 28, 32) — Deadline: 2026-10-16
  MCP architecture: hosts, clients, servers, tools/resources/prompts; building an MCP server with FastMCP/Gradio; connecting servers to agents; transports (stdio, SSE/HTTP); permissions & scopes. Retries, backoff, output validation, deterministic guardrails, fallback chains, circuit breakers.
  Course: Hugging Face: MCP Course — Free, ~3 days

- [ ] **13. Multimodal AI** (Phase 42) — NEW — Deadline: 2026-10-18
  Vision-language models (CLIP, BLIP); OCR pipelines; audio: Whisper transcription, speech synthesis, TTS; combining text + image + audio in one app; multimodal embedding models; building a voice assistant.
  Course: HF: Audio Course + HF: Community CV Course — Free (both), ~4 days

- [ ] **14. LLMOps, observability, eval, cost/latency** (Phases 34, 35, 43, 45, 46, 47) — NEW — Deadline: 2026-10-20
  LLM-as-a-judge: judge prompts, rubrics, pairwise vs pointwise; observability: traces, spans, tokens, latency (Langfuse, LangSmith); data pipelines: ETL, document parsing at scale, queues; LLMOps: prompt/model versioning, experiment tracking; cost optimization: prompt caching, model routing; latency: streaming, parallel tools, response caching.
  Course: DL.AI: Evaluating & Debugging GenAI (W&B) + LLMOps + Langfuse docs — Free videos (no free cert), ~4 days

- [ ] **15. Docker, Kubernetes, Cloud/GPU** (Phases 48, 49, 50) — EXPANDED — Deadline: 2026-10-22
  Docker: images, Dockerfiles, multi-stage builds, docker-compose, env/secrets, containerizing an AI service. Kubernetes: pods, deployments, services, ConfigMaps, scaling AI workloads, ingress. AWS: EC2, S3, IAM, GPU instances, cost monitoring; when to use managed AI services vs self-host.
  Course: KodeKloud: Docker + Kubernetes for Absolute Beginners + AWS Skill Builder: Cloud Practitioner Essentials — Free (KodeKloud cert + AWS badge), ~5 days

- [ ] **16. AI security, distributed systems, research, system architecture (capstone)** (Phases 36, 37, 51, 52, 53) — EXPANDED — Deadline: 2026-10-24
  Prompt injection (direct/indirect), RAG poisoning, jailbreak defenses, red-teaming; least-privilege tools, tenant isolation, permission auditing; message queues, workers, concurrency, consistency; reading papers, reproducing experiments; end-to-end architecture (ingestion → retrieval → agent → serving → observability); capstone repo + architecture doc.
  Course: OWASP LLM Top 10 + Papers With Code + capstone build — No formal cert (capstone is the proof), ~6 days

## Coverage summary

All 53 phases covered. **NEW steps added:** Step 2 (Math for ML — Phase 3), Step 9 (LangChain + LangGraph — Phase 29), Step 13 (Multimodal — Phase 42), Step 14 (LLMOps/observability/eval — Phases 34, 35, 43, 45, 46, 47). **Expanded:** Step 4 now includes PyTorch (Phase 7), Step 7 now covers inference/serving (Phases 40, 41), Step 15 adds AWS Cloud (Phase 49), Step 16 adds distributed systems + research (Phases 51, 52).

## Notes on certificates

Steps 9 and 14 use DeepLearning.AI short courses — videos are free forever, but as of 2026 the certificates require the paid Pro subscription. If you want the credential, apply for Coursera financial aid on the Coursera-mirrored versions (free certificate, up to 16-day approval wait). Step 16 has no certificate by design — system architecture is proven by your capstone repo, not a badge.
