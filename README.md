# OllamaRAG (RAG from Scratch)

A beginner-friendly **Retrieval-Augmented Generation (RAG)** project that lets you **chat with your own documents** locally (free) using:

- **FAISS** for vector storage + similarity search
- **Hugging Face / SentenceTransformers** for embeddings
- **Ollama** (local LLM) for answer generation
- **LangChain** for orchestration

---

## Features

- Load a `.txt` document (example: `data/company_policy.txt`)
- Split text into chunks for better retrieval
- Create embeddings locally (no paid API required)
- Store vectors in a FAISS index
- Retrieve top-k relevant chunks for any question
- Generate grounded answers using an Ollama model (e.g., `phi3:mini`)

---

## Project Structure

```text
rag-from-scratch/
├─ app/
│  ├─ __init__.py
│  ├─ main.py
│  ├─ document_loader.py
│  ├─ vector_store.py
│  └─ rag_chain.py
├─ data/
│  └─ company_policy.txt
├─ requirements.txt
├─ .gitignore
└─ README.md
```
