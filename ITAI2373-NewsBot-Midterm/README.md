# 🤖 ITAI 2373 - NewsBot Intelligence System

## 📌 Project Overview
The **NewsBot Intelligence System** is an end-to-end Natural Language Processing (NLP) pipeline designed to automatically process, categorize, and extract business intelligence from news articles. Built as part of the ITAI 2373 course curriculum, this system addresses real-world applications such as media monitoring, market research, and automated content management.

---

## 🛠️ Key NLP Features & Architecture
- **Text Preprocessing & Pipeline:** Modular text cleaning, tokenization, lemmatization, and POS tagging using **spaCy** and **NLTK**.
- **Vectorization & Feature Extraction:** High-dimensional feature conversion utilizing **TF-IDF Vectorization** with sparse matrix optimizations via **SciPy**.
- **Named Entity Recognition (NER):** Entity tracking to identify organizations, locations, and key entities across news feeds.
- **Dependency Parsing:** Custom parsing of spaCy dependency grammar trees to extract **Subject-Verb-Object (SVO)** action triples for relational analysis.
- **Sentiment & Emotion Analysis:** Rule-based sentiment scoring utilizing **NLTK VADER**.
- **Multi-Class Text Classification:** Machine learning models (**Logistic Regression**, **Multinomial Naive Bayes**, **SVC**) trained with class balancing to categorize news articles accurately.

---

## 📁 Repository Structure
```text
ITAI2373-NewsBot-Midterm/
├── Midterm_NewsBot_Intelligence_System_Anikka_Williams.ipynb   # Main Jupyter Notebook
└── README.md                                                  # Project Documentation
