# Retrieval-Augmented Generation (RAG) with ChromaDB, FAISS, and LangChain

This project demonstrates **Retrieval-Augmented Generation (RAG)** using **Large Language Models (LLMs)** in combination with vector stores **ChromaDB** and **FAISS**, powered by the **LangChain** framework. RAG enhances LLM capabilities by injecting relevant, retrieved context from document corpora to produce accurate, domain-specific, and grounded responses.


**Retrieval-Augmented Generation (RAG)** is a three-step process designed to enhance the performance and factual accuracy of Large Language Models (LLMs):

1. **Retrieval**: 
   The user's query is converted into an embedding and compared against a vector database (ChromaDB and FAISS) to fetch semantically relevant document chunks.

2. **Augmentation**: 
   The retrieved context is combined with the original query to enrich it. This augmented input ensures the LLM has domain-specific or updated context.

3. **Generation**: 
   A Large Language Model (llama 3.2:3B model) generates a response based on the augmented prompt, producing more grounded and accurate answers.

This improves factual accuracy, allows access to up-to-date information, and reduces hallucinations in LLM outputs.

## Features

- Plug-and-play integration with **ChromaDB** and **FAISS**
- Document preprocessing and chunking using **LangChain**
- Embedding generation with **HuggingFace Embeddings**
- LLM utilised **LLAMA3.2:3B**
- Seamless querying through a LangChain retrieval chain
- Support for custom data (TXT, PDF, Markdown, etc.)




