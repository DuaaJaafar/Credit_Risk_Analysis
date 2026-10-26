# 📊 Loan Defaults Risk Analysis

An interactive Tableau dashboard that analyzes loan default risk and highlights which borrower and loan characteristics are linked to the highest defaults and financial exposure.

🔗 *[Live Interactive Dashboard on Tableau Public](ublic.tableau.com/app/profile/duaa.jaafar/viz/CreditRiskDashboard_17911284936460/Dashboard1)*

---

## 🖼️ Dashboard Preview



<img width="1376" height="743" alt="Dashboard 1 (4)" src="https://github.com/user-attachments/assets/c2feaeec-26dc-4979-b513-462889975602" />





---

## 📌 Project Overview

Credit risk is one of the biggest challenges for banks and lenders. This project explores a loan dataset to answer a practical question:

**Who defaults, on what kind of loans, and how much money is at risk?**


The dashboard turns raw loan data into clear KPIs and visuals that support better lending and risk decisions.

---

## 🎯 Business Questions

- What is the overall default rate and total exposure?
- Which home-ownership groups default the most?
- Which loan purposes (intent) carry the highest default counts?
- How does loan amount relate to borrower income?
- Which loan grades contribute the most to default exposure?

---

## 📈 Key Metrics

| Metric | Value |
|---|---|
| Total Default Exposure | 77.13M |
| Total Defaults | 7,108 |
| Default Rate | 21.82% |
| Avg. Loan Amount | $10K |
| Avg. Interest Rate | 11.01% |

---

## 🔍 Key Insights

- *Renters drive defaults:* Rent accounts for 5,192 of 7,108 defaults (~73%), followed by Mortgage (1,690). Homeowners (Own) show very few defaults (193).
- *Medical loans lead by count:* Medical is the loan intent with the most defaults (1,621), followed by Debt Consolidation (1,490) and Education (1,111).
- *Grade D carries the most exposure:* Default amount peaks at Grade D (22.80M, ~30% of total), followed by Grade B (19.12M) and Grade C (13.56M).
- *Higher loan-to-income ratio, higher risk:* Defaulted loans have a higher average loan-percent-income than non-defaulted ones.

---

## 🛠️ Tools & Skills

- *Tableau Public* – dashboard design and interactive visuals
- *Excel / SQL / Python* – data cleaning and preparation
- *Financial Risk Analysis* – default rate, exposure, loan grades

---

## 🧹 Data Preparation

1. Reviewed the dataset structure and data types
2. Handled missing values and duplicates
3. Checked outliers (e.g., unrealistic age or income)
4. Created calculated fields (Default Rate, Default Exposure)
5. Built the dashboard and KPI cards in Tableau

---

## 💡 Recommendations

- Apply stricter review for high loan-to-income applications
- Monitor Grade D and lower-grade portfolios more closely
- Review lending policies for high-default purposes such as Medical and Debt Consolidation

---

## 📂 Repository Structure

Credit_Risk_Analysis/
├── data/            # dataset
├── dashboard/       # Tableau workbook / screenshots
└── README.md

---

## 👩‍💻 Author

*Duaa Jaafar*
Banking professional transitioning into Financial Data Analytics
