# 🔎 AI Research Paper Intelligence System

An AI-powered research paper discovery system that uses **Semantic Search** and **Natural Language Processing (NLP)** to find relevant Machine Learning research papers based on the meaning of a user's query instead of exact keyword matching.

The project demonstrates how transformer-based embeddings and vector similarity search can improve information retrieval from large collections of research papers.

---

## 📌 Overview

Searching research papers using traditional keyword search often misses relevant publications because different authors use different terminology.

This project addresses that challenge by converting research paper abstracts into dense vector embeddings and retrieving the most semantically similar papers using FAISS. To further improve usability, the retrieved papers are summarized automatically and their important topics are extracted.

---

## ✨ Features

- 📄 Load and preprocess Machine Learning research papers
- 🧹 Data cleaning and preprocessing pipeline
- 🤖 Generate semantic embeddings using Sentence Transformers
- ⚡ Fast similarity search using FAISS
- 📝 Automatic abstract summarization
- 🔑 Keyword extraction using KeyBERT
- 📊 Interactive search workflow in Jupyter Notebook

---

## 🔄 Project Pipeline

```
Research Papers Dataset
        │
        ▼
Data Preprocessing
        │
        ▼
Sentence Embeddings
        │
        ▼
FAISS Vector Index
        │
        ▼
Semantic Similarity Search
        │
        ▼
Relevant Research Papers
        │
 ┌──────┴────────┐
 ▼               ▼
Summary      Keywords
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Sentence Transformers
- Hugging Face Transformers
- FAISS
- KeyBERT
- Scikit-learn
- Jupyter Notebook

---

## 📂 Repository Structure

```
CBSOT_PROJECT_2/
│
├── README.md
├── EDA.ipynb
└── AIResearchpapersystem.ipynb
```

---

## 📘 Notebook Details

### 📙 EDA.ipynb

This notebook focuses on:

- Loading the dataset
- Exploring research paper metadata
- Handling missing values
- Data preprocessing
- Preparing text for embedding generation

---

### 📗 AIResearchpapersystem.ipynb

This notebook covers:

- Semantic embedding generation
- Building a FAISS vector index
- Semantic search implementation
- Research paper summarization
- Keyword extraction
- Retrieving the most relevant papers

---

## 🚀 Installation

Clone this repository

```bash
git clone https://github.com/Thakur-saab2001/CBSOT_PROJECT_2.git
```

Move into the project directory

```bash
cd CBSOT_PROJECT_2
```

Install the required libraries

---

## ▶️ How to Run

1. Open Jupyter Notebook.
2. Run **EDA.ipynb** first.
3. Then run **AIResearchpapersystem.ipynb**.
4. Enter a research topic to retrieve similar Machine Learning papers.

---

## 📈 Future Scope

Some possible improvements include:

- Research paper recommendation system
- Hybrid search (keyword + semantic search)
- Citation graph visualization
- Search filters based on author, year, and category
- Streamlit web application
- RAG-based chatbot for research papers

---

## 🎯 Skills Demonstrated

- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Natural Language Processing
- Semantic Search
- Transformer Models
- Vector Databases (FAISS)
- Information Retrieval
- Text Summarization
- Keyword Extraction
- Python Programming

---

## 📚 Dataset

Machine Learning research papers were obtained from the **ML-ArXiv-Papers** dataset available on Hugging Face.

---

## 👨‍💻 Author

**Rohit Kumar Thakur**

Machine Learning & Data Science Enthusiast

---

⭐ If you found this project interesting, consider giving this repository a star!
