# 💬 Sentiment Analysis with Machine Learning

This project performs **Sentiment Analysis** using a Machine Learning model that classifies text reviews as **positive** or **negative**.

---

## 📌 Overview

The model is trained on labeled text data to understand the sentiment behind sentences or reviews (like movie or product reviews). It uses a **bag-of-words approach** for feature extraction and a **Logistic Regression** model for prediction.

---

## 🧠 What It Does

- Takes user reviews or text as input
- Cleans and preprocesses the text
- Converts text into numeric format using **CountVectorizer**
- Trains a **Logistic Regression** model
- Predicts whether the review is **positive** or **negative**

---

## 📂 Dataset

- **Source**: Custom or preloaded reviews
- Each record contains:
  - A **review text**
  - A **label** (`0 = Negative`, `1 = Positive`)

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- Scikit-learn
- CountVectorizer
- Logistic Regression

---

## 📊 Sample Output

```python
Enter your review: This product is amazing!
Prediction: Positive ✅
