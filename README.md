# Fake News Detection

## Overview
This project detects whether a news article is **Fake** or **Real**. It uses **Natural Language Processing (NLP)** and **Machine Learning** to train a model that can classify news articles based on their content.

---

## Dataset
The dataset used is from the **ISOT Fake News Dataset**, containing thousands of real and fake news articles. Each article has a `title` and `text` field.  

- Real news label = 0  
- Fake news label = 1  

---

## Preprocessing
1. Combined `title` and `text` into a single column.  
2. Split dataset into **training** (80%) and **testing** (20%) sets.  
3. Converted text into numeric vectors using **TF-IDF Vectorizer**.  

---

## Model
- **Algorithm:** Logistic Regression  
- **Features:** TF-IDF vectorized text  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, Confusion Matrix  

---

## How to Use
1. Load the trained model and TF-IDF vectorizer.
2. Predict new articles.

## Results
The trained model achieves high accuracy in distinguishing Fake and Real news, making it suitable for quick news verification tasks.

## Requirements
Python 3.x
pandas
scikit-learn
joblib
seaborn, matplotlib (for evaluation/visualization)
