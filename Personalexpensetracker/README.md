# Personal Expense Tracker

Personal Expense Tracker helps you understand your spending by analyzing a transaction history file. It organizes transactions into useful summaries so you can see where your money goes and how your spending changes over time.

## What it tracks

- **Spending by category** — total expenses for each transaction category, such as groceries, transport, or utilities.
- **Spending by keyword** — find and group transactions by words in their descriptions or merchant names. For example, searching for `coffee` can help identify related purchases even when they have different descriptions.
- **Monthly expenditure** — calculate expense totals month by month to make spending patterns easier to compare.

## Transaction history

Provide a transaction history file containing the information needed to identify and summarize each transaction. At minimum, each transaction should have:

- A transaction date
- A description or merchant name
- A category, if available
- An amount

For example, a CSV file might look like this:

```csv
date,description,category,amount
2026-01-05,Neighborhood Market,Groceries,42.50
2026-01-08,City Bus,Transport,12.00
2026-02-02,Neighborhood Market,Groceries,35.25
```

The example is illustrative; use the column names and file format supported by your transaction export.

## Reports

The analysis can be viewed as:

1. **Category totals** — expenses grouped by category.
2. **Keyword results** — matching transactions and their combined expense totals.
3. **Monthly totals** — expenses grouped by calendar month.

## Getting started

1. Export your transaction history from your bank or payment service.
2. Make sure the file includes dates, descriptions, categories where available, and amounts.
3. Use the transaction history file as the input for the expense analysis.
4. Review the category, keyword, and monthly expenditure summaries.

> **Note:** The transaction file format and the exact way to run the analysis depend on the project implementation. Keep your transaction history private and avoid sharing files containing sensitive financial or account information.
