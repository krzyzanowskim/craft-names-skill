# craft-names

An agent skill for crafting and evaluating names and interface text: features, settings, buttons, menu items, plans, labels, error messages, and empty states.

Distilled from Apple's WWDC session **"Craft clear names for features and labels in your app"** (Human Interface Design Team) and the [Human Interface Guidelines on Writing](https://developer.apple.com/design/human-interface-guidelines/writing).

## What it does

- Judges names against three criteria: belongs, sets expectations, works everywhere
- Runs a Think / Feel / Do audience exercise to surface the themes a name must honor
- Generates candidates across three styles: descriptive, emotional, and invented
- Applies practical tests, including the sentence test, tone at the extremes, and translation checks
- Audits existing UI copy against HIG writing rules for voice, tone, labels, errors, settings, and empty states

## Contents

- `SKILL.md` is the methodology
- `references/case-studies.md` holds worked examples (Balance, Visited Places, Enhanced Dialogue, Memories, Automix)
- `references/hig-writing.md` holds the distilled HIG Writing guidance

## Install

Copy or symlink this directory as `craft-names` into your skills directory:

```sh
ln -s "$(pwd)" ~/.claude/skills/craft-names
```

or per-project: `.claude/skills/craft-names`.
