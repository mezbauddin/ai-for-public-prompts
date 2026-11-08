# Turn ward round notes into a task list

**For:** Nurses and AHPs  
**Tool:** Microsoft 365 Copilot  
**Task:** Extract

## Prompt

```text
From the ward round notes below, produce a task list grouped by urgency: before lunch, today, this admission. For each task name the patient by bed number and initials, the action, and who owns it. Flag anything needing a doctor with [DR]. UK English.

Notes:
{paste}
```

## Why it works

Grouping by when it needs doing, not by patient, matches how a shift actually runs. The [DR] flag separates what you can crack on with from what needs escalating.

## Watch out

Bed numbers move. Confirm the board before you action anything time critical.
