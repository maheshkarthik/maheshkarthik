<h1 align="center">Mahesh Duraisamy</h1>

<p align="center">
  <b>I build practical AI applications that keep your data where it belongs.</b><br/>
  Retrieval-augmented generation · Multi-agent systems · Local LLMs · Tested, documented, production-minded code
</p>

<p align="center">
  <a href="https://github.com/maheshkarthik/local-rag-document-assistant"><img src="https://img.shields.io/badge/Featured-Local_RAG_Document_Assistant-0A66C2?style=flat-square" alt="Featured project"/></a>
  <a href="https://github.com/maheshkarthik/multi-agent-research-assistant"><img src="https://img.shields.io/badge/New-Multi--Agent_Research_Assistant-2E7D32?style=flat-square" alt="New project"/></a>
</p>

---

## About me

I'm working through an **AI Engineering Lab**: a series of hands-on projects where each one is built the way real software should be. That means clear architecture, automated tests, honest documentation, and a setup anyone can run in minutes.

My focus is on AI that people can **trust**:

- **Grounded:** answers come from your documents, with citations you can check.
- **Private:** models run locally, so sensitive data never leaves your machine.
- **Verifiable:** the system checks its own output, and tests cover the parts that matter.

---

## Featured project

### [Local RAG Document Assistant](https://github.com/maheshkarthik/local-rag-document-assistant)

Chat with your PDFs, fully offline. Upload documents, ask questions in plain English, and get answers that cite the exact file and page.

<a href="https://github.com/maheshkarthik/local-rag-document-assistant"><img src="https://raw.githubusercontent.com/maheshkarthik/local-rag-document-assistant/main/docs/screenshot.png" alt="Local RAG Document Assistant answering a question with cited sources"/></a>

| Capability | How it works |
|---|---|
| **Hybrid search** | Semantic embeddings and BM25 keyword search merged with Reciprocal Rank Fusion, so it finds paraphrases *and* exact IDs, codes and numbers |
| **Citation checking** | Every citation the model produces is verified against the excerpts it was given; anything unsupported is flagged |
| **Runs on a laptop** | Local LLM through Ollama on an 8 GB Apple M2. No API keys, no cloud, no per-query cost |
| **Built to be tried** | 14 ready-made sample documents and a list of questions to test it with, including ones it should refuse to answer |
| **Tested** | 169 automated tests covering PDF processing, search, the RAG pipeline and the UI |

**Stack:** Python · Streamlit · ChromaDB · Ollama · pypdf

---

## AI Engineering Lab

| # | Project | What it explores | Status |
|---|---|---|---|
| 01 | [Local RAG Document Assistant](https://github.com/maheshkarthik/local-rag-document-assistant) | Chunking, hybrid retrieval, grounded generation, citation verification | ✅ Shipped |
| 02 | [Multi-Agent Research Assistant](https://github.com/maheshkarthik/multi-agent-research-assistant) | A planner, researchers, a reviewer and a writer that research the web and your PDFs and write cited reports; agent orchestration in plain Python, evaluated on six fixed questions | ✅ Shipped |

More projects are in progress. Each will ship with a runnable demo, sample data and tests.

---

## Toolbox

**AI and data:** retrieval-augmented generation, embeddings and vector search, BM25, local LLMs (Ollama), multi-agent orchestration, structured JSON output, LLM evaluation, prompt design<br/>
**Languages and frameworks:** Python, Streamlit<br/>
**Data stores:** ChromaDB<br/>
**Engineering practice:** unit and UI testing, clear documentation, reproducible setups
