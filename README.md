# Scalable Q&A System with LangChain and ChromaDB

This project showcases a scalable Question & Answer (Q&A) system that enables natural language querying across large unstructured documents. It integrates LangChain for orchestration, ChromaDB for efficient vector storage, and Huggingface embeddings for semantic understanding. The system is optimized for real-time performance and cost-efficient processing at scale.

## 🚀 Features

- 🔎 **Natural Language Querying**: Ask plain English questions and get accurate, context-aware answers.
- 📚 **Large Document Support**: Handles multi-format datasets, including URLs and CSVs.
- 🧠 **State-of-the-Art Embeddings**: Utilizes Huggingface embeddings for deep semantic indexing.
- ⚡ **Real-Time Information Retrieval**: Fast responses through live vector search and context-aware retrieval.
- 📦 **Optimized Storage**: Efficient tokenization and storage using ChromaDB for low-latency search.
- 💡 **Cost-Efficient Scaling**: Powered by MosaicML’s MPT-30B models to reduce computational overhead on large datasets.

## 🛠 Architecture Overview

```plaintext
[Data Sources: URLs, CSVs]
        ↓
[Document Processing Pipeline]
  - Tokenization
  - Embedding with Huggingface
        ↓
[Vector Storage in ChromaDB]
        ↓
[LangChain Q&A Interface]
  - Query Embedding
  - Similarity Search
  - Answer Generation
        ↓
[Real-Time Response]
