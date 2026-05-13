# Handbook Refresh — Review Pack

_For: Meng, Rafael, Emma, Jonas | From: Lukas | Date: 2026-05-13_

## What happened

We rebuilt the engineering handbook from scattered Notion pages into a single repo. Six sections, all now written and decisions locked.

## What changed

- **team-norms.md** — Consolidated from 3 Notion pages, removed 4 redundant meeting rules, folded meeting-hygiene into this doc
- **decision-records.md** — ADR template + 3 examples added
- **escalation-paths.md** — New 2-tier escalation structure (Jonas's design)
- **onboarding.md** — 30/60/90 framework, buddy system, first-week checklist. Priya now owns keeping this doc current
- **incident-response.md** — Severity levels, explicit IC duties (IC owns the bridge, sole decision-maker, writes postmortem within 48h, declares resolved). Postmortem template added
- **code-review.md** — Review expectations, PR template. SLA decided: **2h for P0/production/critical-path, 1 business day for everything else**

## Decisions now locked

| Decision | Resolution |
|----------|------------|
| IC responsibilities | Explicit 5-duty list — IC has full authority, not just coordination |
| Code review SLA | Option B: 2h for P0/production/critical-path, 1 business day for the rest |
| Onboarding doc owner | Most recently onboarded engineer (currently Priya) |
| Writing style | Plain English, bullet points, example-driven. No buzzwords |

## Your review assignments

| Section | Primary | Secondary |
|---------|---------|-----------|
| team-norms.md | Meng | — |
| decision-records.md | Emma | — |
| incident-response.md | Rafael | Lukas |
| onboarding.md | Meng | Jonas |
| code-review.md | Rafael | Emma |
| escalation-paths.md | Jonas | — |

## How to review

- **Deadline: Friday 2026-05-16, end of day**
- Read your assigned sections in the repo
- Focus on accuracy, missing edge cases, anything that would confuse a new hire
- Leave comments directly in the markdown files using this marker:

```
> **[REVIEW — Your Name]:** Your comment here
```

- Flag disagreements — we'll resolve async before locking
- Lukas signs off on everything after this review round
