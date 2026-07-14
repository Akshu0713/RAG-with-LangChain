# 📚 LangChain RAG Pipeline using ChromaDB

A complete Retrieval-Augmented Generation (RAG) pipeline built with **LangChain**, **ChromaDB**, and **Hugging Face Embeddings**.

The project demonstrates how to ingest PDF documents, split them into chunks, generate embeddings, store them in a vector database, and retrieve relevant information using semantic search.

---

# 🚀 Features

- 📄 PDF Document Ingestion
- ✂️ Intelligent Text Chunking
- 🔍 Semantic Search
- 🧠 Hugging Face Sentence Transformer Embeddings
- 💾 ChromaDB Vector Database
- ⚡ Fast Document Retrieval
- 📚 Multi-document Support
- 🔗 LangChain Integration

---

# 🛠 Tech Stack

- Python
- LangChain
- ChromaDB
- HuggingFace Embeddings
- Sentence Transformers
- Unstructured
- NLTK

---

# 📂 Project Structure

```
LangChain-RAG/
│
├── 6_2_1_langchain_rag_doc_ingestion.ipynb
├── 6_2_2_langchain_rag_retrieval.ipynb
├── requirements.txt
├── README.md
│
├── data/
│   ├── Evolution.pdf
│   └── Ecosystem.pdf
│
└── images/
    ├── workflow.png
    ├── ingestion_pipeline.png
    ├── retrieval_pipeline.png
    └── semantic_search.png
```

---

# 📌 Project Workflow

```
          PDF Documents
                │
                ▼
      LangChain Document Loader
                │
                ▼
         Text Splitter
                │
                ▼
 HuggingFace Embeddings Model
                │
                ▼
        Chroma Vector Store
                │
                ▼
      Similarity Search
                │
                ▼
    Retrieved Context
                │
                ▼
      LLM Response
```

---

# 📄 Dataset

The project uses two PDF documents as the knowledge base:

- Evolution
- Ecosystem

These PDFs are loaded, processed into chunks, embedded, and indexed inside ChromaDB for semantic retrieval.

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/langchain-rag.git

cd langchain-rag
```

Create a virtual environment

Windows

```bash
python -m venv venv

venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv venv

source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

### Step 1

Run

```
6_2_1_langchain_rag_doc_ingestion.ipynb
```

This notebook:

- Loads PDF documents
- Splits documents into chunks
- Creates embeddings
- Stores vectors in ChromaDB

---

### Step 2

Run

```
6_2_2_langchain_rag_retrieval.ipynb
```

This notebook:

- Loads the Chroma database
- Performs semantic similarity search
- Retrieves the most relevant document chunks

---

# 📦 Dependencies

- langchain-community
- langchain-classic
- langchain-text-splitters
- langchain-huggingface
- langchain-groq
- chromadb
- langchain-chroma
- sentence-transformers
- unstructured
- nltk

---

# 💡 Key Concepts

This project demonstrates:

- Retrieval-Augmented Generation (RAG)
- Document Chunking
- Embedding Generation
- Vector Databases
- Semantic Search
- Similarity Retrieval
- LangChain Pipelines
- Knowledge Base Construction

---

# 🚀 Future Improvements

- Integrate Llama 3 / GPT-4 / Gemini
- Conversational RAG
- Hybrid Search (Keyword + Vector)
- Streamlit Web Interface
- FAISS Support
- Pinecone Integration
- Qdrant Integration
- Metadata Filtering
- Source Citation
- Multi-PDF Upload

---

# 📸 Demo Images

```
images/
│── workflow.png
│── ingestion_pipeline.png
│── retrieval_pipeline.png
│── semantic_search.png
```

---

# 🎯 Learning Outcomes

After completing this project, you'll understand:

- How RAG works
- How embeddings are generated
- How ChromaDB stores vectors
- How semantic retrieval works
- How LangChain orchestrates the RAG pipeline
- How to build a document-based AI assistant

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

# 👨‍💻 Author

**Akshat Gupta**

AI Engineer | Generative AI | LLMs | RAG | LangChain | LangGraph | MCP | Vector Databases | Python
