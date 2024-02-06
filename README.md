Problem Statement: 
The problem statement revolves around the need to classify customer reviews as positive or negative based on the text content. We explore various NLP techniques, including data pre-processing, feature extraction, and machine learning algorithms, to build and evaluate models for sentiment classification. The primary goal is to provide restaurant owners and managers with valuable insights from customer feedback, allowing them to enhance customer satisfaction and improve their services.It focuses on the application of Natural Language Processing (NLP) techniques for sentiment analysis in restaurant reviews

Abstract: 
Customer reviews play a pivotal role in the restaurant industry, shaping customer perceptions and influencing business success. However, manually analyzing a large volume of text reviews is a daunting task. This necessitates the development of a robust sentiment analysis system tailored for restaurant reviews. The problem at hand is to design and deploy an accurate sentiment analysis solution for restaurant reviews.
 This system should be capable of classifying customer reviews into two categories: "Positive" and "Negative." It must provide valuable insights to restaurant owners and managers, enabling them to enhance customer satisfaction, improve service quality, and ultimately drive business success.

Methodology
Data Collection and Preprocessing:
The dataset used in this study comprises restaurant reviews, with labels indicating whether the review is positive or negative.
Data cleaning is performed to remove special characters, convert text to lowercase, and tokenize the reviews.
Exploratory Data Analysis andText Preprocessing:
Descriptive statistics and data visualizations are used to gain insights into the distribution of positive and negative reviews in the dataset.
Text data is pre-processed using techniques such as removing stopwords and stemming words to improve the quality of text data.
Feature Extraction:
CountVectorizer from scikit-learn is used to convert text data into numerical features for machine learning models.
Machine Learning Models:
Two machine learning algorithms, Support Vector Classifier (SVC) and Naive Bayes, are used for sentiment classification.
The Naive Bayes algorithm is trained on the training set and used to predict sentiment on the test set.
A Support Vector Classifier is also trained on the training set and evaluated on the test set.
NLP Pipeline:
A scikit-learn pipeline is constructed, incorporating CountVectorizer and SVC, to streamline the preprocessing and classification processes.
Model Deployment:
The final model is saved using joblib, making it available for use in the Streamlit web application
Project Description
Solution: automating sentiment analysis in restaurant reviews using Natural Language Processing (NLP) techniques, featuring data preprocessing, machine learning models, and a user-friendly Streamlit web application for real-time predictions, benefiting restaurant owners.
Key Features: NLP, Feature extraction using CountVectorizer.
Target Users:Restaurant owners and managers, Data analysts and researchers in the restaurant industry.
Benefits: Insights into customer satisfaction and feedback trends, improved decision-making for restaurant improvements and service enhancements and streamlined text classification process for large volumes of reviews
