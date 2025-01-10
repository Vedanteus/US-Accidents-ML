# US Accidents Severity Prediction

This repository contains code for predicting the severity of accidents in the United States using the "US Accidents" dataset. The project utilizes machine learning techniques, such as data cleaning, exploratory data analysis (EDA), feature engineering, and model training, to predict accident severity based on various features.

## Project Overview

The project includes the following key steps:
1. **Data Cleaning and Processing**: Identifying and handling missing values, removing columns with high missing values, and filling in missing data.
2. **Exploratory Data Analysis (EDA)**: Visualizing accident severity distribution and identifying correlations between numerical features.
3. **Feature Engineering**: Creating new features such as accident duration, encoding categorical variables, and preparing the data for modeling.
4. **Modeling**: Using a Random Forest Classifier to train the model on the dataset and evaluate its performance using classification reports and a confusion matrix.
5. **Recommendations**: Based on the analysis, providing actionable recommendations to reduce accident severity.

## Dataset

- **Dataset Source**: US Accidents dataset (can be downloaded from https://drive.google.com/file/d/1edKrdWNOcgbAo2JtckX-PEyM0FdEq4EG/view).
- **Features**: The dataset contains various features like `Start_Time`, `End_Time`, `Severity`, `Weather_Condition`, `Temperature`, `Humidity`, etc.
- **Target Variable**: The target variable is `Severity`, which represents the severity of the accident.

## Installation

### Prerequisites

Make sure you have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these libraries using `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn