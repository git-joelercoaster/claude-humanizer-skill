# Humanizer

Removes AI patterns from writing and rebuilds it in your voice. Works in Claude. MIT licensed.

## The problem

AI text has tells. Not typos — patterns. Significance inflation ("stands as a testament to"). Fake urgency ("absolutely critical"). Buzzwords that mean nothing (synergy, leverage, unlock). Hedging that undercuts every claim ("it's worth noting that"). Lists of exactly three virtues. Manufactured tension, neatly resolved.

Most people sense something is off but can't name it. This names it.

## Install

**Claude.ai Skills:** download the repo, upload `SKILL.md` in Settings → Skills.

**Any Claude chat:** paste the contents of `SKILL.md` into the conversation.

**Local reference:** clone it and read the files as an editorial checklist. No dependencies.

## Use

Three modes.

**Simple** — feed it text, get it back cleaned up.
```
Humanize this email:
[paste text]
```

**Voice-matched** — give it a sample of your own writing first, and it rewrites to sound like you rather than like generic "good writing."
```
Humanize this. Here's my voice sample:
[paste something you wrote]

Text to humanize:
[paste the AI text]
```

**Interactive** — it walks each tell, explains why it's a tell, proposes a fix, and you accept, reject, or counter.
```
Walk me through each change on this:
[paste text]
```

After humanizing, four reverse modes adjust tone without reintroducing AI patterns: Formalize, Casualize, Hedge, Commit.

## Genres

Different writing has different rules. A pitch needs conviction; an essay needs uncertainty; a lab report needs neither. Nine profiles in `genres/`:

technical · business · academic · creative · marketing · email · interviews · social · ux

Grant proposals don't have a profile yet — there's an annotated sample in `references/pattern-samples.md` to work from.

## What's in here

```
SKILL.md ....................... master guide — start here
genres/ ........................ nine genre profiles
references/
  patterns-extended.md ......... 20+ AI tells, organized by category
  reverse-modes.md ............. formalize / casualize / hedge / commit
  structural-beats.md .......... AI narrative arcs and how to break them
  pattern-samples.md ........... 7 annotated AI samples, tells called out
  interactive-workflow.md ...... guided-mode walkthroughs
```

## Does it work?

Honestly: I haven't benchmarked it. There's no held-out test set and no blind evaluation, so I'm not going to quote you a percentage.

What's actually in here is a pattern library built from [WikiProject AI Cleanup's documentation](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing), extended with genre rules and worked examples. It reliably catches the named tells — significance inflation, buzzword clusters, rule-of-three rhythms, hedge stacking — because those are mechanical and it knows what to look for.

It won't make bad writing good. It won't catch every tell. And on creative work the risk runs the other way: strip too hard and you sand off the specificity that made the writing human to begin with. The false-positive list in `SKILL.md` is there for that reason and is worth reading before you trust any rewrite.

Judge it on the before/afters in the genre profiles. If those don't look better to you, don't use it.

## What it won't do

Legal documents, regulatory copy, and formal reference material are supposed to read that way. Don't run this on them.

It also flags clusters, not isolated hits. One em dash is nothing. One fancy word is nothing. Five tells in a paragraph is a confession. The false-positive list in `SKILL.md` matters as much as the pattern list — over-editing strips the specificity that made writing human in the first place.

## License

MIT. Use it, fork it, sell it, whatever.

---

Based on [Wikipedia:Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) by WikiProject AI Cleanup, extended with voice matching, genre awareness, interactive workflow, and reverse modes.
