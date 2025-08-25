**Summary Report**

# Overview
The goal of this project was to build a deep learning–based Natural Language Processing (NLP) system to classify customer reviews of air fryer products into positive and negative sentiments.

# Steps Taken
1. Loaded the dataset containing air fryer product reviews.
2. Performed text preprocessing: lowercasing, punctuation removal, stopword removal,lemmatization and tokenization.
3. Converted text into numerical embeddings for model input.
4. Built three deep learning models:
   -> Basic Neural Network 
   -> Artificial Neural Network (ANN)
   -> Long Short-Term Memory (LSTM)
5. Trained and evaluated the models using Accuracy, Precision, Recall, and F1 Score.
6. Compared model performance using confusion matrices and accuracy plots.

# Challenges Faced
- Dealing with duplicate records.
- Creating a dataset by considering unique records in given dataset.
- Dealing with imbalanced class distribution.

# Contributions
All preprocessing, model building, and evaluation were done as part of this project.
Primary contributions include:
- EDA and text preprocessing pipeline
- Implementation of ANN and LSTM models
- Evaluation of models with accuracy, precision, recall, and F1-score
- Model comparison and recommendation (LSTM chosen as best)