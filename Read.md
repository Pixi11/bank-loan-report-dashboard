# 📊 Bank Loan Report Dashboard (Power BI + SQL)

## 📌 Project Overview

The **Bank Loan Report Dashboard** is an end-to-end Data Analytics project built using **SQL** and **Power BI** to analyze lending operations, loan performance, and borrower behavior.

This dashboard provides actionable insights into:

- Loan applications & disbursements
- Repayment performance
- Good vs Bad loans
- Interest rate & DTI analysis
- Regional lending trends
- Borrower demographics

The report is divided into **three interactive dashboards**:

1. Summary  
2. Overview  
3. Details  

---

# 🧩 Problem Statement

Financial institutions require a comprehensive reporting solution to monitor lending performance, repayment trends, and borrower risk.

This project aims to build an interactive dashboard that tracks:

- Loan KPIs
- Risk metrics
- Portfolio health
- Regional distribution
- Borrower profiles

---

# 🛠️ Tech Stack

- **SQL** → Data extraction & KPI calculations  
- **Power BI** → Dashboard creation & visualization  
- **Excel / CSV** → Dataset source  
- **DAX** → Measures & calculated fields  

---

# 📈 Dashboard 1 — Summary

## 🔑 Key KPIs

- Total Loan Applications  
- Total Funded Amount  
- Total Amount Received  
- Average Interest Rate  
- Average Debt-to-Income Ratio (DTI)  
- Month-to-Date (MTD) Metrics  
- Month-over-Month (MoM) Changes  

---

## ✅ Good Loan Metrics

- Good Loan Percentage  
- Good Loan Applications  
- Good Loan Funded Amount  
- Good Loan Amount Received  

---

## ❌ Bad Loan Metrics

- Bad Loan Percentage  
- Bad Loan Applications  
- Bad Loan Funded Amount  
- Bad Loan Amount Received  

---

## 📊 Loan Status Grid View

Breakdown by:

- Fully Paid  
- Current  
- Charged Off  

Metrics:

- Applications  
- Funded Amount  
- Amount Received  
- Interest Rate  
- DTI  

---

# 🌍 Dashboard 2 — Overview

Provides trend and segmentation analysis.

## Visualizations Included

1. **Monthly Trends by Issue Date (Line Chart)**  
   → Identifies seasonality & growth trends  

2. **Regional Analysis by State (Filled Map)**  
   → Shows lending distribution  

3. **Loan Term Analysis (Donut Chart)**  
   → 36 vs 60 month loans  

4. **Employee Length Analysis (Bar Chart)**  
   → Impact of employment history  

5. **Loan Purpose Breakdown (Bar Chart)**  
   → Reasons for borrowing  

6. **Home Ownership Analysis (Tree Map)**  
   → Rent vs Mortgage vs Own  

---

# 📋 Dashboard 3 — Details

A transactional drill-through dashboard.

## Fields Included

- Loan ID  
- Purpose  
- Home Ownership  
- Grade & Sub-Grade  
- Issue Date  
- Funded Amount  
- Interest Rate  
- Installment  
- Amount Collected  

This view provides a consolidated snapshot of all loan records.

---

# 🧮 SQL Queries Used

KPIs were calculated using SQL aggregations.

## Example Queries

### Total Loan Applications

```sql
SELECT COUNT(id) AS Total_Applications
FROM bank_loan_data;
