# 🚀 Chat-RAG: Intelligent Document-Based Chatbot with Memory  

## 📝 Overview  

ChatRAG is a production-ready **Retrieval-Augmented Generation (RAG)** application designed to provide **intelligent, context-aware** responses based on stored documents. By leveraging **FastAPI, LangChain, ChromaDB, and SQLite**, this project enables efficient **document ingestion, chat session management, and seamless retrieval of historical context** to generate accurate answers.  

## 🛠 Technologies Used  

🚀 **FastAPI** – High-performance web framework for API development.  
🔗 **LangChain** – Orchestrates LLM-powered workflows.  
📊 **LangSmith** – Monitors and logs API interactions.  
🗂 **ChromaDB** – Stores document embeddings for fast retrieval.  
🧠 **OpenAI Embeddings** – Converts text into meaningful vector representations.  
🛢 **SQLite** – Lightweight database for session and metadata storage.  
🐍 **Python** – Core programming language powering the application. 

![image](https://github.com/user-attachments/assets/7a8afffd-4bd7-4d43-b845-5ba66cfe1f1c)


## 🎯 Project Goals  

✅ Seamless ingestion and storage of multiple document types for retrieval-based Q&A.  
✅ Implement **session-based chat** functionality, allowing users to have **context-aware conversations**.  
✅ Automate the **retrieval and refinement** of user queries using stored chat history and metadata.  
✅ Ensure robustness with **structured logging, exception handling**, and **monitoring** using LangSmith.  

## ⚡ Features  

🔹 **Multi-Document Ingestion**: Supports various document formats, extracting and embedding content using **OpenAI Embeddings**.  
🔹 **Vector Storage with ChromaDB**: Stores and retrieves document embeddings for **semantic search**.  
🔹 **Session-Based Chat**: Assigns **unique session IDs** and stores chat metadata in **SQLite** for history retrieval.  
🔹 **Context-Aware Responses**: Retrieves and refines past **chat history** to improve **answer relevance**.  
🔹 **FastAPI Backend**: Provides structured **API endpoints** for document uploads, chat interactions, and history retrieval.  
🔹 **LangChain Orchestration**: Manages **workflow automation** for efficient query processing.  
🔹 **Logging & Exception Handling**: Ensures **stability and reliability** with structured logging.  
🔹 **Monitoring with LangSmith**: Tracks **API performance, model latency,** and **request processing**.  

