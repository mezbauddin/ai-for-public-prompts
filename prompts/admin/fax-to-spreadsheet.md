# Turn a messy list into a clean spreadsheet

**For:** Admin teams  
**Tool:** Copilot Chat  
**Task:** Extract

## Prompt

```text
Take the messy text below and turn it into a clean table with these columns: {name, date, reference, status}. One row per entry. Where a field is missing, write [blank]. Do not guess values. Output CSV-ready.

Text:
{paste}
```

## Why it works

Naming the columns and banning guesses turns unstructured text into something you can paste straight into Excel. The [blank] marker shows you exactly where the gaps are.

## Watch out

Spot-check a few rows against the source. If the original formatting is wildly inconsistent, fields can land in the wrong column.
