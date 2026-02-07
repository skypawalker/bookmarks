# AI & Research

## 2026-02-03

### Building a Fleet of Vertical Agents with Claude Code
**Author:** @alxfazio (alex fazio)  
**Link:** https://x.com/alxfazio/status/2018744471857279438  
**Saved:** 2026-02-07

A comprehensive thread about building "droids" - vertical agents where each gets its own full computer (100GB disk, 8GB RAM, ~600ms wake). Built entirely on Claude Code CLI using Sprites for near-$0 idle compute with auto-hibernation. Key innovations:

- Each droid lives in a Discord forum channel with isolated sessions
- Hatchable from base config using a "droid hatcher" (like Telegram's BotFather)
- Multiple people can interact concurrently
- Full machine ownership (not containers) - agents can self-improve and edit their own code
- Supports third-party model providers (GLM 4.7 for cost efficiency)
- SSH-accessible for full auditability
- Contractors can bring their own API keys

Author chose this over OpenClaw (too opinionated) and Claude Agent SDK (too high-level). The goal: safer alternative to Claude CoWork with full isolation.

---

## 2026-01-31

### Claude Code Tips from the Team
**Author:** @bcherny (Boris Cherny)  
**Link:** https://x.com/bcherny/status/2017742741636321619  
**Saved:** 2026-02-07

Boris (creator of Claude Code) shares team tips for using Claude Code effectively. Key reminder: there's no one "right way" - everyone's setup is different. Thread includes practical insights from the Claude Code team on workflows and best practices.

**Engagement:** 49.4K likes, 5.6K retweets - highly valuable resource

---

## 2026-02-01

### China's AI Talent Pipeline
**Author:** @zijing_wu (Zijing Wu)  
**Link:** https://x.com/zijing_wu/status/2017820158174408794  
**Saved:** 2026-02-07

FT Magazine feature exploring how China has systematically built a vast pipeline of AI talent through pivotal education programs. Combines investigative reporting with personal reflections on the genius plan behind China's AI dominance.

---

## 2026-01-09

### Code-Simplifier Agent Open Sourced
**Author:** @bcherny (Boris Cherny)  
**Link:** https://x.com/bcherny/status/2009450715081789767  
**Saved:** 2026-02-07

Claude Code team open-sourced their code-simplifier agent. Install with:
```
claude plugin install code-simplifier
```

Or from within a session:
```
/plugin marketplace update claude-plugins-official
/plugin install code-simplifier
```

Use it at the end of long coding sessions or to clean up complex PRs.

**Engagement:** 13K likes, 1.1K retweets

---

## 2026-01-08

### Agent Files: Markdown/JSON Agent Definitions
**Author:** @hwchase17 (Harrison Chase)  
**Link:** https://x.com/hwchase17/status/2009388479604773076  
**Saved:** 2026-02-07

Agents are now just defined by markdown/json files:
- System prompt
- Subagents in subagents/ folder
- Tools via tools.md + mcp.json

Simple, declarative agent architecture that's easy to version and share.

---

## 2026-01-07

### How to Keep Up with Gen AI News
**Author:** @pamelafox (Pamela Fox)  
**Link:** https://x.com/pamelafox/status/2008957358773555234  
**Saved:** 2026-02-07

Updated blog post on staying current with gen AI developments. Recommended follows:
- @simonw
- @GergelyOrosz
- @HamelHusain
- @intellectronica
- @isaac_flath
- @GaryMarcus

Full guide: https://blog.pamelafox.org/2024/08/how-i-learn-gen-ai.html

---
