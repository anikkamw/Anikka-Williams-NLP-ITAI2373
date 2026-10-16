# ITAI 2373 - NewsBot Intelligence System

## Project Overview
The **NewsBot Intelligence System** is an end-to-end Natural Language Processing (NLP) pipeline designed to automatically process, categorize, and extract actionable business intelligence from news articles. Built for the ITAI 2373 course curriculum, this system addresses real-world enterprise applications including media monitoring, market research, and automated content management.

---

## Key NLP Features & Pipeline Architecture
- **Modular Preprocessing:** Text cleaning, lowercasing, tokenization, lemmatization, and POS tagging built with **spaCy** and **NLTK**.
- **Vectorization & Feature Engineering:** Conversion of raw text into high-dimensional numerical feature vectors utilizing **TF-IDF Vectorization** with sparse matrix optimizations via **SciPy**.
- **Named Entity Recognition (NER):** Entity tracking to identify organizations, locations, and key entities across news feeds using spaCy (`en_core_web_sm`).
- **Dependency Grammar Parsing:** Custom parsing of spaCy dependency trees to extract **Subject-Verb-Object (SVO)** action triples for relational analysis.
- **Sentiment & Tone Analysis:** Rule-based sentiment scoring utilizing **NLTK VADER**.
- **Multi-Class Text Classification:** Machine learning models (**Logistic Regression**, **Multinomial Naive Bayes**, **SVC**) trained with balanced class weighting.

---

## 📁 Repository Structure
```text
ITAI2373-NewsBot-Midterm/
├── Midterm_NewsBot_Intelligence_System_Anikka_Williams.ipynb   # Main Jupyter Notebook
├── README.md                                                  # Project Documentation
├── Screenshot 2026-10-16 025501.png                           # Entity Network Graph
├── Screenshot 2026-10-16 025749.png                           # Business TF-IDF Plot
├── Screenshot 2026-10-16 025813.png                           # Sports & Tech TF-IDF Plot
├── Screenshot 2026-10-16 025826.png                           # Sports & Tech TF-IDF Plot
└── Screenshot 2026-10-16 025842.png                           # Politics & Entertainment TF-IDF Plot
