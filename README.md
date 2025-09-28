# 📊 Bank Loan Report Dashboard with Machine Learning

## 🔎 Overview

This project analyzes bank loan data and provides insights using **Power BI** dashboards integrated with **Machine Learning** models. The goal is to help financial institutions track loan performance, predict risks, and support better decision-making.

The dashboard covers:

* Loan applications and funding trends
* Good vs. Bad loan classification (ML model output)
* State-wise, purpose-wise, and borrower profile insights
* Drill-down loan-level details for deeper analysis

---

## ✨ Features

* **Summary Dashboard**:

  * Total loan applications, funded amount, received amount
  * Average interest rate and DTI (Debt-to-Income ratio)
  * Good vs. Bad loan percentage (ML predictions)

* **Overview Dashboard**:

  * Monthly loan trends
  * Loan distribution across states
  * Loan purposes (debt consolidation, small business, home improvement, etc.)
  * Borrower demographics (employment length, home ownership, etc.)

* **Details Dashboard**:

  * Drill-down view with loan ID, purpose, grade, interest rate, funded amount, and repayment details

---

## 🤖 Machine Learning Model

* **Model Type**: Classification

* **Algorithm**: Logistic Regression / Random Forest (replace with what you used)

* **Objective**: Predict whether a loan is “Good” or “Bad” based on features such as:

  * Loan Amount
  * Funded Amount
  * Interest Rate
  * Grade & Subgrade
  * DTI (Debt-to-Income)
  * Employment Length
  * Home Ownership

* **Output**:

  * 84.3% Good Loans
  * 15.7% Bad Loans

These predictions were embedded into the dashboard for interactive analysis.

---

## 🛠 Tech Stack

* **Power BI** – Dashboard design & visualization
* **Python (Scikit-learn, Pandas, Numpy)** – Machine Learning & preprocessing
* **DAX** – Custom measures and KPIs
* **Excel/CSV** – Dataset

---

## 📂 Project Structure

```
├── BANK LOAN REPORT.ipynb   # Python notebooks / scripts for ML 
├── README.md               
├── Screenshot (77).png      # Screenshots / exported reports
├── Screenshot (78).png              
└── Screenshot (79).png                 
```

---

## 🚀 How to Run

1. Clone the repository
2. Open the dataset in Power BI Desktop
3. Connect the ML model predictions (CSV/Excel)
4. Explore the dashboard (Summary, Overview, Details)

---

## 📸 Screenshots

(Add your dashboard images here: Summary, Overview, Details)

---

## 📈 Learnings

* Built an end-to-end project combining **data visualization + machine learning**
* Learned to integrate predictive analytics with business dashboards
* Improved skills in **Power BI, DAX, and ML model building**

---

## 🔖 Keywords

`Power BI` · `Machine Learning` · `Data Analytics` · `Banking` · `Dashboard` · `Data Visualization`
