# 🚨 EDA for Mule Account Detection

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** for
detecting potential **mule accounts** in financial transaction datasets.
Mule accounts are typically used to transfer illegally obtained money
and play a key role in financial fraud.

The goal of this project is to: - Understand customer behavior - Analyze
transaction patterns - Identify anomalies - Generate insights useful for
fraud detection models

This project serves as the foundation for building machine
learning-based fraud detection systems.

------------------------------------------------------------------------

## 🎯 Objectives

-   Perform structured Exploratory Data Analysis (EDA)
-   Analyze relationships between Customers, Accounts, and Transactions
-   Identify suspicious transaction patterns
-   Detect unusual activity indicators
-   Prepare meaningful features for ML modeling

------------------------------------------------------------------------

## 📂 Project Structure

    mahir-bot-2003-eda-mule-detection/
    │
    ├── accounts.csv
    ├── customers.csv
    ├── customer_account_linkage.csv
    ├── transactions_*.csv
    ├── test_labels.csv
    ├── notebooks/
    ├── outputs/
    └── README.md

------------------------------------------------------------------------

## 📊 Dataset Description

### 1️⃣ Customers Dataset

Contains customer demographic and KYC details.

### 2️⃣ Accounts Dataset

Includes account information such as account type, status, and opening
date.

### 3️⃣ Customer-Account Linkage

Maps customers to their respective accounts.

### 4️⃣ Transactions Dataset

Includes: - Transaction ID\
- Sender & Receiver Account\
- Amount\
- Timestamp\
- Transaction Type

### 5️⃣ Test Labels

Used for validating mule detection predictions.

------------------------------------------------------------------------

## 🔎 EDA Performed

### ✔ Data Cleaning

-   Handling missing values\
-   Removing duplicates\
-   Data type corrections

### ✔ Univariate Analysis

-   Transaction amount distribution\
-   Account activity frequency\
-   Customer behavior trends

### ✔ Bivariate & Multivariate Analysis

-   Transaction count per account\
-   High-value transfers\
-   Account-to-account money flow

### ✔ Time-Based Analysis

-   Transaction spikes\
-   Sudden activity detection\
-   Dormant-to-active transitions

### ✔ Network Analysis

-   High-degree node detection\
-   Circular money flow identification\
-   Suspicious transaction chains

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   Python\
-   Pandas\
-   NumPy\
-   Matplotlib\
-   Seaborn\
-   Scikit-learn\
-   Jupyter Notebook

------------------------------------------------------------------------

## 📈 Key Insights

-   Sudden spikes in transaction volume indicate high risk.\
-   Newly opened accounts with large transfers are suspicious.\
-   Circular transactions often signal mule networks.\
-   Accounts linked to multiple customers require investigation.

------------------------------------------------------------------------

## 🚀 Future Improvements

-   Graph-based fraud detection models\
-   Machine learning models (XGBoost, Random Forest, Neural Networks)\
-   Fraud risk scoring system\
-   Real-time fraud monitoring pipeline

------------------------------------------------------------------------

## 🧠 Use Cases

-   Banking fraud detection\
-   Anti-Money Laundering (AML) systems\
-   Financial risk monitoring\
-   Hackathons and research projects

------------------------------------------------------------------------

## 👨‍💻 Author

**Mahir**\
Machine Learning Enthusiast \| Data Analyst\
Focused on Fraud Detection & ML Engineering

------------------------------------------------------------------------

## ⭐ How to Run

1.  Clone the repository

        git clone https://github.com/your-username/mahir-bot-2003-eda-mule-detection.git

2.  Install dependencies

        pip install -r requirements.txt

3.  Launch Jupyter Notebook

        jupyter notebook

------------------------------------------------------------------------

If you find this project useful, consider giving it a ⭐ on GitHub!
