Here I build a machine learning model that can classify whether a tweet is about a real disaster or not. This helps emergency services and news outlets prioritize genuine disaster reports on social media.
# 🌪 Disaster Tweet Classification System

This project uses Natural Language Processing (NLP) and Machine Learning to classify whether a tweet is about a *real disaster* or not. It is inspired by a real-world problem where emergency response teams need to prioritize authentic disaster-related information from social media.

---

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Workflow](#workflow)
- [Model Evaluation](#model-evaluation)
- [Web App (Optional)](#web-app-optional)
- [Future Work](#future-work)
- [License](#license)

---

## 📖 Project Overview

Social media platforms like Twitter are flooded with information, especially during natural disasters. But not all of them are true or useful. This project aims to:
- Detect if a tweet is about a real disaster or not.
- Help emergency services by filtering relevant information.
- Demonstrate end-to-end NLP pipeline — preprocessing, EDA, training, evaluation, and deployment.

---

## 📁 Dataset

- *Source:* [Kaggle NLP Disaster Tweets Dataset](https://www.kaggle.com/competitions/nlp-getting-started/data)
- *Columns:*
  - id: unique ID for the tweet
  - text: the tweet content
  - target: 1 = real disaster, 0 = not a disaster

---

## 🛠 Tech Stack

| Area | Tools |
|------|-------|
| Language | Python |
| Libraries | Pandas, NumPy, Scikit-learn, NLTK, SpaCy, Matplotlib, Seaborn |
| Models | Logistic Regression, Naive Bayes, Random Forest, XGBoost |
| NLP | TF-IDF, CountVectorizer, Word2Vec (optional), BERT (optional) |
| Deployment | Streamlit / Flask (optional) |
| Cloud (optional) | HuggingFace Spaces / Heroku / Render |

---

