# 📧 Email/SMS Spam Detection System

This project implements a machine learning–based spam classifier to distinguish between spam and non-spam emails or SMS messages. It uses a Naive Bayes model with TF-IDF features, built in Python with a Streamlit user interface.

---

## 🚀 Features

- Accepts email or SMS text input
- Preprocesses text with tokenization, stemming, and stopword removal
- Uses a trained Multinomial Naive Bayes classifier
- Shows prediction probabilities
- Clean Streamlit web interface
- Easy to run locally or deploy on Streamlit Cloud

---

## 📂 Project Structure
spam-email-detector/
│
├── app.py # Streamlit frontend
├── train.py # Model training script
├── emails.csv # Labeled spam dataset
├── model.pkl # Saved trained classifier
├── vectorizer.pkl # Saved TF-IDF vectorizer
├── requirements.txt # Dependencies
└── README.md # Project documentation


