# stripe-brain

> "When asked what their greatest barrier to entrepreneurship was, a plurality of founders (43%) said 'bureaucracy.'"
> — Stripe Atlas Census, 2021

Stripe's mission is to **increase the GDP of the internet**. In 2016, we launched [Stripe Atlas](https://stripe.com/atlas) to remove one of the biggest barriers: incorporating a company is still, in most of the world, unnecessarily hard.

Since then, **100,000+ companies** have started with Atlas. They've raised **$4.1 billion** in capital. They employ **99,000 people** across 162 countries. From Istanbul, founders incorporated restaurant tech startups and expanded to 64 countries. From Lagos, from São Paulo, from anywhere with wifi — entrepreneurs are building real businesses.

But incorporation was never the hard part.

**The hard part is everything else.** How do you split equity with your cofounder? How do you pitch investors when you've never done it? How do you hire your first employee without getting burned?

We partnered with Y Combinator to write the answers down. [Michael Seibel](https://www.ycombinator.com/people/michael-seibel), YC's CEO, helped build our pitch framework. [Orrick](https://www.orrick.com/) contributed the equity guide. We documented what experienced founders know but first-time founders have to learn the hard way.

**stripe-brain makes those guides work with AI.**

This repo turns Stripe's founder education into structured prompts — skills you can use in Claude, Cursor, Codex, or any LLM that reads markdown.

---

## What's inside

| Skill | What it does |
|-------|-------------|
| `/atlas-office-hours` | The hard questions before you write a line of code |
| `/pitch` | Investor pitch coaching (with YC's Michael Seibel) |
| `/pitch-deck` | Structure your deck using the 5 pitch plot frameworks |
| `/equity` | Founder splits, vesting, dilution, 83(b) elections |
| `/hiring` | Recruit early talent without getting burned |
| `/founder-stress` | Manage the psychological weight of building |

Each skill is a complete framework. You ask questions. It challenges you. You build something that doesn't fall apart at Series A.

---

## Install — 30 seconds

### For Claude Code

```bash
git clone https://github.com/Annissa-x/stripe-brain.git ~/.claude/skills/stripe-brain
```

Add to your CLAUDE.md:
```markdown
## Skills
- stripe-brain: /atlas-office-hours, /pitch, /pitch-deck, /equity, /hiring, /founder-stress
```

### For Cursor / Codex

```bash
git clone https://github.com/Annissa-x/stripe-brain.git .agents/skills/stripe-brain
```

### For Clawdbot

```bash
git clone https://github.com/Annissa-x/stripe-brain.git ~/.clawdbot/skills/stripe-brain
```

---

## Quick start

```
/atlas-office-hours "I'm building a marketplace for local services"
```

Get challenged like a YC partner would challenge you. Do this **before** you build.

```
/pitch "We help small businesses accept payments in emerging markets..."
```

Get your pitch scored. Rewrite it until it lands in 18 words.

```
/equity "My cofounder wants 50% but they're only working nights and weekends"
```

Learn the frameworks before you make decisions you can't undo.

---

## Why this exists

Stripe Atlas helped 100,000+ companies incorporate. But the best part of Atlas was never the Delaware C-Corp — it was the guides.

The guides taught you what experienced founders know: how to think about equity, how to pitch without rambling, how to hire without regret.

For years, this content lived in PDFs on stripe.com/guides. Now it works the way founders work today — talking to AI at 2am when their cofounder texts them something that changes everything.

---

## The numbers

**Stripe Atlas companies (as of 2021):**
- 100,000+ companies started
- 162 countries
- $4.1 billion raised
- 99,000 employees
- 91% outside Silicon Valley

**Founder demographics:**
- 43% first-time founders
- 28% minorities in their country
- 24% immigrants
- Fastest growth: Nigeria (400% YoY), UAE (165%), India (66%)

Entrepreneurship is going global. The infrastructure should too.

---

## Credits

- Content adapted from [Stripe Atlas Guides](https://stripe.com/guides/atlas-guides)
- Pitch framework developed with [Y Combinator](https://www.ycombinator.com/) and YC CEO [Michael Seibel](https://www.ycombinator.com/people/michael-seibel)
- Equity guide developed with [Orrick](https://www.orrick.com/)
- Original guides: © Stripe

Packaged for AI by the community.

---

## License

MIT — fork it, improve it, ship something.
