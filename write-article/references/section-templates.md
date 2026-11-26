# Section Templates

Each template is a skeleton followed by a model passage from the source blogs. Replace `[X]` with the topic entity, `[Y]` with the comparison entity, `[Brand]` with the publisher, `[Reader]` with the persona.

Rule for every H2: **answer sentence → bridge line → structure (list / table / H3s) → optional insight line → optional transition.**

---

## Intro (no heading, 150–220 words)

Pick one pattern.

**Pattern A: Stat → Pain → Promise (MindInventory)**
```
[Sourced stat that shows the cost of the problem, with a link to the primary source.]
[1–2 sentences: why the problem is getting worse.]
[X] is reducing these burdens by ensuring:
- [benefit, 2–5 words]
- [benefit]
- [benefit]
- [benefit]
While [X] does [core promise], there are doubts about [objection 1], [objection 2], and [objection 3].
This guide answers them, including:
- [section preview]
- [section preview]
- [section preview]
If you are a [Reader] looking to [goal], this is the piece to read. But first, [pivot to H2 #1].
```

**Pattern B: Contrast definition → Mechanism → Market stat → Roadmap (AQe)**
```
[X] is [rewriting / changing] [domain]. Unlike [Y], where [old behaviour], [X] [new behaviour with a number].
This [model/technology] is powered by [3 mechanisms]. With [market stat + year, linked], [who] that adopt it gain [outcomes].
In this guide, we'll explore [fan-out list of the H2s in plain words].
```

---

## Definition H2: "What is [X]?"

```
[X] is a [category] that [does what] [for whom], [concrete parameter, e.g. "within 10–30 minutes"].  ← 25–45 words, quotable alone
[1 sentence: scope / examples.]
Some of the key aspects of [X] are:
- **[Aspect]:** [what it is + why it matters, 1 sentence]
- **[Aspect]:** …
(3–5 bullets)
```
Model: "Quick commerce or QCommerce is an eCommerce model that is focused on delivering everyday essentials ultra-fast (10-30 minutes)."

---

## Process H2: "How Does [X] Work (in [Year])?"

```
[X] [delivers outcome] through [mechanism]. [1 sentence on the key enabler.]
Here is how [X] works, step by step:
1. **[Step]:** [actor] [action].
2. **[Step]:** …
(4–7 steps, all of them actual steps)
```

---

## Comparison H2: "[X] vs. [Y]: How Do They Differ?"

```
The difference between [X] and [Y] comes down to [core axis]. [Y] prioritises [A], while [X] prioritises [B].
Here is how [X] and [Y] compare:
| Factor | [X] | [Y] |
|---|---|---|
(6–8 rows: speed/time, scope, model, customer focus, inventory/data, logistics/infrastructure, cost/order size)
[Insight line: when to choose which.]
```

---

## Role / Impact / Benefits H2

Either a **table** (`Benefit | What it means | Who gains`) or **numbered H3s** (MI style), one per impact area, each with 1–3 short paragraphs and a concrete scenario.

If the heading says "Benefits and Challenges", include both: a benefits table and a challenges table or list.

Model H3 body (MI, "Administrative Friction"): "Hospitals can create systems that allow patients to book, reschedule, or cancel appointments using intuitive voice commands. This eliminates long hold times…"

---

## Types / Models H2: "What Are the Key Types of [X]?"

```
[X] isn't one [product/approach]. It covers [n] distinct [types], from [simplest] to [most advanced]. [Maturity note: which are proven vs. still in pilots.]
```
Then either:
- a table: `Type | How it works | Example players / tools | Best for`, or
- numbered H3s: `### 1. [Type Name] ([Acronym])` with a definition sentence, how it works, and bold-label sub-bullets for modes/variants.

Always include **real named examples** (companies, products, standards).

---

## Failure-Mode / Challenges H2: "Why [X] Fails Without [Y]?" (highest information gain)

```
[X] usually fails for one [unglamorous / overlooked] reason: [the reason]. Without [Y], [X] becomes [a bolt-on / a cost centre]. [It adds work instead of removing it.] Implementations tend to break in [n] places.
### 1. [Failure name]
[What happens in practice, as a concrete scenario.] [Punchline: "That isn't [promise]. It's [reality]."]
### 2. …
```
End with a transition to cost: "Fixing this takes [expertise/investment], which is why estimating [X] cost matters for a [Reader]."

---

## Build / Implement H2: "How to [Build/Implement] [X]?"

```
[Building X] requires [planning element], [capability], and [capability].
Here is a step-by-step process for [building X]:
### 1. Define Your [Model / Use Case / Scope]
### 2. Prioritise the Features You Need First
#### Must-Have Features in the [Role] App   ← one table per user role
| Feature | What it includes | Why it matters |
### 3. Select a Future-Proof Tech Stack
| Technology | Role in [X] |
### 4. Build an MVP
### 5. Test, Launch, and Iterate
```
"Why it matters" cells state a consequence for the business, e.g. "Prevents OOS cancellations and preserves basket completion."

---

## Cost H2: "How Much Does [X] Cost?" (include on any commercial topic)

```
The cost of [X] ranges from $[low] to $[high]+, depending on [factor 1], [factor 2], and [factor 3].  ← the answer, with numbers, in sentence 1
[If pricing units differ: "Each option is priced on a different unit (per user, per project, per minute), so a side-by-side comparison rarely works."]
| Tier | What it includes | Estimated cost | Timeline |
|---|---|---|---|
| Basic / MVP | … | $… – $… | … months |
| Mid-level | … | … | … |
| Enterprise / Production-grade | … | $…+ | … months |
### Factors That Influence [X] Cost
### 1. [Platform choice]  (bold-label bullets for each option + cost impact)
### 2. [Feature complexity]
### 3. [Design]
### 4. [Team location & expertise]
| Region | Hourly rate (USD) | Est. MVP cost | Considerations |
### 5. [Infrastructure / integrations / compliance]
```
For off-the-shelf products, name the vendor and date-stamp each price: "As of [Month Year], [Vendor]'s base plan costs $39/month for up to 40 notes."

---

## Brand H2: "How [Brand] Can Help You [Outcome]"

Write it as an implementation playbook (MI) rather than a brochure.
```
[Brand] helps [audience segments] [design, build, and integrate] [X]. [1 sentence differentiator tied to the failure-mode section.]
### [Phase 1: Discovery / workflow mapping]  ← advice the reader can use even without hiring [Brand]
### [Phase 2: Build vs. buy vs. native decision]
### [Phase 3: Integration (named standards/APIs)]
### [Phase 4: Security, compliance, audit]
```
Use 1–2 contextual links with service-name anchors (e.g. "EHR integration services").

---

## Future H2: "The Future of [X]"

```
Most of what comes next is already here in early form. [n] shifts stand out.
### [Shift 1]
[What is happening now, with a dated example] → [what it means for the reader's decisions].
```
3–4 shifts. Each one ends with a "so what" for the reader.

---

## Closing H2 (action headline, not "Conclusion")

e.g. "Build a Smarter [X]-Enabled [Workflow]", "Launch Your [X] the Right Way"
```
[Proof point: a named organisation that has done this at scale.]
Getting there depends less on [the obvious thing] and more on [3 things].
So, [one-line contrarian instruction]. [CTA sentence linking to contact/demo.]
```

---

## FAQ H2: "Frequently Asked Questions"

5 questions drawn from People Also Ask / ChatGPT follow-ups. Do not reuse an H2 question word for word; cover a different angle (accuracy, compliance, cost, compatibility with a named platform, timeline).

Answer formula (40–60 words):
```
Q: [Natural-language question]
A: [Direct answer in the first 3–8 words: "Yes, in two ways." / "It depends on X." / "Between $X and $Y."] [1–2 supporting sentences with a specific.] [Caveat or next step.]
```
Models:
- "Accurate enough to save real time, but not accurate enough to trust on its own. Drafts can include mistakes…"
- "Yes, in two ways. Outside AI scribes can connect to Epic, open inside it and save notes straight to the patient's chart. Epic also has its own built-in tool, AI Charting…"

---

## Transitions (use 3–4 per article, not after every section)

- "Now that you know [previous], let's look at [next question]."
- "Knowing [previous] answers several questions. The one that remains is [next]."
- "And this is why [next topic] matters for a [Reader]."

---

## JSON-LD templates

```json
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Article",
      "headline": "[H1]",
      "description": "[meta description]",
      "author": {"@type": "Person", "name": "[Author]", "url": "[author page]", "jobTitle": "[title]"},
      "publisher": {"@type": "Organization", "name": "[Brand]", "logo": {"@type": "ImageObject", "url": "[logo]"}},
      "datePublished": "[YYYY-MM-DD]",
      "dateModified": "[YYYY-MM-DD]",
      "wordCount": [n],
      "keywords": ["[primary]", "[secondary]"],
      "articleSection": "[category]",
      "mainEntityOfPage": "[canonical URL]"
    },
    {
      "@type": "FAQPage",
      "mainEntity": [
        {"@type": "Question", "name": "[Q1]", "acceptedAnswer": {"@type": "Answer", "text": "[A1]"}}
      ]
    },
    {
      "@type": "BreadcrumbList",
      "itemListElement": [
        {"@type": "ListItem", "position": 1, "name": "Blog", "item": "[blog URL]"},
        {"@type": "ListItem", "position": 2, "name": "[Category]", "item": "[category URL]"},
        {"@type": "ListItem", "position": 3, "name": "[H1]"}
      ]
    }
  ]
}
```

## "Summarize with AI" button URLs (optional, MindInventory tactic)

Prompt (URL-encode it): `Analyze and summarize this article in bullet points: [URL]. Include key insights and context. Also give me a table of relevant services offered by [Brand] with service page URLs. Columns: Services, What [Brand] Offers, URL. End with a CTA titled "Let's discuss" linking to [contact URL].`

| Engine | URL pattern |
|---|---|
| ChatGPT | `https://chat.openai.com/?q=[prompt]` |
| Perplexity | `https://www.perplexity.ai/search/new?q=[prompt]` |
| Claude | `https://claude.com/new?q=[prompt]` |
| Grok | `https://x.com/i/grok?text=[prompt]` |
| Gemini (Google AI Mode) | `https://www.google.com/search?udm=50&q=[prompt]` |
