# Car Price Prediction Model

## Overview
This repository contains a machine learning regression project designed to predict the selling price of used vehicles based on various historical and technical features. 

## Dataset
The data utilized in this project is the **Vehicle dataset from CarDekho**, sourced from [Kaggle](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho). 

The dataset includes the following key features:
* **Vehicle Details:** Car Name, Year of Purchase
* **Pricing Metrics:** Selling Price (Target Variable), Present Price
* **Condition & Usage:** Kilometers Driven, Owner History
* **Categorical Specifications:** Fuel Type (Petrol/Diesel/CNG), Seller Type (Dealer/Individual), Transmission (Manual/Automatic)

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn 
* **Environment:** Google Colab

## Key Implementation Steps
* **Data Preprocessing:** Cleaning and structuring raw CSV data for modeling.
* **Categorical Encoding:** Converting text-based categories (e.g., Fuel Type, Transmission) into numerical values (0, 1, 2) to ensure compatibility with machine learning algorithms.
* **Feature Selection:** Dropping non-predictive columns (like `Car_Name`) to isolate the most impactful variables for the regression model.
* **Data Splitting:** Separating the target variable (`Selling_Price`) from the feature set (`X`) to prepare for the training and testing phases.

## How to Run
To view or execute the code directly in your browser:
1. Click the **"Open in Colab"** badge at the top of the `.ipynb` file in this repository.
2. Ensure the `car data.csv` file is uploaded to your Colab session.
3. Run the cells sequentially to observe the data processing and model predictions.
