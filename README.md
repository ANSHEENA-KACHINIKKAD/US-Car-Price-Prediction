# US Car Price Prediction

## Overview

This project aims to model car prices in the United States market based on a dataset of various car features. The analysis utilizes several regression algorithms to understand the relationship between different car attributes and their prices. This information will be valuable for a Chinese automobile company looking to enter the US market and strategically position their products.

## Business Goal

The primary objective is to develop a predictive model for car prices in the US market. This model will help management:

* Understand the key factors that significantly influence car prices.
* Quantify the impact of different car features on pricing.
* Inform decisions related to car design, marketing strategies, and pricing to effectively compete in the US market.
* Gain insights into the pricing dynamics of a new market.

## Dataset

The dataset used for this project can be accessed at: [https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view?usp=drive_link](https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view?usp=drive_link)

## Project Structure

The repository is organized as follows:

US-Car-Price-Prediction/
├── data/
│   └── CarPrice_Assignment.csv
├── notebooks/
│   └── car_price_prediction.ipynb
├── README.md
└── requirements.txt

 
* `data/`: Contains the raw dataset (`CarPrice_Assignment.csv`).
* `notebooks/`: Includes the Jupyter Notebook (`car_price_prediction.ipynb`) containing the data loading, preprocessing, model implementation, evaluation, feature importance analysis, and hyperparameter tuning.
* `README.md`: This file, providing an overview of the project.
* `requirements.txt`: Lists the Python libraries required to run the notebook.
* `data/`: Contains the raw dataset (`CarPrice_Assignment.csv`).
* `notebooks/`: Includes the Jupyter Notebook (`car_price_prediction.ipynb`) containing the data loading, preprocessing, model implementation, evaluation, feature importance analysis, and hyperparameter tuning.
* `README.md`: This file, providing an overview of the project.
* `requirements.txt`: Lists the Python libraries required to run the notebook.

## Implementation

The project implements the following regression algorithms:

1.  **Linear Regression**
2.  **Decision Tree Regressor**
3.  **Random Forest Regressor**
4.  **Gradient Boosting Regressor**
5.  **Support Vector Regressor**

The `car_price_prediction.ipynb` notebook covers the following steps:

1.  **Loading and Preprocessing:** Loading the dataset, handling missing values, encoding categorical features, and splitting the data into training and testing sets.
2.  **Model Implementation:** Training and evaluating each of the five regression models on the prepared data.
3.  **Model Evaluation:** Comparing the performance of the models using metrics such as R-squared, Mean Squared Error (MSE), and Mean Absolute Error (MAE) to identify the best performing model. 
      Justification for the best model will be provided based on these metrics.
4.  **Feature Importance Analysis:** Identifying the most significant variables that influence car prices based on the best performing model.
5.  **Hyperparameter Tuning:** Performing hyperparameter tuning on the best model (if applicable) using techniques like GridSearchCV or RandomizedSearchCV to potentially improve its performance. The 
      impact of tuning on the model's performance will be analyzed.

## Requirements

To run the code in this repository, you will need the following Python libraries:

 * pandas
 * numpy
 * scikit-learn
 * matplotlib
 * seaborn
