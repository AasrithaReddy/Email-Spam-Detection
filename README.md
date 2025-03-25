# 📧 Email Spam Detection with Machine Learning

This project demonstrates how to use machine learning and natural language processing (NLP) to detect whether an email is spam or not.

## 📘 Description

Spam detection is a common NLP task where we train a model to classify emails into two categories: **Spam** or **Not Spam**. This notebook walks through data import, preprocessing, feature extraction, model training, and evaluation.

## 🛠️ Tools & Libraries Used

- Python
- Google Colab
- Pandas
- NLTK
- Scikit-learn
- CountVectorizer

## 📂 Dataset

- The dataset is uploaded manually via Google Colab.
- It typically includes labeled email messages indicating whether they are spam or not.

## 💡 Sample Code

```python
from google.colab import files
uploaded = files.upload()
