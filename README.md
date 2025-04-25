# nlp-sentiment-analysis
# Sentiment Analysis on IMDb Dataset

## Overview
This project performs sentiment analysis on movie reviews from the **IMDb** dataset. The dataset has been modified to include **neutral sentiment**, turning it into a **multiclass classification problem** (Positive, Negative, Neutral). The models used in this project are:

- **Multinomial Naïve Bayes (MNB)**
- **Random Forest (RF)**
- **BERT Classifier**

## Table of Contents
1. [Installation](#installation)
2. [Dependencies](#dependencies)
3. [Project Structure](#project-structure)
4. [Models](#models)
5. [Evaluation Metrics](#evaluation-metrics)
6. [Results](#results)
7. [License](#license)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sentiment-analysis-imdb.git
Navigate to the project directory:

bash
Copy
Edit
cd sentiment-analysis-imdb
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Dependencies
Python 3.x

scikit-learn

pandas

numpy

transformers

torch

matplotlib

seaborn

Project Structure
bash
Copy
Edit
sentiment-analysis-imdb/
│
├── data/
│   └── imdb_reviews.csv  # Dataset containing IMDb reviews with added 'neutral' sentiment
├── models/
│   ├── mnb_model.py      # Multinomial Naïve Bayes model implementation
│   ├── rf_model.py       # Random Forest model implementation
│   └── bert_model.py     # BERT model implementation
├── notebooks/
│   └── exploration.ipynb # Exploratory data analysis (EDA)
├── requirements.txt      # Required Python packages
├── README.md             # Project overview and instructions
└── main.py               # Main script for running sentiment analysis
Models
Multinomial Naïve Bayes (MNB): This model uses TF-IDF for feature extraction and applies the Naïve Bayes algorithm for classification.

Random Forest (RF): A robust classifier based on ensemble learning.

BERT Classifier: A state-of-the-art transformer-based model fine-tuned for sentiment classification.

Evaluation Metrics
The following metrics were used to evaluate the performance of each model:

Accuracy

Precision

Recall

F1-score

AUC

Results
The models were compared using the above metrics, and the results are presented in the results section. The BERT classifier showed the highest performance in terms of accuracy and F1-score, outperforming both Multinomial Naïve Bayes and Random Forest models.
