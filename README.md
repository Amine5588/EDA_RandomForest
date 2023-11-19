# Tictactrip_assessment
## Overview

This repository contains code for analyzing ticket price data and predicting ticket prices based on various features available in provided CSV files. The analysis includes data preprocessing, exploration, visualization, predictive modeling, and model evaluation.

## Contents

- `data/`: Folder containing CSV files:
  - `ticket_data.csv`: Contains ticket history data.
  - `cities.csv`: Information about cities served by the ticket service.
  - `stations.csv`: Data about stations served by the ticket service.
  - `providers.csv`: Information about different ticket providers.

- `main.py`: Python script containing the complete code for data preprocessing, exploration, visualization, predictive modeling, and evaluation.

- `README.md`: This file.

## Usage

### Prerequisites

- Python 3.x
- Necessary Python libraries (Pandas, Matplotlib, Seaborn, Geopandas, Scikit-Learn)

### Instructions

1. Clone the repository:

   ```bash
   git clone <repository_url>



### Work 
* Data Processing Steps
Importing Libraries: Initial setup and importing necessary Python libraries for data analysis.
Understanding the Data: Describes the structure and relationships between provided CSV files—ticket history, cities, stations, and providers.
Column Renaming: Renames columns across different datasets for enhanced clarity.
Exploring Datasets: Provides an overview, statistical summary, and handling of missing values within cities, providers, stations, and ticket datasets.
Geographical Representation: Visualizes station locations on a geographical map using GeoPandas and Matplotlib.
Handling Missing Values: Utilizes SimpleImputer from Scikit-Learn to replace missing values in the datasets.
Data Analysis: Calculates ticket prices' statistics, durations, and functions to handle coordinates, transport types, and other details related to the provided ticket data.
Data Visualization and Analysis
Price Distribution: Visualizes the distribution of ticket prices through histograms.
Comparison of Trip Prices: Compares prices among different distance categories and transport types using boxplots.
Transport Type Analysis: Analyzes the distribution of transport types, average prices, and durations per transport type.
* Prediction Modeling
Data Preparation for Prediction: Prepares the training set by encoding categorical variables and selecting relevant columns for the predictive model.
Predictive Modeling: Utilizes Support Vector Regression (SVR) and Random Forest Regression models to predict ticket prices.
Model Evaluation: Scales and splits the data into training and test sets, evaluates model performance using R-squared scores, and visualizes actual vs. predicted prices.
Conclusion
The analysis covers data exploration, visualization, feature engineering, and machine learning modeling to predict ticket prices based on various features and parameters within the provided datasets. The process ensures a thorough understanding, preprocessing, analysis, and predictive modeling of the ticket data.
