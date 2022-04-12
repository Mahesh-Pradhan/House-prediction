# House Price Prediction Project

## Introduction
Creating a Machine Learning model to predict the home prices in Delhi, India. We are going to use the dataset from Kaggle.com.
Main objective of the project is to perform data visulalization techniques to understand the insight of the data. Machine learning often required to getting the understanding of the data and its insights. This project aims apply various Python tools to get a visual understanding of the data and clean it to make it ready to apply machine learning opertation on it.We are also going to create a single page website which will provide the front end to access our model for predictions.

Below Machine Learning concepts are used in this project
* Data loading and cleaning
* Outlier detection and removal
* Feature engineering
* Dimensionality reduction
* Gridsearchcv for hyperparameter tunning
* K fold cross validation

Technology and tools used in this project
* Python
* Numpy and Pandas for data cleaning
* Matplotlib for data visualization
* Sklearn for model building
* Google Colaboratory Notebook
* Python flask for http server
* HTML/CSS/Javascript for UI

## Steps
1. We will first build a model using sklearn and linear regression using banglore home prices dataset from kaggle.com.
2. Second step would be to write a python flask server that uses the saved model to serve http requests.
3. Third component is the website built in html, css and javascript that allows user to enter home square ft area, bedrooms etc and it will call python flask server to retrieve the predicted price. 

  ```
  Step#1: Import the required libraries
  Step#2: Load the data
  Step#3: Understand the data
          -drop unnecessary columns
  Step#4: Data Cleaning
          - Check for na values
          - Verify unique values of each column
          - Make sure values are correct (eg. 23 BHK home with 2000 Sqrft size is worng)
          - Feature Engineering
          - Dimesionality Reduction
          - Outlier removal using domain knowledge (2bhk price < 3bhk price, size per bhk >= 300 sqft)
          - Outlier removal using standard eviation and mean
          - One Hot encoding
  Step#5: Build Machine Learning Model
  Step#6: Testing The model
  Step#7: Export the model
  Step#8: Export any other important info
  ```

## Dataset Reference
* [Delhi House price data](https://www.kaggle.com/Delhi-house-price-data)
* I have also uploaed the csv file in this repository [Delhi_House_Data.csv](Delhi_House_Data.csv)
