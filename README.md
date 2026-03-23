# stripe-brain

> "When asked what their greatest barrier to entrepreneurship was, a plurality of founders (43%) said 'bureaucracy.'"
> — Stripe Atlas Census, 2021

Stripe's mission is to **increase the GDP of the internet**. In 2016, they launched [Stripe Atlas](https://stripe.com/atlas) to remove one of the biggest barriers: incorporating a company is still, in most of the world, unnecessarily hard.

Since then, **100,000+ companies** have started with Atlas. They've raised **$4.1 billion** in capital. They employ **99,000 people** across 162 countries.

But incorporation was never the hard part.

**The hard part is everything else.** How do you split equity with your cofounder? How do you handle taxes in your first year? What contracts do you actually need? How do you price your SaaS?

Stripe wrote the answers down. For years, this content lived in PDFs on stripe.com/guides. 

**stripe-brain makes those guides work with AI.**

This repo turns Stripe's founder education into structured prompts — skills you can use in Claude, Cursor, Codex, or any LLM that reads markdown.

---

## What's inside

| Skill | Source | What it does |
|-------|--------|--------------|
| `/atlas-office-hours` | [Atlas Guides](https://stripe.com/guides/atlas-guides) | The hard questions before you write code |
| `/pitch` | [Pitching](https://stripe.com/guides/atlas/pitching) | Structure your investor pitch |
| `/pitch-deck` | [Pitching](https://stripe.com/guides/atlas/pitching) | The 5 pitch plot frameworks |
| `/equity` | [Equity for founders](https://stripe.com/guides/atlas/equity) | Splits, vesting, dilution, 83(b) |
| `/hiring` | [Employment](https://stripe.com/guides/atlas/employment) | Hiring, IP, contractor agreements |
| `/founder-stress` | [Founder stress](https://stripe.com/guides/atlas/founder-stress) | Managing the psychological load |

### More Stripe Atlas content (coming soon)

| Guide | Source |
|-------|--------|
| Bookkeeping & accounting | [stripe.com/guides/atlas/bookkeeping-and-accounting](https://stripe.com/guides/atlas/bookkeeping-and-accounting) |
| Business taxes | [stripe.com/guides/atlas/business-taxes](https://stripe.com/guides/atlas/business-taxes) |
| Surviving tax season | [stripe.com/guides/atlas/tax-season](https://stripe.com/guides/atlas/tax-season) |
| Contracts & agreements | [stripe.com/guides/atlas/transactions-and-agreements](https://stripe.com/guides/atlas/transactions-and-agreements) |
| SaaS business model | [stripe.com/guides/atlas/business-of-saas](https://stripe.com/guides/atlas/business-of-saas) |
| SaaS pricing | [stripe.com/guides/atlas/saas-pricing](https://stripe.com/guides/atlas/saas-pricing) |
| Starting remote | [stripe.com/guides/atlas/starting-a-remote-company](https://stripe.com/guides/atlas/starting-a-remote-company) |
| Founding documents | [stripe.com/guides/atlas/creating-your-founding-documents](https://stripe.com/guides/atlas/creating-your-founding-documents) |

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

---

## Quick start

```
/atlas-office-hours "I'm building a marketplace for local services"
```

Get challenged on your assumptions before you build.

```
/equity "My cofounder wants 50% but they're only working part-time"
```

Learn the frameworks before you make decisions you can't undo.

```
/pitch "We help small businesses manage inventory..."
```

Get your pitch tightened to land in 60 seconds.

---

## Why this exists

Stripe Atlas helped 100,000+ companies incorporate. But the best part of Atlas was never the Delaware C-Corp — it was the guides.

The guides taught you what experienced founders know: how to think about equity, how to survive tax season, what contracts you actually need in year one.

This repo makes that content work the way founders work today — talking to AI at 2am when they need answers.

---

## The numbers

**Stripe Atlas companies:**
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

---

## Credits

Content adapted from [Stripe Atlas Guides](https://stripe.com/guides/atlas-guides).

Original guides © Stripe.

---

## License

MIT — fork it, improve it, ship something.
