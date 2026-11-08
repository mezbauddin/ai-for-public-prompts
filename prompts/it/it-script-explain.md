# Explain an unfamiliar script before you run it

**For:** IT teams  
**Tool:** Copilot Chat  
**Task:** Analyse

## Prompt

```text
Explain what the script below does, line by line in plain English. UK English. At the end, flag anything destructive, anything that touches production data, anything that needs elevated rights, and anything that looks unsafe or unclear. Do not run anything, just explain.

Script:
{paste}
```

## Why it works

Getting a plain-English read before you run an inherited script catches the destructive line you would otherwise miss. The safety flags at the end are the bit that saves you.

## Watch out

The explanation is a second opinion, not a guarantee. Never run something against production on the strength of an LLM read alone.
