# Incident Response

_Last updated: 2026-05-12 | Status: IN PROGRESS — IC responsibilities need tightening_

## Roles

### Incident Commander (IC)
The IC coordinates the response. [VAGUE — needs explicit ownership language]

Responsibilities: coordinates response, keeps the team focused.

### Comms Lead
Owns external communication. Updates the status page, drafts customer-facing messages, notifies account team if enterprise customers are affected.

### Scribe
Keeps a live incident log. Records decisions, timeline, and action items in the incident doc.

## Severity levels

| Level | Definition | Response time |
|-------|------------|---------------|
| P0 | Complete outage, data loss risk | Immediate |
| P1 | Major feature degraded, significant user impact | 15 min |
| P2 | Minor feature degraded, workaround exists | 2h |
| P3 | Cosmetic issue, low user impact | Next sprint |

## Process

1. Anyone can declare an incident — pull in the IC and open an incident doc
2. IC calls a bridge if needed
3. Comms lead posts first update within 15 min of P0/P1
4. Postmortem required for all P0 and P1 incidents
5. Postmortem template is in Notion

## Unresolved
- How explicit should IC responsibilities be? Current language ("coordinates response") is too vague. Options: explicit list of IC duties, or keep lightweight and trust the IC to figure it out.
