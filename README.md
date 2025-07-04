# 🏦 Banking Dashboard - End-to-End Data Analysis Project

This project focuses on building an interactive **Banking Dashboard** using Power BI. It involves the complete data analysis lifecycle — from data cleaning and transformation to exploratory data analysis (EDA) and visualization.

---

## 📌 Project Workflow

Data ➡️ MySQL ➡️ Data Cleaning & Preparation ➡️ EDA ➡️ Power BI Dashboard

---

## 📊 Dataset Information

- **Number of columns**: 24
- **Stored in**: MySQL

---

## 🔧 Steps Involved

### 1. Data Cleaning & Preparation

- Categorized `Income` into bands:
  - `Low`
  - `Mid`
  - `High`
- Standardized gender, nationality, and other categorical variables.
- Used conditional columns in Power BI to create income bands.
- Replaced branch codes (`'1'`, `'2'`, etc.) with readable branch names.
- Mapped gender codes:
  - `'1'` → `Male`
  - `'2'` → `Female`

---

### 2. Exploratory Data Analysis (EDA)

- Categorical analysis on:
  - Gender
  - Nationality
- Numerical analysis on:
  - Credit Card Balance
  - Bank Loans
  - Bank Deposits
  - Checking Account
  - Saving Account
  - Estimated Income
  - Superannuation Savings

---

### 3. Key Insights from EDA

- Strong positive correlation between:
  - `Bank Deposits`, `Checking Account`, `Saving Account`, and `Foreign Currency Account`.
- Customers with high balance in one account type tend to hold substantial funds in other accounts as well.

---

## 📈 Dashboard Pages (Power BI)

1. **Home**
2. **Loan Analysis**
3. **Deposit Analysis**
4. **Summary**

---

## 🚀 Tools & Technologies

- **Database**: MySQL
- **Visualization**: Power BI
- **Languages**: SQL, DAX (in Power BI)

---

## 🧠 Learnings

- Data wrangling using SQL
- Power BI conditional columns
- Deriving insights through EDA
- Building multi-page dashboards for presentation

---
## 📊 Dashboard Previews

### 🏠 Page 1: Home Page
> Overview of the banking data with summary statistics and key visuals.  
![Home Page](https://raw.githubusercontent.com/Ayu0209/Banking-Dashboard-Data-Analytics/main/POWER_BI/page1_home.png)

---

### 💳 Page 2: Loan Analysis  
> Insights into loan distribution, types, and customer segments.  

![Loan Analysis](https://raw.githubusercontent.com/Ayu0209/Banking-Dashboard-Data-Analytics/main/POWER_BI/page2_loan_analysis.png)

---

### 💰 Page 3: Deposit Analysis  
> Breakdown of account balances, deposit types, and correlation patterns.  

![Deposit Analysis](https://raw.githubusercontent.com/Ayu0209/Banking-Dashboard-Data-Analytics/main/POWER_BI/page3_deposit_analysis.png)

---

### 📋 Page 4: Summary  
> Final insights from EDA, including correlations and demographic trends.  

![Summary](https://raw.githubusercontent.com/Ayu0209/Banking-Dashboard-Data-Analytics/main/POWER_BI/page4_summary.png)
