# Summarise a discharge summary for a busy clinic

**For:** Clinicians  
**Tool:** Copilot Chat  
**Task:** Summarise

## Prompt

```text
Summarise the discharge letter below in three sections. 1) One sentence on what happened in hospital. 2) Bullet list of changes to medication, with old dose and new dose where given. 3) Bullet list of follow-up actions and who is responsible. UK English. Do not add information that is not in the letter.

Letter:
{paste}
```

## Why it works

The three-section frame matches how clinicians actually read a discharge. Asking for old and new dose surfaces the most common transcription error.

## Watch out

Strip identifiers before pasting, whichever Copilot you use, and follow your trust's IG policy. Sign in with your work account, never a personal one, so enterprise data protection applies.

## Example output

Made-up data, for illustration only.

```text
1) Admitted with a chest infection, treated and now stable for discharge.
2) Medication changes:
- Amlodipine increased from 5mg to 10mg
- Course of antibiotics added for 5 days
3) Follow-up:
- GP to recheck blood pressure in 2 weeks (GP)
- Chest clinic review in 6 weeks (hospital)
```
