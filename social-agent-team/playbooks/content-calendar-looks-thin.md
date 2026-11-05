# Playbook: Content calendar looks thin

**Trigger:** Fewer than 5 scheduled items in the next 7 days.

**Departments involved:** orchestrator, content-engine, creative-studio, publishing-social

## Steps
1. Orchestrator lists empty days in content-calendar.md.
2. Pull ideas from: demand-signals-log.md, FAQs, recent 5-star reviews, last month's best posts.
3. Content engine drafts posts so each empty day has one, spread across content pillars.
4. Creative studio adds image prompts. Publishing assigns times from hashtag-and-timing.md.
5. Routine posts → queue/approved/.

## Measure it
Days with at least one post (target 7/7).

## Log it
Append to `logs/activity-log.md`: `date | orchestrator | playbook:content-calendar-looks-thin | <files> | done`
