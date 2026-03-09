# Customer Churn & Revenue Intelligence Platform

An end-to-end analytics and machine learning platform designed to **identify customers at risk of churn and estimate potential revenue loss**.
The project combines **data analysis, predictive modeling, and interactive business dashboards** to help organizations proactively retain customers and protect revenue.

Built using **Python, SQL, and Power BI**, the system transforms raw telecom customer data into **actionable business intelligence and churn risk predictions**.

---

# Project Overview

Customer churn is one of the most critical challenges for subscription-based businesses. Losing customers directly impacts **revenue stability and growth**.

This project addresses the problem by:

* Analyzing customer behavior patterns
* Predicting churn probability using machine learning
* Quantifying revenue at risk from churn
* Delivering insights through a business intelligence dashboard

The system enables **data-driven retention strategies** by helping businesses answer questions such as:

* Which customers are most likely to churn?
* What factors influence churn the most?
* How much revenue is at risk?
* Which customer segments need retention campaigns?

---
<<<<<<< HEAD

# Key Features

### 1. Churn Prediction Model

A machine learning model predicts the probability that a customer will churn.

* Feature engineering on customer demographics, service usage, and billing data
* Data preprocessing and encoding
* Model training using **Scikit-learn**
* Performance evaluation using classification metrics

---

### 2. Revenue Risk Analysis

The platform estimates **potential revenue loss caused by churn**.

Metrics calculated:

* Monthly revenue at risk
* High-value customers likely to churn
* Customer lifetime value indicators

---

### 3. Interactive Power BI Dashboard

An interactive dashboard was built to allow business users to explore churn insights visually.

Key dashboard views include:

* Customer churn distribution
* Revenue loss analysis
* Customer segmentation
* Churn probability by contract type
* Churn trends across demographics

Dashboard Preview
 <img src="/Users/gauravverma/Downloads/customer-churn-revenue-intelligence/dashboard/e4f8cdb7-1.png">

---

# Tech Stack

| Category           | Tools        |
| ------------------ | ------------ |
| Programming        | Python       |
| Data Processing    | Pandas       |
| Machine Learning   | Scikit-learn |
| Database Querying  | SQL          |
| Data Visualization | Power BI     |

---

# Dataset

**IBM Telco Customer Churn Dataset**

* ~7,000 telecom customers
* Customer demographics
* Service subscriptions
* Billing information
* Churn status

Dataset fields include:

* Customer tenure
* Contract type
* Internet service
* Payment method
* Monthly charges
* Total charges
* Churn label

---

# Project Architecture

```
Data Source
   ↓
Data Cleaning & Transformation (Python, Pandas)
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Machine Learning Model (Scikit-learn)
   ↓
SQL Data Aggregation
   ↓
Power BI Dashboard
   ↓
Business Insights & Revenue Risk Analysis
```

---

# Machine Learning Workflow

1. Data preprocessing
2. Handling missing values
3. Encoding categorical variables
4. Feature scaling
5. Train/test split
6. Model training
7. Performance evaluation

Models explored include:

* Logistic Regression
* Random Forest (optional extension)

Evaluation metrics:

* Accuracy
* Precision
* Recall
* F1 Score

---

# Business Insights Generated

The analysis helps answer key business questions:

* Customers with **month-to-month contracts churn the most**
* **High monthly charges increase churn probability**
* Customers with **longer tenure are less likely to churn**
* Certain payment methods correlate with higher churn

These insights enable companies to:

* Target high-risk customers
* Offer retention discounts
* Improve long-term contract adoption
* Reduce revenue leakage

---

# Repository Structure

```
customer-churn-revenue-intelligence
│
├── data
│   └── telco_customer_churn.csv
│
├── notebooks
│   └── churn_analysis.ipynb
│
├── models
│   └── churn_model.pkl
│
├── dashboard
│   └── churn_dashboard.pbix
│
├── sql
│   └── revenue_analysis.sql
│
└── README.md
```

---

# Example Dashboard Metrics

Key KPIs included in the Power BI dashboard:

* Total Customers
* Churn Rate
* Monthly Revenue
* Revenue at Risk
* High-Risk Customer Segments

---

# How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/yourusername/customer-churn-revenue-intelligence.git
```

### 2. Install dependencies

```
pip install pandas scikit-learn numpy matplotlib seaborn
```

### 3. Run analysis notebook

Open:

```
notebooks/churn_analysis.ipynb
```

### 4. Open Power BI dashboard

Open the `.pbix` file in **Power BI Desktop**.

---

# Future Improvements

* Deploy churn prediction model as an API
* Build a real-time churn monitoring dashboard
* Add customer lifetime value prediction
* Automate data pipelines

---

# Project Highlights

* End-to-end data analytics pipeline
* Real-world telecom churn dataset
* Machine learning based churn prediction
* Business-ready Power BI dashboard
* Revenue risk estimation

---

# Author

Gaurav Verma
B.Tech Computer Science
Machine Learning & Data Analytics Enthusiast
# customer-churn-revenue-intelligence
=======

# Key Features

### 1. Churn Prediction Model

A machine learning model predicts the probability that a customer will churn.

* Feature engineering on customer demographics, service usage, and billing data
* Data preprocessing and encoding
* Model training using **Scikit-learn**
* Performance evaluation using classification metrics

---

### 2. Revenue Risk Analysis

The platform estimates **potential revenue loss caused by churn**.

Metrics calculated:

* Monthly revenue at risk
* High-value customers likely to churn
* Customer lifetime value indicators

---

### 3. Interactive Power BI Dashboard

An interactive dashboard was built to allow business users to explore churn insights visually.

Key dashboard views include:

* Customer churn distribution
* Revenue loss analysis
* Customer segmentation
* Churn probability by contract type
* Churn trends across demographics

---

# Tech Stack

| Category           | Tools        |
| ------------------ | ------------ |
| Programming        | Python       |
| Data Processing    | Pandas       |
| Machine Learning   | Scikit-learn |
| Database Querying  | SQL          |
| Data Visualization | Power BI     |

---

# Dataset

**IBM Telco Customer Churn Dataset**

* ~7,000 telecom customers
* Customer demographics
* Service subscriptions
* Billing information
* Churn status

Dataset fields include:

* Customer tenure
* Contract type
* Internet service
* Payment method
* Monthly charges
* Total charges
* Churn label

---

# Project Architecture

```
Data Source
   ↓
Data Cleaning & Transformation (Python, Pandas)
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Machine Learning Model (Scikit-learn)
   ↓
SQL Data Aggregation
   ↓
Power BI Dashboard
   ↓
Business Insights & Revenue Risk Analysis
```

---

# Machine Learning Workflow

1. Data preprocessing
2. Handling missing values
3. Encoding categorical variables
4. Feature scaling
5. Train/test split
6. Model training
7. Performance evaluation

Models explored include:

* Logistic Regression
* Random Forest (optional extension)

Evaluation metrics:

* Accuracy
* Precision
* Recall
* F1 Score

---

# Business Insights Generated

The analysis helps answer key business questions:

* Customers with **month-to-month contracts churn the most**
* **High monthly charges increase churn probability**
* Customers with **longer tenure are less likely to churn**
* Certain payment methods correlate with higher churn

These insights enable companies to:

* Target high-risk customers
* Offer retention discounts
* Improve long-term contract adoption
* Reduce revenue leakage

---

# Repository Structure

```
customer-churn-revenue-intelligence
│
├── data
│   └── telco_customer_churn.csv
│
├── notebooks
│   └── churn_analysis.ipynb
│
├── models
│   └── churn_model.pkl
│
├── dashboard
│   └── churn_dashboard.pbix
│
├── sql
│   └── revenue_analysis.sql
│
└── README.md
```

---

# Example Dashboard Metrics

Key KPIs included in the Power BI dashboard:

* Total Customers
* Churn Rate
* Monthly Revenue
* Revenue at Risk
* High-Risk Customer Segments

---

# How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/yourusername/customer-churn-revenue-intelligence.git
```

### 2. Install dependencies

```
pip install pandas scikit-learn numpy matplotlib seaborn
```

### 3. Run analysis notebook

Open:

```
notebooks/churn_analysis.ipynb
```

### 4. Open Power BI dashboard

Open the `.pbix` file in **Power BI Desktop**.

---

# Future Improvements

* Deploy churn prediction model as an API
* Build a real-time churn monitoring dashboard
* Add customer lifetime value prediction
* Automate data pipelines

---

# Project Highlights

* End-to-end data analytics pipeline
* Real-world telecom churn dataset
* Machine learning based churn prediction
* Business-ready Power BI dashboard
* Revenue risk estimation

---

# Author

Gaurav Verma
B.Tech Computer Science
Machine Learning & Data Analytics Enthusiast





