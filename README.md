# 📦 Sentiment Analysis of Amazon Product Reviews
[![Python](https://img.shields.io/badge/Python-3.x-blue)](#)
[![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-green)](#)
[![Deep Learning](https://img.shields.io/badge/Model-Transformers-orange)](#)
[![Dataset](https://img.shields.io/badge/Dataset-Amazon%20Reviews-lightgrey)](#)

A comprehensive **sentiment analysis project** that classifies Amazon product reviews as **positive or negative** using both **classical machine learning models** and **transformer-based deep learning models**.

---

## 📌 Overview

Online shopping platforms like Amazon rely heavily on user reviews. However, due to the massive volume of textual feedback, manual analysis is impractical.

This project applies **Natural Language Processing (NLP)** techniques to automatically analyze Amazon reviews and determine their sentiment. The study compares the performance of traditional machine learning models with modern **transformer-based models**.

---

## ✨ What This Project Does

- 📄 Processes large-scale Amazon review text data
- 🧹 Cleans and preprocesses textual data
- 🧠 Trains classical ML models for sentiment classification
- 🤖 Trains transformer-based models for comparison
- 📊 Evaluates models using multiple performance metrics
- 📈 Analyzes strengths and weaknesses of different approaches

---

## 📊 Dataset Information

This project uses the **Amazon Reviews Polarity Dataset** from Kaggle.

- **Source:** Kaggle – *Amazon Reviews* by Kritanjali Jain  
- **Link:** https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews/data

### Dataset Description
- Reviews labeled as:
  - **Negative**: ratings 1 & 2
  - **Positive**: ratings 4 & 5
  - Rating 3 is excluded
- Each review contains:
  - `polarity` (label)
  - `title` (review headline)
  - `text` (review body)
- Original dataset size:
  - 1.8M training samples per class
  - 200K testing samples per class

To ensure computational feasibility, a **random subset of the dataset** is used during experimentation.

---

## 🧰 Technology Stack

- **Python**
- **Jupyter Notebook**
- **Natural Language Processing**
- **Scikit-learn**
- **Transformers (Hugging Face)**
- **NumPy, Pandas, Matplotlib**
- **Google Colab**

---

## 📈 Evaluation Metrics

Models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* ROC-AUC Curve

This allows a detailed comparison between classical and deep learning approaches.

---

## 🎯 Applications

* Customer feedback analysis
* Product quality monitoring
* Recommendation systems
* Market sentiment analysis
* NLP research and education

---

## ⭐ What this Project Is about

* Demonstrates real-world NLP pipeline
* Compares classical ML vs transformer models
* Handles large-scale text datasets
* Relevant to industry NLP use cases

---

## 📌 Notes

* Large datasets may require significant memory
* Google Colab is recommended for smooth execution

---
