# **Soccer Match Prediction Pipeline**

This project implements a complete machine learning pipeline for predicting soccer match outcomes. It includes data cleaning, exploratory data analysis, feature engineering, model training, evaluation, and team-specific prediction functionalities.
Project Overview
The goal of this project is to analyze historical soccer match data and build a model that can predict match results. The notebook processes raw data, visualizes trends, and generates predictions for specific teams across different seasons.
Features

## **1. Data Loading and Preprocessing**


- Loads the raw match dataset using pandas.
- Cleans missing or inconsistent values.
- Validates logical consistency across columns.
- Saves a processed version of the dataset as Processed_Dataset.csv.


## **2. Exploratory Data Analysis (EDA)**


- Utilizes matplotlib to produce visual insights.
- Examines distributions of goals, wins, losses.
- Analyzes home versus away performance.
- Investigates seasonal trends.
- Provides clear visual summaries to improve understanding of the data.


## **3. Machine Learning Pipeline**


- Builds a prediction system using scikit-learn preprocessing tools.
- Trains classification models such as Logistic Regression and Random Forest.
- Includes feature engineering steps.
- Performs train–test splitting and model evaluation.
- Uses standard evaluation metrics to validate model performance.


## **4. Team-Specific Predictions**


- Groups data by team and analyzes performance across seasons.
- Generates prediction outputs for individual teams.
- Produces a structured dataframe (results_df) summarizing predicted outcomes.


## **5. Outputs**


- Sample predictions displayed directly in the notebook.
- Cleaned datasets saved for reuse.
- Modular code structure designed for easy future extensions.



### **Technologies Used**


- Python
- pandas
- matplotlib
- scikit-learn
- Jupyter Notebook

