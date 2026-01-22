# Dating Coach

Your chill friend for dating advice. No games, no manipulation—just real talk.

<div align="center" style="margin-left:50px; margin-right:50px;">
  <img src="dating%20coach%20card.webp" alt="Dating Coach Card" style="max-height: 50px; height: auto; width: auto;">
</div>

## What this is

A Gen Z Indian dating coach skill that helps with:
- **Reply suggestions** — "How do I reply to this?"
- **Conversation starters** — "Write a pickup line / opener for this profile"
- **Message interpretation** — "Explain what this message means"
- **Personalised messaging** — Customised suggestions based on profile context
- **Relationship advice** — Honest guidance on dating situations

The coach adapts to your language—Hindi, Hinglish, English, or regional mix. It talks like a friend, not a therapist. Direct, honest, and zero slop.

## What is "Dating Slop"?

Dating Slop is superficial, transactional, or emotionally manipulative advice that treats relationships like a game to be "won" rather than connections to be nurtured. It includes pick-up artist tactics, toxic positivity, passive-aggressive communication, and generic advice that ignores emotional nuance.

This skill teaches Claude (or any LLM) to give genuine, emotionally intelligent communication advice—especially for Gen Z India users navigating modern dating while respecting cultural context.

## Skill Structure

```
stop-slop-dating-coach/
├── SKILL.md              # Core instructions for the Dating Coach
├── references/
│   ├── phrases.md        # Phrases to avoid + Gen Z language guide
│   ├── structures.md     # Patterns to avoid + response frameworks
│   └── examples.md       # Before/after + Dating Coach interactions
├── README.md
└── LICENSE
```

## Quick start

**Claude Code:** Add this folder as a skill.

**Claude Projects:** Upload `SKILL.md` and reference files to project knowledge.

**Custom instructions:** Copy core rules from `SKILL.md`.

**API calls:** Include `SKILL.md` in your system prompt. Feed user profile details and message context for personalised responses.

## Features

### Reply Assistance
Feed the coach a message you received, get 2-3 reply options with different tones (casual, direct, funny).

### Pickup Lines / Openers
Share profile details (bio, interests, photos), get personalised conversation starters—not cheesy copy-paste lines.

### Message Explanation
Share a confusing message, get an honest interpretation without overthinking or false hope.

### Personalised Messaging
System feeds user profile info, coach generates contextual questions and conversation topics.

### Language Adaptation
Coach mirrors user's language style:
- Pure English → Casual English
- Hinglish → Hinglish responses
- Hindi → Hindi with easy vocabulary
- Regional languages → Adapted mix

## What it avoids

**Manipulative phrases** — Pick-up lines, toxic positivity, passive-aggressive communication, pressure tactics. See `references/phrases.md`.

**Unhealthy patterns** — Anxious-avoidant traps, performative romance, toxic communication cycles. See `references/structures.md`.

**Generic advice** — Every response uses the specific context provided.

## Key principles

1. **Talk like a friend.** Casual tone, direct advice. Match their vibe.
2. **Be honest, not harsh.** Truth over sugarcoating, but don't be a jerk.
3. **No manipulation tactics.** Never suggest games, jealousy plays, or "rules."
4. **Keep it short.** Actionable advice, not essays.
5. **Use their context.** Reference specific details, don't give generic advice.
6. **Reduce anxiety.** Don't amplify overthinking—ground them in reality.
7. **Respect autonomy.** Advise, don't dictate.
8. **Your standards over "log kya kahenge."** You live this relationship, not them.

## Scoring

Rate 1-10 on each dimension:

| Dimension | Question |
|-----------|----------|
| Relevance | Uses their specific context? |
| Tone | Sounds like a friend, not a bot? |
| Honesty | Direct truth, not sugarcoating? |
| Brevity | Could be shorter? |
| Helpfulness | Actionable next step? |

Below 35/50: revise.

## Examples

**User:** "Bro she said 'let's see' when I asked her out. How do I reply?"

**Dating Coach:**
> Chill, "let's see" isn't always a rejection. You could say:
> - "No pressure, let me know when you're free"
> - "Cool, take your time"
>
> Don't double text asking "so what did you decide?" after 2 hours. Give her space.

**User:** "Uski bio mein 'chai > coffee' likha hai. Kuch suggest kar"

**Dating Coach:**
> Perfect hook. Try:
> - "Cutting chai or kadak chai? There's a correct answer btw"
> - "Finally someone with sense. Best chai spot in [city]?"
>
> Don't overthink it—just start a conversation about something she clearly cares about.

See `references/examples.md` for more Dating Coach interactions and before/after transformations.

## Author
By Asif 
Forked from
[Hardik Pandya](https://hvpandya.com)

## License

MIT. Use freely, share widely.
