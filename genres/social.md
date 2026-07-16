# Genre Profile: Technical Writing

API docs. System architecture. Dev guides. Lab reports. Engineering specs. Software documentation.

## The Goal

Precision over personality. Specificity over elegance. Clarity is everything.

## What Changes

### DO Strip

- Significance inflation (it doesn't matter that something is "pivotal")
- Enthusiasm language ("exciting new feature")
- Hedging language if unwarranted ("may potentially," "arguably")
- Cargo-cult buzzwords that obscure meaning (synergy, leverage, seamless)
- Fake urgency
- Narrative structure (setup-problem-solution)

### DO NOT Strip

- Formal vocabulary (this is the correct register)
- Precise jargon (keep technical terms as-is)
- Passive voice (often appropriate in technical writing to keep focus on process, not actor)
- Conditional language ("may," "can," "could") — this is appropriate for specifications
- Tables of contents, structured formatting, dense reference material

## Signs of AI in Technical Writing

**Problem areas:**
- "This cutting-edge technology revolutionizes" ← kill "cutting-edge" and "revolutionizes," keep the fact
- "Seamlessly integrates with" ← "integrates with"
- "Unlock the power of" ← stop. Just describe what it does.
- "Industry-leading solution" ← what does it actually do?
- Opening paragraphs that explain significance instead of stating the function
- Fake urgency about routine features

**Good technical prose:**
- Direct (says what it does immediately)
- Specific (gives exact parameters, values, ranges)
- Hierarchical (headers, numbered steps, tables)
- Consistent (same term for same concept throughout)
- Calm (no dramatic language; procedures matter, not feelings)

## Voice in Technical Writing

Technical writing *can* have personality without sacrificing clarity:

- **Contractions welcome** (makes it more readable)
- **First person acceptable** ("We recommend X" instead of "It is recommended that X")
- **Short sentences > long ones** (easier to scan)
- **Humor is okay if it clarifies** (not if it distracts)
- **Examples beat abstract explanation** (always prefer "e.g." to "generally")

## Common Technical AI Mistakes

**Mistake 1: Apologetic hedging**
> "It might be worth considering whether you could potentially use the API to, arguably, improve performance."

**Fix:**
> "You can use the API to improve performance."

**Mistake 2: Significance puffing**
> "This innovative feature represents a paradigm shift in data processing, marking a pivotal moment in the evolution of our platform."

**Fix:**
> "This feature processes data 3x faster than the previous version."

**Mistake 3: Fake urgency**
> "It is absolutely critical that you implement proper error handling to avoid catastrophic failure."

**Fix:**
> "Implement error handling to prevent crashes."

**Mistake 4: Narrative fluff**
> "The problem we faced was significant. Developers were struggling. Then we realized: what if we could make it easier? So we rebuilt the system."

**Fix:**
> "The old system made X hard. We rebuilt it to make X automatic."

## Checkpoints Before Finalizing

- [ ] Can someone unfamiliar with the product understand what it does from the opening?
- [ ] Are all jargon terms defined on first use?
- [ ] Are there concrete examples or code samples?
- [ ] Is the structure hierarchical (headings, steps, indentation)?
- [ ] Are parameters, defaults, and limits specified exactly?
- [ ] Does every paragraph serve a clear purpose (reference, how-to, explanation)?
- [ ] Would a tired developer at 2am be able to find what they need?
- [ ] Is the tone consistent (professional, not cheerleading)?

## Example: API Documentation

**Before (AI-sounding):**
> The API provides a revolutionary way to interact with our platform. By leveraging cutting-edge technology, developers can now seamlessly integrate powerful features into their applications, unlocking unprecedented potential. The authentication system ensures robust security while maintaining ease of use. This innovative approach has been shown to significantly improve developer experience across the industry.

**After (Human technical writing):**
> The API lets you access core platform features from your application. You authenticate with an API key, which you can generate in your account settings. Rate limits: 1000 requests/minute per key. See Authentication for setup details.

---

## Voice Calibration for Technical Writers

If analyzing a technical writer's sample:

Look for:
- **Sentence length** (likely: medium, varies slightly)
- **Jargon handling** (defines on first use? Or assumes it?)
- **Example density** (lots of code samples? Links to examples?)
- **How they handle exceptions** ("unless X" vs "with the following caveat")
- **Tone** (friendly approachable? Formal? Dry?)
- **Paragraph length** (short, scannable sections? Longer paragraphs?)
- **Lists** (numbered? Bulleted? How detailed?)

**Example calibration:**
> "This writer: short paragraphs (2-3 sentences max), defines jargon first use, includes examples in most sections, uses bullet lists for options, tone is patient and assumes some confusion, contractions welcome."

Match this in rewrites.
