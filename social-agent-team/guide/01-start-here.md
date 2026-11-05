# 🚀 START HERE

## What this system does (and what it hands you)
It is a team of AI helpers ("agents") that run your social media and online marketing the way a small agency would.
Every week it hands you:
- A **filled content calendar** (posts for every day)
- **Ready-to-post drafts** in the approval queue (`queue/`)
- **Replies** to reviews and messages, drafted in your voice
- A **one-page weekly report**: what was posted, what it earned, what to do next
You only approve the risky things (money, complaints, offers). Routine work runs on its own.

## How the system works: the 7 zones
| # | Zone | Plain meaning |
|---|---|---|
| 1 | **Signals** | Where news comes from: Google searches, website visits, reviews, mentions |
| 2 | **System of record** | Your customer list, calendar, brand files — one place for facts |
| 3 | **The Brain** | Claude (the AI) that reads, thinks and writes |
| 4 | **Knowledge layer (Brand OS)** | 27 template files = your brand's memory and rules |
| 5 | **Orchestrator** | The team lead: decides what matters and who does it |
| 6 | **8 Departments** | Specialists: search, market, content, creative, publishing, reviews, leads, results |
| 7 | **Engage + Data** | Posts go out; numbers come back; results feed the next week's signals |
Plus **Owner input** (you: voice, budget, approval bar, positioning) and **interrupts** (8 playbooks for surprises).

## What you need before you start
1. A computer (Mac, Windows or Linux).
2. A **Claude account** with Claude Code access (Pro or Max plan) — claude.ai.
3. **Claude Code** installed. *Claude Code = Claude that can read and write files in a folder on your computer.*
4. This project folder (download from GitHub — see below).
5. Optional, later: accounts for tools like Metricool, Canva, Google Search Console. You can start without any.

## Install the project in Claude Code
**Term: "Terminal"** = a window where you type commands. Mac: press ⌘+Space, type *Terminal*. Windows: Start → *PowerShell*.

1. Install Claude Code — paste this into Terminal and press Enter:
   - Mac/Linux: `curl -fsSL https://claude.ai/install.sh | bash`
   - Windows: `irm https://claude.ai/install.ps1 | iex`
2. Download this project: on GitHub open the repo → green **Code** button → **Download ZIP** → unzip it.
3. In Terminal, go into the folder. Type `cd ` (with a space), drag the `social-agent-team` folder into the window, press Enter.
4. Type `claude` and press Enter. Log in when asked.
   Claude now automatically reads `CLAUDE.md` (the team rules).
   *Prefer no terminal? The Claude desktop app → Code tab → open the folder does the same.*

## Your first run, end to end
Type these one at a time into Claude Code:
1. `/setup-brand` — Claude interviews you and fills your voice, positioning, audience and budget (≈15 min).
2. Open `brand-os/conversation/faq-library.md` and `brand-os/signals-seo/competitor-watchlist.md` and fill what you know (or ask Claude: *"help me fill the FAQ library"*).
3. `/weekly-run` — the orchestrator runs the whole team once.
4. `/approve` — review anything waiting for you.
5. `/status` — see what's queued and what happened.
6. Open `dashboard/index.html` in your browser to see everything visually.
