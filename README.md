# DATA 620 - Week 10: Document Classification

This project focuses on building a document classification model to distinguish between spam and non-spam emails using the Spambase dataset.

## Project Overview
The goal of this assignment is to train a machine learning model on labeled email data and evaluate its ability to classify new, unseen documents.

## Approach
- Loaded the Spambase dataset from the UCI Machine Learning Repository
- Separated the dataset into features (X) and target (y)
- Split the data into training and testing sets (70/30 split)
- Trained a Naive Bayes classifier
- Evaluated performance using accuracy and a confusion matrix

## Results
- Accuracy: ~0.825
- The model performed well overall, particularly in identifying spam emails
- Some false positives were observed, where legitimate emails were classified as spam

## Reflection
This project reinforced the idea that machine learning models can be applied to document classification problems. It also highlighted the importance of evaluating model performance beyond accuracy, using tools such as the confusion matrix.

## Files
- DATA620_Week10_DocumentClassification_KevinMartin.ipynb
- PDF version of the notebook
