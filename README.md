# RAG-Based Chatbot with Google Gemini & Pinecone using n8n

This repository contains an **end-to-end Retrieval-Augmented Generation (RAG) chatbot** implemented in **n8n**.  
It integrates **Google Gemini embeddings**, **Pinecone vector storage**, and **AI Agents** to create a fully automated workflow for document ingestion and intelligent Q&A.

---

## 🚀 Features
- 📂 **Automatic Document Ingestion** from Google Drive
- 🧩 **Recursive Character Text Splitting** (500 chars, 10% overlap)
- 🔍 **Vector Embeddings** with Google Gemini
- 📦 **Pinecone Vector Store** for scalable retrieval
- 🤖 **AI Agent with Gemini Chat Model** for context-aware responses
- 🔄 Fully automated workflow in **n8n**

---

## 📐 Workflow Architecture

### A. Document Ingestion Pipeline
- Google Drive Trigger → File Download → Text Splitter → Gemini Embeddings → Pinecone

  

### B. Retrieval & Chatbot Pipeline
- User Query → Gemini Chat Model → AI Agent → Pinecone Retriever → Response



---


