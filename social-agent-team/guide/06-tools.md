# 🧰 EVERY TOOL, BY ZONE
You do **not** need any of these to start. Add them one by one as the business grows.
*"Connecting" a tool* in Claude Code = adding an **MCP connector** (a plug that lets Claude read/post in that app). In the Claude app: Settings → Connectors. Many tools also allow simple CSV export you can drop into the folder.

## Canva — connected ✅
The Creative studio agent creates designs straight into your Canva account, in a folder called **Agent Team – Drafts**, and puts the edit link in each queue item.
- **Using the Claude app or claude.ai/code:** already connected (Settings → Connectors → Canva).
- **Using Claude Code on your own computer:** sign in with the same Claude account and the Canva connector comes along. If it doesn't show up, type this in Terminal once, then follow the Canva sign-in page that opens:
  `claude mcp add --transport http canva https://mcp.canva.com/mcp`
- **Check it works:** in Claude Code type *"Use the creative-studio agent to list my Canva brand kits."*
- Agents never delete or change your existing designs and never share or publish anything from Canva without your approval.

## Metricool: connected ✅ (YouTube + Instagram)
- Results & ROI reads your real numbers every week. First snapshot: `brand-os/reporting/reports/2026-11-05_baseline.md`.
- Publishing & social can see best posting times and, after your OK, schedule approved posts.
- Test it any time: *"Use Metricool to show my YouTube subscribers and Instagram followers."*

## The tool map
| Zone | Tools |
|---|---|
| Signals | Google Search Console, GA4, Semrush, Google Business Profile reviews, Facebook/Instagram Insights, LinkedIn analytics, YouTube analytics, web mentions |
| System of record | HubSpot CRM, content calendar, brand asset drive (Google Drive), brand wiki (Notion), Segment CDP, publish calendar |
| Brain | Claude (reasoning & writing), agent runner (Claude Code / LangGraph), memory store (these files, or pgvector later), Midjourney visuals, voice-over, transcription |
| Search & market | Semrush, Brand24, SparkToro, Similarweb, Google Alerts, Ahrefs, site crawler |
| Content & creative | Claude, Surfer, Frase, Grammarly, Canva, Midjourney, Remotion, Figma, ElevenLabs |
| Publishing, reviews & leads | Metricool, WordPress, GBP posts, Meta, LinkedIn, TikTok, Podium, NiceJob, ManyChat, HubSpot, Twilio, Calendly, Front |
| Data & observability | Airbyte, dbt, BigQuery, Looker Studio, Vercel, Sentry, feature flags |

## Cheapest starter stack (free or low cost)
Claude Code + Google Search Console + Google Business Profile + Metricool (free tier) + Canva (free) + a Google Sheet for results.
