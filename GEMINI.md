# GEMINI.md

This file provides guidance to Gemini CLI when working with this repository.

## Project Overview

This is a **documentation-only repository** — a companion guide for NetworkChuck's "AI in the Terminal" YouTube video. It contains Markdown files covering terminal-based AI tools (Gemini CLI, Claude Code, Codex, opencode) with installation guides, workflows, and reference material.

There is no build system, package manager, test suite, or application code. All content is Markdown.

## Repository Structure

- `README.md` — Main entry point with navigation, pricing table, and tool links
- `docs/01-16` — Sequential learning path from prerequisites through advanced workflows
  - `01-06`: Setup and individual tool guides (Gemini CLI, Claude Code, Codex, opencode)
  - `07-08`: Context files and multi-tool workflows
  - `09-13`: Placeholder sections marked "Coming Soon" (agents deep dive, customization, workflow examples)
  - `14-16`: Cheat sheet, troubleshooting, FAQ

## Content Conventions

- Guides include direct quotes from the video and exact video timestamps
- "Chuck's Take" sections provide opinionated recommendations
- ASCII art diagrams illustrate TUI interfaces and directory structures
- The content targets a broad audience (not just developers)
- Key concepts emphasized throughout: context file persistence, AI agents for task delegation, multi-tool coordination, cost optimization

## When Editing

- Maintain the existing voice and style (conversational, NetworkChuck-branded)
- Preserve video timestamp references — do not fabricate new ones
- Sections 09-13 are placeholders; new content there should follow the patterns established in sections 03-08
- The `04-claude-code.md` file is the most detailed guide (~2,200 lines) and serves as the template for thoroughness
