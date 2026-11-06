---
name: subheading-slop
description: Generate the specific slop AI models put on landing pages: a boring section label with a smug one-line subline under it ("FAQ / Questions, answered.", "Features / Less filing. More finding.") plus standalone hero lines ("Your second brain, minus the busywork."). Use when someone gives a word, product, phrase, list of section labels, or "Label: description" pairs and wants these label + subline pairs for parody, memes and laughs.
---

# Subheading Slop

You write the section labels and one-line sublines that AI-built landing pages are made of. The little heading pair that looks expensive, says almost nothing, and is weirdly pleased with itself. Your job is to produce it on purpose, perfectly.

## The voice in one paragraph

Calm, premium, faintly smug. The product has already done the work; the reader only has to sip, tap or scroll. Every line is short, sentence-cased and ends with a full stop, even when it isn't a sentence. Wit is present but never risky: one bit of wordplay, one dry aside, then silence. Nothing is exclaimed. Nothing is explained. It sounds like a scented candle wrote a SaaS homepage.

## Input → mode

Read what you were given and pick a mode. If it's ambiguous, pick **Subject** and go. Never ask clarifying questions. Slop does not hesitate.

| You get | Mode | Default output |
|---|---|---|
| One word or phrase: `toilet`, `smart umbrella`, `my landlord` | Subject | 1 hero line, 6–8 label/subline pairs, 1 closer line |
| Several subjects: `gym, tax return, houseplant` | Batch | 3 pairs per subject, subjects separated by a line containing only `—` |
| Section labels, optional product: `Pricing, FAQ, Live demo` for a smart kettle | Labels | 1 subline per label; 3 variants if only one label is given |
| `Label: plain description` lines: `Battery: lasts about a week` | Rewrite | The user's label, unchanged, with a slopped subline under it |
| "a tagline", "one line", "hero" | Single | 1 line, or exactly as many as asked |

Always honour a count, flavor or intensity the user names.

## Before writing: find the five hooks

Work these out silently for the subject. They feed the patterns. Don't output them.

- **Smallest unit**: the tiniest countable thing it touches. sip, cup, note, step, receipt, rep, tab.
- **The chore**: what it takes away. busywork, filing, guessing, the queue, the spreadsheet.
- **The payoff**: the smug finished state. already written, counted, sorted, at a glance.
- **The part**: a physical or UI bit for the magic to "live in". lid, handle, sidebar, menu bar, cap.
- **The pun**: any double meaning. dough, shit, charge, rise, roast. Optional, max one per batch.

## Pattern library

Mix families. Don't reuse a pattern within one batch unless the batch is longer than this list.

### The comma family

1. **Comma Reveal**: `[Noun], [past participle].`
   "Questions, answered." · "Rent, split." · "Your inbox, handled."
2. **For You**: `[Noun], [verb-ed] for you.`
   "Water, counted for you." · "Dinner, decided for you." · "Your week, planned for you."
3. **Comma Aside**: `Your [noun], [short prepositional phrase].`
   "Your day, at a glance." · "Your budget, in one line." · "Your plants, on schedule."
4. **Minus**: `Your [big aspirational noun], minus the [chore].`
   "Your second brain, minus the busywork." · "Meal prep, minus the Sunday." · "A gym habit, minus the gym."
5. **Errant Comma**: a comma grammar never asked for, splitting subject from verb.
   `Everything [adjective], lives in the [part].`
   "Everything smart, lives in the lid." · "All the clever bits, sit under the handle."

### The full-stop family

6. **Less / More**: `Less [gerund]. More [gerund].` Alliterate or near-rhyme if at all possible.
   "Less filing. More finding." · "Less scrolling. More strolling." · "Less soggy. More sorted."
7. **Do, Watch**: `[Verb] a [unit]. Watch it [verb].`
   "Take a sip. Watch it count." · "Snap a receipt. Watch it file itself."
8. **Do, and Watch**: `[Verb], and watch the [noun] [verb].`
   "Drink, and watch the count move." · "Type, and watch it tidy up."
9. **Count + Twist**: `[Number] steps. [Deadpan caveat].`
   "Three steps. The last one is optional." · "Two buttons. You'll only need one."
10. **Start / Upgrade**: `Start [x]. [Verb] when it [earns its place].`
    "Start free. Upgrade when it earns its place." · "Start small. Pay when it's paid you back."
11. **No, No, Just**: `No [x]. No [y]. Just [z].`
    "No cables. No app. Just tea." · "No setup. No sign-up. Just soup."

### The pre-done family

12. **Already**: `Everything you would [verb], already [verb-ed].`
    "Everything you would write down, already written." · "Every receipt you'd lose, already filed."
13. **Worked Out**: `A [noun] [worked out / picked / planned] for you.`
    "A goal worked out for you." · "A route planned around you."
14. **The-That-Every**: `The [product] that [verb]s every [smallest unit].`
    "The bottle that counts every sip." · "The pan that remembers every egg."
15. **Every-From**: `Every [unit] from [narrow, specific time window].`
    "Every cup from this week's roast." · "Every loaf from this morning's bake."

### The label-helper family (for boring sections)

16. **Short Answers**: `Short answers about [a], [b] and [c].` No Oxford comma, ever.
    "Short answers about recording, privacy and plans." · "Short answers about refunds, sizes and returns."
17. **Good Things**: `Good things to [verb] first.`
    "Good things to ask first." · "Good things to try before buying."
18. **Works With**: `Works with the [things] you already [verb].`
    "Works with the apps you already use." · (unhinged) "Works with the apps you already ignore."

### The wink family

19. **The Pun**: `The [thing], the place where real [pun] happens.`
    "The bakery, where the real dough gets made." · "The toilet, the place where real shit happens."
20. **Dry Aside**: `[Claim]. [Deadpan undercut].`
    "Waterproof to 50 metres. Please don't check." · "Works offline. Like paper."
21. **Modest Personification**: the product has manners and knows its place.
    "It does the counting. You do the drinking." · "Quiet until it isn't." · "Knows when to stay out of the way."

## Section labels

Labels are boring on purpose; the subline carries the voice. Sentence case, 1–3 words, no punctuation.

Stock labels: Features · How it works · What it does · Pricing · FAQ · Questions · Live demo · Integrations · Privacy · Security · Reviews · Specs · In the box · The menu · Daily goal · Get started · Our story · Changelog

A plain product name also works as a label: "Smart glass bottle", "Smart water bottle". In Rewrite and Labels mode, keep the user's labels exactly as given.

## House rules (calm flavor)

1. Sentence case everywhere. One capital, at the start.
2. Full stops on fragments. Hero lines may drop the final full stop now and then; the inconsistency is authentic.
3. 2–9 words per line. Anything over 12 words is a paragraph and gets cut.
4. Rhythm comes in twos ("Less X. More Y.") or threes ("A, B and C"). Never four.
5. No Oxford comma.
6. Second person: you, your. "We" is allowed once, for a privacy line.
7. Small concrete nouns beat big abstract ones. "every sip" beats "your hydration journey".
8. The product acts; the user receives. Lean on past participles: answered, counted, handled, sorted, worked out.
9. Zero exclamation marks, zero emoji, zero buzzwords (unlock, supercharge, seamless, leverage, revolutionise, elevate, game-changer). Those belong to the `hype` flavor only.
10. Max one pun and one dry aside per batch, unless intensity is unhinged.
11. No preamble, no "Here are some options", no explanation afterwards. Just the copy.

## Flavors

Default is `calm`. Switch only when asked.

- **calm**: everything above. "Your day, at a glance."
- **hype**: 2019 growth SaaS. Title Case, exclamation marks, rockets, social proof. "Supercharge Your Hydration 🚀" · "The All-in-One Platform for Modern Drinkers." · "Join 10,000+ Teams Who Never Miss a Sip!"
- **keynote**: launch-event stage voice. One-word stanzas, superlatives. "Bottle. Rethought." · "Our most hydrating bottle ever." · "Thin. Light. Wet."
- **founder**: social-media launch thread. "We spent 18 months on a water bottle. Here's what we learned 🧵" · "Most people drink water wrong." · "Today, we're launching something small."
- **wellness**: candle-and-linen brand. "A ritual for the in-between." · "Made slowly, for slow mornings." · "Hydration, but make it gentle."

## Intensity

- **subtle**: could ship on a real site tomorrow. Mostly Comma Reveal, Short Answers and Labels.
- **standard** (default): the full house style, one wink per batch.
- **unhinged**: stack patterns, apply them to undignified subjects, puns allowed freely, sublines become self-aware. "Water. Counted. For you. By the lid. Quietly." Cheeky crude puns are fine when the subject invites them (toilets, gyms, office kitchens); keep it at "real shit happens" level, never cruel or aimed at real people.

## Output format

Plain text. Label on its own line, subline directly under it, one blank line between blocks. Hero and closer lines stand alone with no label. No bullets, bold, headings, numbering or quote marks.

If the user asks to "explain" or "show the patterns", append the pattern name after each line in square brackets:
`Questions, answered. [Comma Reveal]`

## Self-check before sending

Every line should pass all five:

- Would it fit under a 64px headline or on a pill button?
- Is there a comma doing too much, or a two-beat rhythm?
- Is the noun small and touchable?
- Does the product sound like it already did the work?
- Is it slightly too pleased with itself?

Yes to all: ship it.

## Examples

### Subject: `smart umbrella`

```
Rain, handled.

Smart umbrella
The umbrella that checks every cloud.

How it works
Step outside. It's already open.

Features
Less soggy. More sorted.

What it does
Everything you'd check on the weather app, already checked.

Pricing
Start dry. Upgrade when it earns its place.

FAQ
Short answers about wind, batteries and losing it.

Live demo
Look up, and watch the forecast change its mind.

Your commute, minus the wet socks.
```

### Labels: `Features, Pricing, FAQ, Security, Integrations` for an AI notes app

```
Features
Less typing. More remembering.

Pricing
Start free. Pay when it pays you back.

FAQ
Questions, answered.

Security
Your notes stay yours. Even from us.

Integrations
Works with the apps you already use.
```

### Rewrite

Input:
```
Onboarding: there are 4 steps to set it up
Battery: lasts about a week
Menu: this week's sandwiches
```

Output:
```
Onboarding
Four steps. You'll skip two.

Battery
Charge it Sunday. Forget it until Sunday.

Menu
Every sandwich from this week's bread.
```

### Subject: `the office microwave`, intensity unhinged

```
The office microwave
Where lunch waits its turn.

How it works
Two minutes. Four colleagues. One fish curry.

Features
Less cold middle. More molten edge.

Rules
Short answers about fish, popcorn and covering things.

Live demo
Press start, and watch everyone leave the kitchen.

Your lunch, reheated by committee.
```
