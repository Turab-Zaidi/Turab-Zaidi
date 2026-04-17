<div align="center">

![Banner](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Mohd%20Turab%20Zaidi&fontSize=52&fontColor=fff&animation=twinkling&fontAlignY=35&desc=AI%20Engineer%20%7C%20CS%20Student%20%7C%20Builder&descAlignY=57&descSize=20)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=6AD3F7&center=true&vCenter=true&width=600&lines=Building+AI+systems+that+work+in+production;Computer+Vision+%2B+NLP+%2B+Agentic+AI)](https://git.io/typing-svg)

<br/>

[![Email](https://img.shields.io/badge/Gmail-turab.z567@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:turab.z567@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-turabzaidi0104-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/turabzaidi0104)

</div>

---

## 🧠 Who am I?

Final-year CS student @ **Jamia Millia Islamia** (CGPA: 8.5/10). I build AI systems at the intersection of **Computer Vision**, **NLP**, and **Agentic AI** — the kind that actually ship, not just score well on benchmarks.

Two things I spend most of my time on:

- **Model Engineering** — VLMs, cross-attention bridges, LoRA fine-tuning, quantization. Not just API wrappers.
- **Agentic Systems** — Multi-agent pipelines with LangGraph where agents reason, retrieve context, and self-correct. Less chatbot, more autonomous analyst.


---

## 🛠️ Tech Stack

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C/C++](https://img.shields.io/badge/C/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### AI / ML
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6B6B?style=for-the-badge&logo=graph&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### Data Science
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-1B813E?style=for-the-badge&logo=nltk&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

### Cloud & Tools
![AWS](https://img.shields.io/badge/AWS_(EC2,S3,Lambda)-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 📈 Auto-Quant Analyst
**Multi-Agent Hedge Fund Intelligence System**

[Repo →](https://github.com/Turab-Zaidi/Auto-Quant-Analyst)

Stateful multi-agent system using LangGraph to automate institutional-grade equity research. A Quant Coder agent writes + executes LLM-generated Python in an isolated Docker sandbox. Data pipeline with SEC EDGAR and FRED APIs, Redis caching for 90%+ latency reduction.

`LangGraph` · `Llama 3.1 70B/8B` · `Redis` · `yFinance` · `SEC EDGAR`

</td>
<td width="50%" valign="top">

### 🛡️ Supply-Chain Agent
**Autonomous Vendor Risk Auditor**

[Repo →](https://github.com/Turab-Zaidi/Supply-Chain-Agent)

Enterprise-grade agent with dual-LLM routing: cheap 8B model classifies intent, expensive 70B model reasons. SQLite stateful memory for contextual follow-ups. Compliance guardrails with automatic PII redaction. Chains weather, finance, and news APIs per supplier.

`LangGraph` · `NVIDIA NIM` · `SQLite Checkpointer` · `Tavily` · `yFinance`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 Multimodal Financial RAG
**Reasoning over 10-K SEC Filings**

[Repo →](https://github.com/Turab-Zaidi/Advanced-Rag)

Multimodal RAG pipeline using IBM Docling for layout-aware parsing. LLM-generated Semantic Bridge summaries for precise table indexing. HyDE + Cross-Encoder reranking + Gemini 2.5 for visual reasoning over charts. Benchmarked with Judge-LLM: **0.90 Faithfulness** · **0.93 Relevance**.

`Docling` · `HyDE` · `Cross-Encoder` · `Gemini 2.5` · `ChromaDB`

</td>
<td width="50%" valign="top">

### 🔄 Corrective RAG
**Mission-Critical Aviation RAG**

[Repo →](https://github.com/Turab-Zaidi/Corrective_RAG)

CRAG pipeline for FAA maintenance documentation. Dedicated 8B evaluator grades every retrieved chunk (0.0–1.0) and dynamically branches: CORRECT uses local data, AMBIGUOUS supplements with web search, INCORRECT falls back entirely to web. Explainable citations with confidence scores.

`Docling` · `ChromaDB` · `Cross-Encoder` · `Llama 3.1 8B` · `Tavily`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏥 OmniMed
**Medical Vision-Language Model**

[Repo →](https://github.com/Turab-Zaidi/OmniMed)

Custom VLM: BiomedCLIP vision encoder (PubMedBERT backbone) → linear projector → LLaMA 3.1 8B with 4-bit NF4 quantization. Trained with LoRA on medical imaging datasets for visual question answering and report generation.

`BiomedCLIP` · `LLaMA 3.1 8B` · `4-bit Quant` · `LoRA` · `PyTorch`

</td>
<td width="50%" valign="top">

### 🎓 StudentHub AI
**Agentic Academic Assistant**

[Repo →](https://github.com/Turab-Zaidi/Student_hub)

Intent classifier routes to modular tools: RAG-based document Q&A over uploaded PDFs (ChromaDB), quiz generation, content summarization, and DuckDuckGo fallback for out-of-domain queries. Streamlit chat UI with persistent session history.

`LangGraph` · `ChromaDB` · `Gemini` · `Streamlit` · `DuckDuckGo`

</td>
</tr>
</table>

---

## 🏆 Achievements

| Achievement | Details |
|:---|:---|
| 🥇 **Amazon ML Competition 2025** | Ranked **42nd globally** out of 82,000+ registered teams — top 0.05% |
| 🏆 **Ukumi AI Hackathon 2024** | **1st Place (Winner)** among 60+ competing teams — built VLM-powered logo replacer + LaMa inpainting pipeline |

---

## 💼 Experience

| Role | Organization | Period |
|:---|:---|:---|
| **Data Engineer Intern** | The Man Company, New Delhi | Nov 2025 – Feb 2026 |
| **AI Engineering Intern** | Ukumi, New Delhi | Sept 2025 – Oct 2025 |
| **Intern Data Scientist** | IIIT Delhi | Nov 2024 – Jan 2025 |

---

## 📜 Certifications

- **Responsible and Safe AI** — IIIT Hyderabad
- **Introduction to LLMs** — IIT Madras

---

