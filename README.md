# Fake News Detection using Machine Learning

## 🔍 Overview
This project uses a machine learning model to detect whether a news article is REAL or FAKE based on its content. It uses Natural Language Processing techniques to analyze the article text.

## 📁 Dataset
- Combined from two CSV files: `Fake.csv` and `True.csv`
- Contains news articles labeled as "FAKE" or "REAL"

## 🛠️ Tools & Libraries
- Python
- Pandas, Numpy
- Scikit-learn
- TfidfVectorizer
- PassiveAggressiveClassifier

## 🧪 Process
1. Preprocess the data (combine + label)
2. TF-IDF Vectorization of text
3. Model Training using PassiveAggressiveClassifier
4. Evaluation using Accuracy Score & Confusion Matrix

## 📈 Accuracy Achieved
Around **90–94%**, depending on random split

## ✅ Output
Model predicts whether the input news article is REAL or FAKE.

## 📍 Sample Result
> “Indian Government launches AI Mission” → **REAL**

