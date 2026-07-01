# Acko-Insurance-AI-Platform
# 🛡️ Acko Insurance AI Assistant

An interactive AI web dashboard built for Acko Insurance. It allows customers to ask questions about policy booklets and get instant answers using a Retrieval-Augmented Generation (RAG) pipeline.

## ✨ Core Features
* **AI Policy Chatbot**: Answers customer queries accurately using real Acko policy PDFs.
* **Smart Search**: Uses ChromaDB and Google Gemini embeddings to find relevant clauses.
* **Hallucination Protection**: Strict prompt rules force the AI to answer using *only* provided documents.
* **Cloud Logging**: Saves chat histories automatically to a secure PostgreSQL database on Render.
* **Claims Portal UI**: Interactive frontend template equipped for vehicle damage image uploads.

## 🛠️ Tech Stack
* **AI Engine**: LangChain & Google Gemini API (`gemini-2.5-flash`)
* **Vector Database**: ChromaDB
* **Cloud Database**: PostgreSQL & SQLAlchemy
* **Frontend UI**: Streamlit
