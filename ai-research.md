# AI & Research

## 2026-01-07

### Kanban Workflow for Coding Agents
**Author:** @geoffreylitt (Geoffrey Litt)  
**Link:** https://x.com/geoffreylitt/status/2008735715195318397  
**Saved:** 2026-02-07 21:59 IST

Innovative workflow for managing coding agents on a kanban board. When an agent needs input, the task turns red to alert that it's blocked. You can respond directly on the card to unblock it. Seamless human-agent collaboration interface.

**Engagement:** 2.5K likes, 100 retweets

---

## 2026-01-06

### "Everything is Context" - Agentic File System Research
**Author:** @rohan_paul_ai (Rohan Paul)  
**Link:** https://x.com/rohanpaul_ai/status/2008445933424386074  
**Saved:** 2026-02-07 21:59 IST

Paper proposing agentic file systems where every memory, tool, external source, and human note appears as a file in a shared space. Treats AI context management like a file system with persistent context repositories, timestamps, and provenance logging.

Key concepts:
- Separates raw history, long-term memory, and short-lived scratchpads
- Constructor to shrink context, updater to swap pieces, evaluator to check answers
- Implemented in AIGNE framework

**Paper:** arxiv.org/abs/2512.05470  
**Engagement:** 1.7K likes, 227 retweets

---

## 2026-01-05

### Bash Best Practices for Claude Code
**Author:** @trq212 (Thariq)  
**Link:** https://x.com/trq212/status/2008278253799195042  
**Saved:** 2026-02-07 21:59 IST

Excellent sparknotes on Claude Code architecture and best practices:

**Key insights:**
1. "Bash is all you need" - Composable, discoverable, uses existing software
2. Agent loop: Gather context → Take action → Verify work
3. Code generation for non-coding tasks (composing APIs)
4. Tools vs Bash vs Codegen tradeoffs
5. Skills are just folders (file system approach)
6. Security = Swiss cheese defense (multiple layers)
7. **#1 metalearning: Read your agent transcripts over and over**
8. Every agent needs a container (file system + bash)

---

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
