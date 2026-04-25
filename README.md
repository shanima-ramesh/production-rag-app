# Production RAG Application

A Retrieval-Augmented Generation (RAG) app that answers questions 
from your own PDF documents using LLaMA 3 + ChromaDB.

## Tech Stack
- LangChain
- Groq API (LLaMA 3.1)
- ChromaDB (Vector Database)
- HuggingFace Embeddings
- Gradio (UI)
- Google Colab

## How it Works
1. Upload any PDF document
2. Document is split into chunks and stored as vectors
3. Ask any question about the document
4. LLaMA 3.1 retrieves relevant chunks and generates an answer

## Installation
pip install langchain langchain-groq langchain-community 
langchain-huggingface chromadb pypdf sentence-transformers gradio

## Setup
Set your Groq API key:
GROQ_API_KEY=enter the api_key
