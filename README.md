# ProblemLab2_CSCN8010
## Overview

This project is a practical lab for the course CSCN8010, focusing on data preprocessing, model building, and evaluation using regression techniques. It is divided into three main parts:

### Part 1: Data Preprocessing and EDA

- Loaded the dataset.
- Performed Exploratory Data Analysis (EDA).
- Visualized features and target variable.
- Checked for missing values and handled them.
- Split the dataset into training and testing sets.

### Part 2: Baseline Models

Built and evaluated the following regression models using selected features:
- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**

Evaluation metrics used:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

### Part 3: Advanced Models

Explored the effects of more complex models:
- **Polynomial Regression** (two degrees)
- **Decision Trees** (two variations with different `max_depth`)
- **Random Forest Regression**
- **K-Nearest Neighbors Regression**

For each model:
- Trained on the training set
- Evaluated on the test set using R², MAE, and MSE
- Compared performance to previous models

---

## Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt
