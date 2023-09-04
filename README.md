# Spam Classifier

This is the final project for the Machine Learning class at the University of Potsdam. The goal of this project is to build a spam classifier that achieves a false positive rate of less than 0.2%. The dataset used for this project contains 10,000 samples.

## Project Overview

In this project, I aim to compare two different text representation techniques: TF-IDF (Term Frequency-Inverse Document Frequency) and Bag of Words (BoW). A logistic regression model is used for spam classification using both TF-IDF and BoW representations. Additionally, I adjust the threshold of the logistic regression model using the ROC (Receiver Operating Characteristic) curve to achieve a false positive rate of 0.0%.

## Dataset

The dataset used for this project contains 10,000 samples and is used for training and testing the spam classifier. The data will be preprocessed and split into training and testing sets to evaluate the performance of the models.

## Methods and Techniques

- Removing 100 stop words.
- Implementing TF-IDF and BoW representations for the text data.
- Building a logistic regression model for spam classification.
- Evaluating the model using the ROC curve.
- Adjusting the threshold to achieve a 0.0% false positive rate.
