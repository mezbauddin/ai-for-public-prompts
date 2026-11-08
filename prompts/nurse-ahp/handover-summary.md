# Build a handover summary from shift notes

**For:** Nurses and AHPs  
**Tool:** Microsoft 365 Copilot  
**Task:** Summarise

## Prompt

```text
Turn the shift notes below into an SBAR handover for the next shift. Keep under 200 words. UK English. If observations are mentioned, group them together. Flag anything outstanding at the top under "needs attention this shift".

Notes:
{paste}
```

## Why it works

SBAR is the format people already know. The "needs attention" prefix makes sure the urgent stuff is the first thing the next nurse reads.

## Watch out

Read every line before passing on. Handover is the single most clinically risky bit of communication you do, and an LLM is not an authority on what matters.
