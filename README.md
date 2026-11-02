# Project C — AI Workspace

Platform-agnostic source of truth for working with any AI assistant
(Mistral, Claude, ChatGPT, or others). Nothing here depends on any
single vendor's memory or storage.

## Structure
- AGENTS.md          → Start here. Instructions for any AI assistant.
- CLAUDE.md         → Pointer so Claude-based tools find AGENTS.md.
- PREFERENCES/      → How I work: durable preferences and personal context.
- BUSINESS/          → The business project: brief, decisions, current state.

## How to use with an AI assistant
1. In a new chat on any platform, connect/add this repo (GitHub connector,
   attachment, or paste the files).
2. Tell the assistant: "Read AGENTS.md and follow it."
3. Work. At the end of a session, ask the assistant to update
   BUSINESS/status.md and BUSINESS/decisions.md, then commit.

## Sync discipline
- This repo is the single source of truth. Pull before you start,
  push when you're done.
- Never store secrets here (no API keys, passwords, tokens).
