# context-hub

Asynchronous RAG (Retrieval-Augmented Generation) pipeline using FastAPI and Vector Databases for intelligent document querying and context synthesis.

## About

This project provides a high-performance asynchronous RAG pipeline designed for intelligent document processing and context management.

### Key Technical Highlights

- **Framework**: FastAPI (Python 3.12+)
  - High-performance async API framework
  - Built-in data validation and serialization
  - Modern Python type hints support

- **Vector Store**: ChromaDB / Pinecone
  - Efficient similarity search capabilities
  - Scalable vector storage and retrieval
  - Support for multiple embedding dimensions

- **Processing**: Async document ingestion with Pydantic v2 validation
  - Non-blocking document processing pipeline
  - Strong type safety with Pydantic v2 models
  - Concurrent ingestion of multiple documents

- **LLM Integration**: OpenAI/Anthropic via LangChain or LlamaIndex
  - Flexible LLM provider support
  - Advanced retrieval strategies
  - Context-aware response generation
