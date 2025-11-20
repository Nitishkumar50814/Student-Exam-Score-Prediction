# Student-Exam-Score-Prediction
Machine Learning Model for Exam Score Prediction 
# Employee Salary Prediction using Linear Regression
A simple and beginner-friendly machine learning project that uses **Linear Regression** to predict employee monthly income based on various HR-related features.

---

##  Project Objective
The goal of this project is to build a machine learning model that predicts an employee’s **MonthlyIncome** using features such as:

- Age  
- Job Level  
- Total Working Years  
- Years At Company  
- Percent Salary Hike  
- Training Times Last Year  
- Years With Current Manager  
- Years In Current Role  
- And more...

---

##  Dataset Information
The dataset contains **employee details** with continuous & categorical features.  
Target column → **MonthlyIncome**

Dataset used: `employee.csv`

---


## Data Preprocessing

Checked for missing values

Applied one-hot encoding for categorical variables

Separated features (X) and target (y)


##  Model Performance

Accuracy : 88.2

Mean Squared Error (MSE):	28.28

RMSE Score: 5.3


##  Technologies Used

Python

Pandas

NumPy

Scikit-Learn

Seaborn / Matplotlib

Jupyter Notebook



##  Machine Learning Workflow

###  Import Libraries
```python
import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error, r2_score
