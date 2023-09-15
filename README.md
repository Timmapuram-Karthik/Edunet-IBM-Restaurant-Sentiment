# Sentiment Analysis of Restaurant Reviews

This repository contains code and resources for a sentiment analysis project conducted as part of an internship with Edunet Foundation in collaboration with IBM. The project involves applying machine learning techniques to analyze sentiment in restaurant reviews and predict whether a review expresses a positive or negative sentiment.

## Explore the Sentiment Analysis of Restaurant Model!
Click below to open the project in an interactive Google Colab notebook:

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Timmapuram-Karthik/Edunet-IBM-Restaurant-Sentiment/blob/main/Sentimental%20Restaurant%20Review.ipynb)


## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Collaboration](#collaboration)
- [Code Overview](#code-overview)
- [Usage](#usage)
- [Results](#results)
- [Acknowledgments](#acknowledgments)
- [Author](#author)

## Introduction

Sentiment analysis, also known as opinion mining, is a text analysis technique used to determine the sentiment expressed in textual data. This project focuses on sentiment analysis applied to restaurant reviews, aiming to uncover customer sentiments and opinions about dining experiences.

## Dataset

The dataset employed in this project comprises restaurant reviews with labeled positive or negative sentiments. The dataset is loaded from a TSV (Tab-Separated Values) file and is available within the `data` directory.

## Collaboration

This sentiment analysis project was undertaken as part of an internship with Edunet Foundation, with a collaborative effort between Edunet Foundation and IBM. The project benefited from the expertise and resources of both organizations to achieve its objectives.

## Code Overview

The code within this repository encompasses the complete sentiment analysis pipeline:

1. **Data Loading and Exploration**: The dataset is loaded using pandas, and initial exploration is performed to understand its structure.

2. **Data Preprocessing**: Text data is preprocessed by converting it to lowercase, tokenizing, stemming, and removing stopwords.

3. **Feature Extraction**: Text data is transformed into numerical features through Count vectorization.

4. **Model Selection and Evaluation**: Multiple machine learning models are considered for sentiment analysis, including Multinomial Naive Bayes, Random Forest, Gradient Boosting, XG Boost and Support Vector Classifier (SVC).

5. **Best Model Identification**: The best-performing model is identified based on accuracy.

6. **Model Evaluation Metrics**: Training scores, testing scores, accuracy, confusion matrix, and classification report are displayed for each model.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Timmapuram-Karthik/Edunet-IBM-Restaurant-Sentiment
   cd Edunet-IBM-Restaurant-Sentiment
   ```
2. Run the Jupyter notebook to perform sentiment analysis on the restaurant reviews dataset.

## Results

The results of the sentiment analysis, including evaluation metrics and insights about the best-performing model, are provided in the code output and comments within the Jupyter notebook.

## Acknowledgments

- This project was carried out during an internship with Edunet Foundation in collaboration with IBM.
- The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/vigneshwarsofficial/reviews).

## Author

- T.Karthik
- [LinkedIn Profile](https://www.linkedin.com/in/timmapuram-karthik/)
- [GitHub Profile](https://github.com/Timmapuram-Karthik)

Feel free to contribute, provide feedback, or use this project for learning and experimentation.
