# Triage a backlog of clinic emails

**For:** Admin teams  
**Tool:** Microsoft 365 Copilot  
**Task:** Analyse

## Prompt

```text
Look at my unread emails from the last seven days. For each one, give me: subject, who from, one-line summary, and a recommended action from this list: Reply today, Reply this week, FYI no reply, Forward to {name}, Archive. Sort with "Reply today" at the top.
```

## Why it works

Constraining the action to a short list is the bit that turns a vague summary into a workable list. M365 Copilot can actually read your inbox, which is the only reason this prompt works.

## Watch out

It only sees emails your account can see. If you have shared mailboxes set up oddly, double check the scope before trusting the list.
