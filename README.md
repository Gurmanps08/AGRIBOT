# ASTRABOT

## Agricultural AI Assistant
ASTRABOT is a domain-specific AI chatbot for agriculture that provides intelligent responses related to crops, soil health, pests, diseases, fertilizers, and sustainable farming practices.

The chatbot uses Retrieval-Augmented Generation (RAG) with Hugging Face, LangChain, ChromaDB, and Mistral-7B-Instruct to retrieve relevant agricultural information and generate context-aware responses.

---

## Features

- Agriculture-focused AI chatbot
- Retrieval-Augmented Generation (RAG)
- Semantic search using vector embeddings
- ChromaDB vector database
- Hugging Face embeddings
- Mistral-7B-Instruct LLM
- LangChain integration
- Agricultural knowledge base
- Flask backend
- REST API
- Render deployment support

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Flask | Backend/API |
| LangChain | RAG pipeline |
| Hugging Face | Embeddings and LLM |
| Mistral-7B-Instruct | Language model |
| ChromaDB | Vector database |
| Sentence Transformers | Text embeddings |
| PyTorch | Deep learning |
| PyPDF | PDF processing |
| Render | Deployment |

---

## Architecture

```text
User
  |
  v
Flask Application
  |
  v
User Query
  |
  v
Embedding Model
  |
  v
ChromaDB
  |
  v
Relevant Documents
  |
  v
RAG Prompt
  |
  v
Mistral-7B-Instruct
  |
  v
Generated Response
  |
  v
User

# PROJECT STRUCTURE
ASTRABOT/
│
├── Data/
│   └── Agricultural documents
│
├── chroma_db/
│   └── ChromaDB vector database
│
├── research/
│   └── Research files
│
├── src/
│   ├── helper.py
│   └── prompt.py
│
├── static/
│   └── Static files
│
├── templates/
│   └── index.html
│
├── app.py
├── store_index.py
├── template.py
├── setup.py
├── requirements.txt
├── render.yaml
├── .gitignore
├── LICENSE
└── README.md

