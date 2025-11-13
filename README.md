# Fake News Detection - Social Media Mining Project

This project focuses on detecting fake news shared across social media platforms using natural language processing (NLP) and machine learning (ML) techniques. It explores linguistic and structural patterns in news content to classify articles as real or fake.

---

## Overview

The rapid spread of misinformation on social media has made fake news detection an essential task.  
This project applies machine learning and text mining to automatically identify fake news by analyzing text content, sentence structure, and word usage patterns.

The notebook `Fake_news_detection.ipynb` performs:
- Data loading and cleaning
- Feature extraction using linguistic and semantic features
- Text embedding using BERT
- Model training and evaluation
- Visualization of results and performance metrics

---

## Features and Techniques Used

- **Data Preprocessing**
  - Loading JSON files containing fake and real news
  - Mapping unique news IDs
  - Cleaning and formatting text data

- **Feature Engineering**
  - Counting quotations in the news text
  - Measuring headline length
  - Counting Part-of-Speech (POS) tags (nouns, verbs, adjectives, adverbs)
  - Counting stopwords
  - Calculating Jaccard similarity between users sharing the same news
  - Generating embeddings using BERT for deep semantic representation

- **Visualization**
  - Class distribution of real vs fake news
  - Data and feature correlations

- **Machine Learning Models**
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
  - Deep Learning using BERT embeddings

- **Evaluation**
  - Accuracy, Precision, Recall, F1-score, and Confusion Matrix

---

## Steps in the Notebook

1. **Load News Data**
   - Reads `News.txt` and maps to JSON content.
   - Labels each news as fake or real.

2. **Text Analysis**
   - Extracts title and main text content.
   - Applies preprocessing and linguistic feature extraction.

3. **Feature Combination**
   - Combines numeric and text features into a single training dataset.

4. **Model Training**
   - Trains classification models to distinguish fake vs real news.

5. **Evaluation and Visualization**
   - Evaluates model accuracy and visualizes class distribution.
     
---
 **Install dependencies:**
     - pip install -r requirements.txt
     
---
**Requirements.txt**
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - nltk
  - spacy
  - transformers
  - torch
  - tensorflow
  - jupyter

---

## Installation and Setup

Clone the repository:

```bash


git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
