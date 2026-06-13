# NexGenData Agent Skills

Open-standard ([agentskills.io](https://agentskills.io)) skills that teach AI coding agents (Claude Code, Cursor, Gemini CLI, +50 more) how to use NexGenData's Apify Actors for niche public-data intelligence. Each skill routes an agent to the right Actor and runs it on the user's own Apify account.

## Skills
| Skill | What it does |
|---|---|
| [`apify-sec-regulatory-intelligence`](skills/apify-sec-regulatory-intelligence/SKILL.md) | U.S. SEC + global financial-regulator filings: insider trades, 8-K events, 13F, activist 13D/G, Form D, NT, fund holdings, SEC litigation, FINRA, and global regulators (FINMA/MAS/SFC/SEBI/ASIC/EDINET). |

*(Roadmap: APAC company & financial data, IP/trademarks & patents, global finance & markets, hiring & compensation, B2B lead-gen pipeline — one quality skill at a time.)*

## Install
```bash
npx skills add TheNextGenNexus/agent-skills
```
Pick the skill and your agent. Requires an [Apify account](https://apify.com) + token (`apify login` or `APIFY_TOKEN`).

## Strategy
See `../agent-skills-strategy-2026-06-13.md` for the full portfolio plan, sequencing, and the GitHub-compliance discipline (one genuine PR at a time — never bulk).
