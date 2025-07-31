# 📚 Final Project – Verba: Retrieval-Augmented Generation (RAG) Application

**Course**: ITAI 2372 – AI Applications  
**Presentation Date**: July 31, 2025  
**Team Members**:  
- Hashim Sayed Hoosini  
- Miguel Mora  
- Michael Garcia  

---

## 🧠 Project Title

**Verba – A Modular RAG Application for Private AI-Powered Document Analysis**

---

## 🎯 Project Overview

This final project showcases Verba, an open-source Retrieval-Augmented Generation (RAG) application built by Weaviate. Verba allows users to ask intelligent questions based on their own documents—without relying on external sources. By combining modular components like chunking, tokenization, embedding, and vector search with powerful LLMs like LLAMA3, Verba exemplifies the future of personalized, privacy-first AI.

---

## 🧩 Core Concepts Covered

- **Chunking**: Breaks large documents into small, manageable text segments  
- **Tokenization**: Splits text into smaller units (tokens) for processing  
- **Embedding / Vectorization**: Converts text chunks into numeric representations for semantic search  
- **Indexing**: Organizes chunks for fast and context-aware retrieval  
- **RAG Architecture**: A modular pipeline with distinct components:  
  - Reader Manager  
  - Chunker Manager  
  - Embedding Manager  
  - Retrieval Manager  
  - Generation Manager  

---

## ⚙️ Technology Stack

- **Frontend**: React  
- **Backend**: Python + FastAPI  
- **Vector Store**: Weaviate  
- **LLM**: LLAMA3 via Ollama  
- **Containerization**: Docker  
- **Install Options**: Docker, pip, or source build  

---

## 🚀 Installation Guide (Docker)

1. Prerequisites: Docker Desktop, Git, Ollama, Python 3.10+  
2. Clone the repo:  
   ```bash
   git clone https://github.com/weaviate/verba.git
   cd verba
   ```
3. Edit `.env` file:
   ```
   OLLAMA_MODEL=llama3
   VERBA_PORT=8000
   LOG_LEVEL=debug
   ```
4. Run Verba:  
   ```bash
   docker compose up -d
   ```
5. Open browser at `http://localhost:8000`

---

## 🧪 How We Used Verba

- Uploaded `.pdf`, `.docx`, and `.txt` documents  
- Ran real-time queries with personalized answers and source traceability  
- Evaluated how RAG improves precision compared to non-augmented LLMs  
- Customized local environment using Ollama and Docker  

---

## 📈 Project Impact

- Demonstrated how RAG improves factual accuracy by grounding answers  
- Ensured **data privacy** by using only local documents and models  
- Explored how chunking and embeddings enhance search speed and quality  
- Gained hands-on experience in deploying and using modular AI systems  

---

## 🌐 Future Possibilities

- Add support for audio, spreadsheet, and code file formats  
- Enable multi-user environments for enterprise workflows  
- Enhance interface usability and retrieval configurations  
- Combine with knowledge graphs or fine-tuned domain LLMs  
- Expand Verba into a general-purpose private research assistant  

---

## 🏁 Conclusion

Verba represents the convergence of modern AI techniques with real-world usability and privacy. This project not only deepened our technical understanding of RAG and vector search, but also equipped us with practical deployment experience. As AI students, we now grasp how to bridge LLMs with domain-specific data to solve real problems—ethically and effectively.

---

## 📚 References

- Slocum, V., & Schmuhl, E. (2024). *Verba: Building an Open Source, Modular RAG Application*. Weaviate.  
- Erzedka. (2025). *NLP: Definition and How It Works*.  
- GitHub: https://github.com/weaviate/verba  

---
