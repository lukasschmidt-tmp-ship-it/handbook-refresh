# Incident Response

_Last updated: 2026-05-13 | Status: DONE_

## Roles

### Incident Commander (IC)

The IC owns the incident from declaration to resolution. This is not a coordination role — the IC has authority and accountability.

**IC duties:**

- Opens the bridge call, runs it, closes it — the IC owns the bridge
- Is the sole decision-maker during the incident (no committee, no consensus — the IC calls it)
- Notifies stakeholders before closing the bridge
- Writes the postmortem within 48 hours of resolution
- Declares the incident resolved

If the IC needs to hand off (e.g. end of day), they explicitly transfer all duties to the next IC. There is always exactly one IC.

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
2. IC opens a bridge call if needed
3. Comms lead posts first update within 15 min of P0/P1
4. Postmortem required for all P0 and P1 incidents — use the [postmortem template](postmortem-template.md) in this handbook
5. Postmortem is due within 48h of resolution, owned by the IC
