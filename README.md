# ybi_internship_prj
This project was completed under the guidance of YBI Foundation as part of their Data Analytics Internship.
# **Financial Market News - Sentiment Analysis**

## **Objective**
The primary goal of this project is to build a machine learning model to analyze the sentiment of top 25 daily financial market news articles. The task involves classifying the news articles into positive or negative sentiment categories.

## **Data Source**
The dataset used in this project is a dummy dataset of financial market news, obtained from the [YBI Foundation Dataset](https://github.com/YBI-Foundation/Dataset/raw/refs/heads/main/Financial%20Market%20News.csv). The dataset consists of 25 news articles with associated sentiment labels indicating whether the sentiment is positive or negative.

## **Libraries Used**
The following Python libraries are used throughout the project:
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **sklearn**: For machine learning model creation, data preprocessing, and evaluation metrics.
  
## **Import Dataset**
The dataset is imported using the pandas library

## **Data Description**
The dataset contains daily news headlines and sentiment labels for each news article. Columns include various metadata and financial information related to each news item.

## **Data Preprocessing**
We extract the relevant text features for sentiment analysis by joining the data columns that contain news information.
This step combines the various columns into a single feature representing the news content for each row.

## **Feature Engineering**
The text data is converted to a bag-of-words representation using the CountVectorizer from sklearn.

## **Define Target and Features**
Feature variable (X): The vectorized news content.
Target variable (y): The Label column, which represents the sentiment of the news (positive or negative).

## **Train-Test Split**
We split the data into training and testing sets using train_test_split from sklearn.

## **Modeling**
A Random Forest classifier is used for sentiment prediction.

## **Model Evaluation**
The model is evaluated using a confusion matrix, classification report, and accuracy score.

## **Prediction**
The trained model predicts the sentiment of the test set, and the results are compared to the true labels.

## **Explanation**
During this project, I gained practical experience in several key areas of data analysis and machine learning, including:

Data Preprocessing: Learned how to clean and combine text features for analysis.
Feature Engineering: Understood the importance of converting text data into a numerical format using Bag-of-Words for model input.
Train-Test Splitting: Gained insights into how to effectively split data to ensure unbiased model evaluation.
Machine Learning Modeling: Trained a Random Forest Classifier, learning how to tune hyperparameters such as the number of estimators to optimize performance.
Model Evaluation: Learned how to interpret confusion matrices and classification reports to assess model performance.
It was a beginner-level project, which helped me solidify fundamental concepts in machine learning.
