---
title: "Medical Assistant — RAG Question Answering"
excerpt: "Built a full retrieval-augmented question-answering pipeline over a medical reference manual using LangChain, ChromaDB, sentence-transformer embeddings, and local Mistral-7B inference, evaluated with an LLM-as-judge methodology."
collection: portfolio
---

Built a full retrieval-augmented question-answering pipeline over a medical reference manual: LangChain chunking (512 tokens, 50 overlap), sentence-transformer embeddings, a persisted ChromaDB vector store, top-k similarity retrieval, and local Mistral-7B-Instruct inference (GGUF-quantized, via llama.cpp) — evaluated with an LLM-as-judge methodology scoring retrieval and generation quality.

**Stack:** LangChain, ChromaDB, Sentence-Transformers, Mistral-7B, llama.cpp
