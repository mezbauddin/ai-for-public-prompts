# Pull actions and chase owners after a meeting

**For:** Project and programme managers  
**Tool:** Microsoft 365 Copilot  
**Task:** Extract

## Prompt

```text
From the meeting notes or transcript below, extract every action into a table: Action, Owner, Due date, Status (default "not started"). Then draft a short, friendly group email listing each person's actions under their name, with due dates, asking them to confirm. UK English. If an owner or date is missing, flag it as [TBC] rather than guessing.

Notes:
{paste}
```

## Why it works

Doing the extraction and the chaser email in one pass is the real time saver. The [TBC] flags stop it quietly inventing owners and deadlines.

## Watch out

Read the action wording before sending. A transcript often records a half-formed idea as a firm commitment.
