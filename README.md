# Considering the Interaction between Hotel Star Rating and Reviewer Contributions in the Study of Review Unreliability: An Evaluation of Machine Learning and Deep Learning Model Performance

This repository contains the code and datasets used for my master's thesis: Considering the Interaction between Hotel Star Rating and Reviewer Contributions in the Study of Review Unreliability: An Evaluation of Machine Learning and Deep Learning Model Performance. The aim of the study is to investigate the inconsistencies between review texts and ratings in the hospitality industry and evaluate the performance of various machine learning and deep learning models to address review unreliability.

## Datasets
The datasets include hotel reviews from three major US cities: New York City, Chicago, and Orlando. These were collected using a web scraping system from **TripAdvisor**, focusing on reviews prior to September 1, 2023. The datasets are divided based on the type of tourism:
- **City Tourism**: Reviews from New York City and Chicago
- **Outdoor Tourism**: Reviews from Orlando

## Models and Methods

The study employs various machine learning and deep learning models, including:

- **Support Vector Regression (SVR)**
- **Random Forest**
- **XGBoost**
- **MLP**
- **Text-CNN**
- **LSTM**

Word embedding methods used include:

- **Bag of Word**
- **TF-IDF**
- **Doc2Vec**
- **GloVe**
- **Longformer**

## Result
The interaction between RC and HSC significantly impacts review ratings, with notable differences in city versus outdoor tourism datasets. Transformer-based models, particularly Longformer, showed superior performance in handling long text reviews. The Longformer-LSTM combination was found to be the most effective in predicting review ratings.


