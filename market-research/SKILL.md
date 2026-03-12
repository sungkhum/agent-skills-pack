---
name: market-research
description: Standalone market research workflow based on BMAD. Use when the user asks for market research, competitive landscape analysis, customer needs, market trends, or a market research report about a business idea.
---

# BMM Market Research

## Overview

Conduct comprehensive market research using current web data and verified sources to produce a structured research document with citations.

## Prerequisite

- Web search is required. If web search is unavailable, stop and tell the user.

## Quick Start

- Ask for research topic, goals, and scope.
- Set `research_type = "market"`, and capture `research_topic` and `research_goals`.
- Create the output file using the template in `references/research.template.md`.
- Follow the step sequence in `references/market-steps/step-01-init.md` onward.

## Output Expectations

- Provide a narrative report with clear sections and citations.
- Use the user’s requested language and skill level; if not provided, ask.

## References

- `references/workflow-market-research.md` for the canonical workflow.
- `references/market-steps/` for the step-by-step execution.
- `references/research.template.md` for the report structure.
