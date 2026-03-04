# blog-research — Claude Code Skill

A Claude Code custom skill that conducts a full blog content research session and generates a professionally formatted Word document report.

## What it does

When you run `/blog-research [topic]`, it:

1. **Launches 4 specialist AI agents in parallel:**
   - **Keyword Research Specialist** — seed keywords, long-tails, LSI keywords, PAA questions, difficulty ratings, intent mapping
   - **Buyer Persona Strategist** — detailed named persona with pain points, goals, objections, content preferences
   - **Content Funnel Analyst** — TOFU/MOFU/BOFU classification, CTA recommendations, internal linking strategy
   - **Blog Outline Architect** — publication-ready editorial brief with H2/H3 structure, word counts, meta description

2. **Generates a styled Word document** (`.docx`) saved to `~/Documents/BlogResearch/` with:
   - Cover page
   - Table of contents
   - All 4 research sections with professional formatting
   - Header/footer with topic name and page numbers

## Installation

1. Copy `blog-research.md` into your Claude Code commands directory:

   **macOS / Linux:**
   ```bash
   cp blog-research.md ~/.claude/commands/blog-research.md
   ```

   **Windows:**
   ```powershell
   copy blog-research.md %USERPROFILE%\.claude\commands\blog-research.md
   ```

2. Requires **Node.js** and **npm** installed on your machine (used to generate the `.docx` file).

## Usage

```
/blog-research content marketing strategy
/blog-research AI tools for small business
/blog-research how to start a podcast
```

Or run it without arguments and it will ask you for the topic:

```
/blog-research
```

## Output

A `.docx` file is saved to:
```
~/Documents/BlogResearch/blog_research_<topic_slug>_<year>.docx
```

After the document is saved, the skill prints a quick summary:

```
## Research Complete: [TOPIC]

Primary Keyword:       ...
Search Intent:         ...
Funnel Stage:          TOFU / MOFU / BOFU
Target Persona:        ...
Recommended Structure: ...
Word Count Target:     <= 2,200 words

Research document saved to: ~/Documents/BlogResearch/...
```

## Pair it with write-article

This skill is designed to work with a companion `/write-article` skill that reads the research and writes the full SEO-optimized article.

## Requirements

- [Claude Code](https://github.com/anthropics/claude-code) CLI
- Node.js >= 18
- npm

## License

MIT
