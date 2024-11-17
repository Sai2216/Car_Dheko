# Car_Dheko
Car Dheko - Used Car Price Prediction
Car Price Prediction Using Machine Learning
Overview
This repository demonstrates a complete machine learning workflow for predicting used car prices based on various features, such as make, model, year, fuel type, and transmission type. Leveraging historical data from CarDekho, this project creates a reliable and user-friendly tool that enhances customer experience and streamlines the pricing process for sales teams. The final deliverable is a deployed Streamlit application that allows users to input car details and receive instant price predictions.

Project Structure

1.VS Code

File: car_dekho.ipynb
Description:
Contains the complete workflow, including:
Exploratory Data Analysis (EDA) to identify key features influencing car prices.
Data Cleaning to handle missing values, encode categorical variables, and scale numerical data.
Model Development, where multiple algorithms (Linear Regression, Decision Trees, Random Forest, Gradient Boosting) were trained, evaluated, and optimized through hyperparameter tuning.

2.Streamlit Application

File: car_dekho_app.py
Description:
An interactive, web-based tool that lets users input car specifications and obtain price predictions. Designed with an intuitive interface, it’s accessible to both technical and non-technical users.

3.Project Report

File: Car_Dekho-Used_Car_Price_Prediction_pdf.pdf
Description:
A detailed document covering the project's lifecycle, including:
Problem definition.
Methodology and justifications.
Model evaluation and deployment.
Results and insights derived from the analysis.

4.User Guide

File: user_guide.pdf
Description:
A comprehensive guide that explains how to use the Streamlit application, covering navigation, input fields, and interpreting the predictions.

5.Resources

File: Structured data.zip
Contents:
Cleaned dataset used for training.
Serialized model files (.pkl files) saved with joblib.
Any additional resources supporting the project.

Getting Started
Prerequisites

Ensure the following are installed before running the notebook or application:

Python 3.7+
Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, streamlit

Using the Streamlit Application

Input Fields: Enter car details such as make, model, year, fuel type, transmission type, mileage, and more.
Price Prediction: Click the Predict button to generate the estimated price.
User-Friendly Interface: Designed for ease of use, even for non-technical users.

Model Training and Evaluation
Data Cleaning:
Handled missing data, encoded categorical variables, and scaled numerical features.
Model Selection:
Trained and evaluated multiple models, including Linear Regression, Decision Trees, Random Forest, and Gradient Boosting.
Performed hyperparameter tuning for optimal results.
Evaluation Metrics:
Models assessed using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² scores.
The best-performing model was selected for deployment.

Results
Best Model: Selected based on the highest R² and lowest MSE/MAE values.
Accuracy: Demonstrated strong predictive accuracy, making the model reliable for real-world car price estimation.

Repository Structure
car_dekho_cleaning_and_modeling.ipynb: Notebook for data processing and model development.
car_dekho_app.py: Script for the Streamlit application.
project_report.pdf: Comprehensive project report.
user_guide.pdf: Step-by-step user guide for the Streamlit application.
Car_Price_Prediction.zip: Includes the cleaned dataset, serialized models, and other resources.

Acknowledgements
This project was developed using:

Data: Provided by CarDekho.
Tools and Libraries:
Scikit-learn for machine learning.
Streamlit for application deployment.

License
This project is licensed under the MIT License.

References
CarDekho Dataset
Scikit-learn Documentation
Streamlit Documentation
