# 🏦 Banking Dashboard - End-to-End Data Analysis Project

This project focuses on building an interactive **Banking Dashboard** using Power BI. It involves the complete data analysis lifecycle — from data cleaning and transformation to exploratory data analysis (EDA) and visualization.

---

## 📑 Table of Contents  

---

## Business Problem 

In modern banking, understanding customer financial behavior across multiple accounts—like deposits, loans, and savings—is vital for improving service delivery, risk management, and profitability. This project builds a comprehensive Power BI dashboard to visualize banking metrics and customer segments, enabling data-driven strategy and informed decision-making.

---

## 📊 Dataset Information

- **Number of columns**: 24
- **Stored in**: MySQL

---

## 🚀 Tools & Technologies

- **Database**: MySQL
- **Visualization**: Power BI
- **Languages**: SQL, DAX (in Power BI)

---

## Project Structure  

```
Amazon-Sales-Report/
│
│── 📂 data/                         
│   │── Banking.csv      # Original dataset
│
│── 📂 EDA/              # Jupyter notebooks for EDA & analysis
│   │── BankEDA.ipynb
│
│── 📂 powerbi/                 # Power BI dashboard
│   │── Banking Dashboard.pbix
│
│── 📂 visuals/                   # Exported plots, charts, and screenshots
│   │── page1_home.png
│   │── page2_loan_analysis.png
│   │── page3_deposit_analysis.png
│   │── page4_summary.png
│
│── 📄 README.md                 # Project overview, business problem, insights,etc
│── 📄 .gitignore                 # Ignore unnecessary files

```
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

---

## ✅ Results & Conclusion
After conducting data cleaning, exploratory data analysis (EDA), and building a Power BI dashboard, the project delivers clear and actionable insights into banking customer behaviors:
- Customers with high balances across one account type (like savings) often hold substantial funds in other accounts—indicating consolidated wealth patterns.
- The dashboard facilitates quick comparisons of loans, deposits, account balances, and estimated income across demographics.
- Users gain clarity on financial trends, enabling strategic decisions by banks in areas like cross-sell, retention, and credit management.

---

## 🔮 Future Work  

- Real-time data integration: Set up live connections to MySQL or other data sources for automatic dashboard updates.
- Advanced analytics: Add predictive analytics for detecting customer churn or detecting credit risk.
- Enhanced visual storytelling: Improve dashboard navigation with drill-throughs, tooltips, and rich visuals.
- Scalability: Deploy the dashboard on Power BI Service for team-wide sharing or embed into internal portals.
  
---

## Author & Contact  
👩‍💻 **Ayushi Kedia**    
📧 Email: ayushikediahm@gmail.com    
🔗 [LinkedIn](https://www.linkedin.com/in/ayushi-kedia-81bb7520b/)  
