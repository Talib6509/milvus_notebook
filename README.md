# Milvus + LangChain Notebook

## Overview
This notebook demonstrates how to use **Milvus** as a vector database with **LangChain** to:
- Generate embeddings
- Store them in Milvus
- Perform similarity search

It serves as a basic foundation for building Retrieval-Augmented Generation (RAG) systems.

---

## Setup

### 1. Start Milvus (Docker)

```bash
wget https://github.com/milvus-io/milvus/releases/download/v2.3.0/milvus-standalone-docker-compose.yml -O docker-compose.yml
docker compose up -d
```

