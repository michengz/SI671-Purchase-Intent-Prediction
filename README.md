# SI671-Purchase-Intent-Prediction
Data Mining Course Final Project @ University of Michigan
## Project Overview
The goal of the project was to explore methods for processing clickstream data and build models that could accurately predict customer purchase intent early in a user's click journey on an e-commerce website. To achieve this, we queried and manipulated 2M+ rows of clickstream data using Google BigQuery (SQL) and Python, and built sequential models (Markov Chains, LSTM) as well as feature-based classification models (SVM). Through this work, we were able to analyze the minimum length of clickstream data necessary for early-stage purchase prediction and achieved a prediction accuracy of 85%.
A few research questions that were explored throughout the project include:
1. Are we able to predict purchase intent at an early stage of a user session? What is the minimum length of clickstream sequence required to make acceptable predictions?
2. Can Sequence Modeling on clickstream data outperform common feature-based classification models?
3. How does the level of interaction (e.g. page-level, event-level) affect prediction performances? Does categorization of pageviews help with improving performance?
