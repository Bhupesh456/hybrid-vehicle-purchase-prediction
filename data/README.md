# Data Folder

This folder contains the datasets used for the **Hybrid Vehicle Purchase Prediction** project.

## Files

### 1. training_data.csv

This dataset is used to train the Linear Regression model.

**Description:**
- Contains historical customer information.
- Includes the target variable indicating whether a customer purchased a hybrid vehicle.
- Used for model training and learning the relationship between customer characteristics and purchase behavior.

**Features:**
- Age
- Education
- Income (Lacs)
- Vehicle Ownership

**Target Variable:**
- Purchase Hybrid Vehicle (0 = No, 1 = Yes)

---

### 2. new_customer_data.csv

This dataset contains new customer records without purchase information.

**Purpose:**
- Used to generate purchase predictions using the trained Linear Regression model.
- Helps identify customers who are more likely to purchase a hybrid vehicle.

**Features:**
- Age
- Education
- Income (Lacs)
- Vehicle Ownership

**Output:**
The predicted purchase percentage for each customer is generated and exported as:

```
Car_Prediction.xlsx
```

---

## Dataset Workflow

```
training_data.csv
        │
        ▼
Train Linear Regression Model
        │
        ▼
new_customer_data.csv
        │
        ▼
Predict Purchase Likelihood
        │
        ▼
Car_Prediction.csv
```

---

## Note

The datasets included in this repository are intended for educational and portfolio purposes only.
