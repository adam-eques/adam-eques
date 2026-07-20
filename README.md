<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=AI%20%26%20Backend%20Engineer&fontSize=48&fontColor=ffffff&animation=fadeIn&desc=Go%20%C2%B7%20Python%20%C2%B7%20TypeScript%20%E2%80%A2%20Agentic%20Systems%20%E2%80%A2%20Event-Driven%20Architecture&descSize=18&descAlignY=72" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=Building+agentic+AI+pipelines+in+production;20%2C000%E2%80%9330%2C000+ads%2Fday+on+Google+Cloud;RAG+%C2%B7+LangGraph+%C2%B7+Multi-agent+orchestration;Go+%C2%B7+Python+%C2%B7+TypeScript+%C2%B7+7%2B+years+backend;QA+gates+%26+eval+loops+before+any+ad+spend;GPU+inference+%C2%B7+2%E2%80%934M+monthly+visits;MCP+servers+%26+clients+in+Go+%C2%B7+zero+dependencies" alt="Typing SVG" />

</div>

---

I build the backend infrastructure that makes AI work at production scale — event-driven agent pipelines, RAG-based document intelligence, and GPU inference serving that holds up under real load.

7+ years of production backend engineering across Go, Python, and TypeScript — now focused on the agentic AI layer: multi-agent orchestration, retrieval pipelines, evaluation loops, and LLM integrations that stay correct under load, retries, and partial failure.

---

### ⚡ Shipped at scale

**🤖 Nova — AI Advertising Automation Platform**
`TypeScript · Node.js (Fastify) · Python (FastAPI) · PostgreSQL (Prisma) · Gemini · Google Cloud Pub/Sub · Cloud Tasks · Meta Ads API`

Seven specialized services — page generation, content, image generation, QA gating, CMS publish, ad launch, budget allocation — coordinated by an event-driven TypeScript/Fastify orchestrator: Cloud Tasks command queues out, Pub/Sub events back, sustaining **20,000–30,000 ads/day**. Message-ID deduplication gives exactly-once event handling over at-least-once delivery, and a monotonic status state machine means duplicate or out-of-order events can never corrupt campaign state. An automated QA gate blocks bad creatives before any ad spend; a monitoring service benchmarks live creatives and feeds results back into prompt selection — a continuously running production eval loop, not an offline benchmark.

---

**🎨 Yodayo — Stable Diffusion Inference, Go Backend**
`Go · RunPod · AWS SageMaker · GLM-4 · DeepSeek V3 · Claude`

Go backend serving a platform with **2–4M monthly visits** (peaked at 12M). Dynamic request batching, concurrent worker pooling, and GPU scheduling keep RunPod/SageMaker workers saturated. pprof-tuned hot path eliminated lock contention and allocation overhead. Integrated GLM-4, DeepSeek V3, and Claude for streaming Tavern chat across 105,000+ community models. Same architecture powers Moescape AI.

---

**📄 Finance Document Intelligence — RAG Pipeline**
`Python (asyncio) · RAG · pgvector (PostgreSQL) · Claude (Anthropic API) · Streaming`

End-to-end document intelligence for finance teams: PDF/DOCX ingestion → chunking → vector embedding → hybrid retrieval → grounded Q&A with source citations. Replaced hours of manual cross-referencing with sub-second answers anchored to retrieved passages, not model weights.

---

### 🔧 Tech Stack

<div align="center">

**💻 Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

**🤖 AI & Agentic Layer**

![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PGNpcmNsZSBjeD0iMTIiIGN5PSI0IiByPSIzIiBmaWxsPSJ3aGl0ZSIvPjxjaXJjbGUgY3g9IjQiIGN5PSIxOSIgcj0iMyIgZmlsbD0id2hpdGUiLz48Y2lyY2xlIGN4PSIyMCIgY3k9IjE5IiByPSIzIiBmaWxsPSJ3aGl0ZSIvPjxwYXRoIGQ9Ik0xMiA3TDQgMTZNMTIgN0wyMCAxNk03IDE5TDE3IDE5IiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIiIGZpbGw9Im5vbmUiLz48L3N2Zz4=&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-1A1A2E?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHJlY3QgeD0iNiIgeT0iNyIgd2lkdGg9IjEyIiBoZWlnaHQ9IjEwIiByeD0iMiIgZmlsbD0id2hpdGUiLz48cmVjdCB4PSI5IiB5PSIzIiB3aWR0aD0iNiIgaGVpZ2h0PSI0IiByeD0iMSIgZmlsbD0id2hpdGUiLz48Y2lyY2xlIGN4PSI5LjUiIGN5PSIxMiIgcj0iMS41Ii8+PGNpcmNsZSBjeD0iMTQuNSIgY3k9IjEyIiByPSIxLjUiLz48cmVjdCB4PSI5IiB5PSIxNyIgd2lkdGg9IjIiIGhlaWdodD0iMyIgcng9IjEiIGZpbGw9IndoaXRlIi8+PHJlY3QgeD0iMTMiIHk9IjE3IiB3aWR0aD0iMiIgaGVpZ2h0PSIzIiByeD0iMSIgZmlsbD0id2hpdGUiLz48cmVjdCB4PSIzIiB5PSI5IiB3aWR0aD0iMyIgaGVpZ2h0PSI0IiByeD0iMSIgZmlsbD0id2hpdGUiLz48cmVjdCB4PSIxOCIgeT0iOSIgd2lkdGg9IjMiIGhlaWdodD0iNCIgcng9IjEiIGZpbGw9IndoaXRlIi8+PC9zdmc+&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-CC785C?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxjaXJjbGUgY3g9IjEyIiBjeT0iNSIgcj0iMi4yIi8+PGNpcmNsZSBjeD0iNSIgY3k9IjE3IiByPSIyLjIiLz48Y2lyY2xlIGN4PSIxOSIgY3k9IjE3IiByPSIyLjIiLz48Y2lyY2xlIGN4PSIxMiIgY3k9IjEzIiByPSIyLjIiLz48cGF0aCBkPSJNMTIgNy4yVjExTTEyIDExTDUgMTVNMTIgMTFMMTkgMTUiIHN0cm9rZT0id2hpdGUiIHN0cm9rZS13aWR0aD0iMS41IiBmaWxsPSJub25lIi8+PC9zdmc+&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxyZWN0IHg9IjIiIHk9IjEwIiB3aWR0aD0iNSIgaGVpZ2h0PSI0IiByeD0iMSIvPjxyZWN0IHg9IjE3IiB5PSIxMCIgd2lkdGg9IjUiIGhlaWdodD0iNCIgcng9IjEiLz48cmVjdCB4PSI5IiB5PSIyIiB3aWR0aD0iNiIgaGVpZ2h0PSI0IiByeD0iMSIvPjxyZWN0IHg9IjkiIHk9IjE4IiB3aWR0aD0iNiIgaGVpZ2h0PSI0IiByeD0iMSIvPjxwYXRoIGQ9Ik03IDEySDE3TTEyIDZWMTgiIHN0cm9rZT0id2hpdGUiIHN0cm9rZS13aWR0aD0iMS41IiBmaWxsPSJub25lIi8+PC9zdmc+&logoColor=white)

**🗄️ RAG & Vector Search**

![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwb2x5Z29uIHBvaW50cz0iMTIsMiAyMSwxOSAzLDE5Ii8+PHJlY3QgeD0iMTAiIHk9IjE5IiB3aWR0aD0iNCIgaGVpZ2h0PSIzIi8+PC9zdmc+&logoColor=white)
![Chroma](https://img.shields.io/badge/Chroma-FF6B35?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTE5IDZBOSA5IDAgMSAwIDE5IDE4IiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIuNSIgZmlsbD0ibm9uZSIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIi8+PGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMyIgZmlsbD0id2hpdGUiLz48L3N2Zz4=&logoColor=white)

**🚀 Backend & Infrastructure**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**☁️ Cloud**

![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0xOS40IDEzLjZBNS41IDUuNSAwIDAgMCAxNCA4YTUuNSA1LjUgMCAwIDAtNS4yIDMuN0E0IDQgMCAwIDAgNSAxNS41IDQgNCAwIDAgMCA5IDE5LjVoMTBhMy41IDMuNSAwIDAgMCAuNC02LjlaIi8+PC9zdmc+&logoColor=white)
![RunPod](https://img.shields.io/badge/RunPod-673AB7?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxyZWN0IHg9IjUiIHk9IjUiIHdpZHRoPSIxNCIgaGVpZ2h0PSIxNCIgcng9IjIiLz48cmVjdCB4PSIyIiB5PSI4IiB3aWR0aD0iMyIgaGVpZ2h0PSIyIi8+PHJlY3QgeD0iMiIgeT0iMTIiIHdpZHRoPSIzIiBoZWlnaHQ9IjIiLz48cmVjdCB4PSIxOSIgeT0iOCIgd2lkdGg9IjMiIGhlaWdodD0iMiIvPjxyZWN0IHg9IjE5IiB5PSIxMiIgd2lkdGg9IjMiIGhlaWdodD0iMiIvPjxyZWN0IHg9IjgiIHk9IjIiIHdpZHRoPSIyIiBoZWlnaHQ9IjMiLz48cmVjdCB4PSIxMiIgeT0iMiIgd2lkdGg9IjIiIGhlaWdodD0iMyIvPjxyZWN0IHg9IjgiIHk9IjE5IiB3aWR0aD0iMiIgaGVpZ2h0PSIzIi8+PHJlY3QgeD0iMTIiIHk9IjE5IiB3aWR0aD0iMiIgaGVpZ2h0PSIzIi8+PC9zdmc+&logoColor=white)

**⚡ Workflow Automation**

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Make.com](https://img.shields.io/badge/Make.com-6D00CC?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PGNpcmNsZSBjeD0iNiIgY3k9IjEyIiByPSIzIiBmaWxsPSJ3aGl0ZSIvPjxjaXJjbGUgY3g9IjE4IiBjeT0iMTIiIHI9IjMiIGZpbGw9IndoaXRlIi8+PHBhdGggZD0iTTkgMTIgQzkgOCAxNSA4IDE1IDEyIiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIiIGZpbGw9Im5vbmUiLz48cGF0aCBkPSJNOSAxMiBDOSAxNiAxNSAxNiAxNSAxMiIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBmaWxsPSJub25lIi8+PC9zdmc+&logoColor=white)
![Zapier](https://img.shields.io/badge/Zapier-FF4A00?style=for-the-badge&logo=zapier&logoColor=white)

</div>

---

### 📦 Open source

**[mcpkit](https://github.com/adam-eques/mcpkit)** · `Go`
Zero-dependency MCP server toolkit for Go — JSON-RPC 2.0, pure stdlib, concurrent request handling, HTTP gateway, and built-in observability. No third-party packages required.

**[mcpc](https://github.com/adam-eques/mcpc)** · `Go`
Zero-dependency MCP client for Go — library + CLI. Connects to any MCP server via stdio or HTTP, usable as a package or standalone tool. Pure stdlib.

**[langgraph-research-agent](https://github.com/adam-eques/langgraph-research-agent)** · `Python`
Multi-agent LangGraph research pipeline — typed `StateGraph`, hybrid BM25 + semantic retrieval with RRF, cross-encoder reranking, FastAPI SSE streaming, and LLM-powered synthesis. Full RAG stack with pgvector and Chroma.

**[finsight-crew](https://github.com/adam-eques/finsight-crew)** · `Python`
Multi-agent CrewAI crew that researches a stock and writes a cited investment brief — company analysis, market data, SEC filings, and risk assessment in one run.

**[extractflow](https://github.com/adam-eques/extractflow)** · `Python`
Schema-validated structured extraction from PDF, DOCX, CSV, and email using LLMs — built for automation pipelines.

**[flowra](https://github.com/adam-eques/flowra)** · `Go`
Self-hostable workflow automation engine in Go. Define LLM-powered pipelines as a single YAML file, ship as one static binary.

---

### 🌱 Currently building with

`LangGraph` · `CrewAI` · `MCP (Model Context Protocol)` · `LangSmith` · `pgvector`

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer" width="100%" />

</div>
