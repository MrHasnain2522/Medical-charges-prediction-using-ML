## Project Title:
Medical Charges Prediction using Machine Learning

# Description:
 
This project uses supervised machine learning techniques to predict individual medical charges based on personal,
and demographic information such as age, sex, BMI, smoking status, and region. It aims to help healthcare providers
and insurance companies estimate future costs and optimize pricing models.

# Problem Statement:

Insurance companies often need to predict medical costs for new customers. This project explores how well we can predict,
these costs using features like age, BMI, and lifestyle choices using regression algorithm

# Machine Learning Algorithms Used:

Linear Regression
Lasso Regression
Ridge Regression

# Features Used:
 
age: Age of the individual
sex: Gender (male/female)
bmi: Body Mass Index
children: Number of dependents
smoker: Smoker (yes/no)
region: Residential region
charges: (Target) Medical cost


# Evaluation Metrics
 Mean Absolute Error (MAE)
 Mean Squared Error (MSE)
 R² Scor

# Libraries Used
Python
pandas, NumPy
scikit-learn
matplotlib, seaborn

# Future Improvements
Add model deployment using Flask or Streamlit
Improve feature engineering (e.g., BMI buckets)
Test on more diverse dataset



