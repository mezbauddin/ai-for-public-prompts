# Ai for public prompts

TL;DR: 82 free, copy-and-paste AI prompts for people working in UK public services. Each one tells you why it works and what to check before you trust the answer. Pick your role below, copy a prompt, fill in the bits in `{curly brackets}`.

Most of these are written for Copilot Chat, because that's the one most public sector staff already have. They'll work in other assistants too, as long as your organisation allows them.

This library is new, and it hasn't had much real-world testing yet. If a prompt gives you a poor answer, I want to know. Open an issue and tell me what happened.

## Before you paste anything

- Don't paste patient-identifiable or staff-identifiable data unless your organisation's information governance rules say you can.
- Sign in with your work account. Never use a personal account for work content.
- Read every answer before you use it. You're responsible for what goes out, not the model.
- Clinical outputs are drafts. They aren't clinical advice, and they need checking by someone qualified.

## How each prompt is laid out

Every prompt has a page with the wording to copy, why it works and what to watch out for. Some have a worked example, and those use made-up data. If you'd rather have everything in one file, it's all in [`prompts.json`](prompts.json).

## The prompts

### Clinicians (8)

- [Turn clinic note bullets into a GP letter](prompts/clinician/clinic-letter-from-bullets.md)
- [Summarise a discharge summary for a busy clinic](prompts/clinician/summarise-discharge-letter.md)
- [Draft a plain-English patient info leaflet](prompts/clinician/patient-info-leaflet.md)
- [Pull actions out of MDT meeting notes](prompts/clinician/mdt-meeting-notes.md)
- [Compare two guidelines side by side](prompts/clinician/guideline-summary.md)
- [Draft a referral letter to another specialty](prompts/clinician/referral-letter-draft.md)
- [Build a differential checklist to think against](prompts/clinician/differential-checklist.md)
- [Explain a procedure for informed consent](prompts/clinician/consent-explainer.md)

### Nurses and AHPs (7)

- [Build a handover summary from shift notes](prompts/nurse-ahp/handover-summary.md)
- [Simplify a care plan for a family carer](prompts/nurse-ahp/care-plan-language.md)
- [Outline a training pack on a new procedure](prompts/nurse-ahp/training-pack-outline.md)
- [Draft survey questions for a small ward audit](prompts/nurse-ahp/audit-survey-questions.md)
- [Turn ward round notes into a task list](prompts/nurse-ahp/ward-round-actions.md)
- [Draft a falls or pressure risk assessment narrative](prompts/nurse-ahp/risk-assessment-prompt.md)
- [Draft a sensitive update message for a family](prompts/nurse-ahp/family-update-message.md)

### Admin teams (8)

- [Triage a backlog of clinic emails](prompts/admin/inbox-triage.md)
- [Minutes from a Teams transcript](prompts/admin/meeting-minutes-from-transcript.md)
- [Spot clashes in a draft rota](prompts/admin/rota-clash-check.md)
- [Personalise a standard response letter](prompts/admin/standard-response-letters.md)
- [Build an agenda from a one-line brief](prompts/admin/agenda-from-brief.md)
- [Draft a waiting list update letter](prompts/admin/waiting-list-letter.md)
- [Turn a messy list into a clean spreadsheet](prompts/admin/fax-to-spreadsheet.md)
- [Write a polite chaser without sounding annoyed](prompts/admin/polite-chaser-email.md)

### Finance (7)

- [Reconcile a supplier statement against ledger](prompts/finance/reconcile-supplier-statement.md)
- [Write a budget variance narrative](prompts/finance/budget-variance-narrative.md)
- [Generate cost improvement ideas for a service line](prompts/finance/cost-improvement-ideas.md)
- [Extract coding details from an invoice batch](prompts/finance/invoice-coding-extract.md)
- [Summarise a finance pack for non-finance readers](prompts/finance/finance-pack-summary.md)
- [Draft the skeleton of a business case](prompts/finance/business-case-skeleton.md)
- [Explain a purchase order query to a budget holder](prompts/finance/po-query-explain.md)

### HR (7)

- [Draft an inclusive job description](prompts/hr/job-description-draft.md)
- [Rewrite a policy into plain English](prompts/hr/policy-plain-english.md)
- [Build a competency-based interview pack](prompts/hr/interview-questions.md)
- [Summarise team absence trends](prompts/hr/absence-trend-summary.md)
- [Prepare for a difficult conversation](prompts/hr/difficult-conversation-prep.md)
- [Write a recruitment advert from a job description](prompts/hr/recruitment-advert.md)
- [Pull themes out of exit interview notes](prompts/hr/exit-interview-themes.md)

### Information governance (7)

- [First draft of a DPIA for a low-risk tool](prompts/ig/dpia-first-draft.md)
- [Draft a holding response to a SAR](prompts/ig/subject-access-response-draft.md)
- [Plain-English explainer of sensitivity labels](prompts/ig/sensitivity-label-guide.md)
- [Draft the narrative for a data incident report](prompts/ig/incident-report-narrative.md)
- [Draft a plain answer to a staff IG question](prompts/ig/ig-query-plain-answer.md)
- [Build a checklist before sharing data externally](prompts/ig/data-sharing-checklist.md)
- [Explain a records retention rule in plain English](prompts/ig/records-retention-explain.md)

### Project and programme managers (14)

- [Write a RAG status report from project notes](prompts/pm/pm-status-report.md)
- [Turn a brain-dump into a structured risk register](prompts/pm/pm-risk-register.md)
- [Draft a project brief or PID skeleton](prompts/pm/pm-project-brief.md)
- [Build a stakeholder map and engagement plan](prompts/pm/pm-stakeholder-map.md)
- [Pull actions and chase owners after a meeting](prompts/pm/pm-meeting-actions-chase.md)
- [Run a structured lessons learned review](prompts/pm/pm-lessons-learned.md)
- [Draft a benefits realisation plan](prompts/pm/pm-benefits-realisation.md)
- [Turn a detailed plan into a plan on a page](prompts/pm/pm-plan-on-a-page.md)
- [Draft a PRINCE2 exception report](prompts/pm/pm-exception-report.md)
- [Draft a PRINCE2 business case outline](prompts/pm/pm-business-case.md)
- [Draft an end stage report for stage boundary](prompts/pm/pm-end-stage-report.md)
- [Write a PRINCE2 product description](prompts/pm/pm-product-description.md)
- [Build a checkpoint report from team updates](prompts/pm/pm-checkpoint-from-updates.md)
- [Draft a work package to hand to a team](prompts/pm/pm-work-package.md)

### IT teams (8)

- [Draft a major incident update for users](prompts/it/it-incident-comms.md)
- [Summarise a long ticket thread for handover](prompts/it/it-ticket-summary.md)
- [Draft a runbook from a fix you just did](prompts/it/it-runbook-draft.md)
- [Write up a change request for CAB](prompts/it/it-change-request.md)
- [Explain an unfamiliar script before you run it](prompts/it/it-script-explain.md)
- [Turn an IT policy into a plain-English staff notice](prompts/it/it-policy-to-staff.md)
- [Clean and standardise a messy asset list](prompts/it/it-asset-data-clean.md)
- [Decode a vendor email and draft a reply](prompts/it/it-vendor-email-decode.md)

### Executive support (8)

- [Turn an executive inbox into a daily action list](prompts/ea/ea-inbox-to-actions.md)
- [Find and untangle diary clashes](prompts/ea/ea-diary-conflicts.md)
- [Build a pre-meeting brief for your exec](prompts/ea/ea-meeting-brief.md)
- [Draft a clean travel itinerary from booking emails](prompts/ea/ea-travel-itinerary.md)
- [Draft a reply in your executive’s voice](prompts/ea/ea-draft-reply-voice.md)
- [Check a board or committee pack is complete](prompts/ea/ea-board-pack-checklist.md)
- [Tidy rough minutes into a clean record](prompts/ea/ea-minutes-tidy.md)
- [Plan a realistic day around fixed commitments](prompts/ea/ea-prioritise-day.md)

### Anyone (8)

- [Explain a tech change to a non-technical board](prompts/general/explain-tech-to-board.md)
- [Tighten an email you have already written](prompts/general/email-tighten.md)
- [Translate clinical jargon for a colleague in a different team](prompts/general/translate-clinical-jargon.md)
- [Brief yourself for a meeting in 5 minutes](prompts/general/meeting-prep.md)
- [Get tough but fair feedback on a document](prompts/general/document-feedback.md)
- [Turn scrappy notes into a status update](prompts/general/turn-notes-into-update.md)
- [Pressure-test a decision before you commit](prompts/general/devils-advocate.md)
- [Decode an email full of acronyms](prompts/general/plain-english-acronym.md)

## Want to help?

Corrections and new prompts are welcome, especially from people who've tried these in a real job. [CONTRIBUTING.md](CONTRIBUTING.md) has the short version of how.

## Licence

[Creative Commons Attribution 4.0](LICENSE). Use it, change it and share it at work, as long as you credit the source.

## Who made this

I'm Mezba Uddin. I work in NHS IT, and I'm a Microsoft MVP and Microsoft Certified Trainer. You can find me on [LinkedIn](https://www.linkedin.com/in/mezbauddin/). The same prompts, plus a short course and role guides, are at [copilotforall.com](https://copilotforall.com).

This is an independent side project. It isn't affiliated with or endorsed by Microsoft, the NHS or my employer, and it doesn't represent any of their views.
