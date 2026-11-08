# Compare two guidelines side by side

**For:** Clinicians  
**Tool:** Copilot Chat  
**Task:** Analyse

## Prompt

```text
Compare these two clinical guidelines on {condition}. Output a table with rows for: First-line treatment, Second-line, Monitoring, Red flags, Patient education. Columns are the names of the two guidelines. Note any disagreements explicitly under the table.

Guideline A:
{paste}

Guideline B:
{paste}
```

## Why it works

Comparison tables are hard to keep in your head and easy to mess up by hand. Asking it to flag disagreements is the bit that actually saves you reading time.

## Watch out

Sanity check the rows that disagree. Sometimes one guideline is silent rather than contradictory, and Copilot will sometimes confuse those.

## Example output

Made-up data, for illustration only.

```text
| Row | Guideline A | Guideline B |
| First-line | Drug X | Drug X |
| Second-line | Drug Y | Drug Z |

Disagreement: A and B differ on second-line choice. B does not mention monitoring intervals.
```
