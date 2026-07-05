# 🔬 AI Research Paper Intelligent System

> An Advanced Deep Learning & NLP-based Research Paper Intelligence System that enables semantic search, hybrid search, keyword extraction, and intelligent analysis of research papers using Transformer models and vector databases.

---

## 📌 Project Overview

Finding relevant research papers using traditional keyword search is often inefficient because different papers may describe the same concept using different terminology.

This project solves that problem by using **Deep Learning**, **Natural Language Processing (NLP)**, and **Semantic Search** to retrieve research papers based on their meaning instead of relying only on exact keyword matches.

The system converts every research paper into dense vector embeddings using a Sentence Transformer model and indexes them in a FAISS vector database, allowing fast and meaningful retrieval of similar papers.

---

# 🎯 Objectives

The objective of this project is to:

- Build an intelligent research paper search system.
- Implement semantic search using Transformer embeddings.
- Perform hybrid search using semantic similarity and keyword matching.
- Extract important keywords automatically.
- Identify named entities from research papers.
- Demonstrate modern NLP techniques taught during the internship.

---

# 🚀 Features

### ✅ Research Paper Dataset Loading

Loads the ML-ArXiv research paper dataset.

---

### ✅ NLP Text Preprocessing

The preprocessing pipeline includes:

- Lowercase conversion
- Tokenization
- Stopword removal
- Lemmatization
- Text cleaning

---

### ✅ Semantic Search

Uses:

- Sentence Transformers
- Cosine Similarity
- FAISS Vector Database

to retrieve research papers based on semantic meaning.

---

### ✅ Hybrid Search

Combines:

- Semantic Search
- Keyword Matching

to improve retrieval quality.

---

### ✅ Keyword Extraction

Automatically extracts important keywords and keyphrases using **KeyBERT**.

---

### ✅ Named Entity Recognition (NER)

Extracts entities such as:

- Organizations
- People
- Products
- Locations
- Events

using **spaCy**.

---

### ✅ AI Research Assistant

The system provides:

- Paper Title
- Similarity Score
- Keywords
- Named Entities
- Research Paper Abstract

for every retrieved research paper.

---

# 🧠 Technologies Used

## Programming Language

- Python

## Deep Learning

- Sentence Transformers
- Transformer Embeddings

## Natural Language Processing

- KeyBERT
- spaCy
- NLTK

## Vector Database

- FAISS

## Machine Learning Libraries

- Scikit-Learn

## Data Processing

- Pandas
- NumPy

## Dataset

- ML-ArXiv Papers Dataset (Hugging Face)

---

# 📂 Dataset

Dataset Used:

**ML-ArXiv Papers Dataset**

https://huggingface.co/datasets/CShorten/ML-ArXiv-Papers

The dataset contains thousands of Machine Learning research papers including:

- Paper Title
- Abstract

---

# ⚙️ Project Workflow

```
Research Paper Dataset
          │
          ▼
Text Preprocessing
          │
          ▼
Sentence Transformer
          │
          ▼
Generate Embeddings
          │
          ▼
FAISS Vector Index
          │
          ▼
Semantic Search
          │
          ▼
Hybrid Search
          │
          ├──────────────┐
          ▼              ▼
Keyword Extraction    Named Entity Recognition
          │              │
          └──────┬───────┘
                 ▼
      AI Research Assistant Output
```

---

# 📊 Project Pipeline

1. Load Dataset

2. Data Cleaning

3. NLP Preprocessing

4. Generate Sentence Embeddings

5. Build FAISS Vector Database

6. Semantic Search

7. Hybrid Search

8. Keyword Extraction

9. Named Entity Recognition

10. AI Research Assistant

---

# 📈 Results

The system successfully:

- Generated dense semantic embeddings for research papers.
- Indexed research papers using FAISS.
- Retrieved semantically relevant research papers.
- Extracted important keywords.
- Detected named entities.
- Combined multiple NLP components into a single intelligent search pipeline.

---

# 📷 Sample Output

The AI Research Assistant returns:

- Research Paper Title
- Similarity Score
- Extracted Keywords
- Named Entities
- Abstract

---

# 📚 Concepts Implemented

- Natural Language Processing (NLP)
- Deep Learning
- Semantic Search
- Sentence Embeddings
- Transformer Models
- Cosine Similarity
- Vector Databases
- Information Retrieval
- Keyword Extraction
- Named Entity Recognition

---

# 📦 Installation

```bash
pip install sentence-transformers
pip install faiss-cpu
pip install datasets
pip install keybert
pip install spacy
pip install nltk
```

---

# ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/AI-Research-Paper-Intelligent-System.git
```

2. Open the notebook

```
AI_Research_Paper_Intelligent_System.ipynb
```

3. Run all cells in Google Colab or Jupyter Notebook.

---

# 🎓 Learning Outcomes

Through this project I learned:

- Building semantic search systems using Transformer embeddings.
- Creating vector databases with FAISS.
- Applying NLP preprocessing techniques.
- Performing keyword extraction using KeyBERT.
- Implementing Named Entity Recognition.
- Designing an end-to-end Deep Learning based research paper retrieval system.

---

# 👨‍💻 Author

**Shashwat Gupta**

Machine Learning & Artificial Intelligence Enthusiast

Coding Blocks School of Technology (CBSOT)

---

# ⭐ If you found this project useful, consider giving it a star!
