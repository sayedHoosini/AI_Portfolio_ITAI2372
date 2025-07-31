# 🤖 In-Depth Case Study: Verba – A Modular RAG Application

**Date**: July 5, 2025  
**Course**: ITAI 2372 – AI Applications  
**Team Members**:  
- Hashim Sayed Hoosini  
- Michael Garcia  
- Miguel Mora  

---

## 📘 Project Overview

This case study explores Verba, an open-source Retrieval-Augmented Generation (RAG) application developed by Weaviate. Verba enables private, intelligent search and question-answering over user-provided documents using LLMs and vector search technologies. The project covers its core design, installation, challenges, and future potential.

---

## 🔧 What is Verba?

- **Open-source RAG tool** designed for document-based AI queries  
- **Built on modular architecture** for flexibility and privacy  
- **Combines vector search (Weaviate) with LLMs (LLAMA3)** to answer questions from uploaded documents  
- Focused on **local deployment, open-source LLM support**, and **transparent configuration**

---

## 🧠 Core Concepts

- **Tokenization**: Text is split into manageable tokens  
- **Vectorization**: Embeddings are created using models like LLAMA3  
- **Indexing**: Semantic search is enabled with Weaviate  
- **Retrieval + Generation**: Modular pipeline fetches and synthesizes answers

---

## 🖥️ Technical Stack

- **Frontend**: React  
- **Backend**: Python with FastAPI  
- **Vector Store**: Weaviate (Docker)  
- **LLM Engine**: Ollama (LLAMA3)  
- **Containerized**: Fully runnable with Docker

---

## ⚙️ Installation (Docker Method Used)

1. Clone the GitHub repo  
2. Set up `.env` file (model, port, log level)  
3. Edit `docker-compose.yml`  
4. Run: `docker compose up -d`  
5. Access app at: `http://localhost:8000`

---

## 🧪 Configuration Example

```env
MODEL=llama3
PORT=8000
LOG_LEVEL=info
```

- Supports local LLMs, OpenAI, and Cohere API keys  
- Deployable to AWS, GCP, or Azure  

---

## 💬 Demo Summary

- Uploaded `.txt`, `.pdf`, `.docx` documents  
- Asked custom questions in real-time via Verba chat interface  
- System booted in under 2 minutes  
- LLAMA3 provided relevant answers using semantic document retrieval  

---

## ⚠️ Challenges Encountered

- **WSL required** for Docker compatibility on Windows  
- **File format limitations**: No PowerPoint or Excel support  
- **Performance bottlenecks** with large files  
- **Requires Docker and command line basics**  

---

## 🚀 Future Improvements

- Multi-user environment  
- UI-based document management  
- Support for additional file formats  
- Enhanced privacy and document lifecycle control  
- Integration with more LLM backends and GPU acceleration  

---

## ✅ Conclusion

Verba showcases the potential of modular RAG tools for private, document-centric AI experiences. With simple configuration and local deployment, Verba is suitable for personal, academic, or enterprise use. It provides a real-world example of how open-source AI infrastructure can scale and adapt to different needs.

---

## 📚 References

- Weaviate – Verba Open-Source Blog (2024)  
- Erzedka – NLP Introduction (2025)  
- GitHub: https://github.com/weaviate/verba
