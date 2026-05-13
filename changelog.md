# Handbook Changelog

## 2026-05-13 — Closed all open items

### Resolved

- **incident-response.md** — IC responsibilities written in: explicit 5-duty list (owns bridge, sole decision-maker, notifies stakeholders, postmortem within 48h, declares resolved). Status → DONE
- **code-review.md** — SLA decided: 2h for P0/production/critical-path (auth, billing, payments-sdk), 1 business day for everything else. "UNRESOLVED" heading removed. Status → DONE
- **onboarding.md** — Doc ownership assigned to most recently onboarded engineer (currently Priya). She updates when stack changes, hands off to the next new hire. Status → DONE
- **reviewer-matrix-draft.md** — Finalized. Deadline set to Friday 2026-05-16 EOD. Feedback format: inline comments in the markdown files. Status → DONE

### Added

- **postmortem-template.md** — Stub template (timeline, root cause, impact, action items, lessons learned). Linked from incident-response.md
- **review-pack.md** — 1-page summary for senior engineers: what changed, decisions made, assignments, review instructions, deadline
- **review-pack.docx** — Word version of the review pack for offline reading

### Status

All six handbook sections are now DONE. Review round in progress — feedback due Friday 2026-05-16 EOD.

---

## 2026-05-12 — Session with agent

### Rewritten from scratch
- team-norms.md (previously scattered across 3 Notion pages)
- escalation-paths.md (previously only existed as a Slack pinned message)

### Substantially updated
- incident-response.md (roles defined, severity levels added)
- code-review.md (expectations written, PR template added)
- onboarding.md (30/60/90 added, buddy system documented)

### Lightly edited / already good
- decision-records.md (template was solid, added 2 example ADRs)

### Removed / consolidated
- Separate meeting-rules.md → merged into team-norms.md
- 4 redundant meeting rules removed
- "Communication charter" doc (was outdated and redundant with team-norms)
