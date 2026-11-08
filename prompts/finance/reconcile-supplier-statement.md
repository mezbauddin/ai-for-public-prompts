# Reconcile a supplier statement against ledger

**For:** Finance  
**Tool:** Copilot Chat  
**Task:** Analyse

## Prompt

```text
Compare the supplier statement and the ledger extract below. Output a table of: Invoice number, Supplier amount, Ledger amount, Difference, Likely cause (from this list: missing on ledger, missing on statement, value mismatch, duplicate). Sort by absolute difference, largest first.

Statement:
{paste}

Ledger:
{paste}
```

## Why it works

A finite "likely cause" list keeps it from inventing categories. Sorting by absolute difference puts the worst rows at the top, where they belong.

## Watch out

Always reconcile the totals manually before trusting the line-by-line. If totals do not match what you pasted, the paste is the bug.
