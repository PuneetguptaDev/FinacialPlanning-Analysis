# 💰 Finance Analysis Dashboard | Power BI

An interactive **Finance Analysis Dashboard** developed in Microsoft Power BI to transform transaction-level financial data into clear business insights.

The dashboard provides an overview of **transaction value, transaction volume, fees, taxes, transaction status, customer segments, geography, gender, and transaction types**.

---

## 📌 Project Overview

Financial transaction datasets can contain a large amount of information that is difficult to interpret through raw tables.

This project uses **Power BI, Power Query, and DAX** to convert transaction data into an interactive dashboard that helps users monitor financial performance and understand transaction patterns.

### Key areas analyzed

- Total transaction amount
- Number of transactions
- Average transaction value
- Transaction fees
- Tax amount
- Monthly transaction trends
- Transaction status
- Customer segments
- Geographic distribution
- Gender distribution
- Transaction types

---

## 🎯 Business Objectives

The main objectives of this project are to:

- Monitor overall financial transaction performance
- Identify monthly transaction trends
- Compare successful, failed, and pending transactions
- Analyze transaction value across customer segments
- Understand geographic transaction distribution
- Compare transaction activity by gender
- Evaluate transaction types by amount, fees, tax, and volume
- Provide interactive filtering for deeper analysis

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI** | Dashboard development & visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | KPI and analytical calculations |
| **Microsoft Excel / CSV** | Data preparation |
| **Data Modeling** | Relationships and analytical structure |

---

## 📊 Dashboard Overview

The dashboard contains an interactive finance overview with the following key KPIs:

| KPI | Dashboard Value |
|---|---:|
| Total Amount | **1.10M** |
| Total Transactions | **76** |
| Average Transaction Value | **14.52K** |
| Total Fee | **1.82K** |
| Total Tax | **328.35** |

> Values shown above correspond to the dashboard screenshot included in this repository and may change when different filters are applied.

---

## 📈 Dashboard Analysis

### 1. Monthly Transaction Amount

The monthly trend visual tracks total transaction amount across the year.

It can be used to identify:

- Monthly peaks and declines
- Seasonal transaction patterns
- Periods of unusually high or low transaction activity
- Changes in transaction value over time

The dashboard currently displays monthly values from **January to December 2024**.

---

### 2. Transaction Status Analysis

A donut chart categorizes transaction amount according to transaction status:

- Success
- Failed
- Pending

This helps users understand the distribution of transaction value across different transaction outcomes.

---

### 3. Customer Segment Analysis

Transaction amounts are compared across customer segments, including:

- Retail
- Premium
- SME
- Corporate
- Wealth

This analysis helps identify which customer groups contribute the largest transaction values.

---

### 4. Geographic Analysis

The dashboard compares transaction amounts across Indian states.

Examples visible in the dashboard include:

- Maharashtra
- Karnataka
- Madhya Pradesh
- Gujarat
- West Bengal
- Tamil Nadu
- Kerala
- Haryana
- Delhi
- Telangana
- Uttar Pradesh
- Rajasthan

This provides a geographic perspective on transaction activity.

---

### 5. Gender Analysis

Transaction amounts are segmented by:

- Male
- Female

This visual provides an additional demographic perspective on transaction activity.

---

### 6. Transaction Type Analysis

The transaction table provides a detailed comparison of transaction types using:

- Transaction Amount
- Fee Amount
- Tax Amount
- Total Transaction

Transaction types shown include:

- Loan EMI
- Transfer
- Deposit
- Investment
- Withdrawal
- Bill Payment
- Card Payment
- Interest Credit
- Refund
- Fee Charge

This allows users to compare both transaction value and associated financial costs.

---

## 🎛️ Interactive Filters

The dashboard provides interactive slicers for:

- **Year**
- **Occupation**
- **Merchant Category**

These filters allow users to drill down into specific customer and transaction segments.

---

## 🧮 Key Analytical Measures

Example DAX measures used for the dashboard include:

### Total Amount

```DAX
Total Amount =
SUM('Transactions'[Amount])
```

### Total Transactions

```DAX
Total Transactions =
COUNTROWS('Transactions')
```

### Average Transaction Value

```DAX
Average Transaction Value =
DIVIDE(
    [Total Amount],
    [Total Transactions]
)
```

### Total Fee

```DAX
Total Fee =
SUM('Transactions'[Fee Amount])
```

### Total Tax

```DAX
Total Tax =
SUM('Transactions'[Tax Amount])
```

> Replace the table and column names with the exact names from your Power BI data model.

---

## 🧱 Data Model

The project follows a structured analytical approach using transaction data and supporting dimensions where applicable.

Typical analytical dimensions include:

```text
                    ┌──────────────┐
                    │     Date     │
                    └──────┬───────┘
                           │
                           │
┌──────────────┐     ┌─────▼─────────┐     ┌──────────────┐
│   Customer   │────►│  Transactions │◄────│    Product   │
└──────────────┘     └─────┬─────────┘     └──────────────┘
                           │
                           │
                    ┌──────▼───────┐
                    │    Geography │
                    └──────────────┘
```

---

## 📸 Dashboard Preview

## 📸 Dashboard Preview

<p align="center">
  <img src="./Finance-Analysis-Dashboard/Finance%20analysis-1.png" 
       alt="Finance Analysis Dashboard" 
       width="100%">
</p>
---

## 📁 Repository Structure

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
│   └── finance-analysis-dashboard.png
│
├── DAX/
│   └── measures.md
│
└── Documentation/
    └── data_dictionary.md
```

---

## 💡 Business Questions Answered

This dashboard can help answer questions such as:

1. How much transaction value was generated?
2. What is the average transaction value?
3. How does transaction amount change month by month?
4. What proportion of transaction value is successful, failed, or pending?
5. Which customer segment contributes the highest transaction value?
6. Which states generate the highest transaction amounts?
7. How does transaction value differ by gender?
8. Which transaction types generate the highest amount?
9. Which transaction types have higher fees and taxes?
10. How do results change when filtering by year, occupation, or merchant category?

---

## 📌 Key Skills Demonstrated

### Financial Analysis
- Transaction analysis
- KPI analysis
- Fee and tax analysis
- Customer segmentation
- Trend analysis

### Power BI
- Interactive dashboards
- DAX measures
- Power Query
- Data modeling
- Slicers and filters
- KPI cards
- Drill-down analysis
- Data visualization

### Data Analytics
- Data cleaning
- Data transformation
- Exploratory analysis
- Business intelligence
- Analytical storytelling

---

## 🚀 Project Outcome

This project demonstrates how transaction-level financial data can be transformed into an interactive **Business Intelligence and Financial Analytics solution**.

The dashboard combines financial KPIs, transaction analysis, customer segmentation, geographic analysis, and interactive filtering to support faster and more structured analysis.

---

## 👨‍💻 Author

**Puneet Gupta**

Master's Student – Finance  
Specialization: Financial Markets & Technologies

### Areas of Interest

- Financial Analysis
- Business Intelligence
- Power BI
- Data Analytics
- Financial Markets
- FinTech
- SQL
- Python
- Financial Modeling

---

⭐ If you find this project useful, feel free to explore the repository and connect with me.
