# Interface writing guidance (Apple Human Interface Guidelines: Writing)

Distilled from the Human Interface Guidelines "Writing" page (developer.apple.com/design/human-interface-guidelines/writing). Names are one kind of interface text; this covers the rest — voice, tone, labels, errors, settings, empty states — and the rules that apply to all of it.

## Voice and tone

- **Determine the app's voice first.** Think about who you're talking to and what vocabulary is familiar to them. How should they feel? A banking app's words convey trust and stability; a game's convey excitement and fun. Keep a list of common terms and reference it to stay consistent — consistent language plus a voice that reflects the app's values makes everything feel cohesive.
- **Voice is constant; tone varies with context.** Consider what people are doing — in the physical world and in the app — when they hit this text. Reaching a fitness goal warrants a light, congratulatory tone; a failed payment or a health alert warrants straightforward and direct. Situational factors affect both what you say and how it's displayed.
- **Write for everyone.** Use simple, plain language. Avoid jargon and gendered terminology. Write with accessibility (screen readers) and localization in mind from the start.

## Clarity and economy

- **Be clear.** Choose words that are easily understood and convey the right thing. Check each word to be sure it needs to be there; if fewer words work, use fewer. When in doubt, read it out loud.
- **Consider each screen's purpose.** Put the most important information first. Format text for easy reading. If conveying more than one idea, consider splitting across screens and think about the flow of information between them.
- **Choose the right delivery method.** Match the message's urgency and importance to the mechanism — notification, alert, action sheet, inline text — and use a tone appropriate to the situation. Think about the context in which someone sees it, whether it requires immediate action, and how much supporting information they need.

## Labels: buttons, links, and actions

- **Be action oriented.** Active voice and clear labels move people from step to step. For buttons and links, a verb is almost always best.
- **Clarity over cleverness.** "Send" works better than "Let's do it!" Resist cute or clever labels at action points.
- **Never "Click here."** Use descriptive link text ("Learn more about UX Writing") — essential for screen-reader users.
- **Use the right gesture words per device.** "Tap" on iPhone/iPad, "click" on Mac. Never "click" for a touch device.
- **Multi-step flows: pick a vocabulary and stick to it.** Open with something like "Get Started." Move forward with "Continue" or "Next" (or a label hinting at the next step) — but be consistent with whichever you choose. Signal completion explicitly with language like "Done."

## Consistency and patterns

- **Build language patterns.** Consistency builds familiarity and makes the app feel cohesive, intuitive, and thoughtfully designed — and makes future writing easier because you return to the same patterns.
- **Adopt capitalization rules and apply them consistently.** Title case reads formal; sentence case reads casual. Choose a style per UI element type (e.g., title case for all alerts, sentence case for all headlines) and never mix within a type.
- **Use possessive pronouns sparingly.** "Favorites" says the same as "Your Favorites," more succinctly. If you do use them, use them consistently and don't switch perspectives (my/your).
- **Never "we."** It's unclear who "we" refers to, especially in errors. "Unable to load content" beats "We're having trouble loading this content."

## Error messages

- **Best error is no error** — help people avoid them in the first place. If language alone can't fix an error that will affect many people, rethink the interaction itself.
- **Display the error as close to the problem as possible** (e.g., right next to the offending field).
- **Avoid blame; say how to fix it.** "Choose a password with at least 8 characters" beats "That password is too short." Instruct positively: "Use only letters for your name" beats "Don't use numbers or symbols."
- **No insincere interjections.** "Oops!" and "uh-oh" are unnecessary and read as insincere — errors are frustrating moments.
- **No robotic dead-ends.** "Invalid name" gives no help at all.

## Settings

- **Label settings as practically as possible.** If the label isn't enough, add an explanation describing what happens when the setting is *on* — people infer the off state (Apple Watch's Handwashing Timer explains a timer starts when you wash your hands; it doesn't also say one won't start when off).
- **Link, don't describe locations.** To send someone to a setting, give a direct link or button rather than describing where to find it.

## Empty states

- **A blank screen is an opportunity, not a void.** Welcome people and educate them about the app; empty states can carry the app's voice — as long as the content is useful and fits the context.
- **Always provide a next step.** An empty screen is daunting if it isn't obvious what to do; guide people to an action with a button or link.
- **Don't park crucial information there.** Empty states are usually temporary; anything important shown only there will disappear.

## Text fields

- **Label every field clearly** and use hint/placeholder text to show the expected format — an example ("name@example.com") or a description ("Your name").
- **Errors next to the field**, phrased as instruction, not scolding.

## Writing per device

Language must stay consistent across devices, but adjust where it helps:

- **iPhone / Apple Watch** — small screens demand brevity; good opportunities for personalization.
- **TV** — a shared screen in a common space: consider that several people see it, and the large viewing distance demands large text, which again demands brevity.
- **Match the input model** — gestures, pointers, remotes, and voice each have their own verbs.
