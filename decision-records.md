# Decision Records

_Last updated: 2026-05-12 | Status: DONE_

## Why we use decision records
We write down significant technical and process decisions so future team members (and future us) understand why something is the way it is, not just what it is.

A decision record is not a design doc. It's short, opinionated, and written after the decision is made.

## Template

```
## ADR-NNN: [Short title]
Date: YYYY-MM-DD
Status: [Proposed | Accepted | Deprecated | Superseded by ADR-NNN]
Deciders: [Names]

### Context
What was the problem? Why did we need to make a decision?

### Decision
What did we decide?

### Consequences
What does this mean going forward? What are the trade-offs?
```

## Example records

### ADR-001: Use Stripe API version 2024-04-10
Date: 2024-04-15 | Status: Accepted | Deciders: Lukas, Rafael

**Context:** We needed to pin a Stripe API version to avoid unexpected breaking changes in webhooks.
**Decision:** Pin to 2024-04-10. Reviewed quarterly.
**Consequences:** Must explicitly upgrade when new Stripe features are needed. Adds a quarterly review task.

### ADR-002: No dedicated QA environment
Date: 2025-01-10 | Status: Accepted | Deciders: Lukas

**Context:** Maintaining a separate QA environment was taking significant infra time.
**Decision:** Drop QA environment. Use feature flags + staging + automated tests.
**Consequences:** Higher bar for test coverage on all PRs. Staging is now the final pre-prod gate.

### ADR-003: Async-first communication default
Date: 2025-03-01 | Status: Accepted | Deciders: Full team

**Context:** Too many decisions were being made informally in Slack and then forgotten or re-litigated.
**Decision:** All decisions go in Linear, GitHub, or the handbook. Slack is for questions and signals.
**Consequences:** Slightly more friction per decision, significantly fewer "wait, when did we decide that?" moments.
