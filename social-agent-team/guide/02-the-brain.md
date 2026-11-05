# 🧠 THE BRAIN

## CLAUDE.md: the rules every agent follows
`CLAUDE.md` sits in the project's main folder. Claude Code reads it automatically every time. It says:
who's in charge, never publish without passing the approval bar, never exceed budget, never invent facts,
log everything, obey the kill switch, and always feed results back into signals. Edit it in any text editor if you want to change a rule.

## The Orchestrator agent
File: `.claude/agents/orchestrator.md`. *An "agent" here is a text file with instructions that Claude follows as a specialist.*
For every event it does six things: **Collects → Scores → Briefs → Drafts → Schedules → Approves.**
Scoring: each signal gets impact, urgency and effort (1–10). Priority = impact × urgency ÷ effort. Top 5 get worked on.
It escalates to you only for budget, complaints/crisis, positioning changes, or disagreements.

## Owner inputs: voice, budget, approval bar, positioning
These four are **human-led and not automated**. They live in `brand-os/brand-brain/`:
| Input | File | Example |
|---|---|---|
| Brand voice | voice-guide.md | "Warm, expert, no slang" |
| Budget cap | budget-and-approval.md | "Max $300/month on boosts" |
| Approval bar | budget-and-approval.md | "Offers and bad reviews need me" |
| Positioning | positioning.md | "The only same-day dentist in Pune" |
Run `/setup-brand` any time to redo them.
