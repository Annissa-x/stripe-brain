# stripe-atlas-brain

> "I don't think I've typed like a line of code probably since December, basically, which is an extremely large change."
> — Andrej Karpathy, No Priors podcast, March 2026

When I heard Karpathy say this, I thought about the **other** side of building — the hard questions that have nothing to do with code. How do you split equity fairly? How do you pitch without sounding like every other deck? How do you hire when you can barely pay yourself?

Stripe Atlas answered these questions for me when I co-founded ADSUM at 26. Not the Delaware C-Corp part — the guides. Patrick Collison and Michael Seibel wrote down everything they wished someone had told them. That content has helped 100,000+ companies get started.

**It's been buried in PDFs for years. Now it works with AI.**

I'm [Annissa Poon](https://linkedin.com/in/annissapoon). I ran operations for the world's largest social token community (WHALE, backed by WhaleShark — Forbes, Yahoo Finance). I advised a billionaire family office on crypto strategy at 21, turning $3M into $6M in one year. I've built communities that scaled to 20K+ members. Now I'm Community Manager at [SafetyWing](https://safetywing.com) (YC W18), helping digital nomads build anywhere.

**stripe-atlas-brain is my answer to a problem I kept seeing:** First-time founders asking the same questions I asked. Questions about equity splits that destroy friendships. Pitches that bury the lede. Hiring mistakes that cost six months. 

This repo turns Stripe's founder education into **skills** — structured prompts that work with Claude, Cursor, Codex, or any LLM that reads markdown.

---

## What's inside

| Skill | What it does |
|-------|-------------|
| `/atlas-office-hours` | The hard questions before you write a line of code |
| `/pitch` | Investor pitch coaching (built with YC's Michael Seibel) |
| `/pitch-deck` | Structure your deck using the 5 pitch plot frameworks |
| `/equity` | Founder splits, vesting, dilution, 83(b) elections |
| `/hiring` | Recruit early talent without getting burned |
| `/founder-stress` | Manage the psychological weight of building |

Each skill is a complete framework. Ask it questions. Get challenged. Build something that doesn't fall apart at Series A because you never had The Conversation about equity.

---

## Install — 30 seconds

### For Claude Code

```bash
git clone https://github.com/Annissa-x/stripe-brain.git ~/.claude/skills/stripe-atlas-brain
```

Then add to your CLAUDE.md:
```markdown
## Skills
- stripe-atlas-brain: /atlas-office-hours, /pitch, /pitch-deck, /equity, /hiring, /founder-stress
```

### For Cursor / Codex

```bash
git clone https://github.com/Annissa-x/stripe-brain.git .agents/skills/stripe-atlas-brain
```

### For Clawdbot

```bash
git clone https://github.com/Annissa-x/stripe-brain.git ~/.clawdbot/skills/stripe-atlas-brain
```

---

## Quick start

```
/atlas-office-hours "I'm building a platform connecting people with spiritual counselors"
```

The AI will challenge you like a YC partner would. Do this **before** you build, not after.

```
/pitch "We help remote workers get health insurance in 180+ countries..."
```

Get your pitch scored against YC criteria. Rewrite it until it lands in 18 words.

```
/equity "My cofounder wants 50% but they're only working nights and weekends"
```

Learn the frameworks before you make decisions you can't undo.

---

## Why this exists

Garry Tan open-sourced his development workflow as [gstack](https://github.com/garrytan/gstack). He's shipping 10,000-20,000 lines of production code per day while running YC.

But code isn't the hard part for most founders. **The hard part is everything before the code** — and everything after.

Stripe Atlas figured this out years ago. They wrote the guides. They just never made them work the way founders work today: talking to AI, building in real-time, needing answers at 2am when your cofounder texts you something that changes everything.

**Now it does.**

---

## Philosophy

> "The definition of happiness is one's feeling of contribution to their community. My goal is to maximize potential and contribution."

I believe the founders you teach become the customers you keep. Stripe gets this. That's why they wrote these guides. That's why Atlas has helped 100,000+ companies.

I'm just making it accessible in the format that matters now.

---

## Credits

- Content adapted from [Stripe Atlas Guides](https://stripe.com/guides/atlas-guides)
- Original guides created by Stripe with input from Y Combinator
- Pitch framework built with YC CEO Michael Seibel
- Equity guide developed with [Orrick](https://www.orrick.com/)

Built by [Annissa Poon](https://twitter.com/annissapoon) with Claude.

---

## License

MIT — fork it, improve it, make it yours.

If you build something with this, tell me. I want to see what you ship.
