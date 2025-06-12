# Amazon Alexa Sentiment Analysis 🗣️📊

This project performs sentiment analysis on customer reviews of Amazon Alexa using NLP techniques and machine learning models. The goal is to classify reviews as **positive (1)** or **negative (0)** based on the content.

---

## 📁 Project Structure

AmazonAlexaSentimentAnalysis/
├── Dataset/
│ └── amazon_alexa.tsv # Raw dataset file
├── Models/
│ ├── countVectorizer.pkl # Saved CountVectorizer
│ └── scaler.pkl # Saved MinMaxScaler
├── SentimentAnalysis.ipynb # Main notebook with all code
├── README.md # This file
└── LICENSE

---

## 🚀 Features

- Cleaned and preprocessed text data (stopwords, stemming, etc.)
- Text vectorization using Bag-of-Words (CountVectorizer)
- Feature scaling with MinMaxScaler
- Classification using:
  - ✅ Random Forest Classifier
  - ✅ XGBoost Classifier
- Model Evaluation using accuracy score
- Word Cloud visualization of reviews

---

## 📦 Requirements

Install these before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn sklearn xgboost wordcloud nltk
