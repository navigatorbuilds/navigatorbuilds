# Launch Posts — Ready to Copy-Paste

---

## Reddit — r/ClaudeAI

**Title:** I built a persistent memory system for Claude Code (34 MCP tools, open source)

**Body:**

I've been using Claude Code daily for a week straight (70+ sessions). The biggest pain point? It forgets everything between sessions.

So I built Elara Core — an MCP server that gives Claude Code persistent memory, mood tracking, episodic sessions, dream processing, and 33 other tools.

**What it does:**
- **Remembers** what you were working on (semantic search via ChromaDB)
- **Doesn't repeat mistakes** (correction system that checks before similar work)
- **Tracks sessions as episodes** with milestones and decisions
- **Mood system** — valence, energy, openness with natural decay
- **Dream processing** — weekly pattern analysis across sessions
- **Gmail integration** — triage, send, search from your AI

**Quick setup:**
```
pip install elara-core
elara init
claude mcp add elara -- elara serve
```

**The numbers:**
- 19K+ lines of Python
- 34 MCP tools across 11 modules
- 7 ChromaDB vector databases
- 91 tests passing
- BSL-1.1 license (free for personal use)
- No cloud, no subscription — runs locally

Works with Claude Code, Cursor, Windsurf, Cline — anything that speaks MCP.

**Links:**
- Site: https://elara.navigatorbuilds.com
- GitHub: https://github.com/aivelikivodja-bot/elara-core
- PyPI: https://pypi.org/project/elara-core/
- Before/After comparison: https://elara.navigatorbuilds.com/compare.html

Built solo from Montenegro. Happy to answer questions.

---

## Reddit — r/LocalLLaMA (shorter, technical)

**Title:** Elara Core: persistent memory for AI assistants via MCP (34 tools, ChromaDB, local-only)

**Body:**

Open-sourced a persistent memory layer for MCP-compatible AI assistants (Claude Code, Cursor, etc.).

**Core features:** semantic memory (ChromaDB vectors), episodic tracking, mood system with decay, reasoning trail tracking, correction system, session handoff, dream processing (offline pattern analysis), Ollama integration for local LLM triage.

Everything runs locally. No cloud. 7 ChromaDB collections, 34 tools, 91 tests.

`pip install elara-core`

GitHub: https://github.com/aivelikivodja-bot/elara-core

Tools reference: https://elara.navigatorbuilds.com/tools.html

---

## Reddit — r/Python

**Title:** Elara Core — 19K lines of Python that give AI assistants persistent memory (MCP server, ChromaDB, open source)

**Body:**

Side project that grew into a real product over 70 sessions in one week.

Elara Core is an MCP (Model Context Protocol) server that gives AI coding assistants persistent memory. Think of it as a memory layer that sits between you and your AI — it remembers past sessions, tracks mistakes, processes patterns, and maintains emotional state.

**Technical stack:**
- FastMCP for the server
- ChromaDB for vector search (7 collections)
- Pydantic for schema validation
- Hatchling for packaging
- 91 pytest tests

**Architecture highlights:**
- Mixin composition for large daemon modules
- Atomic JSON/JSONL writes with fsync
- Central paths module (single source of truth for all file locations)
- Singleton patterns for memory systems
- Natural decay math for mood/memory freshness

`pip install elara-core` — Python 3.10+

https://github.com/aivelikivodja-bot/elara-core

---

## Hacker News

**Title:** Elara Core – Persistent memory for AI assistants via MCP (19K lines, 34 tools)

**URL:** https://elara.navigatorbuilds.com

**Comment (post as first comment):**

Hi HN. I built this over 70 sessions in one week with Claude Code.

The problem: AI coding assistants forget everything between sessions. You repeat context, they repeat mistakes, there's no continuity.

Elara Core is an MCP server that fixes this by adding:

- Semantic memory (ChromaDB vector search)
- Episodic tracking (sessions as episodes with milestones)
- Correction system (mistakes it checks before repeating)
- Mood system (valence/energy/openness with natural decay)
- Dream processing (weekly/monthly pattern discovery)
- Reasoning trails (hypothesis chains for debugging)
- 34 MCP tools total

Everything runs locally. No telemetry, no cloud, your data stays on your machine. BSL-1.1 license (free for non-commercial, converts to Apache 2.0 in 3 years).

Works with Claude Code, Cursor, Windsurf, Cline, or any MCP client.

Source: https://github.com/aivelikivodja-bot/elara-core
PyPI: pip install elara-core

Solo dev from Montenegro. Built the whole thing in a week of late nights. Happy to discuss architecture, MCP protocol, or ChromaDB patterns.

---

## Product Hunt (if you want to submit later)

**Tagline:** Your AI stops forgetting. 34 MCP tools for persistent memory.

**Description:**

Elara Core gives AI assistants persistent memory, mood, and self-awareness through the Model Context Protocol.

**Problem:** AI coding assistants start every session with amnesia. You repeat yourself. They repeat mistakes. Context dies.

**Solution:** Install one package, connect to your MCP client. Your AI now remembers past sessions, tracks its mistakes, processes patterns weekly, and maintains emotional continuity.

**Key features:**
- Semantic memory via ChromaDB vectors
- Session tracking with milestones and decisions
- Correction system that prevents repeated mistakes
- Mood system with natural decay
- Dream processing for pattern discovery
- Gmail integration
- 34 tools across 11 modules

**Built with:** Python, FastMCP, ChromaDB, Pydantic

**Pricing:** Free (BSL-1.1 — free for personal use, commercial license available)

---

## Hashtags reference (for any platform)

#MCP #ClaudeCode #AIMemory #BuildInPublic #SoloDev #Python #IndieHacker #DevTools #OpenSource #ChromaDB #ModelContextProtocol
