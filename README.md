# ShadowFox AI Engineer Internship

This repository contains my completed work for the ShadowFox AI Engineer Virtual Internship.

The projects are completed across three levels, progressing from a basic LLM-powered application to document-based RAG and finally a production-style RAG system.

## 🟢 Beginner — AI Student Utility

A simple AI-powered student utility built using an LLM API.

### Features

- LLM-powered student assistance
- Prompt-based AI generation
- Simple web interface
- User input handling
- Input validation
- Error handling
- Environment-based API configuration

### Technologies

- Python
- Flask
- Jinja2
- HTML/CSS
- LLM API

## 🟡 Intermediate — Document Question Answering

A document-based Question Answering system that uses Retrieval-Augmented Generation (RAG) to answer questions using information retrieved from uploaded documents.

The system processes documents, splits the content into chunks, generates embeddings, retrieves relevant information, and uses the retrieved context to generate grounded answers.

### RAG Pipeline

Document Upload → Document Loading → Text Extraction → Text Chunking → Embeddings → Vector Store → Similarity Retrieval → Relevant Context → Question Answering → Grounded Response

### Features

- Document upload
- Text extraction
- Text chunking
- Embedding generation
- Vector-based retrieval
- Context-grounded question answering
- Source context
- Input validation
- Error handling
- Automated testing

### Technologies

- Python
- RAG
- Embeddings
- Vector Search
- LLM API
- Pytest

## 🔴 Advanced — Production-Style RAG Assistant

A production-style Retrieval-Augmented Generation application for grounded question answering over documents.

The system combines document ingestion, preprocessing, chunking, embeddings, vector retrieval, query rewriting, reranking, grounded generation, and groundedness validation into a modular workflow.

### Architecture

User Query → Query Processing / Rewriting → FAISS Vector Search → Candidate Retrieval → Cross-Encoder Reranking → Relevant Context → Grounded LLM Generation → Groundedness Validation → Final Response

### Features

- PDF, TXT and Markdown document support
- Document parsing and preprocessing
- Text chunking
- Embedding generation
- FAISS vector search
- Document-scoped retrieval
- Query rewriting and refinement
- Cross-encoder reranking
- Grounded answer generation
- Groundedness validation
- Safe handling of unsupported questions
- Pydantic validation
- FastAPI backend
- Streamlit frontend
- LangGraph workflow
- Docker support
- Automated tests
- One-command local launcher

### Technologies

- Python
- FastAPI
- Streamlit
- Pydantic
- LangGraph
- FAISS
- Sentence Transformers
- Cross-Encoder
- Groq
- Docker
- Pytest

### Running the Advanced Project

    python run.py

The application provides:

- FastAPI: http://127.0.0.1:8000
- Swagger API Documentation: http://127.0.0.1:8000/docs
- Streamlit Interface: http://127.0.0.1:8501

## 🧪 Testing

The projects include validation and testing appropriate to their respective levels.

The Advanced project includes automated tests covering core application behavior and RAG functionality.

    pytest -q

## 🧠 Skills Demonstrated

- Large Language Model APIs
- Prompt Engineering
- Retrieval-Augmented Generation
- Document Processing
- Text Chunking
- Embeddings
- Vector Search
- Semantic Retrieval
- Query Rewriting
- Cross-Encoder Reranking
- Grounded Generation
- Hallucination Reduction
- FastAPI
- Streamlit
- Pydantic
- LangGraph
- FAISS
- Docker
- Automated Testing
- AI Application Architecture

## 🔐 Environment Configuration

API keys and other secrets are not included in the repository.

Each project contains a .env.example file showing the required environment variables.

Create a local .env file and add the required API credentials before running the applications.

The .env file should not be committed to GitHub.

## 📁 Repository Structure

ShadowFox-AI-Engineer-Internship/
├── Beginner/
├── Intermediate/
├── Advanced/
└── README.md

## 🎯 Internship Progression

Beginner
↓
LLM Integration
↓
Intermediate
↓
Document RAG
↓
Retrieval + Embeddings
↓
Advanced
↓
Production-Style RAG
↓
Query Rewriting
↓
Reranking
↓
Groundedness Validation
↓
API + UI + Workflow

## 👨‍💻 Author

Amogh Reddy

B.Tech — Computer Science Engineering (AI & ML)

GitHub: @amoghreddy07

## 📜 About

This repository was created as part of the ShadowFox AI Engineer Virtual Internship Program and contains the completed Beginner, Intermediate, and Advanced projects.
