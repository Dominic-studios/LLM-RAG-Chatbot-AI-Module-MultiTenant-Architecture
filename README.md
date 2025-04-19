# LLM-RAG Chatbot AI Module

This module powers an intelligent chatbot system using **Retrieval-Augmented Generation (RAG)** and a fine-tuned **LLaMA 2** model. It transforms raw website content into meaningful chatbot responses with high accuracy and domain relevance.

---

## 🧠 Core Features

- 🔍 **Context-Aware RAG Pipeline**  
  Combines dense MPNet embeddings with ChromaDB to retrieve semantically relevant chunks before generating answers.

- 🦙 **LLaMA 2 Integration**  
  Uses a quantized LLaMA 2 model (7B) to generate human-like, domain-specific responses.

- 🧾 **Dynamic Text Classification**  
  NLP preprocessing pipeline classifies and segments web content into structured headings.

- 🧠 **Embedding Generation**  
  Utilizes MPNet for high-quality, dense sentence embeddings for similarity-based retrieval.

---

## 🧪 Demo (Coming Soon)

- Query example: `“What are the refund policies on this site?”`  
- Response: LLaMA 2 generates a human-readable answer using context retrieved from your uploaded website data.

---

## ⚙️ Stack

- **Model**: LLaMA 2 (7B, 4-bit quantized)
- **RAG Framework**: Custom Python
- **Embeddings**: MPNet via SentenceTransformers
- **Vector Store**: ChromaDB
- **NLP**: spaCy, Regex-based cleanup

---

## 🔐 Usage

1. Load cleaned web content.
2. Generate embeddings and store in ChromaDB.
3. Query → Retrieve context → Generate answer via LLaMA 2.

---
