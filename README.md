# ToxicTweets

**Toxic Tweets Classification Project**

**Overview**

This project involves the application of Natural Language Processing (NLP) methods to predict the toxicity of tweets. The dataset contains labeled tweets, where toxicity is denoted as 1 and non-toxicity as 0. The dataset can be downloaded from Toxic Tweets Dataset on Kaggle.

**Steps to Reproduce**

1. Data Preparation
Download the dataset from the provided Kaggle competition link.
Upload the CSV file to your Google Drive.

2. Google Colab Setup
Open the Jupyter Notebook (Toxic_Tweets_Classification.ipynb) using Google Colab.
Mount Google Drive to access the dataset file.

3. Data Processing
Convert the CSV file to a Pandas DataFrame.
Convert the text to the following representations:
Bag of Words
TF-IDF

4. Model Training
Train the following models:
Decision Trees
Random Forest
Naive Bayes
K-NN Classifier
SVM

5. Evaluation
Evaluate each model using metrics:
Precision, Recall, F1-Score
Confusion Matrix
RoC - AUC Curve

**Instructions for Google Colab Execution**

Open the provided Jupyter Notebook in Google Colab.

Mount your Google Drive to access the dataset file.

Execute the cells step by step to process data, train models, and evaluate results.
