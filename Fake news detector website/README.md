# Fake News Prediction with Chatbot Integration

A scalable Fake News Detection system built using Flask and Machine Learning, integrated with a chatbot interface to simulate real-time user interactions. The project explores personalization and trust scoring mechanisms to improve prediction accuracy and user validation.

🚀 Features
Fake News Classifier trained on real-world datasets
Interactive Chatbot to engage users and accept news inputs
Production-style Flask App with modular ML pipeline
Personalization Layer using trust scoring to enhance user-based prediction reliability
Comprehensive preprocessing including NLP techniques like TF-IDF, stopword removal, and stemming

📦 Tech Stack
Frontend: Chatbot UI (HTML/CSS + JavaScript)
Backend: Python, Flask
Machine Learning: scikit-learn, pandas, NumPy
NLP: NLTK, spaCy
Model: Logistic Regression / Naive Bayes (configurable)

🧠 ML Pipeline Overview
Data Cleaning – Remove punctuation, stopwords, and apply stemming
Feature Extraction – TF-IDF Vectorization
Model Training – Train/test split and evaluation with cross-validation
Trust Score Mechanism – Assign scores based on source/user reliability
Prediction – Model outputs probability with custom threshold
