# 🔁 RUN IT EVERY WEEK

## The weekly loop (≈20 minutes of your time)
| Day | You do | Team does |
|---|---|---|
| Monday | type `/weekly-run` | collects signals, scores, briefs, drafts, fills the calendar, writes last week's report |
| Monday | type `/approve` and pick numbers | moves approved items to the queue |
| Tue–Sun | nothing (or `/playbook …` when something happens) | publishes, replies to reviews/DMs |
| Friday | `/status` (optional) | shows what went out |
Want it automatic? In Claude Code type `/loop` or ask *"schedule /weekly-run every Monday 9am"* (needs Claude Code scheduled tasks).

## Approvals, queues and the kill switch
- `queue/pending/` — waiting for **you**
- `queue/approved/` — cleared, will be published
- `queue/published/` — live, with links
- **Kill switch:** type `/kill-switch ON` and every agent stops. `/kill-switch OFF` to restart. (It just writes ON/OFF into the `KILL_SWITCH` file.)
- **Activity log:** `logs/activity-log.md` lists every action, who did it and when.

## Measuring what it earns
Results & ROI fills `brand-os/reporting/weekly-report-template.md` each week and records each post/ad in `roi-attribution.md`.
The key numbers: **leads, bookings/sales, spend, cost per lead, revenue ÷ cost**. If you only look at one thing, look at *"Needs the owner"* and *"Top 3 lessons."*
