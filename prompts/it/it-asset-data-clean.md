# Clean and standardise a messy asset list

**For:** IT teams  
**Tool:** Copilot Chat  
**Task:** Extract

## Prompt

```text
Standardise the asset list below into a clean table. Columns: Asset tag, Device type, Make/model, User or location, Status. Normalise device types to a consistent set (laptop, desktop, monitor, phone, other). Where a field is missing write [blank], do not guess. Flag any duplicate asset tags in a separate list.

List:
{paste}
```

## Why it works

Normalising device types to a fixed set is what makes the data reportable. Surfacing duplicate tags catches the errors that break an asset audit.

## Watch out

Spot-check the normalisation. The model can misclassify an all-in-one or a docking station, so eyeball the "other" rows.
