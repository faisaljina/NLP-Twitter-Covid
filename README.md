### **Page available at https://faisaljina.github.io/NLP-Twitter-Covid/**
#

# NLP in Python to build a misinformation classifier of Covid-19 tweets

This project uses a research dataset from the Center for Machine Learning and Health at Carnegie Mellon University. The data comprises public Twitter posts on the topic of Covid-19, but, whilst derived from public postings, is itself privately held, so is not available to share here in full.
The data is ~3.5k tweets that have been labelled into 16 different categories depending on the content. These categories are:
- Irrelevant
- Politics
- True public health response
- News
- Calling out or correction
- Sarcasm or satire
- Fake cure
- Conspiracy
- True prevention
- Ambiguous or hard to classify
- False fact or prevention
- Panic buying
- Commercial activity or promotion
- Fake treatment
- Emergency
- False public health response

The goal is to build a classifier to identify tweet misinformation around Covid-19 using NLP techniques. This required use of the `re`, `nltk`, and `nrclex` packages, as well as `sklearn` and `imblearn` for modelling.

### Features
- EDA and Visualisation
- Tokenizing, Stopwords, Normalisation
- Feature Engineering
- Parts-of-Speech tagging
- Sentiment Analysis

### Techniques
- RegEx
- POS analysis
- VADER Affect analysis
- NRCLex Emotional analysis
- CountVectorizer
- TfidfVectorizer
- SMOTE-NC
- Bayesian & Logistic Regression Modelling

## Summary
1. The data was explored, cleaned, and tokenized, removing stopwords and normalising the tweets.
2. Simple metrics were derived, before POS tagging and analysis.
3. Sentiment analysis was conducted using VADER for affect and NRCLex for emotion.
4. Features were engineered and the data split and oversampled to address class imbalance.
5. The classification modelling used combinations of Count/Tfidf Vectorizer with Naive Bayes/Logistic Regression.
