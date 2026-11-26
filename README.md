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

`write-article/` is the companion skill. It writes the full article, engineered to be cited in Google AI Overviews, AI Mode, ChatGPT, Perplexity and Gemini answers. It can take the `/blog-research` report as input.

The method comes from reverse-engineering two posts that are cited in AI answers:
- AQe Digital, *A Comprehensive Guide To Building a Quick Commerce App For Your Business* (the "Build Guide" archetype)
- MindInventory, *Voice Technology in Healthcare: Use Cases, EHR Integration, and Cost Guide* (the "Tech-in-Industry" archetype)

```
write-article/
├── SKILL.md                         # 6-step workflow: brief → fan-out map → research → draft → score → deliver
└── references/
    ├── teardown.md                  # metrics, structure maps, quotes, and the mistakes to avoid
    ├── section-templates.md         # skeletons for every section type, JSON-LD, AI-summary button URLs
    └── qa-checklist.md              # 100-point AIO Citability Scorecard (ship at ≥ 85)
```

**Install:**

```bash
cp -r write-article ~/.claude/skills/write-article
```

**Use:**

```
/write-article voice AI agents for insurance claims
/write-article how to build a telemedicine app
```

It writes `articles/<slug>.md` (the article) and `articles/<slug>-publish-pack.md` (SEO title, meta, JSON-LD, internal links, sources, image briefs, scorecard).

## Requirements

- [Claude Code](https://github.com/anthropics/claude-code) CLI
- Node.js >= 18
- npm

## License

MIT
