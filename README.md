# Spam Email Filter using NLP

This project implements a robust spam email filter using Natural Language Processing (NLP) and machine learning techniques in Python. The model is trained and evaluated on a dataset of emails to classify them as spam or non-spam.

## Features

- **Data Preprocessing:**  
  - Lowercasing, tokenization, removal of stopwords, and filtering non-alphabetic tokens using NLTK.
- **Exploratory Data Analysis:**  
  - Class distribution, word frequency, word clouds, and various visualizations (histograms, box plots, violin plots, pie charts).
- **Model Building:**  
  - Uses a pipeline with `CountVectorizer` and `MultinomialNB` (Naive Bayes classifier).
- **Evaluation Metrics:**  
  - Accuracy, precision, recall, F1-score, confusion matrix, classification report, and precision-recall curve.
- **Feature Analysis:**  
  - Identifies top words contributing to spam and non-spam predictions.

## Dataset

- The dataset (`emails.csv`) contains two columns:
  - `text`: The raw email content.
  - `spam`: Label (1 for spam, 0 for non-spam).

## Libraries Used

- pandas
- scikit-learn
- nltk
- matplotlib
- seaborn
- wordcloud