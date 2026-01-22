# Stop Slop: Dating Coach

A skill for removing performative romance and toxic dating advice from relationship communication.

<div align="center">
  <img src="dating%20coach%20card.webp" alt="Dating Coach Card" style="max-height: 100px; height: auto; width: auto;">
</div>

## What this is

Dating Slop is superficial, transactional, or emotionally manipulative advice that treats relationships like a game to be "won" rather than connections to be nurtured. It includes pick-up artist tactics, toxic positivity, passive-aggressive communication, and generic advice that ignores emotional nuance.

This skill teaches Claude (or any LLM) to recognise performative romance and replace it with genuine, emotionally intelligent communication—especially for Gen Z India users navigating modern dating while respecting cultural context.

## Skill Structure

```
stop-slop-dating-coach/
├── SKILL.md              # Core instructions
├── references/
│   ├── phrases.md        # Phrases to avoid in dating & relationships
│   ├── structures.md     # Relationship patterns to avoid
│   └── examples.md       # Before/after transformations
├── README.md
└── LICENSE
```

## Quick start

**Claude Code:** Add this folder as a skill.

**Claude Projects:** Upload `SKILL.md` and reference files to project knowledge.

**Custom instructions:** Copy core rules from `SKILL.md`.

**API calls:** Include `SKILL.md` in your system prompt. Reference files load on demand.

## What it catches

**Manipulative phrases** — Pick-up lines, toxic positivity, passive-aggressive communication, pressure tactics. See `references/phrases.md`.

**Unhealthy patterns** — Anxious-avoidant traps, performative romance, toxic communication cycles, boundary violations. See `references/structures.md`.

**Dating slop examples** — Before/after transformations showing performative romance vs. healthy communication. See `references/examples.md`.

## Key principles

1. **Name feelings, don't hint at them.** "I feel X" is clearer than "It's interesting how you..."
2. **Make requests, not complaints.** "Can we..." invites collaboration; "You never..." invites defensiveness.
3. **Replace rules with responsiveness.** Forget "wait 3 days"—respond based on how you actually feel.
4. **Validate before solving.** Acknowledge emotions before jumping to advice or solutions.
5. **Boundaries are kind, not cruel.** Setting limits protects the relationship, not just yourself.
6. **Consistency over intensity.** Daily kindness beats monthly grand gestures.
7. **Direct over decoded.** Speak plainly; don't make them guess.
8. **Your standards over "log kya kahenge."** You live this relationship, not them.

## Scoring

Rate 1-10 on each dimension:

| Dimension | Question |
|-----------|----------|
| Directness | Clear statements or vague hints? |
| Authenticity | Genuine connection or performative romance? |
| Emotional intelligence | Validates feelings or dismisses them? |
| Respect | Respects autonomy or uses pressure? |
| Cultural awareness | Acknowledges context or ignores it? |

Below 35/50: revise.

## Examples

**Dating Slop:**
> "Don't text them for 3 days—make them miss you. Play it cool, yaar. If they're into you, they'll chase."

**Healthy Communication:**
> "Had a really nice time today. Would love to do this again if you're up for it."

See `references/examples.md` for more before/after transformations covering texting, boundaries, breakups, family pressure, and more.

## Author

[Hardik Pandya](https://hvpandya.com)

## License

MIT. Use freely, share widely.
