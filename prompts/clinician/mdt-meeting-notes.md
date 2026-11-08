# Pull actions out of MDT meeting notes

**For:** Clinicians  
**Tool:** Microsoft 365 Copilot  
**Task:** Extract

## Prompt

```text
From the MDT notes below, produce a table with four columns: Patient initials, Decision, Action, Owner. One row per patient. If owner is not named, write [unassigned]. Below the table, list any patients where the plan is still open.

Notes:
{paste}
```

## Why it works

Structured output as a table is what Copilot is genuinely good at. The unassigned flag forces the meeting chair to chase up the gaps.

## Watch out

Patient initials only. Never paste full names or NHS numbers into a chat session that is not inside your tenant.

## Example output

Made-up data, for illustration only.

```text
| Initials | Decision | Action | Owner |
| AB | For surgery | Add to list | Mr Patel |
| CD | Needs scan | Request MRI | [unassigned] |

Still open: CD, pending MRI before a plan can be agreed.
```
