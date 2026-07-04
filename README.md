# 📰 Real vs Fake News Detection using Machine Learning

## 🚀 Overview
This project is an end-to-end Natural Language Processing (NLP) system that classifies news articles as Real or Fake using machine learning models. It uses TF-IDF vectorization and multiple classifiers to detect misinformation effectively.

## 🎯 Objective
- Detect fake news using text data
- Compare multiple ML models
- Extract meaningful linguistic patterns
- Build a complete NLP pipeline

## 📊 Dataset
- ~44,689 news articles
- Fake: ~23,478 | Real: ~21,211
- Features: title, text, subject, date

## 🧹 Preprocessing
- Lowercasing
- Removing URLs, HTML, punctuation
- Stopword removal (keeping negations)
- Porter stemming
- TF-IDF (5000 features, unigram + bigram)
- Train-test split (80/20 stratified)

## 🧠 Models Used
- Logistic Regression
- Naive Bayes
- SVM
- Decision Tree
- Random Forest
- Passive Aggressive Classifier

## 📈 Results

Random Forest: 99.88% accuracy  
SVM: 99.69%  
Passive Aggressive: 99.68%  
Decision Tree: 99.61%  
Logistic Regression: 99.23%  
Naive Bayes: 94.93%

## 🔍 Key Insights
- Fake news tends to be slightly longer
- Subject column is biased and not used directly
- TF-IDF bigrams improve performance significantly
- Retaining negation improves accuracy

## 🛠 Tech Stack
Python, Pandas, NumPy, Scikit-learn, NLTK, TF-IDF

## 📌 Conclusion
Traditional ML models with proper preprocessing achieve very high accuracy for fake news detection.

## 👨‍💻 Author
Vishal Prajapati
IIT Bhubaneswar
