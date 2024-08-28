# Streamlit-Customer-Churn-Predictor

Welcome to the Customer Churn Prediction Web App project! This repository demonstrates how to build and deploy a machine learning model using Streamlit to predict customer churn. Retaining existing customers is crucial for businesses, and churn prediction plays a vital role in retention management. This project showcases the development of a churn model and its deployment as a user-friendly web application.

## Introduction

It's much easier to keep an existing customer than to acquire a new one. That's why churn prediction and retention management is a strategically important data science use case. In this project, I aim to demonstrate how to create a churn prediction model and deploy it as an interactive web app using Streamlit.

## Project Overview

The project follows a typical machine learning workflow with a focus on customer churn prediction:

- **Importing Data**: Loading customer data for churn analysis.
- **Split Data into Training and Testing**: Dividing the data to train and evaluate the model.
- **Exploring Why Customers Might be Leaving**: Conducting exploratory analysis to identify potential churn indicators.
- **Data Preprocessing**: Preparing the data for modeling, including handling missing values and scaling features.
- **Feature Engineering for Churn**: Creating new features that may improve the model's ability to predict churn.
- **Building Classification Models**: Developing models to classify customers as likely to churn or not.
- **Evaluation for Classification and Prediction**: Assessing the model's performance using appropriate classification metrics.
- **Deployment**: Deploying the model using Streamlit to create an interactive web application.
- **Test Scoring**: Testing the model's performance on unseen data to ensure accuracy.
- **Creating a Customer Churn Streamlit App**: Building a user-friendly web app that allows users to input customer data and receive churn predictions.

## Prerequisites

Ensure you have the following installed:

- Python 3.x
- Streamlit
- pandas
- scikit-learn
- numpy

## Project Workflow

1. **Importing Data**  
   The first step involves importing customer data that will be used to predict churn. This data serves as the foundation for the project.

2. **Split Data into Training and Testing**  
   The dataset is split into training and testing sets to evaluate the model's performance on unseen data.

3. **Exploring Why Customers Might be Leaving**  
   Exploratory analysis is performed to uncover potential reasons for customer churn, which helps in feature selection and model building.

4. **Data Preprocessing**  
   Data preprocessing includes handling missing values, encoding categorical variables, and scaling features to prepare the data for modeling.

5. **Feature Engineering for Churn**  
   New features are engineered based on the exploratory analysis to enhance the model's predictive power.

6. **Building Classification Models**  
   Various classification models are built and trained to predict whether a customer is likely to churn.

7. **Evaluation for Classification and Prediction**  
   The models are evaluated using metrics such as accuracy, precision, recall, and F1-score to determine their effectiveness.

8. **Deployment**  
   The trained model is deployed using Streamlit, allowing users to interact with it through a web-based interface.

9. **Test Scoring**  
   The model is tested on a separate dataset to verify its accuracy and reliability.

10. **Creating a Customer Churn Streamlit App**  
    Finally, a Streamlit-based web app is created, enabling users to input customer data and obtain churn predictions in real-time.

## Future Work

Future work could include enhancing the model, expanding data sources, or improving the app’s interface.
