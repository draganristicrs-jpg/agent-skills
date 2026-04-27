# Agent Skills

Production-tested skill modules for Hermes AI agents.

## What is this?

A collection of standardized skill files (`.md` format) that define how an AI agent performs specific tasks. Each skill covers: purpose, inputs, outputs, rules, and success criteria.

Built as part of the [ORBIRESEARCH](https://orbiresearch.com) four-layer agent architecture.

## Available Skills

### Foundation Skills
- `transcription.md` — Audio to text via Whisper API
- `translation.md` — Serbian to English, context-aware
- `content-generation.md` — Topic to multi-format content (LinkedIn, X, YT Shorts)

### Research Skills
- `multi-source-search.md` — Parallel search across 6+ sources
- `signal-filtering.md` — Remove noise from raw search results
- `relevance-ranking.md` — Score and rank signals by relevance

### Quality Skills
- `voice-check.md` — Verify tone consistency against reference texts
- `topic-extraction.md` — Identify distinct topics from long-form text

## Skill Format

Every skill file follows this structure:

Purpose: What the skill does
When used: In which workflow step
Input: What it receives
Output: What it returns
Rules: Constraints and boundaries
Success: How to verify it worked

## Methodology

These skills are part of the ORBIRESEARCH four-layer architecture:

1. **Miro** — Visual architecture (10 frames, 156 questions)
2. **Notion** — Operational contracts (4 databases)
3. **Mermaid** — Technical verification (3 diagrams)
4. **Hermes** — Implementation (skills, config, runtime)

Skills belong to Layer 4 (Hermes) but are derived from Layers 1-3.

## License

MIT — use freely, attribution appreciated.

## Links

- [ORBIRESEARCH](https://orbiresearch.com)
- [Architecture](https://orbiresearch.com/architecture)
- [Weekly Signal Newsletter](https://orbiresearch.com/signal)
