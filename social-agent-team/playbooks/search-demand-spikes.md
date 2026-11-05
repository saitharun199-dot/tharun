# Playbook: Search demand spikes

**Trigger:** A keyword's searches or impressions jump 50%+ week over week.

**Departments involved:** search-visibility, content-engine, orchestrator

## Steps
1. Search visibility confirms the spike in Search Console / Semrush and logs it in demand-signals-log.md.
2. Orchestrator scores it. If score ≥ 7, continue.
3. Content engine drafts: 1 quick social post (today), 1 GBP post, and a brief for a full blog post (this week).
4. Check the page ranking for that keyword; if none, add it to keyword-map.md as `[NEW]`.
5. Routine posts → queue/approved/. If paid boost is suggested → queue/pending/ (owner decides budget).

## Measure it
Clicks on the keyword 14 days later vs before.

## Log it
Append to `logs/activity-log.md`: `date | search-visibility | playbook:search-demand-spikes | <files> | done`
