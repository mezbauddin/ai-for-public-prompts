# Write a RAG status report from project notes

**For:** Project and programme managers  
**Tool:** Copilot Chat  
**Task:** Draft

## Prompt

```text
Write a weekly highlight report from the notes below. UK English. Structure: overall RAG status with one-line justification, progress this week, planned for next week, risks and issues (each with an owner and a next action), and decisions needed from the board. Keep it to one page. Use the facts as given, do not invent progress or dates.

Notes:
{paste}
```

## Why it works

Forcing a one-line justification next to the RAG colour stops the status being a gut feeling. Separating "decisions needed" makes the report actionable rather than just informative.

## Watch out

You own the RAG rating, not the model. If it calls something green that you know is amber, override it. Check every date against the plan.
