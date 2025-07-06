# RAG-based Web Content Assistant 🌐💬

This project is an AI-powered assistant that performs Question Answering (QA) over web page content using a Retrieval-Augmented Generation (RAG) approach. It leverages LangChain's `WebBaseLoader` to extract and parse web content, FAISS for vector-based semantic search, and Gemini API to generate accurate, context-aware answers.

## 🚀 Features
- 🔗 Load and parse any public website using WebBaseLoader
- 🔍 Semantic search with FAISS on web content chunks
- 💡 Natural language QA using Gemini API
- 🌐 Clean, interactive UI built with Streamlit
- 📦 Lightweight, easily deployable (Streamlit Cloud or Docker-ready)

## 🛠️ Tech Stack
- Python
- LangChain
- Gemini API (Google Generative AI)
- FAISS (Facebook AI Similarity Search)
- Streamlit

## 📦 Installation

```bash
git clone https://github.com/your-username/rag-based-web-content-assistant.git
cd rag-based-web-content-assistant
pip install -r requirements.txt
streamlit run app.py

