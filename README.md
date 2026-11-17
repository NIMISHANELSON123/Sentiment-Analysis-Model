# Sentiment-Analysis-Model

Sentiment and Emotion Analysis using Machine Learning

This repository contains the Jupyter Notebook and source code for Assignment 11, focusing on Natural Language Processing (NLP) to classify text sentiments and emotions using machine learning algorithms.


📌 Project Overview

The objective of this assignment is to build, train, evaluate, and compare two different machine learning classifiers—Multinomial Naive Bayes and Support Vector Machine (SVM)—on a given sentiment dataset (nlp_dataset.csv).


🛠️ Tech Stack & Libraries Used

 * Python (Core programming)
   
 * Pandas (Data manipulation and cleaning)
   
 * NLTK (Natural Language Toolkit for text preprocessing, tokenization, and stop-words removal)
   
 * Scikit-Learn (For TF-IDF feature extraction, model training, and performance evaluation)
   
 * Matplotlib & Seaborn (For data visualization, confusion matrix heatmaps, and accuracy comparison charts)
   
📂 Project Structure

The workflow inside the Jupyter Notebook (Sentiment_Analysis_Model.ipynb) is structured into the following parts:

 * Loading and Preprocessing: Loading the dataset, checking for missing values, lowercasing, text cleaning, tokenization, and removing stop words.
   
 * Feature Extraction: Transforming text documents into numerical feature vectors using TfidfVectorizer.
   
 * Model Development: Splitting the dataset (80\% training, 20\% testing) and training both Multinomial Naive Bayes and Linear SVM classifiers.
   
 * Model Comparison & Evaluation: Evaluating models using Accuracy, F1-Score, Classification Reports, Confusion Matrices, and an Accuracy Comparison Bar Chart.
   
📊 Results & Performance Summary

| Model | Accuracy | Key Observations |
|---|---|---|
| Multinomial Naive Bayes | 91.08% | Provides a strong, efficient baseline for text count distributions. |
| Support Vector Machine (SVM) | 94.44% | Outperformed Naive Bayes due to superior capability in handling high-dimensional sparse feature spaces and optimal hyperplane separation. |

🚀 How to Run the Code

 * Clone the repository or download the files.
   
 * Ensure you have Jupyter Notebook and the required libraries installed (pandas, nltk, scikit-learn, matplotlib, seaborn).
   
 * Place nlp_dataset.csv in the same directory as the notebook.
   
 * Open Sentiment_Analysis_Model.ipynb and run all the cells sequentially.

 * Open Sentiment_Analysis_Model.ipynb and run all the cells sequentially.
