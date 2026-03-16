# AI RAG Stock Research Agent

<img src="https://i.ytimg.com/vi/JOP-FaPXIps/maxresdefault.jpg" alt="AI RAG Overview" width="800">

A **Python‑based Retrieval‑Augmented Generation (RAG) agent** for automated financial risk analysis of SEC 10‑K filings. This agent processes **20GB+ of Alphabet Inc. filings**, embeds each section with **OpenAI’s text‑embedding‑3‑small**, and performs **semantic search via LlamaIndex**. Using a **ReAct workflow with GPT‑4.1 mini**, it produces **structured, evidence‑backed risk scores (1–5)** across multiple risk categories, including financial, operational, regulatory, and macroeconomic exposures.

---

## Key Features

- **Massive document handling:** Efficiently processes thousands of pages of SEC filings.  
- **Vectorized search:** Semantic retrieval of any financial disclosure in **sub‑second latency**.  
- **Automated risk scoring:** Generates structured risk scores strictly based on document evidence.  
- **Tool‑based workflow:** Combines LLM reasoning with retrieval tools for accurate, repeatable analysis.  

---

## Tech Stack

Python, LlamaIndex, OpenAI GPT‑4.1 mini, OpenAI text‑embedding‑3‑small

---

## Example Workflow

This diagram shows how the agent processes filings, embeds content, performs semantic retrieval, and generates risk scores.

---

## Installation

```bash
git clone https://github.com/yourusername/ai-rag-stock-agent.git
cd ai-rag-stock-agent
pip install -r requirements.txt
