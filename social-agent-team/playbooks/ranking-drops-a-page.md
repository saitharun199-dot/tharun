# Playbook: Ranking drops a page

**Trigger:** A tracked page falls 10+ positions (about one Google page).

**Departments involved:** search-visibility, content-engine, orchestrator

## Steps
1. Search visibility checks: is the page still live? any technical error? new competitor page?
2. Compare our page to the top 3 results: length, freshness, questions answered.
3. Content engine drafts an update: refresh dates, add missing questions, add FAQs.
4. Technical fixes (site code) → queue/pending/ for owner or web person.
5. Re-check ranking in 14 days and log result.

## Measure it
Position recovered within 30 days.

## Log it
Append to `logs/activity-log.md`: `date | search-visibility | playbook:ranking-drops-a-page | <files> | done`
