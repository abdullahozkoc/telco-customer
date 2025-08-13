# Telco Customer Churn Analysis

## 📌 Overview
This project analyzes the **Telco Customer Churn** dataset to explore customer behavior, identify patterns, and determine the key factors contributing to churn. Using Python’s data analysis and visualization libraries, the project covers data cleaning, exploratory data analysis (EDA), and insights extraction.

## 🛠 Technologies Used
- **Python** (Pandas, NumPy)
- **Data Visualization:** Matplotlib, Seaborn
- **Jupyter Notebook**

## 📂 Dataset
The dataset contains information about a telecommunications company's customers, including:
- **Customer demographics** (gender, senior citizen, partner, dependents)
- **Service details** (phone service, internet service, streaming)
- **Account information** (contract type, payment method, monthly charges, total charges)
- **Target Variable:** `Churn` (Yes/No)

**File Used:** `telco.csv`

## 📊 Project Steps
1. **Data Loading** – Importing the dataset into a Pandas DataFrame.
2. **Data Cleaning** – Handling missing values, fixing data types.
3. **Univariate Analysis** – Analyzing individual variables.
4. **Bivariate Analysis** – Exploring relationships between variables and churn.
5. **Visualization** – Creating charts and graphs to understand data patterns.

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone <repo_url>
   cd <repo_folder>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook main.ipynb
   ```
4. Run all cells to reproduce the analysis.

## 📈 Insights & Results
- Customers with month-to-month contracts show a higher churn rate.
- Senior citizens tend to churn more compared to younger customers.
- Higher monthly charges are correlated with higher churn probability.

## 📌 Future Improvements
- Apply machine learning models to predict churn.
- Automate data cleaning and feature engineering.
- Create an interactive dashboard for churn visualization.
