
# Sentiment Analysis Using NLP on IMDB Movie Reviews

This project demonstrates sentiment analysis using Natural Language Processing (NLP) techniques on the IMDB movie reviews dataset. The goal is to classify reviews as **positive** or **negative** based on their content.
---

## Overview
Sentiment analysis is a key application of NLP that analyzes the sentiment behind text data. In this project:
- The IMDB movie reviews dataset is used as the data source.
- Machine learning models are trained to classify reviews as positive or negative.
- Techniques such as text preprocessing, tokenization, and vectorization are applied.

---

## Features
- Load and preprocess the IMDB dataset.
- Perform tokenization, stopword removal, and text vectorization (e.g., TF-IDF ).
- Train machine learning or deep learning models (e.g.,Multinomial Bayes).
- Evaluate model accuracy, precision, recall, and Confusion matrix
- Predict sentiment for new reviews.

---

## Dataset
The IMDB dataset contains 50,000 movie reviews:
- **50% positive reviews**
- **50% negative reviews**

It is freely available from [Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews?resource=download) or via the `tensorflow_datasets` library.

---

## Required Libraries
- numpy
- pandas
- matplotlib
- scikit-learn
- nltk 


---
## Results
- The analysis has achieved:

- Accuracy: Approximately 85% on test data.
- Performance: Successfully classifies new reviews as positive or negative.
