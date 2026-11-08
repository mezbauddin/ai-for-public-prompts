# Draft a runbook from a fix you just did

**For:** IT teams  
**Tool:** Copilot Chat  
**Task:** Draft

## Prompt

```text
Turn the rough notes below into a clean runbook for the next engineer. UK English. Structure: symptom, prerequisites and access needed, numbered steps, how to verify it worked, and a rollback if it goes wrong. Flag any destructive step with a warning line. Keep commands exactly as I wrote them, do not "tidy" them.

Notes:
{paste}
```

## Why it works

A verify step and a rollback are what separate a runbook from a note to self. Telling it not to tidy commands stops it silently breaking your syntax.

## Watch out

Test the runbook on a non-live system before trusting it. Commands the model has reformatted can fail in subtle ways.
