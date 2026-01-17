# Workspace Instructions for AI Agents

This workspace contains five interconnected projects focused on software architecture knowledge and course delivery. **Each repository has its own `.github/copilot-instructions.md`** tailored to its specific patterns and workflows.

## Repository Index

| Repository | Purpose | Key Pattern |
|---|---|---|
| [courses/](courses/.github/copilot-instructions.md) | Python CLI: markdown → Google Slides → PDF → HeyGen videos | Content parsing, batch API sync, browser automation |
| [materials/](materials/.github/copilot-instructions.md) | Knowledge library from architecture & organizational books | Read-heavy, structured notes, topic hierarchies |
| [social-posts/](social-posts/.github/copilot-instructions.md) | Social media content database (LinkedIn, Substack, general) | Platform-specific tone, progress tracking, cross-linking |
| [software-architecture-guild.github.io/](software-architecture-guild.github.io/.github/copilot-instructions.md) | Hugo static website: guide, blog, authors | Ilya's style guide, quality attributes, traceability |
| [prompts/](prompts/.github/copilot-instructions.md) | AI copywriting prompt templates | Standardized AI workflows, quality gates |

## Quick Navigation

When working on a specific repository, **always check that repo's `.github/copilot-instructions.md` first**. It contains:
- Project-specific architecture and data structures
- Key development commands and workflows
- Code style and patterns for that repo
- Critical rules and constraints (e.g., commit permissions, testing protocols)
- Common debugging approaches

## Workspace-Level Patterns

### Cross-Project Integration

1. **Materials → Courses:** Knowledge library informs course content (reference, cite sources)
2. **Courses → Social Posts:** Video scripts repurposed as social content; promotions link back
3. **Prompts → All:** Standardized AI prompts generate content across courses, guides, social
4. **Guild Website ← All:** Guide/blog articles cross-link to courses, materials, social posts

### Shared Conventions

- **Ilya's voice:** Conversational, direct, mentor-to-peer; consistent across all platforms
- **Traceability:** All claims grounded in source material (books, documented patterns)
- **Quality attributes:** Every recommendation ties to performance, scalability, security, modifiability
- **Trade-offs:** Explicitly call out competing priorities (speed vs. formality, discovery vs. iteration)
- **Spell-checking:** All repos use cspell with `project-words.txt` dictionary

### Critical Rules (All Repos)

1. **NO COMMITS without permission** — Always wait for explicit user approval
2. **Test single item first** — Never run multi-item operations without one test
3. **Ask before major changes** — Refactors, new files, signature changes need approval
4. **No assumptions** — If instruction is ambiguous, ask for clarification


