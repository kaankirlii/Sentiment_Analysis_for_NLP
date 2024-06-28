# Sentiment Analysis using Natural Language Processing (NLP)

This repository contains a project for performing sentiment analysis using Natural Language Processing (NLP) and machine learning. The aim is to classify text data into positive, negative, or neutral sentiments.

## Project Overview

Sentiment analysis is a crucial task in NLP that helps in understanding the emotional tone behind a series of words. It has applications in various fields such as customer feedback analysis, social media monitoring, and market research.

## Dataset

A sample dataset containing 100 rows is used for this project. Each row consists of a text and its corresponding sentiment label (positive, negative, neutral).

## Files

- `sentiment_dataset.csv`: The dataset file containing 100 rows of text and sentiment labels.
- `sentiment_analysis.ipynb`: Jupyter Notebook containing the code for loading data, preprocessing, training the model, and evaluating its performance.
- `sentiment_model.pkl`: The trained sentiment analysis model.
- `tfidf_vectorizer.pkl`: The TF-IDF vectorizer used for transforming text data.

## Getting Started

### Prerequisites

Make sure you have the following libraries installed:

- pandas
- scikit-learn
- joblib
- google.colab (for Colab usage)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/sentiment-analysis-nlp.git
    cd sentiment-analysis-nlp
    ```

2. Install the required Python packages:
    ```sh
    pip install pandas scikit-learn joblib
    ```

### Usage

1. Upload the dataset to your Google Colab environment:
    ```python
    from google.colab import files
    uploaded = files.upload()
    ```

2. Run the `sentiment_analysis.ipynb` notebook to preprocess data, train the model, and evaluate its performance.
