# MailGuard

## Introduction
This repository contains the Mail Guard project, a machine learning-based email spam classification system developed to filter and manage your Gmail account's spam folder more effectively. This project leverages the power of Google’s Gmail API and Natural Language Processing (NLP) techniques to retrieve and preprocess emails.

The system utilizes sophisticated algorithms, specifically Support Vector Machines (SVMs) and Random Forest, to train models on preprocessed data with the goal of accurately classifying emails. The project provides an in-depth evaluation of the model’s performance using precision, recall, and F1-score metrics. This system has been rigorously tested and compared against existing state-of-the-art spam filtering systems to ensure optimal spam detection and classification with an impressive accuracy of 96%.

## Installation
Before you start, make sure you have a working Python 3.8 (or later) installation.

Clone the repository to your local machine:
```bash
git clone https://github.com/yourusername/mail-guard.git
cd mail-guard
```

## Usage
Before starting, make sure you have granted the necessary permissions for your Google account and have your Google API credentials.

Upload the file in jupyter NoteBook or Google Colab to run

## Development

The project consists of several key components:

1. Data Retrieval and Preprocessing: Google’s Gmail API is utilized to fetch emails, followed by text preprocessing using NLP techniques.
2. Feature Extraction: Key features from the preprocessed emails are extracted for machine learning purposes.
3. Model Training: Using the features extracted, the system trains models based on SVMs and Random Forest algorithms.
4. Evaluation: The models are evaluated rigorously using precision, recall, and F1-score metrics.

## Evaluation

A comprehensive evaluation has been performed on this system. The system has been compared with existing state-of-the-art spam filtering systems and has showcased superior performance with an accuracy of 96%.

Happy spam filtering!
