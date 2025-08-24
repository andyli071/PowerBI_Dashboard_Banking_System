# Banking Analytics Dashboard

This project simulates a realistic banking system using synthetic data generated with Python and Faker. It includes customer information, bank accounts, financial transactions, and loans — all linked together in a relational model ready for Power BI visualization.

### Live Demo
**Open the interactive Power BI report:** [Dashboard](https://app.powerbi.com/reportEmbed?reportId=3f46ed1f-84f2-467c-bf11-8c3af851cd64&autoAuth=true&ctid=8322cefd-0a4c-4e2c-bde5-b17933e7b00f&actionBarEnabled=true)


### Dataset Overview

| Table         | Description                                                |
|---------------|------------------------------------------------------------|
| `customers`   | Personal and contact info of 500 synthetic customers       |
| `accounts`    | 1–3 bank accounts per customer (Chequing, Savings)         |
| `transactions`| 1-10 transactions per account (Deposit, Withdrawal, Payroll, E-transfer, Bill payment)  |
| `loans`       | 0–2 loans per customer with amortization + interest        |


## Tools Used

- **Python** (`pandas`, `faker`, `random`) for datasets sitmulation
- **Power BI for visualization and analysis
- **Jupyter Notebook / Colab** for running and editing scripts

### What’s inside
- **Executive KPIs:** Customers, Accounts, Loans, Deposits, Withdrawals, Net Cash Flow  
- **Health Checks:** LDR Ratio (+ target status chip), Two-Product Penetration  
- **Trends:** Deposits vs Withdrawals, Net Cash Flow (Quarter), audit matrix  
- **Customer Growth:** Active Customers **YoY %** (gracefully shows “N/A” when no prior year)

### Key Measures (selection)
- `Total Deposits` (Deposit + Payroll), `Total Outflows`, `Net Cash Flow`
- `LDR = Loan Portfolio / Deposits (Balance)`
- `Active Customers YoY %` (transaction-based)
- `Two-Product Penetration %` (≥1 account **and** ≥1 loan, snapshot)


### Files Included
- customers.csv
- accounts.csv
- transcations.csv
- loans.csv

