# Retrieval-Augmented Generation (RAG) with ChromaDB and FAISS

This project demonstrates Retrieval-Augmented Generation (RAG) using Large Language Models (LLMs) combined with two vector stores: **ChromaDB** and **FAISS**. RAG enhances LLM capabilities by retrieving relevant context from a document corpus, making it ideal for domain-specific question answering, documentation bots, and knowledge-based search.



RAG stands for Retrieval-Augmented Generation — a method where:
1. A user's query is converted into an embedding.
2. Relevant documents are retrieved from a vector database (like ChromaDB or FAISS).
3. The retrieved context is passed along with the original query to a language model (like OpenAI GPT or HuggingFace models) to generate accurate, context-aware responses.

## Features

Plug-and-play support for **ChromaDB** and **FAISS**
 Fast and efficient document retrieval
Load and chunk custom documents (PDF, TXT, etc.)

## 🧱 Tech Stack

- Python 3.9+
- [LangChain](https://www.langchain.com/)
- [ChromaDB](https://www.trychroma.com/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [OpenAI API](https://platform.openai.com/) or HuggingFace Transformers

## 📁 Directory Structure

