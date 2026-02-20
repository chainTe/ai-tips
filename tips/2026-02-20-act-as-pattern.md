# Tip #1: The "Act As" Pattern

**Date**: 2026-02-20  
**Category**: Prompt Engineering  
**Difficulty**: Beginner

## The Tip

Start your prompts with "Act as [specific role]" to get better results.

## Why It Works

LLMs are trained on human conversations. When you assign a role, you activate a specific "mode" of response that matches that persona's expertise and communication style.

## Examples

❌ **Vague**: "Explain quantum computing"

✅ **Specific**: "Act as a physics professor explaining quantum computing to a curious high school student. Use analogies and avoid jargon."

❌ **Vague**: "Write code for a web scraper"

✅ **Specific**: "Act as a senior Python developer. Write a robust web scraper with error handling, rate limiting, and respect for robots.txt. Include comments explaining your choices."

## Variations

- "Act as a skeptical reviewer..."
- "Act as an enthusiastic mentor..."
- "Act as a devil's advocate..."

## Pro Tip

Combine with output format instructions:

> "Act as a documentation expert. Review this code and output your feedback as a markdown table with columns: Issue, Severity, Suggestion"

---

*Have a tip to share? Open an issue or PR!*
