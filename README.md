<h1 align="center">Ahmed Berrais</h1>

<p align="center">
  <b>AI/ML Engineer · Full-Stack Developer · LLM Infrastructure Specialist</b>
</p>

<p align="center">
  Building intelligent systems with LangGraph, LangChain, and optimized LLM inference
</p>

---

### 🔧 What I Do

I design and build **AI-powered applications** — from multi-agent pipelines to production web platforms. My focus is on making large language models work in **real-world, resource-constrained environments** without relying on expensive GPU infrastructure.

---

### 🏥 SmilhCare — AI-Powered Home Care Platform

> **Live at [smilhcare.com](https://smilhcare.com)**

A full-stack home care services platform with an integrated AI chatbot, built as a collaborative project.

**My contributions:**
- Built the **complete frontend** using **React** with a premium, responsive design
- Developed the **Flask backend API** with **Supabase** integration
- Engineered the **AI chatbot** from scratch using **LangChain** + **Qwen 2.5 7B** running on **llama.cpp**
- Achieved **9 tokens/sec** inference on a **CPU-only server** (12 cores, 48GB RAM, zero GPU) through careful optimization of quantization, context management, and threading
- Integrated **Cohere embedding model** for semantic search and retrieval

| Component | Tech |
|-----------|------|
| Frontend | React |
| Backend | Flask + Supabase |
| LLM | Qwen 2.5 7B (llama.cpp, CPU-only) |
| Embeddings | Cohere |
| Inference | 9 tok/s @ 12 CPU cores, 48GB RAM |

---

### 🤖 AI Agent Portfolio

A collection of production-ready AI agents built with **Python**, **LangGraph**, and **LangChain**, demonstrating progressive mastery of agentic architectures:

| Project | Description | Stack |
|---------|-------------|-------|
| [**Draft Agents**](https://github.com/ahmed-berrais/draft_agents) | Evolution of agent design from basic ReAct to advanced multi-tool architectures (v1→v4) | LangGraph, LangChain, Groq |
| [**Interviewer Agent**](https://github.com/ahmed-berrais/interviewer_agent) | Multi-node AI interview system with structured evaluation and report generation | LangGraph, Flask, Groq |
| [**Sports Agent**](https://github.com/ahmed-berrais/sports_agent) | Real-time sports data agent with live scores, standings, and match analysis | LangGraph, Flask, SerpAPI |
| [**Travel Agent**](https://github.com/ahmed-berrais/travel_agent) | Multi-tool travel planning agent with flights, hotels, weather, and itinerary generation | LangGraph, Flask, Amadeus API |
| [**OCR Agent**](https://github.com/ahmed-berrais/ocr_agent) | Multi-agent document extraction pipeline for Tunisian financial documents | LangGraph, Qwen VL, Flask |

---

### ⚡ CPU-Only LLM Deployment

I specialize in deploying LLMs on **CPU-only infrastructure** using llama.cpp, proving that production AI doesn't always need GPUs:

```
┌─────────────────────────────────────────────────────┐
│  Chatbot (Qwen 2.5 7B)                             │
│  → 9 tokens/sec · 12 CPU cores · 48GB RAM · No GPU │
├─────────────────────────────────────────────────────┤
│  OCR Pipeline (Qwen 2.5 7B VL + Corrector Model)   │
│  → Full extraction in ~90s · Image encoding +       │
│    ~1200 token processing · CPU-only · llama.cpp    │
│  → Passive workflow — no user wait time             │
└─────────────────────────────────────────────────────┘
```

---

### 🛠 Tech Stack

```text
Languages       Python · JavaScript · SQL
AI/ML           LangGraph · LangChain · llama.cpp · Cohere · Groq
Models          Qwen 2.5 7B · Qwen 2.5 7B VL · Llama 3
Frameworks      React · Flask · Vite
Infrastructure  Supabase · CPU-optimized inference · Linux servers
Tools           SerpAPI · Amadeus API · GitHub Actions
```

---

<p align="center">
  <i>Building AI systems that run anywhere — no GPU required.</i>
</p>
