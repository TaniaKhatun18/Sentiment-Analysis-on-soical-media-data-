# Sentiment Analysis Project

##  Overview

This project performs sentiment analysis on Twitter data using machine learning techniques. It classifies text into Positive and Negative sentiments, with an additional Neutral category introduced using probability thresholding.

##  Features

* Text preprocessing (cleaning, stopwords removal)
* TF-IDF feature extraction
* Logistic Regression model
* Gradio web app for real-time predictions
* Visualization (confusion matrix, charts)

##  Dataset

Sentiment140 Dataset (Kaggle)
https://www.kaggle.com/datasets/kazanova/sentiment140

##  Installation

```bash
pip install pandas numpy scikit-learn nltk gradio joblib
```

##  Run the Project

Open Jupyter Notebook

Open the file:

Sentiment_analysis_on_Social_Media_Data.ipynb

Click "Run All Cells"

##  Model

* Algorithm: Logistic Regression
* Feature Extraction: TF-IDF

##  Results

* Balanced dataset (Positive & Negative)
* Good accuracy on test data
* Neutral class handled using probability threshold

##  Future Work

* Add deep learning models (LSTM, BERT)
* Improve UI using Streamlit
* Expand dataset with neutral sentiment

##  Author

Tania Khatun
