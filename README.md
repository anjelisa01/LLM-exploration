# LLM Exploration Projects

This repository contains two experimental notebooks exploring key techniques in modern NLP using Large Language Models (LLMs). The projects demonstrate retrieval-augmented generation (RAG), summarization, and basic experiment tracking.

## Contents

### 1. **RAG with LangChain, FAISS, and FLAN-T5**
- Loads an AI-generated FAQ PDF about a chatbot as the knowledge base.
- Uses **LangChain** and **FAISS** to implement document chunking, embedding, and vector retrieval.
- Applies **FLAN-T5** as the summarization model for responses.
- Mimics a lightweight Q&A system using local retrieval + LLM generation.

Notebook: `LLM_pdfRAGchatbot.ipynb`

### 2. **Simple Text Summarization with Logging**
- Uses **FLAN-T5-base** to summarize free-form text inputs.
- Adds functionality to **log summarization outputs** for analysis or evaluation.
- Logging the results for testing prompt quality and model behavior on different text types.

Notebook: `LLM_simple_summarization.ipynb`

## Models & Tools
- [FLAN-T5 (base)](https://huggingface.co/google/flan-t5-base)
- LangChain
- FAISS
- PyPDF / PDF extraction
- Hugging Face Transformers
- Python logging
