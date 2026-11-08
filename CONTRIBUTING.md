# Contributing

Thanks for helping. The most useful thing you can tell me is what happened when you used a prompt in your real job.

## Never include real data

No patient details, staff details or anything from your organisation that isn't public. That goes for prompts, examples, issues and pull requests. Examples have to be made up. If you spot real data anywhere in this repo, open an issue without repeating the data and I'll take it down.

## What makes a good prompt here

- It solves a job someone in a UK public service really has.
- You've tried it and it worked.
- It says what the output should look like.
- It tells the model not to invent facts where that matters.
- It's in plain UK English.

## Adding or changing a prompt

Add a page under `prompts/<role>/` using the same headings as the others, add the matching entry to `prompts.json`, and link it from the README. Every prompt needs a 'Why it works' and a 'Watch out'.

If you're not comfortable with pull requests, open an issue instead and I'll add it for you.

## Corrections

If something's wrong, especially about data handling or licensing, please link to the source so I can check it.
