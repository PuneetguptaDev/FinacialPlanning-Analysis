# 💰 Finance Analysis Dashboard | Power BI

An interactive **Finance Analysis Dashboard** built using **Microsoft Power BI** to transform transaction-level financial data into meaningful business insights.

This project analyzes financial transactions across customer segments, transaction status, geography, gender, merchant categories, and transaction types through interactive visualizations and KPI reporting.

---

## 📌 Project Overview

Financial institutions generate thousands of transactions every day. Raw transaction data is difficult to interpret without proper visualization and analysis.

This dashboard converts transaction data into an interactive Business Intelligence solution that helps users monitor financial performance, identify transaction patterns, compare customer segments, and analyze transaction behavior.

---

## 🎯 Business Objectives

The dashboard is designed to answer important business questions such as:

- Monitor overall transaction performance
- Analyze monthly transaction trends
- Compare successful, failed, and pending transactions
- Identify high-value customer segments
- Analyze state-wise transaction distribution
- Compare transaction activity by gender
- Evaluate different transaction types
- Track fees and taxes across transactions
- Enable interactive filtering using slicers

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard development & visualization |
| Power Query | Data cleaning & transformation |
| DAX | KPI calculations & business measures |
| Excel / CSV | Data preparation |
| Data Modeling | Relationship management |

---

# 📊 Dashboard Features

## 1️⃣ Overview Analysis

The first dashboard page provides a complete financial overview using KPI cards and analytical visuals.

### Key Performance Indicators

| KPI | Value |
|-----|------:|
| Total Amount | **1.10M** |
| Total Transactions | **76** |
| Average Transaction Value | **14.52K** |
| Total Fee | **1.82K** |
| Total Tax | **328.35** |

### Analysis Included

- Monthly transaction amount trend
- Transaction status distribution
- Customer segment contribution
- State-wise transaction analysis
- Gender-wise transaction amount
- Transaction type analysis
- Interactive slicers for Year, Occupation, and Merchant Category

---

## 2️⃣ Transaction Details

The second dashboard page provides detailed transaction-level analysis.

Users can explore:

- Account ID
- Customer Name
- Transaction Date
- Transaction Type
- Transaction Status
- Gender
- Customer Segment
- State
- Transaction Amount
- Total Fee
- Total Tax

Interactive filters allow users to drill into specific transaction records and customer groups.

---

# 📸 Dashboard Preview

## Overview Dashboard

![Finance Analysis Dashboard](Screenshots/Finance%20analysis-1.png)

---

## Transaction Details Dashboard

![Finance Analysis Transaction Dashboard](Screenshots/Finance%20analysis-2.png)

---

# 📈 Key Insights

The dashboard enables analysis of:

- Financial transaction performance over time
- Monthly revenue and transaction movement
- Success vs Failed vs Pending transaction distribution
- Customer segment contribution to total transaction value
- Geographic distribution across states
- Gender-based transaction comparison
- Transaction types with associated amount, fees, and taxes
- Detailed transaction records for operational analysis

---

# 🧮 Example DAX Measures

### Total Amount

```DAX
Total Amount =
SUM(Transactions[Amount])
```

### Total Transactions

```DAX
Total Transactions =
COUNTROWS(Transactions)
```

### Average Transaction Value

```DAX
Average Transaction Value =
DIVIDE([Total Amount],[Total Transactions])
```

### Total Fee

```DAX
Total Fee =
SUM(Transactions[Fee Amount])
```

### Total Tax

```DAX
Total Tax =
SUM(Transactions[Tax Amount])
```

> Update table and column names according to your Power BI data model.

---

# 🧱 Repository Structure

```text
Finance-Analysis-Dashboard/
│
├── README.md
│
├── PowerBI/
│   └── Finance_Analysis_Dashboard.pbix
│
├── Dataset/
│   └── transactions.csv
│
├── Screenshots/
│   ├── Finance analysis-1.png
│   └── Finance analysis-2.png
│
├── DAX/
│   └── measures.md
│
└── Documentation/
    └── data_dictionary.md
```

---

# 📂 Data Dictionary

| Column | Description |
|--------|-------------|
| Account ID | Unique customer account identifier |
| Customer Name | Name of customer |
| Transaction Date | Date of transaction |
| Transaction Type | Type of financial transaction |
| Transaction Status | Success, Failed or Pending |
| Gender | Customer gender |
| Customer Segment | Retail, Premium, SME, Corporate, Wealth |
| State | Customer state |
| Amount | Transaction amount |
| Fee Amount | Transaction fee |
| Tax Amount | Tax charged |

---

# 💼 Skills Demonstrated

- Financial Analysis
- Business Intelligence
- Power BI Dashboard Development
- DAX Calculations
- Power Query
- Data Modeling
- KPI Development
- Data Visualization
- Customer Segmentation
- Transaction Analytics
- Interactive Reporting

---

# 🚀 Project Outcome

This project demonstrates the ability to transform raw financial transaction data into a professional interactive dashboard that supports business reporting, financial analysis, and data-driven decision making.

---

## 👨‍💻 Author

**Puneet Gupta**

Master's Student – Finance  
Specialization: Financial Markets & Technologies

Skills: Power BI | SQL | Python | Excel | DAX | Financial Analysis | Business Intelligence
