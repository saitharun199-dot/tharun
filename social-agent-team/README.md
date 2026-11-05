# AI-Native Social Media Agent Team
A ready-to-run Claude Code project: 1 orchestrator + 8 department agents + 8 playbooks + 27 Brand OS templates + a visual dashboard.

**New here? Read [`guide/01-start-here.md`](guide/01-start-here.md).**

| Guide | |
|---|---|
| 🚀 [Start here](guide/01-start-here.md) | what it does, 7 zones, install, first run |
| 🧠 [The brain](guide/02-the-brain.md) | CLAUDE.md, orchestrator, owner inputs |
| 🏢 [8 departments](guide/03-departments.md) | |
| ⚡ [8 playbooks](guide/04-playbooks.md) | |
| 📁 [Brand OS](guide/05-brand-os.md) | 27 templates |
| 🧰 [Tools](guide/06-tools.md) | every tool, by zone |
| 🔁 [Weekly loop](guide/07-weekly-loop.md) | approvals, kill switch, ROI |

## Commands (type inside Claude Code)
`/setup-brand` · `/weekly-run` · `/playbook <what happened>` · `/approve` · `/status` · `/kill-switch ON|OFF`

## Folder map
```
CLAUDE.md            rules every agent follows
.claude/agents/      orchestrator + 8 departments
.claude/commands/    the slash commands above
playbooks/           8 "when something happens" recipes
brand-os/            27 templates = brand memory
queue/               pending → approved → published
logs/                activity log
dashboard/index.html visual control room (open in a browser)
guide/               the user guide
```
