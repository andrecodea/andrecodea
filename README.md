<div align="center">
  <h1 align="center">Hi, I'm André Codea 👋</h1>
  <h3>Jr. AI/ML Engineer | LLMOps Analyst | Cognitive Architect</h3>
  
  <p align="center">
    Building the bridge between <strong>Deterministic Engineering</strong> and <strong>Probabilistic AI</strong>.
  </p>

  <div>
    <a href="https://www.linkedin.com/in/andrecodea/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:codeajr@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://www.datacamp.com/portfolio/andrecodea" target="_blank">
      <img src="https://img.shields.io/badge/DataCamp-Portfolio-05192D?style=for-the-badge&logo=datacamp&logoColor=03E860" alt="DataCamp" />
    </a>
  </div>
</div>

<br/>

## ⚡ About Me

I am a **Jr. AI Engineer** and **Computer Science** student focused on architecting autonomous intelligent systems. My expertise lies in **LLMOps** and **Prompt Engineering**. I am driven by the tangible impact that my solutions generate and potentialize. In my free time, I like to play videogames, study, code, lift weights, and cook! 

Currently, I'm focused on engineering **Machine Learning Systems**, **Cognitive Systems**, and preparing for the **Microsoft Azure AI Fundamentals (AI-900)** certification (wish me luck!).

---

## 🛠️ The Tech Stack

### 🧠 AI & Orchestration
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF4F00?style=for-the-badge&logo=graphql&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### 🔭 LLMOps, Observability & PromptOps
![LangSmith](https://img.shields.io/badge/LangSmith-000000?style=for-the-badge&logo=databricks&logoColor=white)
![PromptOps](https://img.shields.io/badge/Prompt%20Engineering-4B0082?style=for-the-badge&logo=openai&logoColor=white)
![Supabase](https://img.shields.io/badge/pgvector%20(Supabase)-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=for-the-badge&logo=firebase&logoColor=white)

### 💻 Engineering & Backend
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### ☁️ Cloud, DevOps & Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Coolify](https://img.shields.io/badge/Coolify-6B21A8?style=for-the-badge&logo=serverless&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### 📊 Data Science & Machine Learning
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5600?style=for-the-badge&logo=xgboost&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

---

## 🌟 Featured Projects & Architectures

### 🔍 Deep Research System with RAG via HITL ([Repo](https://github.com/andrecodea/agentic-deep-research))
> *Multi-agent research pipeline with semantic memory and knowledge curation via HITL.*
- **Architecture:** Orchestrated an advanced `StateGraph` using **LangGraph** featuring four specialized agents (Orchestrator, Router, Researcher, Writer).
- **Control:** Implemented **Human-in-the-Loop (HITL)** breakpoints for knowledge base curation in **ChromaDB**, ensuring zero hallucinations before web searches via **Tavily API**.
- **Observability:** Full-node tracing and **PromptOps** via **LangSmith**, exposing reasoning traces through a mandatory `<thought>` protocol before any tool call.
- 🏷️ `LangGraph` `LangSmith` `HITL` `ChromaDB` `PromptOps`

### 📈 Financial Research Agentic API ([Repo](https://github.com/andrecodea/financial-research-agentic-api))
> *Real-time market analysis API with Generative UI and aggressive payload compression.*
- **Optimization:** Slashed token consumption by **60%** (from ~100k to ~40k) via a payload compression pipeline (JSON → CSV + pruning).
- **Telemetry:** Actively monitored Time To First Token (TTFT) and latency via **LangSmith**.
- **UX Innovation:** Delivered real-time financial dashboards via **Generative UI (Thesys SDK)**, orchestrating LangChain and Yahoo Finance with Chain-of-Thought reasoning.
- 🏷️ `FastAPI` `LangChain` `GenUI` `LangSmith`

### 🤖 Multi-Agent Productivity System (MCP & RAG) ([Repo](https://github.com/andrecodea/multi-agent-productivity-system-with-mcp))
> *Cognitive Operating System for personal productivity via Telegram, governed by strict guardrails.*
- **Memory:** Three-tiered architecture inspired by the Atkinson-Shiffrin model (Sensory buffer in PostgreSQL, Short-term window, Daily consolidation via RAG in Supabase/pgvector) using **Llama 3.3 70B**.
- **Security:** Deployed guardrails using **Llama 3.1 70B** (0.7 threshold) for NSFW and jailbreak detection.
- **Orchestration:** Integrated specialized sub-agents (Calendar, Gmail, Tasks) via **Model Context Protocol (MCP)** with mandatory Chain-of-Thought reasoning.
- 🏷️ `n8n` `MCP` `Supabase/pgvector` `Llama 3.1`

### 🛒 Retail Demand Forecasting & Sales Analytics ([Repo](https://github.com/andrecodea/retail-demand-forecasting-and-analytics))
> *Dashboard for Sales Intelligence, Customer Clustering, and AI-driven narrative reporting.*
- **Machine Learning:** Built a customer segmentation pipeline via **K-Means** and a weekly revenue forecasting model using **Prophet** with 95% confidence intervals.
- **Observability:** Tracked LLM latency in real-time via token-by-token streaming (TTFT P50: ~800ms).
- **Reporting:** Generated narrative PDF reports combining ML trends with LLM analysis via ReportLab.
- 🏷️ `Python` `Scikit-learn` `Prophet` `Streamlit`

---

## 📊 GitHub Analytics

<div align="center">
  <a href="https://stats.hyo.dev/stats/andrecodea"><img src="https://stats.hyo.dev/api/github-stats-advanced?login=andrecodea" width="600" /></a>
  <br/>
  <br/>
  <a href="https://stats.hyo.dev/stats/andrecodea"><img src="https://stats.hyo.dev/api/github-trophies?login=andrecodea" width="600" /></a>
</div>

---

<p align="center">
  Let's build the future of autonomous systems. 🚀
</p>
