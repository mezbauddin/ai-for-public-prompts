# Summarise team absence trends

**For:** HR  
**Tool:** Microsoft 365 Copilot  
**Task:** Analyse

## Prompt

```text
Look at the absence data attached. Summarise: total days lost this quarter vs last, top three reason categories, any individuals with more than {n} episodes, and any pattern by day of week. Output as short bullets. Do not name individuals, just initials.
```

## Why it works

Asking for initials only sets the privacy ground rules in the prompt itself, rather than relying on you to redact after.

## Watch out

Even initials can be identifying in a small team. If you forward the summary, swap initials for "Person A, Person B".

## Example output

Made-up data, for illustration only.

```text
- Days lost: 84 this quarter, up from 71.
- Top reasons: coughs and colds, stress, musculoskeletal.
- More than 3 episodes: AB, CD.
- Pattern: Mondays slightly higher.
```
