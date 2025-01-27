# 📧 Email Filtering Project

This project implements an email classification system that filters emails into different categories (e.g., spam or not spam) using four different machine learning models: **Random Forest**, **Bernoulli Naive Bayes**, **Logistic Regression**, and **Support Vector Classifier (SVC)**. The goal is to compare the performance of these models and select the one with the best accuracy for classifying emails.

## 📜 Project Overview

The email filtering system classifies emails into categories based on features extracted from the email content (e.g., words, phrases, email metadata). The classification process uses machine learning models trained on a labeled dataset of emails.

### 🔍 Models Used

- **🌳 Random Forest**: An ensemble learning method that combines multiple decision trees to improve classification accuracy.
- **📊 Bernoulli Naive Bayes**: A probabilistic model based on Bayes' theorem, suitable for binary features.
- **📝 Logistic Regression**: A linear model that is often used for binary classification tasks.
- **⚖️ Support Vector Classifier (SVC)**: A powerful model for classification tasks, especially with non-linear decision boundaries.

## 🌟 Features

- **📅 Dataset**: The project uses a labeled dataset of emails, with features such as the subject, body text, and metadata.
- **🧹 Preprocessing**: The text data is preprocessed to remove noise, such as stopwords, punctuation, and special characters.
- **🛠️ Model Training**: The models are trained on the preprocessed data and evaluated on accuracy.

## 📋 Requirements

To run this project, you will need the following Python libraries:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib` (optional, for visualizing results)
- `seaborn` (optional, for visualization)

You can install the dependencies using `pip`:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
