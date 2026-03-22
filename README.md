# 🏥 MEDTECH RAG: Medical Report Q&A System

## 📌 Overview

This project is a **Retrieval-Augmented Generation (RAG)** based system that enables users to **interact with medical reports (PDFs)** using natural language.

It allows users to ask questions about patient reports and receive **context-aware, AI-generated responses**.

---

## 🚀 Features

* 📄 Upload and process medical PDF reports
* 🔍 Extract and chunk document content
* 🧠 Semantic search using vector embeddings
* 💬 Chat interface for natural language queries
* ⚡ FastAPI-based backend for scalable APIs
* 📊 Efficient retrieval using vector database

---

## 🧠 How It Works

1. PDF documents are loaded and parsed
2. Text is split into smaller chunks
3. Embeddings are generated for each chunk
4. Stored in a vector database
5. User query is converted into embedding
6. Relevant chunks are retrieved
7. LLM generates a final answer using retrieved context

---

## 🛠️ Tech Stack

* **Python**
* **FastAPI**
* **LangChain**
* **Vector Database (FAISS / ChromaDB)**
* **OpenAI / LLM APIs**
* **Pandas / NumPy**

---

## 📂 Project Structure

```
MEDTECH/
│── app/
│   ├── chat_utils.py
│   ├── config.py
│   ├── pdf_utils.py
│   ├── ui.py
│   ├── vectorstore_utils.py
│
│── sample_data/
│   ├── medical_history_1.pdf
│   ├── ...
│
│── main.py
│── requirements.txt
│── .gitignore
```

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/MEDTECH.git
cd MEDTECH
pip install -r requirements.txt
```

---

## 🔐 Environment Setup

Create a `.env` file:

```bash
API_KEY=your_api_key_here
```

---

## ▶️ Run the Application

```bash
python main.py
```

---

## 💡 Example Use Cases

* Patient medical history analysis
* Doctor support tool
* Clinical document summarization
* Medical Q&A assistant

---

## ⚠️ Disclaimer

This project is for **educational purposes only** and should not be used as a substitute for professional medical advice.

---

## 📈 Future Improvements

* Multi-PDF support
* UI enhancements
* Deployment (Streamlit / Cloud)
* Advanced medical entity recognition

---

## 👨‍💻 Author

Durga Charan Mishra

---
