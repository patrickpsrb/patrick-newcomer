# B2B SaaS LinkedIn Research Project

This repository contains structured research on LinkedIn organic content strategy for B2B SaaS.

## Chosen Topic

**How B2B SaaS founders and marketers use LinkedIn organic content to generate inbound pipeline.**

## Project Objective

The goal is to collect high-signal examples from proven practitioners, analyze repeatable patterns, and turn findings into a practical playbook that supports shorter B2B SaaS sales cycles.

## Research Scope

- Analyze 10 LinkedIn experts with strong execution track records.
- Collect and review YouTube transcripts and selected LinkedIn posts.
- Extract practical patterns for hooks, content formats, authority building, comments, and CTA design.

## Methodology

- **Automated transcript collection:** `youtube-transcript-api` via `fetch_transcripts.py`.
- **Fallback retrieval:** `yt-dlp` subtitle fallback when direct API fetch is blocked.
- **Manual curation:** selective capture of high-value LinkedIn posts by expert.
- **Repository-first workflow:** research artifacts stored and versioned in this project.

## Repository Structure

```text
patrick-newcomer/
├── README.md
├── fetch_transcripts.py
├── youtube_sources.json
└── research/
    ├── sources.md
    ├── linkedin-posts/
    ├── youtube-transcripts/
    └── other/
```

## Selected Experts

1. **Justin Welsh**: Built a $1.7M business from LinkedIn alone; created the "Content OS" system.
2. **Lara Acosta**: Grew from 0 to 200K followers in 2 years; documents the process publicly.
3. **Richard van der Blom**: Publishes the annual LinkedIn Algorithm Report; strongly data-driven.
4. **Jasmin Alic**: Best-in-class LinkedIn copywriting frameworks with consistently high engagement.
5. **Matt Barker**: Ghostwriter for B2B SaaS founders; understands what works inside real companies.
6. **Tibo Louis-Lucas**: Co-founder of Taplio; has platform-level data on LinkedIn content performance.
7. **Guillaume Moubeche**: CEO of Lemlist; built $10M+ ARR with LinkedIn and content as a core channel.
8. **Sam Szuchan**: Known for format testing and consistency; practical and example-heavy.
9. **Brendan Hufford**: B2B SaaS content practitioner focused on execution inside operating companies.
10. **Chris Donnelly**: Founder of Verb agency; strong POV on founder-led LinkedIn distribution.

## Current Status

- Transcript files are present for all 10 selected experts.
- LinkedIn post research folders are initialized and ready for deeper annotation.
- Core extraction script is available and versioned.

## Next Step

Synthesize findings into a repeatable "content-to-lead" framework covering:
- content pillars,
- post structures and hook formulas,
- comment strategy,
- and CTA patterns by funnel stage.