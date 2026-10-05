# Credit Card Fraud Detection & Risk Analysis

End-to-end fraud analytics project using SQL and Power BI to detect suspicious patterns in 280,000+ credit card transactions.

---

## Project Overview

This project analyzes a large dataset of credit card transactions to identify fraudulent behavior, high-risk patterns, and time-based anomalies.  

The goal is to simulate a real-world risk & fraud monitoring workflow used by financial institutions (banks, payment companies, and card issuers).

**Dataset Size:** 283,726 transactions  
**Fraud Rate:** 0.83%  
**Tools Used:** SQL + Power BI

---

## Key Findings

- Fraud rate is low (0.83%), but the monetary impact is significant
- Clear “small-test” fraud pattern detected: many fraudulent accounts first make very small transactions ($1–$19) before larger fraud attempts
- Fraud activity peaks at specific hours: **11:00 AM** and **2:00 PM**
- Interactive Power BI dashboard built for monitoring fraud trends, amounts, and time patterns

---

## Tech Stack

| Tool       | Purpose                                      |
|------------|----------------------------------------------|
| SQL        | Data cleaning, transformation & pattern detection |
| Power BI   | Interactive fraud monitoring dashboard       |

---

## Project Structure

- `1. Sql_scripts/` → SQL queries used for analysis
- `2. Powerbi_dashboard_pdf/` → Dashboard screenshots / PDF
- Power BI file & original dataset links are available in the repository

---

## How to Explore

1. Review the SQL scripts to understand the data preparation and analysis logic
2. Open the Power BI dashboard (or view the PDF version) to explore fraud patterns
3. Use filters and drill-through to investigate high-risk transactions

---

## Business Impact

This type of analysis helps risk teams:
- Detect early warning signals (small test transactions)
- Focus monitoring on high-risk time windows
- Reduce potential fraud losses through faster identification

---

## Skills Demonstrated

- Large-scale transaction analysis
- Fraud pattern detection
- Risk analytics storytelling
- SQL for financial data
- Interactive dashboard design in Power BI

---

## Future Enhancements

- Build machine learning models for real-time fraud scoring
- Add automated alert rules based on amount + time + frequency patterns
