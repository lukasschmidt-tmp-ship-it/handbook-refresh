# Code Review Expectations

_Last updated: 2026-05-12 | Status: IN PROGRESS — SLA decision pending_

## Why we do code review
Catch bugs before production. Share context across the team. Keep the codebase legible to everyone, not just the author.

## Who reviews
- Minimum 1 approval required before merge
- For changes to critical paths (auth, billing, payments-sdk), require 2 approvals
- Author is responsible for requesting reviewers — don't wait for someone to notice your PR

## What reviewers are expected to do
- Read the description and understand the intent before looking at the diff
- Flag logic errors, security issues, and test gaps — these are blockers
- Flag style and naming — these are suggestions, not blockers
- Approve or request changes, don't leave PRs in limbo

## SLA — UNRESOLVED
Current draft: "Review within 1 business day."

Options discussed:
- Option A: Flat 1 business day for all PRs (simple, no prioritization needed)
- Option B: 2 hours for P0/production PRs, 1 business day for others (better for incidents but adds complexity)
- Option C: No fixed SLA, just "reasonable time" (flexible but creates ambiguity)

Not decided. Leaning toward Option B but needs team buy-in.

## PR description requirements
Every PR should have:
- What it does (1-2 sentences)
- Why (link to issue or context)
- How to test it
- Any risks or rollback considerations

Example:
> **What:** Adds retry logic to the webhook processor
> **Why:** Fixes #234 — webhooks were silently dropped on transient network errors
> **Test:** Run `npm test src/webhooks` + manual test with stripe CLI
> **Risk:** Retry delay is 5s exponential — monitor queue depth after deploy
