# 📧 Email Spam Classification using Neural Networks

## Overview

This project focuses on building an Email Spam Classification system using a Neural Network.

The goal is to classify emails into:

* Spam
* Ham (Legitimate Email)

The project combines basic Exploratory Data Analysis (EDA), text preprocessing, TF-IDF vectorization, and a feedforward Neural Network for binary classification.

---

## Dataset

Dataset Used:

**190K+ Spam/Ham Email Dataset**

The dataset contains approximately:

* 102,159 Ham emails
* 91,691 Spam emails

Due to GitHub file size limitations, the dataset is not included in this repository.

---

## Project Workflow

```text
Email Data
    ↓
Data Cleaning
    ↓
Exploratory Data Analysis
    ↓
Text Preprocessing
    ↓
TF-IDF Vectorization
    ↓
Neural Network
    ↓
Spam / Ham Prediction
```

---

## Exploratory Data Analysis

Performed:

* Missing Value Analysis
* Class Distribution Analysis
* Character Count Analysis
* Word Count Analysis
* Sentence Count Analysis

Example Features:

* Character Count
* Word Count
* Sentence Count

---

## Text Preprocessing

Implemented:

* Lowercase Conversion
* Tokenization
* Stopword Removal
* Stemming using Porter Stemmer

---

## Feature Extraction

TF-IDF (Term Frequency - Inverse Document Frequency) was used to convert textual data into numerical vectors suitable for Neural Network training.

---

## Neural Network Architecture

```text
Input Layer
      ↓
Dense (128, ReLU)
      ↓
Dense (64, ReLU)
      ↓
Dense (32, ReLU)
      ↓
Dense (1, Sigmoid)
```

Loss Function:

* Binary Cross Entropy

Optimizer:

* Adam

Evaluation Metric:

* Accuracy

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTK
* Scikit-Learn
* TensorFlow / Keras

---

## Computational Notes

This dataset contains nearly 190,000 emails.

TF-IDF vectorization and Neural Network training required significant memory resources during experimentation. The project provided practical experience in handling larger NLP datasets and highlighted the importance of memory-efficient preprocessing techniques.

---

## Learning Notes

This project was primarily focused on:

* Basic EDA
* Text preprocessing fundamentals
* TF-IDF vectorization
* Neural Network implementation

I have not yet completed a dedicated NLP learning path. This project was built as an early exploration of NLP concepts while focusing mainly on data analysis and Neural Network modeling.

Future NLP topics planned:

* Word Embeddings
* Word2Vec
* GloVe
* RNNs
* LSTMs
* Transformers
* BERT
* Modern NLP Architectures

---

## Future Improvements

* Hyperparameter Tuning
* Model Comparison (Logistic Regression, Random Forest, XGBoost)
* Streamlit Web Application
* Model Deployment
* Advanced NLP Techniques
* Transformer-Based Models

---

## Author

Manvendra Singh Chouhan

AI/ML Engineering Student

Exploring Machine Learning, Deep Learning, Computer Vision, and NLP.
