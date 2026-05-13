# Recent Session Context — Engineering Handbook Refresh

_This file captures the state from our last session so we can pick up without re-explaining._

## What we built

Lukas and the agent rebuilt the team engineering handbook from fragmented Notion pages. All files live in this repo (lukasschmidt-tmp-ship-it/handbook-refresh).

### Section status
| File | Status | Notes |
|------|--------|-------|
| team-norms.md | DONE | Consolidated from 3 Notion pages. 4 redundant meeting rules removed. |
| decision-records.md | DONE | Template + 3 example ADRs added. Emma asked to own this section. |
| escalation-paths.md | DONE | 2-tier structure. Jonas suggested the structure. |
| onboarding.md | MOSTLY DONE | 30/60/90 added, buddy system documented. Open: who owns updating it when stack changes? Currently Lukas by default. |
| incident-response.md | IN PROGRESS | Roles defined, severity levels added. IC responsibilities are too vague ("coordinates response"). Needs explicit duties. |
| code-review.md | IN PROGRESS | Expectations written, PR template added. SLA is unresolved. |

## Unresolved items (must close this session)

### 1. Incident Commander (IC) responsibilities
Current text is too vague. Agreed it needs to be explicit. Draft duties:
- IC owns the bridge call — opens it, runs it, closes it
- IC is the sole decision-maker during the incident (no committee)
- IC notifies stakeholders before closing the bridge
- IC writes the postmortem within 48h of resolution
- IC declares the incident resolved

### 2. Code review SLA
Three options were discussed:
- **Option A:** Flat 1 business day for all PRs — simple, no prioritization needed
- **Option B:** 2h for P0/production PRs + 1 business day for everything else — better for incidents, slightly more complex
- **Option C:** No fixed SLA, just "reasonable time" — flexible but creates ambiguity

Leaning toward Option B. Needs to be decided and written in.

### 3. Reviewer matrix
Draft exists (reviewer-matrix-draft.md) but not finalized or sent. Proposed assignments:
- Meng: team-norms.md, onboarding.md
- Rafael: incident-response.md, code-review.md
- Emma: decision-records.md
- Jonas: escalation-paths.md
- Lukas signs off everything

## Decisions already locked
- Policy language: concise + example-driven, no heavy process layer
- meeting-hygiene.md folded into team-norms.md
- Lukas's writing preference: plain English, no buzzwords ("leverage", "synergy" etc.), bullet points over paragraphs

## What Lukas wants today
1. Close all three unresolved items above
2. A review pack he can send to the senior engineers today — 1-page summary of what changed, the decisions now resolved, and the reviewer matrix with a deadline

## Lukas's context
- Engineering Manager, fully remote in Berlin
- Team: 8 engineers — Meng, Rafael, Emma, Jonas, Priya, Tobias, Sven + Lena (contract QA)
- First meeting 9:30am CET, evenings protected for family after 18:00
- Prefers durable docs over chat-only agreements
- Works in short windows so wants decisions made, not re-opened
