# 📝 Text Summarizer App (T5 + FastAPI)

A simple **AI-powered text summarization web app** built using:
- 🤖 Hugging Face Transformers (T5 model)
- ⚡ FastAPI (backend)
- 🌐 HTML + JavaScript (frontend)

This app allows users to paste text and generate concise summaries instantly.

---

## 🚀 Features

- ✨ Text summarization using a fine-tuned T5 model  
- ⚡ FastAPI backend for fast inference  
- 🌐 Simple and clean web interface  
- 🧹 Input text cleaning before processing  
- 💻 Works on CPU, CUDA (GPU), and Apple MPS  

---

## 🏗️ Project Structure

---

## ⚙️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/devkumar-AI/text-summarizer.git
cd text-summarizer
```
### 2. Install dependencies
```bash
pip install fastapi uvicorn transformers torch pydantic
```
### 3.Running the App
```bash
uvicorn app:app --reload
```
