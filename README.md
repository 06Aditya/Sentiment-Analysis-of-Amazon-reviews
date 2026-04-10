# Amazon Reviews Sentiment Analysis

A machine learning project that analyzes Amazon product reviews to classify sentiment as positive or negative.

---

## Overview

With the rise of e-commerce, customer reviews play a crucial role in influencing purchasing decisions. This project applies sentiment analysis techniques to understand how customers feel about products based on their reviews.

The goal is to build a model that can automatically predict the sentiment of a given review.

---

## Dataset

The dataset is sourced from Kaggle:
https://www.kaggle.com/datafiniti/consumer-reviews-of-amazon-products

It contains product reviews along with associated metadata, which are used to train and evaluate the model.

---

## Approach

### Data Preprocessing

* Cleaned and normalized text data
* Removed unnecessary characters and noise
* Handled missing values

---

### Feature Engineering

* Converted text into numerical features using vectorization techniques (e.g., TF-IDF)

---

### Model

* Used **Support Vector Machine (SVM)** for classification
* Trained on labeled review data to predict sentiment

---

## Tech Stack

* Python
* Pandas, NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Project Structure

```id="q3xk1b"
Amazon-Reviews-Sentiment-Analysis/
│── notebook.ipynb
│── dataset/
│── images/
│── README.md
```

---

## Future Improvements

* Experiment with advanced models (LSTM, BERT)
* Improve text preprocessing and feature engineering
* Deploy as a web application
* Add real-time sentiment prediction

---

## Contact

* LinkedIn: https://www.linkedin.com/in/aditxya/

---

If you found this project useful, consider giving it a ⭐
