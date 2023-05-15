# KNN-Tweets-and-Metadata

## KNN Algorithm with Nearest Neighbors Concept and Classifier Comparison

This Jupyter Notebook demonstrates the implementation of a K-Nearest Neighbors (KNN) algorithm using the concept of nearest neighbors without using direct classifiers. It also includes exploratory data analysis (EDA) and comparison of three classifiers.

## Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [K-Nearest Neighbors Algorithm](#k-nearest-neighbors-algorithm)
- [Classifier Comparison](#classifier-comparison)
  - [Classifier 1: Tweet Metadata](#classifier-1-tweet-metadata)
  - [Classifier 2: Text with TFIDF and PCA](#classifier-2-text-with-tfidf-and-pca)
  - [Classifier 3: Features-Tweet and Text](#classifier-3-features-tweet-and-text)

## Introduction

The K-Nearest Neighbors (KNN) algorithm is a simple and effective method for both classification and regression. It is based on the concept of finding the K closest instances in the feature space to a given test instance and making predictions based on the majority class of those K neighbors.

This notebook explores the implementation of the KNN algorithm without using direct classifiers. Instead, it focuses on the concept of nearest neighbors to make predictions.

## Dataset

The dataset used in this notebook contains a collection of tweets with associated labels. It includes both tweet metadata (e.g., user information, timestamp) and the text of the tweets. The goal is to classify the tweets into different categories based on their content.

## Exploratory Data Analysis

Before applying the KNN algorithm, it is essential to understand the dataset through exploratory data analysis. This step includes tasks such as data cleaning, handling missing values, feature selection, and visualizing the data distribution.

## K-Nearest Neighbors Algorithm

The KNN algorithm is implemented using the nearest neighbors concept. Instead of relying on pre-defined classifiers, the algorithm finds the K nearest neighbors to a test instance based on some distance metric (e.g., Euclidean distance). The majority class among the neighbors is used to predict the label of the test instance.

## Classifier Comparison

To evaluate the performance of the KNN algorithm, three different classifiers are built and compared:

### Classifier 1: Tweet Metadata

This classifier uses only the tweet metadata features to predict the labels. The KNN algorithm is applied using the metadata as the input features, and the accuracy is evaluated.

### Classifier 2: Text with TFIDF and PCA

This classifier focuses on the text of the tweets. The text data is preprocessed by applying TFIDF (Term Frequency-Inverse Document Frequency) to represent the importance of each word in the tweets. Principal Component Analysis (PCA) is then applied to reduce the dimensionality of the feature space. The KNN algorithm is applied using the transformed text features, and the accuracy is evaluated.

### Classifier 3: Features-Tweet and Text

This classifier combines both tweet metadata features and the processed text features. The KNN algorithm is applied using the combined features, and the accuracy is evaluated.

Note: The code and implementation details for each classifier can be found in the Jupyter Notebook.

Please refer to the Jupyter Notebook for detailed code implementation, explanations, and results.

