# Target Track — AI Engineer (LLM Agents & RAG) Job

A trimmed version of the [main roadmap](README.md), aimed at one job description: LangChain/LangGraph agents, RAG, evaluation, observability, MCP, FastAPI, Docker and cloud.

12 steps · ~45 days · Total cost ≈ ₹549 (one Udemy course; everything else free).

Deadlines are staggered 2 days apart, starting 2026-09-24.

**Skipped from the main roadmap:** Step 2 (Math for ML), Step 3 (Classical ML), Step 4 (Neural nets + PyTorch), Step 13 (Multimodal AI), Pandas/EDA from Step 1, Kubernetes from Step 15, and paper reading from Step 16.

## Checklist

| Done | # | Topic | Phases | Course | Cert? | Price | Time | Deadline |
|:---:|:---:|---|:---:|---|:---:|---:|---:|---|
| ☐ | 1 | Python (+ OOP refresher) | 1 | Kaggle: [Python](https://www.kaggle.com/learn/python) | Free | ₹0 | 2d | 2026-09-24 |
| ☐ | 5 | Async Python, Pydantic, FastAPI | 1 adv. | Udemy: [Complete FastAPI Course with OAuth & JWT](https://www.udemy.com/course/fastapi-course-python/) | Yes | ₹549 | 2d | 2026-09-26 |
| ☐ | 6 | Transformers basics, tokenization, embeddings *(trimmed)* | 8–11 | Hugging Face: [LLM Course](https://huggingface.co/learn/llm-course) | Chapter certs | ₹0 | 3d | 2026-09-28 |
| ☐ | 7 | Fine-tuning + inference/serving | 38–41 | HF: [smol-course](https://huggingface.co/learn/smol-course) + DL.AI: [Fast & Efficient LLM Inference with vLLM](https://www.deeplearning.ai/courses/fast-and-efficient-llm-inference-with-vllm) | Partial | ₹0 | 5d | 2026-09-30 |
| ☐ | 8 | Prompt engineering, structured outputs, LLM APIs | 12–14 | Anthropic Academy: [Claude Platform 101](https://academy.claude.com/courses/claude-platform-101) + [AI Fluency](https://anthropic.skilljar.com/ai-fluency-framework-foundations) | Free | ₹0 | 3d | 2026-10-02 |
| ☐ | 9 | LangChain + LangGraph *(go deeper)* | 29 | DL.AI: [LangChain for LLM App Development](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/) + [AI Agents in LangGraph](https://www.deeplearning.ai/courses/ai-agents-in-langgraph) | No free cert | ₹0 | 2d+ | 2026-10-04 |
| ☐ | 10 | RAG — full stack (+ pgvector, Qdrant/Pinecone hands-on) | 15–22, 44 | Neo4j GraphAcademy: [GenAI & RAG Certification](https://graphacademy.neo4j.com/certifications/genai-certification/) | Free | ₹0 | 4d | 2026-10-06 |
| ☐ | 11 | Agents — full stack | 23–27, 30, 31, 33 | Hugging Face: [AI Agents Course](https://huggingface.co/learn/agents-course/unit0/introduction) | Free (2 certs) | ₹0 | 8d | 2026-10-08 |
| ☐ | 12 | MCP + agent reliability | 28, 32 | Hugging Face: [MCP Course](https://huggingface.co/learn/mcp-course/unit0/introduction) | Free | ₹0 | 3d | 2026-10-10 |
| ☐ | 14 | LLMOps, observability, eval, cost/latency (+ LangSmith) | 34, 35, 43, 45–47 | DL.AI: [Evaluating & Debugging GenAI (W&B)](https://www.deeplearning.ai/short-courses/evaluating-debugging-generative-ai/) + [Langfuse docs](https://langfuse.com/docs) + [LangSmith docs](https://docs.smith.langchain.com/) | No free cert | ₹0 | 4d | 2026-10-12 |
| ☐ | 15 | Docker + Cloud *(no Kubernetes)* | 48, 50 | KodeKloud: [Docker](https://kodekloud.com/courses/docker-for-the-absolute-beginner) + AWS: [Cloud Practitioner Essentials](https://explore.skillbuilder.aws/learn/course/external/view/elearning/134/aws-cloud-practitioner-essentials) | Free | ₹0 | 3d | 2026-10-14 |
| ☐ | 16 | AI security, queues/event-driven patterns, capstone | 36, 37, 51, 53 | [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/) + capstone build | None (capstone) | ₹0 | 6d | 2026-10-16 |

## Gaps to fill alongside the courses

- **OOP (Step 1):** classes, inheritance vs composition, dataclasses, abstract base classes.
- **LangGraph depth (Step 9):** checkpointing, human-in-the-loop, subgraphs, conditional loops.
- **Vector DBs (Step 10):** hands-on with pgvector and Qdrant or Pinecone, not just Neo4j.
- **LangSmith (Step 14):** tracing, datasets, experiments.
- **Automated agent testing (Step 14):** pytest eval suite in CI against a golden dataset (accuracy, latency, cost).

## Capstone

A LangGraph agent with an async FastAPI backend, doing RAG over pgvector/Qdrant with hybrid search and reranking, calling tools through your own MCP server, returning Pydantic structured outputs, with guardrails, retries and fallbacks. Traced in LangSmith, with an eval suite in CI, background workers on a queue, a vLLM-served open-source model as a cheaper fallback (Step 7), Dockerized and deployed on AWS.
