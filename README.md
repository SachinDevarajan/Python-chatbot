<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0F9D58&height=220&section=header&text=Python%20PDF%20Chatbot&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=GenAI%20|%20NLP%20|%20FAISS%20|%20Semantic%20Search&descAlignY=58&descColor=ffffff&descSize=18"/>

# 🤖 Python PDF Chatbot

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-00C853?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-4285F4?style=for-the-badge)
![Sentence Transformers](https://img.shields.io/badge/Sentence--Transformers-FF6F00?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-7B2CBF?style=for-the-badge)

### 🚀 Intelligent Question Answering System using PDF Documents

</div>

---

# 📖 Project Overview

This project is an **AI-powered PDF Chatbot** that allows users to ask natural language questions from a PDF document and receive context-aware answers.

The chatbot extracts text from a PDF, preprocesses the content, generates semantic embeddings, stores them inside a **FAISS Vector Database**, and retrieves the most relevant information for answering user queries.

This project demonstrates the core concepts behind **Retrieval-Augmented Generation (RAG)** systems.

---

# 🎯 Objective

Build an intelligent chatbot capable of answering questions directly from PDF documents using:

- 📄 PDF Text Extraction
- 🧠 Natural Language Processing
- 🔍 Semantic Search
- ⚡ FAISS Vector Database

---

# 📂 Project Structure

```text
Python Chatbot/
│
├── python.pdf              # Source PDF
├── data_process.ipynb      # Data Processing Notebook
├── chatbot.ipynb           # Chatbot Notebook
├── chunks.csv              # Text Chunks
├── chunks.pkl              # Saved Chunks
├── faiss_index.index       # FAISS Vector Index
└── README.md
```

---

# 📄 Dataset

Instead of a traditional dataset, this project uses a **Python Programming PDF** as the knowledge source.

The chatbot retrieves answers directly from the PDF content.

---

# ⚙️ Workflow

```text
PDF Document
      │
      ▼
Extract Text
      │
      ▼
Text Cleaning
      │
      ▼
Chunking
      │
      ▼
Sentence Embeddings
      │
      ▼
FAISS Vector Database
      │
      ▼
User Question
      │
      ▼
Similarity Search
      │
      ▼
Relevant Chunks
      │
      ▼
Answer
```

---

# 🧠 Technologies Used

- Python
- Pandas
- NumPy
- FAISS
- Sentence Transformers
- Joblib
- Jupyter Notebook

---

# 🤖 Core Components

### PDF Processing

- Extract Text
- Clean Text
- Normalize Content

### Text Processing

- Chunking
- Tokenization
- Text Normalization

### Semantic Search

- Sentence Embeddings
- FAISS Similarity Search
- Top-K Retrieval

---

# 📝 NLP Pipeline

- PDF Text Extraction
- Lowercase Conversion
- Remove Extra Spaces
- Chunk Creation
- Sentence Embedding Generation
- Vector Index Creation
- Similarity Search

---

# 📊 Workflow Architecture

```text
User Question
      │
      ▼
Embedding Model
      │
      ▼
FAISS Search
      │
      ▼
Top Similar Chunks
      │
      ▼
Retrieved Context
      │
      ▼
Final Answer
```

---

# ✨ Features

- ✅ PDF Question Answering
- ✅ NLP Text Processing
- ✅ Semantic Search
- ✅ FAISS Vector Database
- ✅ Sentence Embeddings
- ✅ Intelligent Context Retrieval
- ✅ Fast Search
- ✅ Scalable Architecture

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/SachinDevarajan/Python-chatbot.git
```

Move into the project

```bash
cd Python-chatbot
```

Install dependencies

```bash
pip install pandas numpy faiss-cpu sentence-transformers PyMuPDF notebook
```

---

# ▶️ Run the Project

### Step 1

Open data processing notebook

```bash
jupyter notebook data_process.ipynb
```

### Step 2

Run chatbot notebook

```bash
jupyter notebook chatbot.ipynb
```

---

# 🛠 Skills Demonstrated

- Generative AI Fundamentals
- Retrieval-Augmented Generation (RAG)
- Natural Language Processing
- Semantic Search
- Vector Databases
- FAISS
- Sentence Transformers
- Text Chunking
- PDF Processing
- Python

---

# 🔮 Future Improvements

- Gemini API Integration
- OpenAI API Integration
- LangChain Pipeline
- Streamlit Web App
- Flask REST API
- Multi-PDF Support
- Conversation Memory
- Voice-based Chatbot
- Docker Deployment

---

# 📌 Applications

- Educational PDF Assistant
- Research Paper Search
- Company Knowledge Base
- Technical Documentation Chatbot
- Digital Library Search
- AI Learning Assistant

---

# 🤝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# 👨‍💻 Author

## Sachin Devarajan

**Data Analyst | Machine Learning & GenAI Enthusiast**

📊 Passionate about Data Analytics, Machine Learning, NLP, and Generative AI.

💡 Building intelligent AI solutions using Python, Vector Databases, and Retrieval-Augmented Generation (RAG).

🌱 Currently learning Advanced Machine Learning, LLMs, LangChain, PySpark, and Data Engineering.

---

<div align="center">

## ⭐ If you found this project useful, please give it a Star!

### 💬 "Transforming PDF documents into intelligent conversational assistants using NLP and Vector Search."

<img src="https://capsule-render.vercel.app/api?type=waving&color=0F9D58&height=120&section=footer"/>

</div>
