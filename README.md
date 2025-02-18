# Password Strength Checker

## 📌 Project Overview

This project aims to evaluate the strength of passwords using **TF-IDF (Term Frequency-Inverse Document Frequency)** vectorization combined with machine learning classifiers. By analyzing the characteristics of passwords, the model classifies them into categories such as 'Weak', 'Medium', or 'Strong'.

## 🚀 Features

- **Data Processing**: 
  - Loaded and preprocessed a dataset of passwords with associated strength labels.
  - Applied TF-IDF vectorization to transform password strings into numerical feature vectors.

- **Model Training & Evaluation**:
  - Implemented machine learning classifiers including:
    - **Random Forest Classifier**
  - Evaluated model performance using metrics like accuracy.

- **Prediction Functionality**:
  - Developed functions to predict the strength of new passwords based on the trained models.

## 🛠 Tech Stack

- **Programming Language**: Python 3.x
- **Libraries**:
  - Data Processing: `pandas`, `numpy`
  - Machine Learning: `scikit-learn`
  - Text Vectorization: `nltk` (for TF-IDF)
  - Visualization: `matplotlib`, `seaborn`
- **Development Environment**: Jupyter Notebook

## 📊 Dataset

The project utilizes a dataset containing passwords labeled with their respective strength levels:
- **Weak**: Passwords that are easily guessable.
- **Medium**: Passwords with moderate complexity.
- **Strong**: Passwords that are complex and hard to crack.
