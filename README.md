# RAG Assignment – Agentic AI

## Objective

Build a Retrieval-Augmented Generation (RAG) system that answers user queries based on custom documents.

---

## Features

* Document loading and preprocessing
* Text chunking
* Embedding generation
* Vector database storage
* Semantic search
* Context-aware answer generation

---

## Project Workflow

1. Load document (`sample.txt`)
2. Split text into chunks
3. Generate embeddings
4. Store in vector database
5. Retrieve relevant chunks
6. Send context + query to LLM
7. Generate final answer

---

## Tech Stack

* Python
* LangChain
* OpenAI API
* FAISS
* Jupyter Notebook

---

## Installation

Clone the repository:

```
git clone https://github.com/Paul-NIROB/agentic-ai.git
cd agentic-ai/Assignment1
```

Install dependencies:

```
pip install -r requirements.txt
```

Create a `.env` file:

```
OPENAI_API_KEY=your_api_key_here
```

Run the application:

```
python app.py
```

---

## Files Description

| File              | Description               |
| ----------------- | ------------------------- |
| app.py            | Main RAG application      |
| RAG_Project.ipynb | Development notebook      |
| sample.txt        | Sample knowledge document |
| requirements.txt  | Dependencies              |

---

## Future Improvements

* Add multi-document support
* Add web interface (Streamlit)
* Add memory (Agentic behavior)
* Add multi-modal RAG

---

## Author

**Prayutshu 2023827099**
