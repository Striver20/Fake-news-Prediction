1. Introduction
With the proliferation of online news sources, the dissemination of fake news has become a significant problem. This project aims to build a machine learning model that can effectively classify news articles as fake or real, providing a tool to help combat misinformation.

2. Dataset
The dataset used in this project is the Fake News Detection dataset from Kaggle.

 3. Data Preprocessing
We load the dataset and handle any missing values. The content for each news article is prepared by combining the 'author' and 'title' columns. We also define the dependent and independent variables.

4. Text Stemming and Cleaning
We preprocess the text data by removing non-alphabet characters, converting to lowercase, and removing stop words. Stemming is applied to reduce words to their root form.

5. Transforming Data with TF-IDF Vectorizer
The text data is transformed into numerical data using TF-IDF Vectorizer to convert the collection of raw documents to a matrix of TF-IDF features.

6. Train-Test Split
We split the dataset into training and testing sets to evaluate the model's performance on unseen data.

7. Model Training
We initialize and train a Logistic Regression model using the training data.

8. Model Evaluation
The trained model is evaluated on both the training and testing data to determine its accuracy.

9. Making a Predictive System
A function is created to make predictions on new data. This function preprocesses the input, transforms it using the TF-IDF Vectorizer, and then predicts whether the news is real or fake.
        
