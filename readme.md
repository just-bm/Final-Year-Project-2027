# Memory Lane 📸🧠

An AI-powered personal memory management platform that helps users store, organize, search, and relive their memories through semantic search and conversational AI.

## 🚀 Overview

Memory Lane is a smart digital memory vault where users can upload photos, videos, journals, and other personal content. Using AI-powered embeddings, semantic search, and Retrieval-Augmented Generation (RAG), users can search memories using natural language and interact with their memories through a conversational assistant.

### Example Queries

* "Show me my happiest moments from 2024"
* "Find beach trips with friends"
* "Show memories from Chennai last summer"
* "Summarize my graduation memories"

---

## ✨ Features

### Core Features

* User Registration & Authentication
* Secure JWT-based Authorization
* Image & Video Upload
* Memory Collections
* Tagging System
* Personal Gallery Dashboard

### AI Features

* AI-generated Image Captions
* Semantic Search using Embeddings
* Intelligent Memory Retrieval
* Memory Summarization
* Conversational Memory Assistant (RAG)

### Search Features

* Natural Language Search
* Metadata Filtering
* Collection-based Search
* Date-based Search
* Similar Memory Discovery

---

## 🏗️ System Architecture

```text
Frontend (Next.js)
        │
        ▼
Spring Boot Backend
        │
        ├── PostgreSQL
        ├── AWS S3
        ├── ChromaDB
        │
        ▼
FastAPI AI Service
        │
        ├── CLIP Embeddings
        ├── BLIP Captioning
        ├── Whisper Transcription
        └── RAG Pipeline
```

---

## 🛠️ Tech Stack

### Frontend

* Next.js
* React
* TypeScript
* Tailwind CSS

### Backend

* Java 21
* Spring Boot
* Spring Security
* JWT Authentication
* JPA / Hibernate

### AI Service

* Python
* FastAPI
* Transformers
* LangChain
* CLIP
* BLIP
* Whisper

### Databases

* PostgreSQL
* ChromaDB

### Storage

* AWS S3

### DevOps

* Docker
* GitHub Actions

---

## 📂 Project Structure

```text
memory-lane/
│
├── frontend/
│   ├── app/
│   ├── components/
│   ├── hooks/
│   └── services/
│
├── backend/
│   ├── src/main/java
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── entity/
│   └── security/
│
├── ai-service/
│   ├── api/
│   ├── models/
│   ├── embeddings/
│   ├── rag/
│   └── utils/
│
├── docs/
│
└── docker-compose.yml
```

---

## 📌 MVP Roadmap

### Phase 1

* [x] Project Planning
* [ ] User Authentication
* [ ] PostgreSQL Integration
* [ ] Memory Upload System
* [ ] Gallery Dashboard

### Phase 2

* [ ] Image Captioning
* [ ] Embedding Generation
* [ ] ChromaDB Integration
* [ ] Semantic Search

### Phase 3

* [ ] Conversational AI Assistant
* [ ] Memory Summaries
* [ ] Collections & Sharing
* [ ] Deployment

---

## 🔐 Authentication

The system uses:

* JWT Access Tokens
* Refresh Tokens
* Password Hashing using BCrypt
* Role-Based Access Control

---

## 🔍 Semantic Search Workflow

```text
User Query
     │
     ▼
Generate Embedding
     │
     ▼
ChromaDB Similarity Search
     │
     ▼
Retrieve Relevant Memories
     │
     ▼
Return Ranked Results
```

---

## 🤖 RAG Workflow

```text
User Question
      │
      ▼
Query Embedding
      │
      ▼
Retrieve Relevant Memories
      │
      ▼
Build Context
      │
      ▼
LLM Response Generation
      │
      ▼
Answer User
```

---

## 🚦 Getting Started

### Clone Repository

```bash
git clone https://github.com/your-username/memory-lane.git
cd memory-lane
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

### Backend

```bash
cd backend
./mvnw spring-boot:run
```

### AI Service

```bash
cd ai-service
pip install -r requirements.txt
uvicorn main:app --reload
```

---

## 📊 Future Enhancements

* Mobile Application
* Face Recognition
* Voice-Based Search
* Memory Timeline Visualization
* Collaborative Albums
* Smart Memory Recommendations
* Multi-language Support

---

## 👨‍💻 Team

Final Year Project

**Memory Lane — Relive Your Memories Through AI**

---

## 📄 License

This project is developed for educational and research purposes as part of a Final Year Engineering Project.
