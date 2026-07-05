# 📚 AI Research Paper Intelligence System

An intelligent research paper search system that leverages **Natural Language Processing (NLP)**, **Semantic Search**, and **Transformer models** to help users discover relevant Machine Learning research papers based on their meaning rather than exact keyword matches.

The project converts research paper abstracts into semantic vector embeddings, performs fast similarity search using **FAISS**, and enhances the retrieved results with **automatic summarization** and **keyword extraction** for easier understanding.

---

## 🚀 Features

* 🔍 Semantic search over Machine Learning research papers
* 🧠 Searches by meaning instead of exact keywords
* ⚡ Fast vector similarity search using FAISS
* 📝 Automatic research paper abstract summarization
* 🏷️ Keyword extraction using KeyBERT
* 📊 Interactive notebooks demonstrating the complete workflow

---

## 🎯 Project Workflow

The system follows these steps:

1. Load the Machine Learning research paper dataset.
2. Clean and preprocess the paper metadata and abstracts.
3. Generate semantic embeddings using a Sentence Transformer.
4. Build a FAISS vector index for efficient similarity search.
5. Convert the user's query into an embedding.
6. Retrieve the most relevant research papers based on cosine similarity.
7. Generate concise summaries of retrieved papers.
8. Extract important keywords from each paper.

---

## 🧠 Architecture

```text
                    ML-ArXiv Papers Dataset
                              │
                              ▼
                  Data Cleaning & Preprocessing
                              │
                              ▼
         SentenceTransformer (all-MiniLM-L6-v2)
                  Text → Vector Embeddings
                              │
                              ▼
                    FAISS Vector Index
                              │
                  User Query Embedding
                              │
                              ▼
                Top-K Similar Research Papers
                              │
              ┌───────────────┴───────────────┐
              ▼                               ▼
     Abstract Summarization          Keyword Extraction
              │                               │
              └───────────────┬───────────────┘
                              ▼
                     Final Search Results
```

---

## 🛠️ Tech Stack

| Category                | Technologies                               |
| ----------------------- | ------------------------------------------ |
| Programming Language    | Python                                     |
| Dataset                 | Hugging Face ML-ArXiv-Papers               |
| Data Processing         | Pandas, NumPy                              |
| NLP Embeddings          | Sentence Transformers (`all-MiniLM-L6-v2`) |
| Vector Search           | FAISS                                      |
| Summarization           | Hugging Face Transformers (DistilBART)     |
| Keyword Extraction      | KeyBERT                                    |
| Machine Learning        | Scikit-learn                               |
| Development Environment | Jupyter Notebook                           |

---

## 📂 Repository Structure

```text
AI-Research-Paper-Intelligence-System/
│
├── README.md
├── requirements.txt
├── AI_Research_paper_intelligence_system.ipynb
└── Exploratory_Data_Analytics.ipynb
```

### Notebook Description

**Exploratory_Data_Analytics.ipynb**

* Load the ML-ArXiv Papers dataset
* Explore the dataset
* Clean missing and duplicate records
* Prepare the data for semantic search

**AI_Research_paper_intelligence_system.ipynb**

* Generate sentence embeddings using Sentence Transformers
* Build the FAISS vector index
* Perform semantic similarity search
* Generate summaries using DistilBART
* Extract keywords using KeyBERT

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/AI-Research-Paper-Intelligence-System.git

cd AI-Research-Paper-Intelligence-System
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Open Jupyter Notebook or JupyterLab and execute the notebooks in the following order:

1. **AI_Research_paper_intelligence_system.ipynb**
2. **Exploratory_Data_Analytics.ipynb**

The notebooks guide you through the complete pipeline, from preprocessing the dataset to building a semantic search engine for research papers.

---

## 💡 Key Concepts Used

* Natural Language Processing (NLP)
* Sentence Embeddings
* Semantic Search
* Vector Similarity Search
* FAISS Indexing
* Transformer Models
* Text Summarization
* Keyword Extraction
* Information Retrieval

---

## 📈 Future Improvements

* Search filters by publication year, author, and category
* Hybrid keyword + semantic search
* Personalized paper recommendations
* Research paper chatbot using Retrieval-Augmented Generation (RAG)
* PDF upload and question answering
* Streamlit web application deployment
* Citation graph visualization

---

## 📚 Learning Outcomes

This project helped me gain practical experience in:

* Data preprocessing
* Text representation using embeddings
* Transformer-based NLP models
* Semantic information retrieval
* Vector databases (FAISS)
* Automatic text summarization
* Keyword extraction
* Building end-to-end NLP applications

---

## 👨‍💻 Author

**Aditya Kumar**

Aspiring Machine Learning Engineer with interests in Artificial Intelligence, Natural Language Processing, Machine Learning, and Data Science.

If you found this project helpful, consider giving it a ⭐ on GitHub!
