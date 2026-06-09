# Naming case studies

Worked examples distilled from the Apple WWDC session "Craft clear names for features and labels in your app". Use these to pattern-match. Each one shows a naming problem, the candidates considered, why they failed, and why the winner works. Cite the relevant case when explaining a recommendation.

## Balance (Apple Cash): when the obvious word wins

**Problem:** Label the amount of money available to send, shown right next to the send button.

| Candidate | Verdict |
|---|---|
| Spending Power | Compelling but not concrete. It raises questions (credit limit? a score?), and in a financial context ambiguity alone disqualifies it. It also fails the tone test: "Spending Power: $0" reads as a judgment, and payment services run on trust. |
| Current Funds | Accurate but spreadsheet language. The sentence test fails because nobody says "let me check my current funds." |
| **Balance** ✓ | The industry-standard term: well understood, clear, and neutral in every state. It belongs, sets exactly the right expectation, and travels without friction. |

**Lesson:** Clarity and trust come before brand expression in high-stakes contexts. Sometimes the most obvious word is right because it's already doing the job.

## Basic Access / All Access (gym app plans): the brand trade-off

**Problem:** Name two subscription tiers.

"Lightweight" and "Heavyweight" are fun and on-brand for a gym, but they add a learning curve exactly where the user is making a purchase decision. What do they actually mean? That friction makes choosing harder. "Basic Access" and "All Access" are instantly comparable.

**Lesson:** Branded names aren't wrong; they just carry extra work to make themselves understood. Decide deliberately whether the brand payoff is worth it at that spot in the flow, given what the user is trying to do there.

## Visited Places (Apple Maps): the Think/Feel/Do exercise end-to-end

**Problem:** Name a feature that remembers places you've been. It was built with privacy in mind: encrypted, unreadable by Apple.

**Exercise:** The audience is people trying to recall a café from last week or a park with accessible trails. Brainstormed Think/Feel/Do notes clustered into three themes: ease (find it without effort), excitement (the fun of rediscovering a place you loved), and security (the privacy work has to come through).

Candidates like "Private Memories" were culled. Some didn't fit the app, some were vague, some wouldn't translate. The sentence test was applied: "Hey, check out ___." and "Just search for ___."

**Winner:** **Visited Places.** Descriptive, clear, and already at home in an interface that says "places" throughout. It sets the right ownership expectation (these are *your* places, unreadable by Apple) and works across languages.

**Lesson:** Themes from the audience exercise turn abstract criteria into specific, testable requirements. Existing app vocabulary is a strong signal that a name belongs.

## Memories (Apple Photos): clarity from emotion

**Problem:** Name an algorithmic feature that surfaces photo groupings that matter: a birthday, a trip, a Tuesday worth remembering.

The person on the other end just found a video of a laugh they hadn't heard in years. They aren't thinking about algorithms; they're looking for a memory. A technical label like "Photo Groupings" could never meet them there.

**Lesson:** Descriptive isn't the only path to clear. "Memories" is still straightforward, but its clarity comes from emotion rather than explanation. Name the meaning, not the mechanism.

## Enhanced Dialogue (Apple Podcasts): iterating toward the answer

**Problem:** Name a playback feature that isolates voices and reduces background noise. It lives in the same menu as playback speed.

| Candidate | Verdict |
|---|---|
| Vocal Isolation | An audio-engineering term. It describes what the technology does, not what you experience. |
| Isolate Vocals | The right instinct (a verb puts the user in control, since the feature is something you *do*) but the wrong vocabulary. |
| Clarify Speech | Closer, but it tells only half the story. |
| Enhance Playback | Puts the feature before the person. What's enhanced? For whom? |
| **Enhanced Dialogue** ✓ | Answers both questions before you tap, fits the context, and delivers exactly what it promises when enabled. As a bonus, the same name already exists on Apple TV for a similar feature, which is precedent that it belongs. |

**Lesson:** Iterate by asking what each candidate fails to answer. Cross-product precedent is evidence that a name belongs.

## Automix (Apple Music): the invented word that explains itself

**Problem:** Name a setting that blends song transitions automatically, like a DJ, so playback never stops.

**Auto** (it happens without you) plus **mix** (it blends songs) forms a word that doesn't exist yet is understood immediately. The invented word earns its clarity from its parts, so it never has to explain itself.

**Lesson:** Coined names are legitimate, including for non-hero features, when each part carries its meaning. Invented and opaque is the failure mode; invented and self-evident is the win.
