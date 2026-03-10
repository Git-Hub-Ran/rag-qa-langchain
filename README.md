# RAG Web QA with LangChain

This project implements a Retrieval-Augmented Generation (RAG) pipeline using LangChain.

## Overview

The system:
1. Loads external web documents (New York Governor news + Wikipedia page).
2. Splits documents into chunks.
3. Creates embeddings using OpenAI.
4. Stores embeddings in Chroma vector database.
5. Uses a retriever to fetch relevant chunks.
6. Generates answers using an LLM (gpt-4o-mini).

## Technologies Used

- LangChain (v0.3.27)
- ChromaDB
- OpenAI Embeddings
- UnstructuredURLLoader
- Google Colab

## How It Works

User Question → Retriever → Relevant Document Chunks → LLM → Final Answer
