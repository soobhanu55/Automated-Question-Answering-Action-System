# LLM + RAG Based Function Execution API

An **LLM-powered Retrieval-Augmented Generation (RAG) system** that interprets natural language queries, retrieves relevant context using vector search, and dynamically executes the appropriate function or code pipeline.

The system demonstrates how **LLMs can act as reasoning engines that trigger real system actions**, combining semantic retrieval, intent detection, and tool execution.

---

## Key Features

- Retrieval-Augmented Generation (RAG) with vector similarity search  
- Intent detection for mapping queries to executable functions  
- Context-aware reasoning with memory handling  
- Hybrid retrieval (keyword + embedding search)  
- Modular execution pipeline for scalable AI workflows  

---

## System Flow
User Query
Intent Detection (LLM)
Context Retrieval (Vector Store)
Function Selection
Execution Layer
LLM Response

---

## Tech Stack

- Python  
- Large Language Models (LLMs)  
- Retrieval-Augmented Generation (RAG)  
- Vector Embeddings & Semantic Search  
- LangChain-style execution pipelines  
- Jupyter Notebook  

---

## Setup

```bash
git clone https://github.com/your-username/llm-rag-function-execution.git
cd llm-rag-function-execution
pip install -r requirements.txt
jupyter notebook "LLM RAG Execution.ipynb"
