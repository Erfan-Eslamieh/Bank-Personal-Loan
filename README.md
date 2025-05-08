# Bank Loan Prediction: Understanding Customer Loan Behavior 🏦📊

The banking industry relies heavily on **data-driven decision-making** when offering personal loans to customers. The **"Bank Personal Loan Dataset"** provides valuable insights into customer behavior, financial status, and loan acceptance trends.

By analyzing factors such as **income, experience, education level**, and **financial habits**, we can better understand what influences a customer's **likelihood of accepting a personal loan offer**.

---

## 🎯 Objective of the Study

This study aims to analyze customer behavior and build predictive models to determine whether a customer is likely to accept a **personal loan offer**. We use **data visualization, feature engineering**, and **machine learning techniques** to explore and model the data.

---

## ✅ Key Steps in the Study:

### 1. Data Cleaning and Preprocessing
- Handling missing values and ensuring consistency.
- Converting **categorical features** (e.g., education level, online usage) into numerical values for modeling.

### 2. Exploratory Data Analysis (EDA) 🔍
- Visualizing distributions of **income, experience, family size**, and **loan acceptance**.
- Identifying relationships between **education level** and **loan decisions**.

### 3. Pattern Identification & Financial Trends 📈
- Investigating how **income** impacts **loan acceptance**.
- Analyzing the effect of **credit card usage, mortgage status**, and **internet banking** on financial behavior.

### 4. Machine Learning Models & Prediction 🤖
- Applying classification algorithms:
  - **Logistic Regression**
  - **K-Nearest Neighbors (KNN)**
  - **Gaussian Naive Bayes**
- Training models to **predict loan acceptance**.
- Evaluating model performance using accuracy, precision, recall, and F1-score.

---

## 📊 Column Descriptions:

| Column | Description |
|--------|-------------|
| `ID` | Unique identifier for each customer |
| `Age` | Customer's age |
| `Experience` | Years of professional experience |
| `Income` | Annual income in $000s |
| `ZIP Code` | Residential ZIP Code |
| `Family` | Number of family members |
| `CCAvg` | Avg. credit card spending per month ($000s) |
| `Education` | Education level (1: Undergrad, 2: Graduate, 3: Advanced) |
| `Mortgage` | Mortgage value ($000s) |
| `Personal Loan` | Loan accepted (1 = Yes, 0 = No) |
| `Securities Account` | Has securities account? (1 = Yes, 0 = No) |
| `CD Account` | Has CD account? (1 = Yes, 0 = No) |
| `Online` | Uses online banking? (1 = Yes, 0 = No) |
| `CreditCard` | Has bank-issued credit card? (1 = Yes, 0 = No) |

---

## 📥 Input Data for Prediction

We have a specific customer's data. Will they accept the loan?

```text
ID: 5071
Age: 42
Experience: 16
Income: 30
ZIP Code: 992037
Family: 3
CCAvg: 0.5
Education: Advanced (→ 3)
Mortgage: 0
Securities Account: 1
CD Account: 0
Online: 1
Credit Card: 1
```
---

## 💡 Insights & Applications

- Customers with **higher income** and **advanced education levels** are more likely to accept personal loans.
- Possession of a **CD account** or **securities account** shows a strong correlation with loan acceptance.
- **Online banking usage** and **credit card ownership** are key behavioral indicators in predicting financial decisions.
- Education level has a substantial influence on the likelihood of accepting loan offers, especially among professionals.

---

## 🏷️ Tags

`#BankLoanPrediction` `#PersonalLoan` `#CustomerBehavior` `#ClassificationModels` `#EDA` `#MachineLearning` `#Python`

---

## 🤝 Contribute

Feel free to **fork this repository**, open **issues**, or contribute by improving model performance, adding new algorithms, or enriching the dataset with real-world financial behavior patterns.

---

