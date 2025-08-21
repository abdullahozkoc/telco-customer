# Telco Customer Churn Analysis

## 📌 Overview

This project analyzes the **Telco Customer Churn** dataset to explore
customer behavior, identify patterns, and determine the key factors
contributing to churn. The project includes **data cleaning, exploratory
data analysis (EDA), outlier detection, feature engineering, and
predictive modeling**.

## 🛠 Technologies Used

-   **Python** (Pandas, NumPy, Scikit-learn, XGBoost, imbalanced-learn)
-   **Data Visualization:** Matplotlib, Seaborn
-   **Jupyter Notebook**

## 📂 Dataset

The dataset contains information about a telecommunications company's
customers, including: - **Customer demographics** (gender, senior
citizen, partner, dependents) - **Service details** (phone service,
internet service, streaming) - **Account information** (contract type,
payment method, monthly charges, total charges) - **Target Variable:**
`Churn` (Yes/No)

**File Used:** `telco.csv`

## 📊 Project Steps

1.  **Data Loading** -- Importing the dataset into a Pandas DataFrame.
2.  **Data Cleaning** -- Handling missing values, fixing data types.
3.  **Univariate Analysis** -- Analyzing individual variables with
    histograms and boxplots.
4.  **Multivariate Analysis** -- Exploring relationships between
    variables and churn.
5.  **Outlier Analysis** -- Detecting anomalies in numerical features.
6.  **Data Preparation** -- Encoding categorical variables, feature
    transformation.
7.  **Modeling with Logistic Regression**
8.  **Modeling with Random Forest**
9.  **Modeling with XGBoost**
10. **Handling Class Imbalance with SMOTE**
11. **Remodeling and Performance Comparison** -- Logistic Regression &
    Random Forest after SMOTE.
12. **Hyperparameter Tuning** -- GridSearchCV on Random Forest.
13. **Feature Importance Analysis** -- Identifying the most influential
    features.

## ▶️ How to Run

1.  Clone the repository:

    ``` bash
    git clone <repo_url>
    cd <repo_folder>
    ```

2.  Install dependencies:

    ``` bash
    pip install -r requirements.txt
    ```

3.  Open the notebook:

    ``` bash
    jupyter notebook main.ipynb
    ```

4.  Run all cells to reproduce the analysis.

## 📈 Insights & Results

-   Customers with month-to-month contracts show a higher churn rate.
-   Senior citizens tend to churn more compared to younger customers.
-   Higher monthly charges are correlated with higher churn probability.
-   Predictive models (Logistic Regression, Random Forest, XGBoost) were
    applied.
-   SMOTE balancing improved minority class prediction.
-   Hyperparameter tuning improved Random Forest performance.
-   Feature importance analysis highlighted **Contract type, Tenure, and
    Total Charges** as key churn drivers.

## 📌 Future Improvements

-   Experiment with deep learning models (e.g., ANN).
-   Apply cross-validation with additional metrics (AUC, F1-score).
-   Create an interactive dashboard for churn visualization.
