# News Classification using Natural Language Processing

This project aims to classify news articles into different categories such as politics, science, and technology using natural language processing (NLP) techniques. The process involves preprocessing the text data, extracting relevant features, training classification models, and evaluating their performance.

## Data Source

The dataset utilized in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/khoshbayani/news-texts). It comprises news articles with three columns: date, text (news headline), and label (category).

## Note

Please note that this project is no longer in active development and is provided here for reference purposes.

## Notebooks

### 1. Preprocessing

This notebook focuses on preprocessing the raw text data. It includes steps such as data cleaning, duplicate removal, tokenization, and encoding labels.

### 2. Embedding

In this notebook, the text data is embedded into vector representations using two different techniques: Doc2Vec and TF-IDF. The resulting vectors are saved for further processing.

### 3. Training and Evaluation

This notebook covers the training and evaluation of classification models using the preprocessed data. It includes the implementation of a dense neural network model using PyTorch and evaluation metrics such as accuracy, precision, recall, and confusion matrix.

### 4. Model Comparison

This notebook compares the performance of different classification models, including Logistic Regression and Naive Bayes, using the TF-IDF features. It provides insights into the strengths and weaknesses of each model.

## Conclusion

This project demonstrates the application of NLP techniques for news classification. While specific models and techniques were explored here, further experimentation and optimization may be required for real-world applications.