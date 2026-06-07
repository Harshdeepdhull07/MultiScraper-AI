# 🚀 MultiScraper AI

## 📌 Overview

MultiScraper AI is a Generative AI-powered application that extracts, summarizes, and analyzes content from YouTube videos, websites, and PDF documents. The system combines Retrieval-Augmented Generation (RAG), FAISS vector search, and Large Language Models to provide intelligent content retrieval and question-answering capabilities.

The application supports YouTube transcript summarization, website scraping, PDF parsing, semantic search, and AI-powered information extraction through an interactive Streamlit interface.

---

## ✨ Features

* 🎥 YouTube Video Transcript Summarization
* 🌐 Website Content Scraping and Processing
* 📄 PDF Document Parsing and Analysis
* 🤖 AI-Powered Question Answering
* 🔍 Semantic Search using FAISS Vector Database
* 🧠 Retrieval-Augmented Generation (RAG)
* 📊 Response Evaluation using ROUGE Score
* 💬 Interactive Streamlit User Interface
* 🦙 Local LLM Support using Ollama (Llama 3)
* ☁️ Gemini API Integration with Ollama Fallback

---

## 🏗️ Project Architecture

1. Content Extraction

   * YouTube Transcript API
   * Selenium Web Scraping
   * PDF Text Extraction

2. Text Processing

   * Content Cleaning
   * Text Chunking

3. Embedding Generation

   * Sentence Transformers (all-MiniLM-L6-v2)

4. Vector Storage

   * FAISS Vector Database

5. Retrieval

   * Semantic Similarity Search

6. Generation

   * Gemini API / Llama 3 (Ollama)

7. Evaluation

   * ROUGE Score Analysis

---

## 🛠️ Tech Stack

### Frontend

* Streamlit

### Backend

* Python

### AI & Machine Learning

* Google Gemini API
* Ollama (Llama 3)
* LangChain
* Sentence Transformers

### Vector Database

* FAISS

### Web Scraping

* Selenium
* BeautifulSoup

### Document Processing

* PDFMiner
* PyPDF2

### Evaluation

* ROUGE Score

---

## 📂 Project Structure

```bash
MultiScraper-AI/
│
├── app.py
├── scrape.py
├── parse.py
├── rag.py
├── evaluation.py
├── baseline.py
├── requirements.txt
├── .gitignore
└── README.md
```

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/Harshdeepdhull07/MultiScraper-AI.git
cd MultiScraper-AI
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows:

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Ollama

```bash
ollama pull llama3
ollama serve
```

### Run Application

```bash
streamlit run app.py
```

---

## 🎯 Usage

### YouTube Summarizer

1. Paste YouTube URL
2. Select transcript language
3. Click "Summarize Video"
4. Get AI-generated summary

### Website Parser

1. Enter website URL
2. Scrape content
3. Ask questions about extracted information

### PDF Parser

1. Upload PDF document
2. Process and index content
3. Ask natural language questions

---

## 📈 Future Enhancements

* Multi-PDF Support
* Image Understanding
* Audio File Processing
* Chat History Management
* Cloud Deployment
* Advanced Evaluation Metrics
* Multi-Language Support

---

## 👨‍💻 Author

**Harshdeep Singh**

B.Tech Computer Science Engineering

---

## ⭐ Project Highlights

* Generative AI Application
* Retrieval-Augmented Generation (RAG)
* FAISS Semantic Search
* Local LLM Integration
* Multimodal Content Processing
* Interactive Streamlit Dashboard
