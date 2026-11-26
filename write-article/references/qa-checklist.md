# AIO Citability Scorecard (100 points)

Score the finished draft. **Ship at ≥ 85.** Below that, fix the failing items and re-score. Report the score table to the user.

## A. Fan-out coverage (20)
| # | Check | Pts |
|---|---|---|
| A1 | Title (H1 or SEO title) previews 2–3 facets, e.g. "[X]: Use Cases, Integration & Cost" | 3 |
| A2 | 6–9 H2s, each mapping to a distinct sub-query from the fan-out map | 5 |
| A3 | Includes a definition/role section, a types/models section, and a cost section (if commercial intent) | 5 |
| A4 | Includes at least one information-gain section (failure modes, hidden costs, build-vs-buy, decision framework) | 4 |
| A5 | ≥ 60% of H2s phrased as natural-language questions | 3 |

## B. Chunk-level extractability (25)
| # | Check | Pts |
|---|---|---|
| B1 | Every H2 opens with a 25–50-word answer sentence that names the entity (no opening "it/this/they") | 8 |
| B2 | Every list/table is introduced by a bridge line ("Here is…", "Some of the key… are:") | 3 |
| B3 | Mean paragraph ≤ 40 words; no paragraph > 75 words | 4 |
| B4 | Enumerable content uses numbered H3s or real lists, never inline run-ons | 3 |
| B5 | Bold-label bullets ("**Label:** sentence") for definitions/options | 2 |
| B6 | Each heading delivers exactly what it promises (e.g. "benefits and challenges" covers both) | 5 |

## C. Structured data (15)
| # | Check | Pts |
|---|---|---|
| C1 | ≥ 3 tables (Build Guide archetype: ≥ 5) | 5 |
| C2 | One comparison table (X vs Y, or options side by side) | 3 |
| C3 | One tiered cost table with ranges + scope (+ timeline if building) | 4 |
| C4 | At least one table has a consequence column ("Why it matters" / "Best for") | 3 |

## D. Specificity & evidence (20)
| # | Check | Pts |
|---|---|---|
| D1 | ≥ 15 numeric facts (ranges, rates, percentages, timelines) | 5 |
| D2 | Every statistic links to a primary source (gov, association, research firm, vendor pricing page) | 5 |
| D3 | ≥ 10 named entities: real companies, products, standards, regulations | 4 |
| D4 | Every product price names the vendor and carries "as of [Month Year]" | 3 |
| D5 | At least one development from the last 12 months, dated | 3 |

## E. Voice & information gain (10)
| # | Check | Pts |
|---|---|---|
| E1 | ≥ 4 practitioner punchlines / opinionated lines ("That isn't X. It's Y.") | 4 |
| E2 | Reader persona named in the intro | 2 |
| E3 | 3–4 transitions that name the next question | 2 |
| E4 | No banned phrases (see SKILL.md) | 2 |

## F. Conversion & E-E-A-T (10)
| # | Check | Pts |
|---|---|---|
| F1 | Brand section written as a usable playbook, placed after cost | 3 |
| F2 | 5 FAQs, answers 40–60 words, direct answer in the first 3–8 words | 3 |
| F3 | Publish pack complete: SEO title ≤ 60 chars, meta 140–160 chars, slug, Article + FAQPage JSON-LD, author bio, image briefs with alt text | 2 |
| F4 | 4–8 internal links with service-name or descriptive anchors; mid-article CTA placement marked | 2 |

## Report format

```
AIO Citability Score: [n]/100
A Fan-out coverage      [n]/20
B Extractability        [n]/25
C Structured data       [n]/15
D Specificity/evidence  [n]/20
E Voice/info gain       [n]/10
F Conversion/E-E-A-T    [n]/10
Fixed in revision: [list]
Open items for the user: [unverifiable facts, missing brand URLs, author details]
```
