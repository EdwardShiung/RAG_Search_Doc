# RAG_Search_Doc

This document guides you through setting up a simple RAG (Retrieval-Augmented Generation) search environment using OpenAI, ChromaDB, and Sentence Transformers in a Jupyter Notebook.

---

## 1. Prerequisites

Make sure you have already installed the following tools:

- **uv**: [uv installation guide](https://docs.astral.sh/uv/getting-started/installation/)
- **Jupyter Notebook**: [Jupyter installation guide](https://jupyter.org/install)

---

## 2. Install Required Packages

Use `uv` to install the required dependencies:

```bash
    uv add sentence-transformers chromadb python-dotenv openai
```

## 3. Create or update your .env file in the project root:

```environment

    OPENAI_API_KEY=XXX
```

## 4. Use uv to launch your Jupyter Lab environment:

```bash
    uv add sentence-transformers chromadb python-dotenv openai
```
