# Email Spam Classifier (NLP Project)

This repository contains a Natural Language Processing (NLP) project to classify emails as **spam** or **not spam** using machine learning techniques. The project includes text preprocessing, feature extraction, model training, and evaluation.

## 📂 Contents

- `NLP.ipynb` — Jupyter notebook with code for preprocessing, feature engineering, model building, and evaluation.
- `email.csv` — Dataset of emails labeled as spam or not spam.

## ⚙️ Technologies Used

- Python 3.x  
- Jupyter Notebook  
- pandas  
- numpy 
- scikit-learn  
- matplotlib / seaborn (for visualizations)

## 🚀 Features

- Read and explore `email.csv` dataset.
- Preprocess email text: 
  - Lowercasing
  - Removing punctuation
  - Stopword removal
  - Stemming / lemmatization (if applicable)
- Convert text to numerical features using:
  - Bag of Words
  - TF-IDF
- Train and evaluate machine learning models:
  - Naive Bayes
  - Logistic Regression
  - (Other models if included)
- Compute accuracy, precision, recall, and F1-score.
- Visualize results (e.g., confusion matrix)
