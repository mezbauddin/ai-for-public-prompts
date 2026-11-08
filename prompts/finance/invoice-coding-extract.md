# Extract coding details from an invoice batch

**For:** Finance  
**Tool:** Microsoft 365 Copilot  
**Task:** Extract

## Prompt

```text
From the invoices in {folder name}, extract: Supplier, Invoice date, Net, VAT, Gross, Likely cost centre based on supplier name and description, Confidence (high, medium, low). Output as a CSV-ready table. Flag any with confidence "low" in a separate list at the bottom.
```

## Why it works

Confidence-tagged extraction means you can split your time. Trust the highs, audit the lows.

## Watch out

Test on a known batch first. The cost-centre mapping is only as good as the conventions in your supplier names.

## Example output

Made-up data, for illustration only.

```text
Supplier,Date,Net,VAT,Gross,Cost centre,Confidence
Acme,03/02,1000,200,1200,Estates,high

Low confidence to review:
- Invoice 5567, supplier name unclear.
```
