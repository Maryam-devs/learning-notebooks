# RAG Pipeline (From Scratch, No Frameworks)

## Overview

This project implements a **Retrieval-Augmented Generation (RAG) system from scratch** without using frameworks like LangChain or LlamaIndex.

The goal is to understand how modern LLM applications work internally by building every component manually, including:
- document ingestion
- text chunking
- embeddings generation
- vector database storage (ChromaDB)
- similarity search
- LLM-based response generation (Groq)

---

---

## Features

- Load multiple PDF files
- Extract text using PyPDF
- Split text into overlapping chunks
- Generate embeddings using SentenceTransformers
- Store embeddings in persistent ChromaDB
- Perform semantic similarity search
- Build context-aware prompts
- Generate answers using Groq LLM
- Return responses grounded in retrieved documents

---

## Tech Stack

- Python
- PyPDF
- SentenceTransformers (`all-MiniLM-L6-v2`)
- ChromaDB
- Groq API 
- python-dotenv

---

## Key Concepts Learned

- Vector embeddings and semantic similarity
- How vector databases (ChromaDB) store and retrieve data
- Chunking strategies and their impact on retrieval quality
- End-to-end RAG system design
- Reducing hallucinations using context grounding

