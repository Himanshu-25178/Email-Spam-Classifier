# 📧 Email Spam Classifier

## 🚀 Overview

An end-to-end Machine Learning and NLP project that classifies emails as **Spam** or **Ham (Not Spam)**. The model was trained on a dataset containing **5,169 email messages** and deployed as a web application for real-time predictions.

---

## 🎯 Problem Statement

Spam emails create inbox clutter, waste time, and can pose security risks. The objective of this project was to build a reliable machine learning system capable of automatically detecting spam emails while minimizing false positives.

---

## ⭐ Project Journey (STAR Method

### Situation

Email users receive a large number of unwanted spam messages daily. Manually filtering these messages is inefficient and prone to errors.

### Task

Build a machine learning model that accurately classifies emails as Spam or Ham while achieving high precision and reducing the chances of legitimate emails being incorrectly marked as spam.

### Action

#### 1. Data Cleaning

* Removed duplicate records
* Handled missing values
* Prepared a clean dataset for analysis

#### 2. Exploratory Data Analysis (EDA)

* Analyzed the distribution of spam and ham emails
* Explored message lengths and word frequencies
* Identified patterns in email content

#### 3. Text Preprocessing

Implemented a complete NLP preprocessing pipeline:

* Lowercasing
* Tokenization
* Removing special characters
* Removing stopwords
* Removing punctuation
* Stemming

#### 4. Feature Engineering

Converted textual data into numerical features using:

* Bag of Words (BoW)
* TF-IDF Vectorization

#### 5. Model Building

Trained and compared multiple machine learning algorithms:

* Gaussian Naive Bayes
* Multinomial Naive Bayes
* Bernoulli Naive Bayes

#### 6. Model Optimization (Major Challenge)

The most challenging part of the project was improving both **Accuracy** and **Precision** simultaneously.

To overcome this challenge:

* Tuned the **TF-IDF max_features** parameter
* Applied **Min-Max Scaling**
* Experimented with **Stacking Techniques**
* Compared multiple model configurations and feature sets

#### 7. Model Evaluation

Evaluated performance using:

* Accuracy Score
* Precision Score
* Confusion Matrix

#### 8. Web Application Development

Built an interactive web application where users can enter email text and instantly receive spam/ham predictions.

#### 9. Deployment

Deployed the trained machine learning model for real-time predictions.

---

## 📊 Final Results

| Metric    | Score           |
| --------- | --------------- |
| Accuracy  | **97%**         |
| Precision | **100% (1.00)** |

### Key Achievement

Through extensive experimentation with NLP preprocessing, TF-IDF feature engineering, model comparison, and parameter tuning, the final model achieved:

✅ **97% Accuracy**

✅ **100% Precision**

✅ Reliable Spam Detection Performance

✅ Real-Time Prediction Capability Through Web Deployment

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* TF-IDF Vectorizer
* Bag of Words
* Naive Bayes Algorithms
* Streamlit
* Git
* GitHub

---

## 📂 Project Workflow

```text
Raw Email Dataset
        │
        ▼
Data Cleaning
        │
        ▼
EDA
        │
        ▼
Text Preprocessing
        │
        ▼
TF-IDF / Bag of Words
        │
        ▼
Model Training
        │
        ▼
Model Optimization
        │
        ▼
Model Evaluation
        │
        ▼
Web Application
        │
        ▼
Deployment
```

---

## 🔮 Future Improvements

* Deep Learning Models (LSTM, GRU)
* Transformer Models (BERT)
* Multi-language Spam Detection
* Real-Time Email Integration

---

## 👨‍💻 Author

**Himanshu**

GitHub: https://github.com/Himanshu-25178
