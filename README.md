# Spam Detection

This project aims to detect spam emails using various machine learning algorithms, including K-Nearest Neighbors (KNN), Logistic Regression, Random Forest, and AdaBoosting.


## Introduction

Spam detection is the task of identifying unsolicited and unwanted emails that are sent in bulk. It is an important problem in email filtering and has various applications in the field of cybersecurity. In this project, we explore different machine learning algorithms to build a spam detection system.

## Data

To train and evaluate the spam detection models, we use a labeled dataset consisting of both spam and non-spam emails. The dataset is preprocessed and features are extracted to represent each email. The features may include word frequencies, presence of certain keywords, and other relevant information.

## Algorithms

### K-Nearest Neighbors (KNN)

KNN is a simple and intuitive classification algorithm that assigns a class label to a data point based on the majority class of its k nearest neighbors. In the context of spam detection, KNN can be used to classify emails as spam or non-spam based on the similarity of their feature vectors.

### Logistic Regression

Logistic Regression is a popular algorithm for binary classification. It models the relationship between the input features and the probability of an email being spam. By fitting a logistic function to the training data, it can predict the probability of an email being spam and classify it accordingly.

### Random Forest

Random Forest is an ensemble learning algorithm that combines multiple decision trees to make predictions. Each decision tree is trained on a random subset of the training data and features. In the context of spam detection, Random Forest can be used to identify important features and make accurate predictions.

### AdaBoosting

AdaBoosting is another ensemble learning algorithm that combines multiple weak classifiers to create a strong classifier. It iteratively trains weak classifiers on different subsets of the training data, giving more weight to misclassified samples in each iteration. In the context of spam detection, AdaBoosting can be used to improve the overall classification performance.

## Usage

To use this project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/spam-detection.git`
2. Install the required dependencies
3. Run the main script: `train.ipynb`



