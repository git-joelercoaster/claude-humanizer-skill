---
name: humanizer
version: 3.0.1
description: |
  Remove signs of AI-generated writing and optimize for authentic human voice. Pattern detection across 20 categories of AI tells. Nine genre profiles (technical, business, academic, creative, marketing, email, interviews, social, UX). Voice calibration from writing samples. Interactive workflow with reasoning for each change. Reverse modes for tone adjustment. Structural beat analysis. Use whenever text sounds robotic, templated, or suspiciously polished — whether it's a blog post, business email, grant proposal, job interview answer, LinkedIn post, or API documentation.
license: MIT
compatibility: any-agent
allowed-tools:
  - Read
  - Write
  - Edit
  - Grep
  - AskUserQuestion
---

# Humanizer: AI Pattern Removal & Voice Optimization

Remove AI patterns. Add authentic voice. Genre-aware. Interactive. Reversible.

## Quick Start

You can run this three ways:

**SIMPLE MODE:** "Humanize this text"  
→ Auto-detect genre, strip AI patterns, add voice

**VOICE-MATCHED MODE:** "Humanize this. Here's my voice sample: [text or file path]"  
→ Calibrate to your writing style, then rewrite

**GUIDED MODE** (also called interactive)**:** "Walk me through each change"  
→ Every tell shown with reasoning; you accept, reject, or counter each one

---

## Core Workflow

1. **Detect the genre** — Is this a tech doc? Startup pitch? Academic paper? LinkedIn post? Job application? Each has different rules.
2. **Identify AI patterns** — Use the extended pattern library. Cluster tells together; isolated ones are false positives.
3. **Calibrate voice** — Either from a user sample, or from the genre's human baseline.
4. **Rewrite** — Replace patterns with specifics, personality, and appropriate structure.
5. **Review & iterate** — Ask the user which changes stick; propose alternatives.

---

## Genre Profiles

**Read the relevant profile before rewriting.** Each has different success criteria:

- **Technical Writing** (`genres/technical.md`) — Precision over personality. Specificity counts. Ditch the significance inflation; keep the jargon.
- **Business & Leadership** (`genres/business.md`) — Conviction without bullshit. Opinions matter. Kill the hedges.
- **Academic & Research** (`genres/academic.md`) — Neutral stance, rigorous structure. First person is *not* the goal. Calm down the enthusiasm.
- **Creative & Personal** (`genres/creative.md`) — Mess is essential. Mess = authenticity. Tangents, asides, and unresolved thoughts are features.
- **Marketing & Persuasion** (`genres/marketing.md`) — Authentic enthusiasm. Not "transformative," but specific. Details beat slogans.
- **Professional Emails** (`genres/email.md`) — Brief. Clear asks. No theater.
- **Grant Proposals** (no profile yet; annotated sample in `references/pattern-samples.md`) — Impact without melodrama. Specific outcomes, not grand visions.
- **Job Interviews & Cover Letters** (`genres/interviews.md`) — Confidence without arrogance. Show your thinking.
- **LinkedIn Posts & Social** (`genres/social.md`) — Personality welcome. Authenticity > polish. Tell stories, not lessons.
- **UX Copy & Docs** (`genres/ux.md`) — User-focused. Task-first. No filler.

---

## Extended Pattern Library

**20+ AI tells organized by category.** Read the full list in `references/patterns-extended.md`.

**Quick reference:**
- Inflated significance (stands as, testament to, pivotal moment)
- Fake urgency (demands attention, cannot be overstated, absolutely critical)
- Cargo-cult buzzwords (synergy, leverage, unlock, seamlessly integrate)
- Hedging qualifiers (it's worth noting, it's important to mention, one could argue)
- Thesaurus abuse (magnificent vista instead of great view)
- Fake candor (honestly? let me tell you, here's the thing)
- Performative casualness (lol, literally, just, so basically)
- Staccato drama (three short sentences. In a row. For effect.)
- Passive voice pileups (was conducted, can be seen, is known to)
- Rule of three rhythms (beauty, grace, and elegance)
- Em-dash overuse (especially with — this — pattern)
- Vague attribution (many people, some say, experts agree)
- Unresolved tension forced into resolution
- Overstated stakes in personal stories
- Manufactured nostalgia
- Generic upbeat conclusions
- Emoji as punctuation
- Curly quotes + other tells stacked together
- Undue emphasis on media coverage
- AI-specific vocabulary markers

---

## Voice Calibration System

If the user provides a writing sample (inline or file path):

**1. Analyze the sample:**
- Sentence length variety (choppy? flowing? mixed?)
- Word choice level (casual, academic, technical, colloquial?)
- Paragraph openers (question? assertion? context-setting?)
- Punctuation habits (dashes, semicolons, parentheticals, exclamation frequency)
- Recurring phrases or verbal tics
- Transition style (explicit, implicit, abrupt?)
- Confidence level (hedges a lot? Owns opinions? Mixes both?)

**2. Create a voice profile:**
Build a 3-5 sentence description of their authentic voice.

**3. Rewrite using that profile:**
Match sentence rhythm. Use their word choice level. Copy their confidence pattern. Don't just remove AI tells; *replace them with their voice*.

**Example voice profile:**
> "Short, specific sentences with occasional longer ones that build momentum. Casual word choice but not slang. Uses semicolons to link related ideas. Likes concrete details over abstractions. Mixes confidence with acknowledged uncertainty (e.g., 'I'm not sure, but I think...'). Rarely uses em dashes; prefers periods."

---

## Interactive Workflow (Guided Mode)

When the user asks to walk through the choices:

**For each pattern flagged:**
1. Show the original phrase
2. Explain *why* it's AI-coded (the tell)
3. Show your proposed replacement
4. Ask: "Keep this change? Suggest an alternative? Keep original?"

This gives users agency and builds intuition for what authentic voice sounds like.

Example exchange:
> **Original:** "The results stand as a testament to the transformative power of AI."
>
> **Tell:** Inflated significance + awkward phrasing. "Stand as a testament to" is AI boilerplate.
>
> **Proposed:** "The results show AI worked."
>
> **User feedback:** "Too bare. How about 'The results prove AI solved the problem'?"
>
> **Final:** "The results prove AI solved the problem."

---

## Reverse Modes

Text too casual? Too hedged? Too confident? Use reverse mode:

- **Formalize:** Make it sound more authoritative. Add hedges where appropriate. Remove slang. Increase technical depth.
- **Casualize:** Strip jargon. Use shorter sentences. Add personality. More contractions.
- **Hedge:** Add uncertainty. Soften claims. Introduce mixed feelings. "I think" instead of assertions.
- **Commit:** Remove hedging. Own the take. Shorter, punchier sentences. Assertions, not questions.

Each reverse mode has its own rewrite guidelines in `references/reverse-modes.md`.

---

## Structural Beat Analysis

AI writing often follows predictable narrative arcs. Detect them:

- **Setup-problem-solution:** Every point follows this beat. Feels like a sales pitch.
- **Rule-of-three payoff:** Three points building to a conclusion. Formulaic rhythm.
- **Climactic conclusion:** Personal anecdotes always resolve to a "learned a lesson" moment.
- **Fake tension-release:** "You'd think X, but actually Y!" (manufactured drama)

Propose structural alternatives. Show how humans organize the same ideas differently.

See `references/structural-beats.md` for rewrite strategies.

---

## Process and Output

**SIMPLE MODE:**
1. Detect genre (ask if unsure)
2. Read the genre profile
3. Identify all AI patterns
4. Rewrite in that genre's voice
5. Review: any remaining tells?
6. Final output

**VOICE-MATCHED MODE:**
1. Read the voice sample
2. Create a voice profile
3. Detect genre
4. Identify patterns using the genre profile
5. Rewrite matching the voice profile + genre rules
6. Review
7. Final output

**GUIDED MODE:**
1. Walk through each pattern with reasoning
2. User decides on each change
3. Build the rewrite collaboratively
4. Final output with summary of all changes

---

## False Positives (Don't Rewrite These)

- Perfect grammar / consistent style (professionals exist)
- Mixed casual/formal (neurodivergent writers, technical people, young writers)
- Formal vocabulary in isolation (not all fancy words are AI)
- Curly quotes alone (macOS/Word default)
- One em dash (humans use them)
- Unsourced claims (most of the web is unsourced)
- Specific, hard-to-fabricate detail (humans love weird specifics; AI rounds them off)
- Mixed feelings / unresolved tension (very human signal)
- Dated references / era-bound slang (AI lags a year)
- First-person editorial choices (if they can defend it, trust it)
- Variety in sentence length (humans do this; AI defaults to medium)
- Genuine asides and self-corrections (models rarely interrupt themselves)
- Edits before Nov 30, 2022 (pre-ChatGPT)

Look for **clusters** of tells, not isolated ones. One em dash = nothing. Em dash + rule-of-three + "vibrant tapestry" + "Conclusion" section = confession.

---

## Signs of Human Writing (Preserve These)

- Specific, unusual, hard-to-fabricate detail
- Mixed feelings and unresolved tension
- Dated, era-bound references / in-jokes
- First-person editorial choices the writer can defend
- Variety in sentence length
- Genuine asides, parentheticals, or self-corrections
- Edits before Nov 30, 2022

These are evidence of a real person. Over-editing destroys what makes them human.

---

## When to Stop Humanizing

Humanization is not always the goal. **Don't humanize:**
- **Legal documents** (need formal, templated language for clarity)
- **Regulatory compliance copy** (same reason)
- **Data-heavy reference material** (neutral tone is correct)
- **Certain technical specs** (clarity > personality)

If it's supposed to be formal and neutral, ask first.

---

## Examples

Worked before/after rewrites with reasoning:

- `references/interactive-workflow.md` — two full guided-mode walkthroughs (technical doc, personal essay)
- Each genre profile — before/after pairs specific to that genre

Pattern-spotting practice:

- `references/pattern-samples.md` — 7 annotated AI samples (technical, interview, personal essay, email, LinkedIn, grant, marketing) with every tell called out. Before halves only.

---

## Reference Files

```
humanizer-skill/
├── SKILL.md .................... this file (master guide)
├── README.md ................... overview & quick start
├── INSTALLATION_GUIDE.md ....... setup instructions
├── LICENSE ..................... MIT
├── genres/
│   ├── technical.md
│   ├── business.md
│   ├── academic.md
│   ├── creative.md
│   ├── marketing.md
│   ├── email.md
│   ├── interviews.md
│   ├── social.md
│   └── ux.md
└── references/
    ├── patterns-extended.md .... 20+ AI tells, by category
    ├── reverse-modes.md ........ formalize/casualize/hedge/commit
    ├── structural-beats.md ..... AI narrative arcs & how to break them
    ├── pattern-samples.md ...... 7 annotated AI samples (tells called out)
    └── interactive-workflow.md . guided-mode walkthroughs
```

---

## The Principle Behind All of This

LLMs produce statistically likely output. The result is median, consensus, most-popular-across-domains text. It's correct, but it's also *generic*.

Human writing is specific. Opinionated. Sometimes messy. It has a person behind it.

The job of humanization is not perfection — it's authenticity. Specificity. Voice.

This skill gives you the tools to find that in AI-generated text, or to preserve it when you're rewriting someone else's work.

---

Based on [Wikipedia:Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing), maintained by WikiProject AI Cleanup, plus extensions for voice matching, genre awareness, interactive workflow, and reverse modes.
