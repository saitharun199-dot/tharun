# Playbook: Competitor drops a promo

**Trigger:** Market radar spots a new discount, offer or campaign from a watched competitor.

**Departments involved:** market-radar, orchestrator, content-engine, creative-studio

## Steps
1. Market radar records: competitor, offer, channel, start/end date, screenshot link.
2. Orchestrator decides: ignore / counter with value / counter with offer.
3. Never match a price automatically. Any offer or discount → queue/pending/ for the owner.
4. Default response: a value post on our strengths from positioning.md (no competitor named).
5. Creative studio makes 1 visual; Publishing schedules within 48h once approved.

## Measure it
Our enquiries during their promo window vs normal week.

## Log it
Append to `logs/activity-log.md`: `date | market-radar | playbook:competitor-drops-a-promo | <files> | done`
