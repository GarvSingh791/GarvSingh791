### Hi, I'm Garv Singh Saini 👋

**Software & AI/ML Engineer building production LLM systems, multi-agent pipelines, and full-stack apps.**

* **Former Undergraduate Research Assistant – Lead Researcher:** LLM Safety & Multi-Agent Systems
* **Former Undergraduate Research Assistant – Lead Researcher:** Meta Reality Labs (Project Aria) – Real-Time Data & ML Pipelines

| | |
|---|---|
| 🎯 **Looking for** | Internships and early-career roles in software and AI/ML engineering |
| 🔥 **My best work** | [**Atlas**](https://github.com/GarvSingh791/atlas-concur-ai): a full-stack, SAP Concur-style travel & expense app with a RAG policy assistant that cites the exact clause or abstains. **[Try the live demo](https://atlas-concur-ai.vercel.app)** |
| 🧪 **What I do differently** | I measure my systems and test my tests: my faithfulness score sat at 0.775 until I found the bug was in my judge, not my model. After the fix: **0.981**, zero confirmed hallucinations |
| 🧰 **Core stack** | Python · FastAPI · TypeScript · Next.js · PostgreSQL + pgvector · LangGraph · Docker · GitHub Actions |

---

### 🧭 Featured: Atlas

My dad has used SAP for as long as I can remember. I never really understood what it did, so I spent months finding out by building a piece of it: an independent engineering study of SAP Concur-style travel & expense.

<table>
<tr>
<td width="62%">

Plan a trip → capture receipts → approve → reimburse → audit, for three roles.

- **Full stack:** FastAPI (14 modules, 80 endpoints), Next.js 14, PostgreSQL + pgvector
- **Hybrid RAG:** dense + full-text retrieval, rank fusion, cross-encoder rerank, calibrated abstention
- **Measured:** recall@10 0.819 → 0.959 with a live reranker; 0.981 LLM-judged faithfulness
- **Shipped:** 7-job CI that deploys only the commit it tested; 4,200+ pytest and 970+ Vitest tests

**[Live demo](https://atlas-concur-ai.vercel.app)** · **[Code and docs](https://github.com/GarvSingh791/atlas-concur-ai)**

</td>
<td width="38%">

<a href="https://github.com/GarvSingh791/atlas-concur-ai"><img src="https://raw.githubusercontent.com/GarvSingh791/atlas-concur-ai/main/docs/assets/atlas-demo-poster.png" alt="Atlas: policy assistant answering with clause citations"></a>

</td>
</tr>
</table>

---

### 💼 Experience

**Lead Researcher, LLM Safety & Multi-Agent Systems** · University of the Fraser Valley · *Jan 2025 – Sep 2026*
Built a multi-agent LLM evaluation framework (LangGraph, FastAPI) across 4 models for threat detection, lifting F1 from 83.8% to 98.2%. Fine-tuned Llama-3.1-70B with QLoRA on dual A100 80GB GPUs and shipped the backend and MLOps stack as the sole engineer.

**Lead Researcher, Meta Reality Labs (Project Aria)** · University of the Fraser Valley · *Sep 2024 – Aug 2026*
Trained perception models (YOLO11m, SlowFast R50) on 500+ GB of egocentric video; built real-time ETL pipelines and on-device FP16/INT4 optimizations (OpenVINO).

**Lab Monitor, Technical Support & System Administration** · University of the Fraser Valley · *Jan 2024 – Apr 2026*
First-line support for 1,000+ students; cut lab downtime by 30%.

---

### 📂 Public projects

| Project | What it is | Stack |
|---|---|---|
| [**atlas-concur-ai**](https://github.com/GarvSingh791/atlas-concur-ai) | Travel & expense copilot with policy-aware agents and RAG with calibrated abstention | FastAPI, Next.js, PostgreSQL + pgvector |
| [**Sketchagent**](https://github.com/GarvSingh791/Sketchagent) | Multi-agent pipeline that turns hand-drawn wireframes into deployed Next.js sites | LangGraph, FastAPI, Next.js, WebSocket, MCP |
| [**local-rag-intel**](https://github.com/GarvSingh791/local-rag-intel) | Fully local, privacy-first RAG on Intel hardware: no data leaves the machine | LlamaIndex, ChromaDB, Ollama, OpenVINO |
| [simple-local-rag](https://github.com/GarvSingh791/simple-local-rag) | A fork of an open-source tutorial I used to learn local RAG from scratch | Jupyter, PyTorch |

---

### 🔎 What I care about

- **Ground it, or abstain.** An AI that says "the policy is silent on this" is a feature.
- **Test the tests.** Measure the evaluator before you trust the score.
- **Deploy what CI tested,** and verify it from the running service.

### 📬 Open to

Internships and early-career roles in software and AI engineering. Feedback on my projects is welcome, especially the critical kind: open an issue or reach out on LinkedIn.

<sub>Atlas is an independent project, not affiliated with or endorsed by SAP. All data is synthetic.</sub>
