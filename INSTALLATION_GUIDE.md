# Humanizer Skill v3.0.0 — Installation Guide

Choose your installation method based on your workflow.

---

## Option A: Claude.ai Skills (Easiest)

**Prerequisites:** Claude.ai account

**Steps:**

1. Download `humanizer-skill-v3.zip`
2. Extract the folder to your computer
3. Go to **Claude.ai** → **Settings** → **Skills** (or **Custom Skills**)
4. Select **Add Skill** or **Upload Skill**
5. Point to the `SKILL.md` file from the extracted folder
6. Confirm installation

**Use immediately:**
```
Humanize this [genre]: [your text]
```

---

## Option B: Copy/Paste into Chat

**Prerequisites:** Claude.ai or Claude app, any chat

**Steps:**

1. Open `SKILL.md` in a text editor
2. Copy the entire contents
3. Start a new chat in Claude.ai or the Claude app
4. Paste the skill content into the chat
5. Save the chat (or pin it for reference)

**Use:**
```
I saved your skill guide. Now I can:
[Your text to humanize]
```

---

## Option C: Save to Claude Memory (Claude.ai Pro)

**Prerequisites:** Claude.ai Pro subscription

**Steps:**

1. Open `SKILL.md` in a text editor
2. Copy the entire contents
3. Start a new chat in Claude.ai
4. Tell Claude: `"Save this skill guide to my memory: [paste SKILL.md]"`
5. Claude will confirm it's saved
6. Future chats will have access automatically

**Use in any future chat:**
```
Using my humanizer skill, can you humanize this [genre]: [text]?
```

---

## Option D: Local Reference (Terminal/IDE)

**Prerequisites:** Text editor, terminal

**Steps:**

1. Extract `humanizer-skill-v3.zip`
2. Save the folder in your workspace
3. Reference the files as needed in your workflow
4. Open `SKILL.md` as your reference guide
5. Open genre profiles as needed

**Use:**
- Reference the patterns in `genres/` while editing your own work
- Use reverse modes from `genres/reverse-modes.md` for tone adjustment
- Check examples in `examples/` for guidance

---

## Which Files Do You Need?

### Minimum Setup (Just Get Started)
- `SKILL.md` — The master guide
- `genres/` folder — Genre profiles you actually use

### Recommended (Full Power)
- Everything above, plus:
- `genres/test-results.md` — See examples of humanization in action
- `genres/reverse-modes.md` — Adjust tone after humanizing

### Complete (Deep Learning)
- All files
- Study the examples to understand the process
- Reference patterns as you learn

---

## First Steps After Installation

1. **Read the master guide** — `SKILL.md` (15 min)
2. **Pick your genre** — Read the relevant profile (15 min)
3. **Try simple mode** — "Humanize this text" with a sample (5 min)
4. **Try interactive mode** — "Walk me through the changes" (10 min)
5. **Use on real work** — Apply to your actual writing

---

## Troubleshooting

**Q: The skill isn't showing up in my Claude.ai profile**
- Refresh your browser
- Make sure you're logged in
- Try Option B or C instead

**Q: I pasted the skill but it's not working**
- Make sure the entire `SKILL.md` was pasted (all text)
- Start fresh with a new chat and paste again
- Try saving it as a memory (Option C) if you're a Pro user

**Q: I don't know which genre profile I need**
- Technical writing? → `genres/technical.md`
- Email? → `genres/email.md`
- LinkedIn? → `genres/social.md`
- Not sure? → Read `SKILL.md` intro for genre table

**Q: I want to customize the skill**
- All files are plain Markdown
- Edit them in any text editor
- All rules and patterns are documented and changeable

---

## Getting Help

If something isn't working:

1. Check the genre profile for your writing type
2. Review `test-results.md` for examples
3. Try interactive mode to understand the process
4. Reference `genres/patterns-extended.md` if a pattern isn't clear

---

## Keeping It Updated

This is version 3.0.0. If updates are released:

1. Download the latest ZIP
2. Extract to a new folder
3. Compare any files you've customized
4. Merge your changes into the new version

---

## Next: Using the Skill

Once installed, start with:

**Simple mode:**
```
Humanize this [genre]:

[Your text here]
```

**Voice-matched mode:**
```
Humanize this. Here's my voice sample:

[A sample of your own writing]

[Text to humanize]
```

**Interactive mode:**
```
I need help humanizing this. Walk me through the changes.

[Your text]
```

---

## Questions?

Refer to:
- `SKILL.md` — All features explained
- `genres/` — Specific rules by type
- `test-results.md` — See it in action
- `examples/` — Real before/afters

Everything is documented. You've got this.
