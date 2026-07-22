# Jupyter Notebook

This folder contains the Python implementation of the **Hybrid Vehicle Purchase Prediction** project using **Linear Regression**.

The notebook demonstrates the complete machine learning workflow—from loading the dataset and training a Linear Regression model to generating predictions for new customers and visualizing the results.

---

# Notebook

### hybrid_vehicle_purchase_prediction.ipynb

This notebook implements a Linear Regression model using **Scikit-learn** to estimate the likelihood of customers purchasing a hybrid vehicle based on demographic and financial information.

---

# Objectives

The objectives of this notebook are to:

- Load and prepare customer data
- Train a Linear Regression model
- Predict purchase likelihood for new customers
- Visualize prediction results
- Understand how machine learning can support business decision-making

---

# Notebook Workflow

```text
Import Libraries
        │
        ▼
Load Training Dataset
        │
        ▼
Feature Selection
        │
        ▼
Train Linear Regression Model
        │
        ▼
Load New Customer Dataset
        │
        ▼
Predict Purchase Likelihood
        │
        ▼
Export Prediction Results
        │
        ▼
Visualize Results
        │
        ▼
Business Conclusion
```

---

# Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Features Used

The model is trained using the following customer attributes:

- Age
- Education
- Income (Lacs)
- Vehicle Ownership

### Target Variable

- Purchase Hybrid Vehicle

---

# Machine Learning Model

The notebook uses **Linear Regression** from Scikit-learn.

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X, y)
```

The trained model learns the relationship between customer characteristics and the likelihood of purchasing a hybrid vehicle.

---

# Prediction

After training, the model predicts purchase likelihood for new customers.

The prediction results are exported as:

```
Car_Prediction.csv
```

---

# Visualizations

The notebook includes visualizations to help interpret the prediction results.

Current visualizations include:

- Feature Importance (Regression Coefficients)
- Income vs Predicted Purchase

These visualizations help explain how customer attributes influence the predicted purchase likelihood.

*(Additional visualizations can be added as the project evolves.)*

---

# Key Learning Outcomes

Through this notebook, I learned how to:

- Build a Machine Learning workflow using Python
- Train a Linear Regression model using Scikit-learn
- Generate predictions for unseen customer data
- Interpret regression coefficients
- Visualize prediction results
- Apply machine learning concepts to a business problem

---

# Skills Demonstrated

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Linear Regression
- Predictive Analytics
- Data Visualization
- Machine Learning Fundamentals

---

# Conclusion

This notebook demonstrates how Linear Regression can be used to estimate customer purchase likelihood based on historical customer data.

By combining data preparation, model training, prediction, and visualization, the project illustrates a complete introductory machine learning workflow. It also complements the Excel implementation by showing how the same regression concepts can be automated and applied programmatically using Python.
