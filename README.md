# 🐧 Penguin Classification using KNN and Naive Bayes 📊

This project explores the classification of penguin species by evaluating two popular machine learning algorithms: K-Nearest Neighbours (KNN) and Naive Bayes. The analysis aims to determine which algorithm performs best for classification based on different metrics. The notebook includes data loading, cleaning, and visualisation, followed by model training (with and without cross-validation), hyperparameter tuning, and comprehensive evaluation. The performance of the models is assessed using confusion matrices, precision, recall, F1-score, ROC curves, and Area Under the Curve (AUC). Additionally, the impact of Principal Component Analysis (PCA) on the performance of these models is investigated.

## 📜 Contents

This notebook covers the following steps:

1.  **Installation:** Installing the necessary R packages. 📦
2.  **Data Setup:** Loading and preparing the `palmerpenguins` dataset. 📁
3.  **Data Cleaning:** Handling missing values and selecting relevant features. ✨
4.  **Data Visualisation:** Exploring the distribution of key features. 📊
5.  **KNN without Cross-Validation:** Training and evaluating a basic KNN model. 🤖
6.  **Naive Bayes without Cross-Validation:** Training and evaluating a basic Naive Bayes model. 🤖
7.  **KNN with Cross-Validation:** Implementing KNN with 10-fold cross-validation for improved hyperparameter tuning. 🔄
8.  **Naive Bayes with Cross-Validation:** Implementing Naive Bayes with 10-fold cross-validation. 🔄
9.  **Principal Component Analysis (PCA):** Investigating the effect of dimensionality reduction on model performance using KNN and Naive Bayes. 🔍
10. **Evaluation:** Comparing the performance of all models using confusion matrices, precision, recall, F1-score, ROC curves, and AUC. ✅

## 📊 Dataset 

This project uses the `palmerpenguins` dataset. 🐧

## Tech and Libraries

This project uses the R programming language and several libraries, including `tidyverse`, `palmerpenguins`, `caret`, `class`, `scales`, `ggplot2`, `pROC`, `naivebayes`, and `e1071`. 📚

## Models

The following machine learning models are evaluated:

*   K-Nearest Neighbours (KNN)
*   Naive Bayes

## 🛠️ Installation

To run this notebook, you need to have R installed. The required packages can be installed directly from within the R environment using the code in the notebook. ⬇️

## 📈 Results

The notebook presents the evaluation metrics for each model, both with and without cross-validation and PCA. The confusion matrices, precision, recall, F1-scores, ROC curves, and AUC values provide insights into the performance of KNN and Naive Bayes for penguin species classification on this dataset. 🎯

## 🙏 Acknowledgements

This project utilises the `palmerpenguins` dataset, generously provided by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER. 🙌

## How to Run the Notebook

To use this notebook:

1.  Open the notebook in a compatible environment (like Google Colab with R kernel). 💻
2.  Run the cells sequentially to follow the data analysis and model training process. ▶️
3.  Examine the outputs and visualisations to understand the data and model performance. 👀

---
