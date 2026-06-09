---
name: craft-names
description: >-
  Craft and evaluate names and interface text for an app or product —
  features, settings, buttons, menu items, tabs, plans, labels, error
  messages, empty states, and onboarding copy. Use when the user asks "what
  should I call this?", wants to brainstorm or compare name candidates, asks
  for a review of UI copy/labels/microcopy, or is writing anything users read
  in an interface. Distilled from Apple's WWDC session "Craft clear names for
  features and labels in your app" and the Human Interface Guidelines on
  Writing: three criteria (belongs, sets expectations, works everywhere), a
  Think/Feel/Do audience exercise, evaluation tests, and HIG rules for voice,
  tone, labels, and errors.
---

# Craft Names

Distilled from the Apple WWDC session "Craft clear names for features and labels in your app" (Human Interface Design Team) and the Human Interface Guidelines on Writing.

A name is interface. It shapes whether someone finds a feature, trusts it, and feels at home in the app. This skill walks from audience to candidates to a defensible final pick. Don't just generate a list of names — run the process below and show the reasoning.

## The three criteria

Judge every candidate against these. A name doesn't have to pass all three — but you must be able to say which one you're trading away and why.

1. **Belongs** — Fit. Does it sound like this app, sit naturally alongside everything else already named, and match what users expect to find in that spot? Reuse the app's existing vocabulary (if the app says "places" everywhere, a feature about places should too). Check for precedent: if the same name already labels a similar feature elsewhere in the product family or platform, that's strong evidence it belongs.
2. **Sets expectations** — Clarity and trust. Someone reading the name is already predicting what they'll find. The right name delivers exactly that, and trust builds. A name that overpromises, underpromises, or is ambiguous breaks trust — especially in high-stakes contexts (money, health, privacy, security), where ambiguity is disqualifying.
3. **Works everywhere** — Travel. Does it hold up across languages, markets, platforms, screen sizes, and every context where it appears (menu, notification, search result, spoken aloud by a voice assistant)? Puns, idioms, and culturally loaded words usually fail here.

Users may add criteria of their own (trademark, regulation, SEO). Treat the three as a guide, not a rulebook — the trade-offs belong to the user.

## The process

### 1. Audience first

Never name by what the thing does technically. Name by what it does *for the person using it*. Before generating anything, establish: who is this for, and what are they trying to do in the moment they encounter this name? If the user hasn't said, ask — or state your assumption explicitly.

### 2. Think / Feel / Do

With the audience in mind, brainstorm (alone or facilitate it with the user), one idea per line, no filtering yet:

- **Think** — What should they think when they encounter this? (e.g., "this is easy," "this is clever," "this is safe")
- **Feel** — What should they feel? (e.g., delight at rediscovery, security that it's private)
- **Do** — What should they do? (find it, turn it on, share it)

Quantity over quality here. You're hunting for themes, not the perfect word.

### 3. Group into themes

Step back and cluster the ideas — different words pointing at the same feeling. Two to four themes is typical (e.g., ease, excitement, security). These themes are what the final name must honor; they turn the abstract criteria into something specific and testable.

### 4. Generate candidates

Produce a wide slate across the three styles of clarity — don't anchor on one:

- **Descriptive** — says what it is, in the user's language, not the engineer's ("Enhanced Dialogue," not "Vocal Isolation"). For features the user actively controls, prefer a verb phrase — the feature is something you *do*, not something you *have*.
- **Emotional/evocative** — meets the user at the meaning, not the mechanism ("Memories" for algorithmic photo grouping — the person isn't thinking about algorithms; they're looking for a memory). Clarity from emotion, not explanation.
- **Branded/invented** — a coined word that earns instant clarity from its parts ("Automix" = auto + mix). Invented is fine when the parts explain themselves; invented-and-opaque is not.

Also always consider the boring industry-standard term ("Balance"). Sometimes the most obvious word is right precisely because it's already doing the job. Clarity and trust usually beat brand expression — lean branded only when the context is low-stakes and the brand payoff is worth the learning curve, and say so explicitly when recommending it.

### 5. Cull and test

Cross out candidates that fail on sight (don't fit the app's voice, vague, won't translate, sound like a spreadsheet). Then run the surviving candidates through the tests:

- **Sentence test**: drop the name into real sentences a user would read or say. "Hey, check out ___." "Just search for ___." "Turn on ___ in Settings." A name that sounds natural spoken aloud is worth exploring; one that sounds stilted ("let me check my current funds") fails the gut check.
- **Tone-at-the-extremes test**: read the name next to its worst-case value or state. "Spending Power: $0" stops being a label and starts feeling like a judgment. Names near money, health, or personal data must stay neutral in every state.
- **Question test**: does the name answer questions or raise them? "Enhanced Playback" raises "what's enhanced, for whom?"; "Enhanced Dialogue" answers both before you tap.
- **Promise test**: when the user taps/enables it, do they get exactly what the name promised?
- **Travel test**: any idioms, puns, or words with awkward translations or unfortunate meanings in major markets? Does it still work truncated, in a notification, spoken by a voice assistant?

### 6. Recommend with reasoning

Present the final shortlist (2–4 names) in a comparison against the three criteria plus the themes from step 3. Make one recommendation and name the trade-off (e.g., "leans clarity over brand"). If the user's context suggests different priorities — a playful game vs. a banking app — say which criterion you weighted and invite them to reweigh.

## Red flags in candidates

- Named after the technology or internal function, not the user benefit ("Vocal Isolation," "Algorithmic Grouping")
- Marketing-speak that's compelling but not concrete ("Spending Power")
- Spreadsheet language nobody says out loud ("Current Funds")
- Clever/branded names that add a learning curve at a decision point ("Lightweight/Heavyweight" plans instead of "Basic/All Access") — acceptable only if the brand fit is worth the extra explaining
- A label that reads as judgment in some state of the data
- Inconsistent with vocabulary already established elsewhere in the app
- A made-up word whose parts don't explain it

## Beyond names: interface writing rules

Names live inside the rest of the app's text. When the work touches labels, errors, settings, or flows — or when reviewing copy broadly — apply these baseline rules (full guidance in [references/hig-writing.md](references/hig-writing.md)):

- **Voice is constant, tone varies with context.** Establish the app's voice from its audience and values; shift tone with the situation (congratulating a fitness goal vs. reporting a failed payment).
- **Buttons and links take verbs.** "Send" beats "Let's do it!"; never "Click here" — descriptive link text matters doubly for screen readers. Use device-correct gesture words (tap on iPhone, click on Mac).
- **Fewer words, read aloud.** Check that each word earns its place; if in doubt, say it out loud.
- **Pick one capitalization style per UI element type** (e.g., title case for alerts, sentence case for headlines) and never mix.
- **Possessives sparingly, "we" never.** "Favorites" over "Your Favorites"; "Unable to load content" over "We're having trouble…".
- **Errors: no blame, no "oops," say the fix.** "Choose a password with at least 8 characters" beats "That password is too short." Show the error next to the problem.
- **Flows use one consistent vocabulary**: open with "Get Started," advance with the same word throughout ("Continue" *or* "Next"), close explicitly with "Done."
- **Settings describe the on state only**; empty states always offer a next step and never hold crucial info.

## Reviewing existing names and copy

When asked to audit existing labels/names rather than invent new ones: inventory the names, check each against the three criteria, the tests above, and the interface writing rules; flag inconsistent vocabulary across the app (the same concept named two ways, one word meaning two things, mixed capitalization, mixed flow verbs); and propose replacements using the full process for any that fail. Names build on each other — every good one makes the next easier, and together they become the language of the app.

## References

- [references/case-studies.md](references/case-studies.md) — worked naming examples to pattern-match against (Balance, Visited Places, Enhanced Dialogue, Memories, Automix)
- [references/hig-writing.md](references/hig-writing.md) — full HIG Writing guidance: voice and tone, labels, errors, settings, empty states, text fields, per-device writing
