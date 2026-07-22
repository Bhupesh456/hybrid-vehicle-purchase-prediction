# Hybrid Vehicle Purchase Prediction using Linear Regression

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-LinearRegression-orange)
![Excel](https://img.shields.io/badge/Microsoft-Excel-green)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-red)

## My Learning Journey

I recently completed an introductory Machine Learning course where I learned the fundamentals of **Linear Regression**. Rather than stopping at the theory, I wanted to understand how the algorithm works behind the scenes.

I first implemented Linear Regression in **Microsoft Excel** using the Analysis ToolPak, where I explored concepts such as regression statistics, coefficients, intercept, ANOVA, and the regression equation **(Y = a + bX)**. By manually applying the regression equation, I gained a deeper understanding of how predictions are calculated.

After building this foundation, I implemented the same problem in Python using **Scikit-learn**. I trained a Linear Regression model on historical customer data and used it to predict the purchase likelihood of new customers.

This project helped me connect the mathematical concepts of Linear Regression with their practical implementation in Python, strengthening both my analytical thinking and machine learning skills.

## Project Overview

This project demonstrates how **Linear Regression** can be applied to predict the likelihood of customers purchasing a hybrid vehicle.

The primary goal of this project was **learning and understanding Linear Regression** by implementing the same concept using **Microsoft Excel** and **Python (Scikit-learn)**.

Instead of relying on only one tool, I explored how regression works mathematically in Excel and then implemented the same concept programmatically using Python.

This project helped me strengthen both my **Machine Learning fundamentals** and my **Data Analytics skills**.

---

# Business Problem

A vehicle company wants to identify customers who are more likely to purchase a hybrid vehicle.

Using customer demographic and financial information, we can build a predictive model that estimates each customer's purchase likelihood.

These predictions can help businesses:

- Improve marketing campaigns
- Identify potential customers
- Reduce unnecessary marketing costs
- Support data-driven decision making

---

# Project Objectives

- Learn the fundamentals of Linear Regression
- Understand regression coefficients and intercept
- Perform Linear Regression using Microsoft Excel
- Build the same model using Python and Scikit-learn
- Predict purchase likelihood for new customers
- Compare Excel and Python implementations

---

# Dataset

The project uses two datasets.

### Training Dataset

Used to train the Linear Regression model.

Features:

- Age
- Education
- Income (Lacs)
- Vehicle Ownership

Target Variable:

- Purchase Hybrid Vehicle

---

### New Customer Dataset

Contains customer information without purchase data.

The trained model predicts the purchase likelihood for each customer.

---

# Project Workflow

```text
Training Data
      │
      ▼
Data Preparation
      │
      ▼
Linear Regression
(Excel & Python)
      │
      ▼
Model Training
      │
      ▼
Prediction on New Customers
      │
      ▼
Business Insights
```

---

# Excel Implementation

To understand how Linear Regression works mathematically, regression analysis was performed using **Microsoft Excel Analysis ToolPak**.

During this implementation, I learned:

- Regression Statistics
- Multiple R
- R Square
- ANOVA Table
- Coefficients
- Intercept
- Regression Equation

Using the regression equation

**Y = a + bX**

I manually calculated customer purchase predictions and understood how each coefficient contributes to the final prediction.

---

# Python Implementation

The same problem was solved using **Scikit-learn**.

The workflow includes:

- Importing datasets
- Data preprocessing
- Feature selection
- Training Linear Regression model
- Predicting purchase likelihood
- Exporting prediction results

Libraries used:

- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# Project Structure

```text
Hybrid-Vehicle-Purchase-Prediction/

│
├── data/
│   ├── training_data.csv
│   └── new_customer_data.csv
│
├── excel/
│   └── Linear Regression.xlsx
│
├── notebooks/
│   └── hybrid_vehicle_purchase_prediction.ipynb
│
├── output/
│   └── Car_Prediction.xlsx
│
├── screenshot/
│   ├── regression_summary.png
│   ├── prediction_distribution.png
│   └── income_vs_prediction.png
└── README.md
```

---

# Results

The trained model was used to estimate the purchase likelihood of new customers.

The prediction results can assist businesses in:

- Identifying high-potential customers
- Planning targeted marketing campaigns
- Supporting business decision-making

---

## Visualizations

The following visualizations summarize the regression analysis and prediction results.

### Regression Summary (Excel)

The regression summary provides key statistics including **R², ANOVA, regression coefficients, and p-values** generated using Microsoft Excel Analysis ToolPak.

<p align="center">
  <img src="./screenshot/regression_summary.png" width="850">
</p>

---

### Distribution of Predicted Purchase Percentage

This histogram shows how the predicted purchase percentages are distributed across new customers.

<p align="center">
  <img src="./screenshot/prediction_distribution.png" width="850">
</p>

---

### Income vs Predicted Purchase

This scatter plot illustrates the relationship between customer income and the predicted purchase likelihood.

<p align="center">
  <img src="./screenshot/income_vs_prediction.png" width="850">
</p>


# Key Learning Outcomes

This project helped me understand:

- Machine Learning fundamentals
- Linear Regression
- Regression Equation
- Coefficients
- Intercept
- Excel Regression Analysis
- Scikit-learn Linear Regression
- Predictive Analytics
- Business-oriented thinking

More importantly, I learned that understanding the mathematical foundation of a model makes it much easier to implement the same concept using programming.

---

# Future Improvements

Some improvements that can be made in future versions include:

- Logistic Regression for binary classification
- Model evaluation metrics (MAE, MSE, RMSE, R²)
- Hyperparameter tuning
- Feature engineering
- Cross-validation
- Interactive dashboard using Power BI

---

# Skills Demonstrated

- Python
- Pandas
- NumPy
- Scikit-learn
- Microsoft Excel
- Linear Regression
- Predictive Analytics
- Machine Learning Fundamentals
- Data Analysis
- Data Visualization

---

# Author

**Bhupesh**

Aspiring Data Analyst passionate about solving business problems using data, analytics, and machine learning while continuously improving practical skills through real-world projects.
