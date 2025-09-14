# 📚 LangChain for RAG Workflows

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](#)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)](#)
[![LangChain](https://img.shields.io/badge/LangChain-RAG-green)](#)

This repository contains my training exercise on building
**Retrieval-Augmented Generation (RAG)** workflows using **LangChain**.\
The notebook demonstrates how to load, chunk, embed, and query text data
using a language model, with **Alice's Adventures in Wonderland** as the
sample corpus.

------------------------------------------------------------------------

## 📖 Contents

-   `Langchain_for_RAG_Workflows.ipynb` -- Jupyter Notebook covering:
    -   Loading text documents (`alice_in_wonderland.txt`)
    -   Splitting content into chunks
    -   Creating embeddings for semantic search
    -   Building a vector store
    -   Querying with a language model in a RAG pipeline
-   `alice_in_wonderland.txt` -- Sample dataset (Project Gutenberg
    edition of *Alice's Adventures in Wonderland* by Lewis Carroll)

------------------------------------------------------------------------

## 🚀 How to Use

### 1) Clone this repository

``` bash
git clone https://github.com/your-username/langchain-rag-workflows.git
cd langchain-rag-workflows
```

### 2) Create and activate a virtual environment (recommended)

``` bash
python -m venv venv
source venv/bin/activate   # On Linux / macOS
venv\Scripts\activate    # On Windows
```

### 3) Install dependencies

``` bash
pip install -r requirements.txt
```

### 4) Launch Jupyter Notebook

``` bash
jupyter notebook Langchain_for_RAG_Workflows.ipynb
```

------------------------------------------------------------------------

## 🛠️ Requirements

Core dependencies include: - `langchain` - `openai` - `tiktoken` -
`faiss` or `chromadb` - `jupyter` - `python-dotenv`

*(Exact dependencies should be listed in `requirements.txt` if
provided.)*

------------------------------------------------------------------------

## 📌 Notes

-   The notebook demonstrates a **basic RAG pipeline**: Load → Split →
    Embed → Store → Retrieve → Generate.
-   The dataset (`alice_in_wonderland.txt`) is from **Project
    Gutenberg** and serves as an example for retrieval tasks.
-   You can replace `alice_in_wonderland.txt` with your own text corpus
    to adapt the workflow.

------------------------------------------------------------------------

## 📜 License

This project is for **educational purposes** only.\
*Alice's Adventures in Wonderland* is in the public domain via Project
Gutenberg.
