# DAX Measures

Core measures used or recommended for the Finance Analysis Dashboard.

```DAX
Total Amount =
SUM('Transactions'[Amount])

Total Transactions =
COUNTROWS('Transactions')

Average Transaction Value =
DIVIDE(
    [Total Amount],
    [Total Transactions]
)

Total Fee =
SUM('Transactions'[Fee Amount])

Total Tax =
SUM('Transactions'[Tax Amount])
```

Replace table/column names if your Power BI model uses different names.
