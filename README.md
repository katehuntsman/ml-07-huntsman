# ml-07-huntsman

## Overview 
This project aims to predict individual medical insurance costs based on personal and demographic attributes using regression modeling. The dataset includes features such as age, BMI, number of children, region, gender, and smoking status.

We implemented and compared multiple regression pipelines including:

Standard Linear Regression

Polynomial Regression (degree 3)

## Dataset
Name: Medical Cost Dataset

Source: Provided in assignment / insurance.csv

Size: 1338 rows × 7 columns

Target Variable: charges (insurance cost)

## Features
Feature	        Type	        Description
age	        Numerical	    Age of primary beneficiary
sex	        Categorical	      Gender (male/female)
bmi	        Numerical	       Body Mass Index
children	Numerical	    Number of children/dependents
smoker	    Categorical	      Smoking status (yes/no)
region	    Categorical	    Residential area (northeast, southwest...)
charges	    Numerical	    Target: Medical insurance cost

## Project Structure
1. Data Inspection
2. Exploratory Data Analysis (EDA)
3. Feature Engineering & Selection
4. Regression Modeling (Linear and Polynomial)
5. Pipeline Implementation
6. Model Evaluation
7. Reflections and Final Insights

## Key Findings
Smoking and BMI are strong predictors of medical costs.

Polynomial Regression (degree 3) captured non-linear relationships better and improved model accuracy.

Proper preprocessing (encoding, scaling) significantly impacts model performance.

## Important Links
View the Notebook: [here](https://github.com/katehuntsman/ml-07-huntsman/blob/main/regression_huntsman.ipynb)

View My Peer Review: [here](https://github.com/katehuntsman/ml-07-huntsman/blob/main/peer_review.md)