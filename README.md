# Car Price Prediction Using Machine Learning

Car Price Prediction Using Machine Learning 🚗💸

This project aims to build a machine learning model that predicts the price of a car based on various features such as the car's brand, model, year of manufacture, transmission type, mileage, fuel type, tax, miles per gallon (MPG), and engine size.

📌 Technologies Used
Python 🐍

Jupyter Notebook 📒

Pandas & NumPy (for data manipulation)

Matplotlib & Seaborn (for data visualization)

Scikit-learn (for machine learning models and preprocessing)

📊 Dataset
The dataset used in this project contains information on used cars in the UK. Each row represents a car listing with features such as:

Model

Year

Transmission

Mileage

Fuel Type

Tax

MPG

Engine Size

Price (Target variable)

📈 Workflow
Data Loading & Cleaning: Loaded the dataset, checked for null values, and handled categorical features using label encoding.

Exploratory Data Analysis: Used visualizations to understand relationships between features and the target variable.

Feature Engineering: Encoded categorical features numerically and selected relevant features for modeling.

Model Training:

Used a Random Forest Regressor.

Split data into training and testing sets (80/20 split).

Evaluated performance using R² score.

Evaluation:

Model achieved R² score of around 96%, indicating high accuracy in predicting car prices.

✅ Outcome
A robust car price prediction model capable of estimating the value of a car with a high degree of accuracy
