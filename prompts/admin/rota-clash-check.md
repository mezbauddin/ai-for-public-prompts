# Spot clashes in a draft rota

**For:** Admin teams  
**Tool:** Copilot Chat  
**Task:** Analyse

## Prompt

```text
Check the rota below for problems. Look for: anyone working two shifts in 24 hours, anyone with fewer than 11 hours between shifts, any shift with nobody assigned, anyone scheduled when their leave dates overlap. List each issue with the date and the people involved.

Rota:
{paste as a table}
```

## Why it works

Rota maths is exactly the kind of fiddly logic an LLM can do reliably if you tell it the rules. The explicit rules are doing the work.

## Watch out

Always paste the rota in a clean tabular format. If columns drift, the analysis goes wrong silently.

## Example output

Made-up data, for illustration only.

```text
Issues found:
- 12 Mar: J. Doe has only 9 hours between a late and an early.
- 14 Mar: night shift has nobody assigned.
- 15 Mar: A. Khan is scheduled during booked annual leave.
```
