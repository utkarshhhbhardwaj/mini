# Fake News Detection using BERT

## Overview

This project builds a simple NLP system that classifies news articles as **Fake** or **Real**.
The model is trained using a transformer-based deep learning model called BERT.

## Dataset

The **Kaggle Fake News Dataset** was used. It contains news articles labeled as fake or real.

## Model

The project uses **BERT (Bidirectional Encoder Representations from Transformers)** for text classification.
The model was fine-tuned on the dataset to learn how to detect fake news.

## Steps in the Project

1. Loaded and explored the dataset
2. Tokenized text using the BERT tokenizer
3. Trained the model on the training data
4. Evaluated the model using accuracy, precision, recall, and F1-score
5. Performed error analysis on incorrect predictions
6. Compared BERT with DistilBERT for faster performance

## Results

The model was able to classify fake and real news with good accuracy.
A confusion matrix and classification report were used to evaluate performance.

## Author

Utkarsh Bhardwaj
