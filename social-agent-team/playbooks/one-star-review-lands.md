# Playbook: One-star review lands

**Trigger:** Any 1–3 star review on Google, Facebook, Trustpilot, etc.

**Departments involved:** reviews-reputation, orchestrator

## Steps
1. Reviews & reputation reads the review and tags the issue (service, price, wait, product, unclear, fake).
2. Draft a calm reply using gbp-response.md: thank, own it, move it offline, no excuses, no customer details.
3. Save to queue/pending/ with `needs_owner: yes`. NEVER auto-publish.
4. Notify the owner in one sentence: who, what star, what issue, suggested reply ready.
5. If 3+ negative reviews in 48h → start reputation/crisis-protocol.md.

## Measure it
Reply time (target < 24h) and whether the reviewer updated the rating.

## Log it
Append to `logs/activity-log.md`: `date | reviews-reputation | playbook:one-star-review-lands | <files> | done`
