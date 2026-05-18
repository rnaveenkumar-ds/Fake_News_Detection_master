# Fake News Detection using Machine Learning

A Machine Learning and Natural Language Processing (NLP) project that detects whether a news statement is Fake or Real using TF-IDF Vectorization and Passive Aggressive Classifier.

---
# Project Overview

This project uses:

- Python
- Pandas
- Scikit-learn
- NLTK
- TF-IDF Vectorizer
- Passive Aggressive Classifier

The model is trained on textual news statements and predicts whether the news is:

- Fake News
- Real News

---

# Features

- Text preprocessing using NLP
- Stopword removal
- Lemmatization
- TF-IDF Vectorization
- Machine Learning Classification
- Confusion Matrix Visualization
- Accuracy Evaluation
- Model Saving using Pickle
- Real-time News Prediction

---

# Dataset

Dataset used:

LIAR Dataset

Labels:

- true
- mostly-true
- half-true
- barely-true
- false
- pants-fire

Converted into:

- Real
- Fake

---

# Installation

```bash
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection
pip install -r requirements.txt
