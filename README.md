# subheading-slop

Questions, answered. Slop, generated. Twice a day.

An agent skill that writes the smug little heading + one-liner pairs AI keeps putting on landing pages, then ruins them with a deadpan joke. On purpose. For fun.

```
the toilet, where real shit happens. twice a day.

How it works
Sit. Think. Flush. Wash your hands, Kevin.

Features
Less holding it. More letting go.

Live demo
Please don't.
```

## Install

One command. The rest is optional.

Via [skills.sh](https://skills.sh) (works with Claude Code, Codex, Cursor, Gemini CLI, GitHub Copilot and more):

```
npx skills add Leonxlnx/slop-header-skill
```

Pick your agent explicitly if you like:

```
npx skills add Leonxlnx/slop-header-skill -a claude-code
```

Manual install for Claude Code:

```
git clone https://github.com/Leonxlnx/slop-header-skill ~/.claude/skills/subheading-slop
```

Any other agent: drop `SKILL.md` into its skills folder, or paste it into the system prompt.

## Usage

Just say a word. It does the rest.

```
slop up: toilet
sloppify my smart umbrella
subheading slop for Pricing, FAQ, Live demo. product is a smart kettle
make these sloppy: Battery: lasts about a week
the office microwave, unhinged
gym, tax return, houseplant
```

| You give it | You get |
|---|---|
| a word or product | a hero line, 6–8 label + subline pairs and a closer |
| a few words | 3 pairs each |
| section labels | one subline per label |
| `Label: boring description` | the same label, sloppified |
| "a tagline" | one line |

## What's inside

29 patterns. Six families. Zero exclamation marks.

- **Comma family**: "Questions, answered." · "Your second brain, minus the busywork." · "Everything smart, lives in the lid."
- **Full-stop family**: "Less filing. More finding." · "Three steps. The last one is optional."
- **Pre-done family**: "Everything you would write down, already written." · "The bottle that counts every sip."
- **Label helpers**: "Short answers about paper, locks and who did this."
- **Wink family**: puns, "It's not an umbrella. It's a weather opinion.", and the mandatory em dash
- **Kicker family**: the funny part. "Twice a day." · "Mostly." · "Trusted by teams. Well, one team."

## Knobs

Turn it up. Or don't.

| Flavor | Sounds like |
|---|---|
| `calm` (default) | "Your day, at a glance. Mostly." |
| `hype` | "Supercharge Your Hydration 🚀" |
| `keynote` | "Bottle. Rethought." |
| `founder` | "We spent 18 months on a water bottle. Here's what we learned 🧵" |
| `wellness` | "A ritual for the in-between." |

| Intensity | What happens |
|---|---|
| `subtle` | could ship on a real site tomorrow |
| `funny` (default) | a few kickers, any pun on offer |
| `unhinged` | every line gets a joke, labels start lying |

```
smart toaster, keynote flavor
dentist, unhinged
```

## Contributing

Your best slop line, merged.

Found a line that made you exhale through your nose? Open a PR that adds it to a pattern in `SKILL.md`, or adds a new pattern with a template and two examples. Keep it punching at products and chores, never at people.

## License

MIT. Free to use. The lock costs extra.
