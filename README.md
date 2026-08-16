# Linear and Logistic Regression Models

## Objective
Build and evaluate **linear regression** (continuous value prediction) and **logistic regression** (classification) models using scikit-learn, including best practices for array copying with NumPy.

## Content

### 1. Linear Regression — Housing Prices
- Dataset: [House Data](https://www.kaggle.com/datasets/shree1992/housedata)
- Data cleaning, linear regression model training using `sklearn`
- Residual visualization (difference between actual and predicted values) by city using box plots

### 2. Logistic Regression — Lung Cancer
- Dataset: [Lung Cancer](https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer)
- Train/test split, classifier training, score evaluation
- Model coefficient interpretation by feature

### 3. Linear Regression — Anti-Smog Educational Network (ESA)
- Proposed analysis on air quality data from the ESA network (dane.gov.pl)

### 4. NumPy Deep Copy
- Practical demonstration of the difference between shallow copy and deep copy (`np.copy`) in NumPy arrays — a fundamental concept to prevent silent bugs when manipulating data

## Technologies
`Python` `scikit-learn` `pandas` `NumPy` `seaborn` `matplotlib`

## How to Run
```bash
pip install scikit-learn pandas numpy seaborn matplotlib kaggle
jupyter notebook "regresja liniowa wprowadzenie i sklearn.ipynb"
jupyter notebook "regresja logistyczna.ipynb"