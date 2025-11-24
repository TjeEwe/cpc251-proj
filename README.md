# CPC251 Machine Learning Project – Cancer Risk Prediction

## Overview
This project applies machine learning techniques to classify cancer risk using the **risk_factors.csv** dataset.  
The project is divided into two parts:

- **Part 1:** Logistic Regression (Default & Tuned) and Decision Tree  
- **Part 2:** Logistic Regression (Default & Tuned) and Neural Network (Keras)

The main evaluation metric is **F1-score**, chosen due to class imbalance and to balance precision and recall in medical predictions.

## Repository Structure
```
├── Project Part 1.ipynb               # Logistic Regression + Decision Tree
├── Project Part 2.ipynb               # Logistic Regression + Neural Network
├── Project Part 2 Keras Ver.ipynb     # Neural Network tuned with Keras
├── keras_tuner_results/               # Saved NN tuning results
├── risk_factors.csv                   # Dataset
└── README.md
```

## Methods
### Part 1
- Logistic Regression (default + hyperparameter tuning)
- Decision Tree Classifier
- Evaluation metrics: Accuracy, Precision, Recall, **F1-score**

### Part 2
- Logistic Regression retested for comparison
- Neural Network built and tuned using **Keras Tuner**
- Evaluated using **F1-score** to determine the best-performing model

## Findings
- **Logistic Regression (Default)** achieved the highest F1-score overall.
- Neural Network performed reasonably but did not outperform Logistic Regression.
- F1-score was prioritized to manage false positives and false negatives in medical prediction.

## Requirements
```
python >= 3.8
numpy
pandas
matplotlib
seaborn
scikit-learn
tensorflow
keras-tuner
```
