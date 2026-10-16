# 🤖 ITAI 2373 - NewsBot Intelligence System

## 📌 Project Overview
The **NewsBot Intelligence System** is an end-to-end Natural Language Processing (NLP) pipeline designed to automatically process, categorize, and extract actionable business intelligence from news articles. Built for the ITAI 2373 course curriculum, this system demonstrates how raw news text gets turned into actionable business insights.

---

## 🛠️ Key NLP Features & Pipeline Architecture
- **Modular Preprocessing:** Text cleaning, lowercasing, tokenization, lemmatization, and POS tagging built with **spaCy** and **NLTK**.
- **Vectorization & Feature Engineering:** Conversion of raw text into high-dimensional numerical feature vectors utilizing **TF-IDF Vectorization** with sparse matrix optimizations via **SciPy**.
- **Named Entity Recognition (NER):** Entity tracking to identify organizations, locations, and key entities across news feeds using spaCy (`en_core_web_sm`).
- **Dependency Grammar Parsing:** Custom parsing of spaCy dependency trees to extract **Subject-Verb-Object (SVO)** action triples for relational analysis.
- **Sentiment & Tone Analysis:** Rule-based sentiment scoring utilizing **NLTK VADER**.
- **Multi-Class Text Classification:** Machine learning models (**Logistic Regression**, **Multinomial Naive Bayes**, **SVC**) trained with balanced class weighting.

---
## Visual Samples & Business Insights

### NetworkX Knowledge Graph
Relational knowledge graph built from extracted Subject-Verb-Object (SVO) triples to track entity co-occurrences and structural relationships across news categories:

![NetworkX Knowledge Graph](Screenshot%202026-10-16%20025501.png)

---

### spaCy Entity Trends
Top TF-IDF key terms and entity frequency trends extracted across news categories to turn unstructured article text into actionable insights:

![Business Entity Trends](Screenshot%202026-10-16%20025749.png)

![Technology Entity Trends](Screenshot%202026-10-16%20025813.png)

![Sports Entity Trends](Screenshot%202026-10-16%20025826.png)

![Politics & Entertainment Entity Trends](Screenshot%202026-10-16%20025842.png)

---

## 📁 Repository Structure
```text
ITAI2373-NewsBot-Midterm/
├── Midterm_NewsBot_Intelligence_System_Anikka_Williams.ipynb   # Main Jupyter Notebook
└── README.md                                                  # Project Documentation

