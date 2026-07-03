## AI Engineer — agentic systems · RAG pipelines · Go + Python

I build the backend infrastructure that makes AI work at production scale — event-driven agent pipelines, RAG-based document intelligence, and high-throughput GPU inference serving.

7+ years of Go and Python backend engineering, now focused on the agentic AI layer: multi-agent orchestration, retrieval pipelines, and LLM integrations that hold up under real load.

---

### What I've shipped

**Nova** — agentic AI advertising platform sustaining **20,000–30,000 ads/day**
Seven independent Python agent-services coordinated via Google Cloud Pub/Sub and Cloud Tasks. Claude and Google Imagen generate creatives; a QA agent gates bad output before any ad spend; a monitoring agent feeds live performance data back into generation prompts.

**Yodayo** — Stable Diffusion inference optimization, **2–4M monthly visits** (peaked 12M)
Go backend with dynamic request batching, concurrent worker pooling, and RunPod / AWS SageMaker GPU scheduling. pprof-tuned hot path — eliminated lock contention and allocation overhead. Same architecture powers Moescape AI. Integrated GLM-4, DeepSeek V3, and Claude for streaming Tavern chat across 105,000+ community models.

**Finance Document Intelligence** — RAG pipeline for finance teams
End-to-end: PDF/DOCX ingestion → chunking → vector embedding → hybrid retrieval → grounded Q&A with source citations. Replaced hours of manual cross-referencing with sub-second answers anchored to retrieved passages.

**[langgraph-research-agent](https://github.com/adam-eques/langgraph-research-agent)** — open source
Multi-agent LangGraph research pipeline: typed StateGraph, hybrid BM25 + semantic retrieval, cross-encoder reranking, FastAPI SSE streaming, and LLM-powered synthesis. Full RAG stack with pgvector and Chroma.

**[extractflow](https://github.com/adam-eques/extractflow)** — open source
Schema-validated structured extraction from PDFs, DOCX, CSV, and email using LLMs — built for automation pipelines.

**[flowra](https://github.com/adam-eques/flowra)** — open source
Self-hostable, code-first workflow automation engine in Go. Define LLM-powered pipelines as a single YAML file, ship as one static binary.

---

### Stack

| Layer | Tools |
|---|---|
| Languages | Python · Go · TypeScript |
| Agentic / LLM | LangGraph · CrewAI · LangChain · Claude · OpenAI · MCP |
| RAG & Retrieval | pgvector · Pinecone · Chroma · BM25 · hybrid search |
| Backend | FastAPI · WebSocket · SSE · microservices |
| GPU Inference | RunPod · AWS SageMaker · dynamic batching |
| Automation | n8n · Make.com · Zapier |
| Infrastructure | Docker · Kubernetes · Google Cloud · AWS · PostgreSQL · Redis |

**Currently building with:** LangGraph · CrewAI · MCP (Model Context Protocol) · LangSmith · pgvector

---

### Reach me

**Telegram:** [@dracoeques](https://t.me/dracoeques)
