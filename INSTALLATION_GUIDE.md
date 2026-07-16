# Installation

## Claude.ai Skills

1. Download and extract the repo (or clone it).
2. Claude.ai → Settings → Skills → add a skill.
3. Point it at `SKILL.md`.
4. Use it: `Humanize this email: [text]`

## Paste into a chat

Open `SKILL.md`, copy the whole thing, paste it into a Claude conversation. Works in any chat, no setup. You'll need to re-paste in new conversations.

## Local reference

Clone it. Everything is plain Markdown with no dependencies — read the genre profile for whatever you're writing and use it as an editorial checklist by hand.

```
git clone https://github.com/USERNAME/humanizer-skill.git
```

## Which files do I actually need?

`SKILL.md` alone is enough to use the skill — it contains the workflow, the pattern quick-reference, the voice calibration framework, and the false-positive list.

Add the one genre profile you write most (`genres/`) and you've got the full value for your use case.

The `references/` folder is for going deeper: the complete 20+ pattern library, the four reverse modes, structural beat analysis, and every worked example.

## First 30 minutes

1. Read `SKILL.md` (15 min).
2. Read the genre profile matching what you write (10 min).
3. Run simple mode on something you wrote recently (5 min).

Then try interactive mode once. It's slower, but it's how you stop needing the tool.

## Troubleshooting

**Skill isn't showing up in Claude.ai** — refresh, confirm you're signed in, or fall back to pasting `SKILL.md` into a chat.

**Pasted it but nothing happens** — make sure the entire file got pasted, frontmatter included, and start a fresh conversation.

**Output sounds flat and generic** — that's over-humanizing. Use voice-matched mode with a sample of your own writing, or check the false-positive list in `SKILL.md`. Stripping every pattern strips your voice too.

**Not sure which genre** — read the genre table in `SKILL.md`. If it's still unclear, say what the writing is for and let the skill pick.
