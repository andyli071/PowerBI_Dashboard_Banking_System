# Banking Database Simulation (SQL + Python + Power BI)

This project simulates a realistic banking system using synthetic data generated with Python and Faker. It includes customer information, bank accounts, financial transactions, and loans — all linked together in a relational model ready for SQL analysis and Power BI visualization.

---

## Dataset Overview

| Table         | Description                                                |
|---------------|------------------------------------------------------------|
| `customers`   | Personal and contact info of 500 synthetic customers       |
| `accounts`    | 1–3 bank accounts per customer (Chequing, Savings)         |
| `transactions`| 1-10 transactions per account (Deposit, Withdrawal, Payroll, E-transfer, Bill payment)  |
| `loans`       | 0–2 loans per customer with amortization + interest        |

---

## Tools Used

- **Python** (`pandas`, `faker`, `random`) for dataset generation
- **CSV** files for portability and compatibility
- **Power BI / SQL** for visualization and analysis
- **Jupyter Notebook / Colab** for running and editing scripts

---

## Files Included

- customers.csv
- accounts.csv
- transcations.csv
- loans.csv
