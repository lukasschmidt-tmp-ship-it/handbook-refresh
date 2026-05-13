# Handbook Refresh — Review Pack

_For: Meng, Rafael, Emma, Jonas | From: Lukas | 2026-05-13_

## What this is

- We moved the engineering handbook out of scattered Notion pages into one repo
- Six sections, all written, all decisions made
- **Repo:** [lukasschmidt-tmp-ship-it/handbook-refresh](https://github.com/lukasschmidt-tmp-ship-it/handbook-refresh)
- I need each of you to review your assigned sections before we lock it

## What changed

- **team-norms.md** — rebuilt from 3 Notion pages, cut 4 redundant meeting rules, folded meeting-hygiene in
- **decision-records.md** — ADR template + 3 examples
- **escalation-paths.md** — 2-tier structure (Jonas's design)
- **onboarding.md** — 30/60/90 plan, buddy system, first-week checklist. Priya owns keeping this doc current going forward
- **incident-response.md** — severity levels, IC duties spelled out (owns the bridge, sole decision-maker, writes postmortem within 48h, declares resolved). Postmortem template added
- **code-review.md** — review expectations, PR template, SLA: **2h for P0/production/critical-path, 1 business day for everything else**

## Decisions made

| What | Answer |
|------|--------|
| IC responsibilities | Explicit list — IC has full authority, not a coordination role |
| Code review SLA | 2h for P0/production/critical-path, 1 business day for the rest |
| Onboarding doc owner | Most recently onboarded engineer (Priya right now) |
| Writing style | Plain English, bullet points, examples. No jargon |

## Your assignments

| Section | Primary | Secondary |
|---------|---------|-----------|
| team-norms.md | Meng | — |
| decision-records.md | Emma | — |
| incident-response.md | Rafael | Lukas |
| onboarding.md | Meng | Jonas |
| code-review.md | Rafael | Emma |
| escalation-paths.md | Jonas | — |

## What to do

1. Open the repo: [handbook-refresh](https://github.com/lukasschmidt-tmp-ship-it/handbook-refresh)
2. Read your assigned files
3. For each thing you'd change, add a comment directly in the markdown file using this format:

```
> **[REVIEW — Your Name]:** Your comment here
```

4. Look for:
   - Anything wrong or outdated
   - Edge cases we missed
   - Anything that would confuse a new hire reading this on day one
   - Anything you disagree with

5. **Due: Friday 2026-05-16, end of day**

## What happens after

- I'll go through all comments next week
- If there are disagreements, I'll start a Slack thread to sort them out
- Once resolved, we lock the files and this becomes the handbook
