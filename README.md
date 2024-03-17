# Airline Review Sentiment Analysis and Recommendation Prediction
This Python project utilizes sentiment analysis to predict the likelihood of a flight being recommended based on customer reviews. It leverages the vaderSentiment library to analyze textual data and logistic regression for prediction.

Abstract
This project aims to predict the recommendation status of flights by analyzing customer reviews. It employs sentiment analysis techniques using the vaderSentiment library to extract sentiment scores from textual data. Logistic regression is then utilized to predict whether a flight is likely to be recommended based on various features extracted from the reviews.

Introduction
The project begins with the installation of the vaderSentiment library via pip. It then proceeds to data processing, including text preprocessing and feature extraction. Logistic regression is employed as the predictive model, trained on features extracted from customer reviews.

Data Preparation
The dataset, "data_airline_reviews.xlsx", contains various features including overall ratings and customer reviews. Preprocessing steps involve cleaning the data, removing unnecessary columns, and extracting sentiment scores from the text.


Modeling Approach
Logistic regression is chosen as the predictive model due to its effectiveness in binary classification tasks. Features such as overall ratings and sentiment scores are used to train the model. The project utilizes the vaderSentiment library for sentiment analysis, providing a comprehensive understanding of customer sentiment.

Prediction Results
The trained logistic regression model is used to predict the likelihood of flights being recommended based on input features. Evaluation metrics such as accuracy are calculated to assess the model's performance.

Dependencies
Ensure you have the following dependencies installed:

pandas
scikit-learn
matplotlib
vaderSentiment
You can install these dependencies using pip:

'''pip install pandas scikit-learn matplotlib vaderSentiment'''

How to Run
Make sure you have the "data_airline_reviews.xlsx" file containing airline review data in the same directory as your Python script.
Run the Python code.
Use the provided function predict_recommendation() to predict the recommendation status based on input features.


Conclusion
The vaderSentiment Analysis and Prediction project demonstrates the application of sentiment analysis in predicting the likelihood of flight recommendations. By leveraging customer reviews and sentiment analysis techniques, the project provides insights into the factors influencing customers' recommendations. This can be valuable for airlines in understanding customer sentiment and improving service quality.
