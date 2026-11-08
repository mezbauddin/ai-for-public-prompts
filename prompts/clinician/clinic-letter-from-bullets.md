# Turn clinic note bullets into a GP letter

**For:** Clinicians  
**Tool:** Microsoft 365 Copilot  
**Task:** Draft

## Prompt

```text
Draft a GP letter from the bullet points below. Tone: courteous, professional, NHS letter convention. Use UK English. Start with a one-line summary of the diagnosis. End with a clear plan with bullet points for the GP. Keep under 300 words. Do not invent investigations or medications. If something is unclear, leave it as [TO CONFIRM].

Bullet points:
{paste your notes}
```

## Why it works

Naming the convention and the length stops it waffling. The "do not invent" line cuts hallucination on meds and tests, which is the dangerous failure mode here.

## Watch out

Always read the whole letter before sending. Drug doses and follow-up intervals are the two things to double check every time.

## Example output

Made-up data, for illustration only.

```text
Dear Dr Smith,

Mr Jones was seen in clinic today with stable angina, well controlled on current treatment.

Plan for you:
- Continue current medication, review in 6 months
- Repeat lipid profile before next review
- [TO CONFIRM] whether a recent ECG is available

With thanks,
```
