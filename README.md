# Loan-Default-Prediction-Model

## Project Overview

This project builds and evaluates machine learning models to predict whether a customer is likely 
to default on a loan. Accuarte loan default prediction helps financial institutions reduce risk, make informed 
lending decisions and minimise financial losses.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis
feature engneering, model training and model evaluation.

## Objectives:
-Clean and preprocess the loan dataset
-Explore the data to identify patters and relationships.
-Prepare the data for macjhine learning
-TRain multiple classification models.
-Compare model performance

# Dataset
The dataset contains information about loan applicants, including demographic, financial and loan-related attributes.

Examples of features include:
-Applicant income
-Loan Amount
-Loan Term
-Credit History
-Gender
-Education
-Property Area
-Loan Staus (Target Variable)

## Stack used 
- Python, Pandas, Matplotlib, Scikit-learn

## Project Workflow

1. Data Loading
    - Importeed the dataset into a pandas dataframe

2. Data Cleaning
    -Checked for missing values
    -Handled missing data using appropriate imputation techniques

3. Exploratory data analysis
    -Examined feature distributions
    - Analysed relationships between variables
    -Investigated correlations and data quality

4. Data Preprocessing 
    -Encoded categorical variables using One-Hot Encoding
    -Scaled numerical features where appropriate
    -Split the dataset into training, validation and testing sets

5. Model Training
The following machine learning model were trained and evaluated:
    -Logistic Regression
    -Decision Tree Classifier
    -Random Forest Classifier

6. Model Evaluation 
Models were evaluated using classification performance metrics such as:
    -Accuracy
    -Confusion Matrix
    -Classification Report

7. Results
The project demonstartes how different machine learning algorithms perform on a loan default prediction task. Model comparison highlights the strengths and weaknesses of each algorithm and provides insights into selecting an appropriate model for binary classification problems.

8. How to Run

-Clone the repository
-Navigate to the project folder
-Install the required libraries
-Launch Jupyter Notebook and run all cells
