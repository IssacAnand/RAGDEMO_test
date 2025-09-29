# RAG System with ChromaDB

A Retrieval-Augmented Generation (RAG) system using ChromaDB for vector storage and Groq LLMs.

## Prerequisites

- Python 3.10 or higher
- Git

## Setup Instructions (Windows)

### 1. Install uv

Open PowerShell and run:
```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

### 2. Clone repository
git clone https://github.com/IssacAnand/RAGDEMO_test.git
cd RAGDEMO_test

### 3. Creating Virtual Environment
uv venv
.venv\Scripts\activate (Windows environment)

### 4. Install Packages
uv install -r requirements.txt

### 5. Setting up .env file for Groq API
GROQ_API_KEY=your_groq_api_key_here
