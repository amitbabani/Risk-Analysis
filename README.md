
# 🏦 Banking Dashboard for Risk Analysis

A **Power BI**-based interactive dashboard project designed to visualize key financial metrics and support comprehensive **risk analysis** in a banking environment.

---

## 🚀 How to Use

This project includes several components to help you explore and analyze banking risk data effectively:

* **Power BI File**:

  * `Risk Analysis Dashboard.pbix` (not shown here, but implied): Load into Power BI Desktop to interact with the full dashboard.
* **Main Dataset**:

  * `banking.csv`: The core dataset used across the project for analysis and visualization.
* **Dashboard PDF**:

  * `Risk Analysis.pdf`: A 5-page static version of the dashboard for quick reference and sharing.
* **EDA Notebooks**:

  * Located in the `banking-eda-versions` folder; includes exploratory data analysis (EDA) scripts to understand and prepare the data.
* **Extra Info Folder**:

  * Contains various supplementary files offering a clearer view of data segments and preprocessing steps.
* **Background Images Folder**:

  * Includes all **5 background images** used for designing the dashboard visuals in **Canva**.

---

## 📋 Overview

The dashboard is structured into several key sections, accessible via tabs:

* **Home**
* **Loan Analysis**
* **Deposit Analysis**
* **Summary**

It also includes a detailed **client table** and a **time-series graph**.

---

## 📊 Features

### 🏠 Home Tab

* High-level overview of core banking metrics.
* Displays:

  * **Total Clients**: 3,000
  * **Total Loan**: \$4.38B
  * **Total Deposit**: \$3.77B
  * **Bank Deposit**: \$698.73M
  * **Checking Accounts**: \$963.28M
  * **Saving Accounts**: \$2.6B
* Filters:

  * **Joining Year**
  * **Gender**

### 💳 Loan Analysis Tab

* Focuses on loan-related data.
* Metrics:

  * **Total Loan**: \$4.38B
  * **Bank Loan**: \$1.77B
  * **Business Lendings**: \$2.6B
  * **CC Balance**: \$9.53M
* Breakdown by:

  * Banking Relationship
  * Nationality
  * Occupation
  * Income Band
* Filters:

  * Banking Relationship
  * Gender
  * Institutional Advisor
  * Year

### 💰 Deposit Analysis Tab

* Focuses on deposit-related data.
* Metrics (filtered example):

  * **Total Deposit**: \$135.52M
  * **Bank Deposit**: \$73.6M
  * **Saving Account Amount**: \$24.99M
  * **Checking Account Amount**: \$33.79M
  * **Foreign Currency Amount**: \$3.14M
* Breakdown by:

  * Nationality
  * Occupation
  * Income Band
* Filters:

  * Banking Relationship
  * Gender
  * Institutional Advisor
  * Year

### 📈 Summary Tab

* Consolidated view of key metrics.
* Metrics:

  * Total Clients, Loans, Deposits, Business Lending, Superannuation Savings, CC Amount, etc.
* Filters:

  * Banking Relationship
  * Gender
  * Institutional Advisor
  * Year

### 👤 Client Detail Table

* Lists individual client details (6748 entries).

  * Name, Banking Relationship, Risk Weighting, Deposits, Loans, Income Band.

### 📉 Historical Trend Visualization

* Line chart showing:

  * **Loans vs. Deposits over Years**
  * Useful for analyzing financial trends.

---

## 🔍 Supporting Risk Analysis

This dashboard supports risk-focused insights through:

* Client-level **risk weighting** information.
* Loan/deposit exposure analysis by **Income Band**.
* Demographic segmentation (Gender, Occupation, Nationality).
* Historical trend visualization for strategic forecasting.

---

## 📂 Project Structure

```
📁 Risk-Analysis-Dashboard/
├── Risk Analysis.pdf                  # 5-page static dashboard
├── banking.csv                        # Main dataset
├── banking-eda-versions/             # EDA notebooks and versions
├── extra-info/                       # Additional context and data views
├── background-images/                # 5 Canva-designed backgrounds
└── README.md                         # Project documentation
```
