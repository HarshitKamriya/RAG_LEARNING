# RAG Learning Repository

A comprehensive learning repository for **Retrieval-Augmented Generation (RAG)** - a powerful approach that combines large language models with external knowledge bases to generate more accurate, contextual, and up-to-date responses.

## 📚 Overview

This repository documents a complete learning journey through RAG concepts and implementations, from basic data ingestion to advanced multi-modal systems. Each section builds upon previous concepts with hands-on Jupyter notebooks and practical examples.

## 🗂️ Repository Structure

### **0-DataIngestParsing/** 📥
Foundation for RAG systems - learning how to ingest and parse various data formats:
- **1-dataingestion.ipynb** - Basic data ingestion techniques
- **2-dataparsingpdf.ipynb** - Extracting text from PDF files
- **3-dataparsingdoc.ipynb** - Parsing Word documents (.docx)
- **4-csvexcelparsing.ipynb** - Handling CSV and Excel files
- **5-jsonparsing.ipynb** - Processing JSON and JSONL data
- **6-databaseparsing.ipynb** - Extracting data from databases
- **data/** - Sample datasets including PDFs, JSON files, CSVs, and text files

### **1-VectorEmbeddingAndDatabases/** 🔢
Understanding embeddings and vector representations:
- **embedding.ipynb** - Introduction to embeddings and vectorization
- **openaiembeddings.ipynb** - Using OpenAI's embedding models

### **2-Vector Stores/** 🗃️
Exploring different vector database solutions for storing and retrieving embeddings:
- **1-chromadb.ipynb** - Chroma DB implementation
- **2-faiss.ipynb** - Facebook AI Similarity Search (FAISS)
- **3-Othervecotrstores.ipynb** - Alternative vector store options
- **4-Datastaxdb.ipynb** - DataStax vector database
- **5-PineconeVectorDB.ipynb** - Pinecone managed vector service

### **3-AdvancedChunking/** ✂️
Techniques for efficiently splitting documents:
- **1-semanticchunking.ipynb** - Context-aware document chunking strategies

### **4-Hybrid Search Strategies/** 🔍
Advanced retrieval techniques:
- **1-densesparse.ipynb** - Dense and sparse vector search combinations
- **2-reranking.ipynb** - Reranking retrieved documents for relevance
- **3-mmr.ipynb** - Maximal Marginal Relevance (MMR) search

### **5-QueryEnhancement/** 🎯
Improving query effectiveness:
- **1-queryexpansion.ipynb** - Expanding queries for better results
- **2-querydecomposition.ipynb** - Breaking down complex queries
- **3-HyDE.ipynb** - Hypothetical Document Embeddings

### **6-MultiModel RAG/** 🎨
Working with multiple modalities (text, images, etc.):
- **1-multimodalOPENAI.ipynb** - Multi-modal OpenAI implementations
- **1-multimodalopenai.ipynb** - Additional multi-modal examples

### **RAG WITH updated Langchain/** 🔗
Modern RAG implementation using LangChain framework:
- **1-lanchainintro.ipynb** - LangChain fundamentals
- **2-modelintegration.ipynb** - Integrating language models
- **3-tools.ipynb** - Using LangChain tools and utilities
- **4-Message.ipynb** - Message management and conversational flow
- **5-structuredoutput.ipynb** - Generating structured outputs
- **6-middleware.ipynb** - Middleware and custom chains

### **project_side_by_side/** 🚀
Practical projects and working examples:
- **working.ipynb** - Active development notebook

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab
- Required packages (see `requirements.txt`)

### Installation

1. **Clone/Download the repository**
   ```bash
   cd "RAG LEARNING"
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter**
   ```bash
   jupyter notebook
   ```

4. **Navigate to desired section** and open notebooks sequentially

## 📋 Learning Path

**Recommended order for beginners:**
1. Start with **0-DataIngestParsing** to understand data sources
2. Move to **1-VectorEmbeddingAndDatabases** for embedding concepts
3. Explore **2-Vector Stores** to learn storage solutions
4. Study **3-AdvancedChunking** for optimization techniques
5. Practice **4-Hybrid Search Strategies** for advanced retrieval
6. Enhance queries with **5-QueryEnhancement**
7. Scale up with **6-MultiModel RAG**
8. Implement with **RAG WITH updated Langchain**

## 🛠️ Technologies & Libraries

- **Data Processing**: pandas, numpy
- **Embeddings**: OpenAI API, sentence-transformers
- **Vector Stores**: Chroma, FAISS, Pinecone, DataStax
- **RAG Framework**: LangChain
- **PDF/Document Parsing**: pypdf, python-docx
- **LLMs**: OpenAI GPT models

## 📝 Main Entry Points

- **main.py** - Main Python script (if applicable)
- **pyproject.toml** - Project configuration
- **requirements.txt** - Package dependencies

## 🎓 Key Concepts Covered

- ✅ Data ingestion and preprocessing
- ✅ Vectorization and embeddings
- ✅ Vector database management
- ✅ Semantic chunking strategies
- ✅ Hybrid search approaches
- ✅ Query optimization and expansion
- ✅ Multi-modal information processing
- ✅ LangChain framework integration

## 💡 Tips

- Each notebook is self-contained and builds progressively
- Run cells sequentially to understand the flow
- Experiment with sample data first before using your own
- Check the `data/` folders for available sample files

## 📖 Resources

- [RAG Overview](https://en.wikipedia.org/wiki/Retrieval-augmented_generation)
- [LangChain Documentation](https://python.langchain.com/)
- [OpenAI API Docs](https://platform.openai.com/docs)
- [Vector Store Guides](https://www.pinecone.io/)

## 📝 Notes

This repository is a learning journey. Content is progressively updated as new concepts are explored and implemented.

---

**Happy Learning! 🚀**