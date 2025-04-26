# Sentiment Analysis on IMDb Dataset

## Overview
This project performs sentiment analysis on movie reviews from the **IMDb** dataset. The dataset has been modified to include **neutral sentiment**, turning it into a **multiclass classification problem** (Positive, Negative, Neutral). The models used in this project are:

- **Multinomial Naïve Bayes (MNB)**
- **Random Forest (RF)**
- **BERT Classifier**

## Installation

1. Clone the repository:
   git clone https://github.com/fai05/NLP-based-Sentiment-Analysis.git

2. Navigate to the project directory:
   cd NLP-based-Sentiment-Analysis

3. Install the required dependencies:

- Python 3.x
- scikit-learn
- pandas
- numpy
- transformers
- torch
- matplotlib
- seaborn


## Models

1. **Multinomial Naïve Bayes (MNB)**: This model uses **TF-IDF** for feature extraction and applies the Naïve Bayes algorithm for classification.
2. **Random Forest (RF)**: A robust classifier based on ensemble learning.
3. **BERT Classifier**: A state-of-the-art transformer-based model fine-tuned for sentiment classification.

## Evaluation Metrics

The following metrics were used to evaluate the performance of each model:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **AUC**
