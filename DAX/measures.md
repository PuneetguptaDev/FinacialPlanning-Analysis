# DAX Measures

```DAX
Total Amount = SUM(Transactions[Amount])

Total Transactions = COUNTROWS(Transactions)

Average Transaction Value =
DIVIDE([Total Amount],[Total Transactions])

Total Fee = SUM(Transactions[Fee Amount])

Total Tax = SUM(Transactions[Tax Amount])
```
