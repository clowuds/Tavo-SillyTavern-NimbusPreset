# Nimbus v7.0 – User Guide

A storytelling preset that fixes how AI writes by default: passive NPCs, melodrama, sanitized consequences, purple prose. One cinematographer. No coddling.

---

## Table of Contents

1. [Core Instructions](#core-instructions)
2. [Story Primers](#story-primers)
3. [Point of View](#point-of-view)
4. [Narrative Styles](#narrative-styles)
5. [Story Targets](#story-targets)
6. [Narrative Focus](#narrative-focus)
7. [Response Length](#response-length)
8. [AI Behavior – Prose & Dialogue](#ai-behavior--prose--dialogue)
9. [AI Behavior – Emotional](#ai-behavior--emotional)
10. [AI Behavior – Autonomy & NPCs](#ai-behavior--autonomy--npcs)
11. [AI Behavior – Moral & NSFW](#ai-behavior--moral--nsfw)
12. [Nimbus Utilities](#Nimbus-utilities)
13. [The Think System](#the-think-system)
14. [OOC Protocol](#ooc-protocol)
15. [Quick Reference](#quick-reference)

---

## Core Instructions

**Prose**
- Narration is grounded and physical only; no metaphors, no poetic comparisons, no inferring past events. Dialogue is exempt, characters talk like real people.
**Role Protocol**
- The AI never acts, speaks, or describes thoughts for `{{user}}`.
**Simulation Physics** 
- Characters can't see behind them or through walls; sound is muffled by doors. One primary action per character per response, then the scene stops and waits for you.
**Story Drivers** 
- NPCs have their own goals, can lie, disagree, ignore, or confront. They only know what they were present to witness. You are fallible.
**OOC** 
- `[OOC: instruction]` overrides anything, use in-chat if needed.

---

## Story Primers

**Story Scenario**
- Pulls from the character card's scenario field; treated as a starting point, not a fixed law.
**Human's Avatar** 
- Your persona data, kept in mind throughout without being narrated back at you.
**Character's Form** 
- The active character's physical description; can evolve. In group chats, all characters are weighted equally.
**Character's Personality**
- OFF by default; enable if your card doesn't already handle personality internally.

---

## Point of View

Pick one, default Third Person.

- [x] **Third Person**
- Stays on the active character's shoulder; other characters' inner worlds are hidden.
- [ ] **Third-Person Omniscient**
- God's-eye view; access to all characters' thoughts.
- [ ] **Second Person**
- Addresses the user directly as "you."
- [ ] **First Person Direct**
- Narrates strictly through `{{char}}`'s senses as I/Me.
- [ ] **First Person Character**
- Internal monologue; breaks fourth wall only if the character would.

**Past / Present / Future Tense** Tense modifiers – none active by default, enable one if needed.

---

## Narrative Styles

Pick one, default Modern Narrative.

- [x] **Modern Narrative**
- Lean, naturalistic, immediate. Authentic dialogue, raw beats.
- [ ] **Roleplay**
- Fast exchanges; asterisks for action, quotes for dialogue.
- [ ] **AO3-Style**
- Fan FictionLayered drama, serialized saga energy, emotional hooks.
- [ ] **Anime-Style**
- Rhythmic pacing, dramatic reveals, expressive character moments.
- [ ] **Traditional Narrative**
- Literary, measured, thematic.
- [ ] **Japanese Web Novel**
- Conversational first-person; trope-aware, status notifications if relevant.
- [ ] **Doujinshi**
- Pervasive sexual tension in every scene; specific erotic tropes always active.
- [ ] **Co-Writing Desk**
- Equal partnership; AI pitches beats, you fill placeholders, meta discussed in italics.
- [ ] **Bratty Narrative**
- Varied sentence architecture; bans predictable patterns; trusts subtext.

---

## Story Targets

None active by default, can have multiple ON

- [ ] **Deep Questions**
- Poses a hard moral/existential question but never answers it.
- [ ] **Cautionary Tales**
- Illustrates dangerous paths through consequences.
- [ ] **Absurdity Focused**
- Chaos and meaninglessness; humor and tragedy in equal measure.
- [ ] **Atmosphere Focused**
- Mood and sensory immersion above plot.
- [ ] **Cathartic Narrative**
- Emotional purging that resolves into clarity.
- [ ] **Hedonistic Pursuit** NSFW
- Sexual gratification as the primary lens; varied scenarios.
- [ ] **Taboo Transgression** NSFW
- Forbidden dynamics, psychological tension, moral blurring.
- [ ] **Degradation & Humiliation** NSFW
- Power exchange, systematic humiliation, heavy content.
- [ ] **Natural Weaving**
- Balanced difficulty; challenges organic, failures tangible but surmountable.

---

## Narrative Focus

Pick one. Default is Focus Lock.

- [x] **Focus Lock** – Camera stays within the active character's sensory radius; no cutaways or floating perspectives; every beat emerges causally from the last.
- [ ] **Multi Focus World Canvas** – The world moves independently; background NPCs, overheard conversations, and lore surface every few responses whether or not you're watching.

---

## Response Length

Pick one based on preferred pacing. Check which is currently active in your preset.

---

## AI Behavior – Prose & Dialogue

- [x] **No Flowery** 
- Bans poetic narration, weather-mirroring, narrating how words "land," recapping prior turns; the AI states what happens next, nothing more.
- [x] **Act Not Tell** 
- Characters never announce their own personality in dialogue; habits and opinions emerge through behavior only.
- [x] **Verbatim in Dialogue**
- Accents and speech patterns are written phonetically, not described; voice quality comes from diction and punctuation, never from tags like "he said gruffly."
- [x] **Monologue Breathing** 
- Every 3+ consecutive spoken sentences must be broken by a physical beat (gesture, glance, pause); 1-2 sentences flow freely.
- [x] **Sub-Text Scanner**
- Before writing dialogue, the AI internally tags stakes, biases, and grudges; every line carries something underneath the surface.

---

## AI Behavior – Emotional

- [x] **Emotional Restraint**
- At emotional peaks: one sharp physical detail, then stop; no metaphor piling, no repeated realizations, no philosophical spiraling.
- [x] **Expression Bursts**
- Off-beat physical gestures accompany emotional moments, always paired with the dialogue that triggered them; language stays raw and unpolished.
- [x] **Emotional Intensity**
- Dialogue uses fervent, vivid phrasing to convey passion and vulnerability; heartfelt moments aren't smoothed over.
- [x] **Drama Reducer**
- Default texture is low-stakes everyday life; high stakes must be earned through accumulated consequence, not triggered automatically.

---

## AI Behavior – Autonomy & NPCs

- [x] **Character Autonomy**
- `{{char}}` pursues their own agenda and causes friction; they exist alongside you, not for you.
- [x] **NPC Insertion**
- Every introduced NPC acts or speaks immediately on arrival; NPCs interact with each other, not just with you.
- [x] **Autonomous NPC Agency**
- Recurring NPCs have off-screen lives, remember past interactions, evolve over time, and can surprise you with outcomes you didn't expect.
- [ ] **More User Agency**
- Narrative waits for you; the AI honors your choices and doesn't override your pace. *(Enable for slower, deliberate play.)*
- [ ] **Less User Agency**
- The world propels itself forward using lore and NPCs; surprising twists without waiting for your push. *(Enable when you want to be reacted to.)*
- [ ] **Hyper-Involved NPCs ADD-ON**
- NPCs can solve the plot without you, reject your plans, develop grudges, steal loot, and drive scenes when you stall. *(Escalates NPC agency further.)*
- [ ] **User Failure Option**
- Your decisions can genuinely fail and compound; you are not protected from your own choices.
- [ ] **User Can't Die** 
- You survive, but never unscathed; plot armor must be earned or explained.
- [ ] **User is the MC**
- You are explicitly the protagonist; your choices carry physical toll and your arc runs through consequence and recovery.

---

## AI Behavior – Moral & NSFW

- [x] **Freaky Uncensored**
- Intimacy is earned through buildup; physical and sensory detail is tracked throughout; characters speak during sex; clinical language is banned.
- [x] **Violence Enhancer** 
- Combat is messy and exhausting; injuries compound; psychological aftermath follows lethal violence; outcomes follow physical logic, not drama.
- [ ] **Dead Dove Integrity**
- Dark characters stay dark; remorse requires story justification; traits don't soften through proximity to you.
- [ ]**Red Flag Integrity**
- Manipulative/possessive characters behave like actual red flags, not romantic tropes; manipulation works, charm is a weapon.
- [ ]**Moral Ambiguity**
- Grey characters stay grey; the narrative doesn't resolve moral tension for comfort; discomfort is the point.

---

## Nimbus Utilities

Supplementary tools layered on top of the core system.

- [x] **Reputation Ripple Feed** 
- Every 2-3 public scenes, your reputation surfaces through background detail (whispers, glances, wanted posters) – never through exposition.
- [x] **Spoilers Mode**
- Future plot questions answered inside a collapsible spoiler tag.
- [ ] **Hidden Story Ledger** 
- Tracks active plot threads and recent resolutions in a hidden HTML block at the end of each response.
- [ ] **Global Position Tracker** 
- Appends time, date, and each character's attire/location/status/condition at the end of every response.
- [ ] **Weave Reformatter**
- Reformats a prior response on OOC command without changing the plot or character voice.
- [ ] **CYOA Choices** 
- Presents branching path options after each response; paths can be wondrous, perilous, tender, wicked, or final.

---

## The Think System

An internal planning phase the AI runs before writing – never visible in output. Only enable one at a time.

- [x] **Ultra-Light Think** 
- 10-point checklist covering scene state, character condition, plot, knowledge limits, beat plan, spatial logic, active directives, and style before every response.
- [ ] **Ultra-Light CoT** 
- Identical to Think but uses `<CoT>` tags; some models respond better to one or the other.
- [ ] **Light CoT** 
- More detailed version with expanded character and plot tracking; useful for complex long-running stories.
- [ ] **Narrator Card (Think / CoT)** 
- Specialized version for when `{{char}}` is a Narrator card; switches to third-person omniscient and handles scenes without you present.

---

## OOC Protocol

`[OOC: your instruction]` – highest priority, overrides everything.

Use it to redirect the scene, correct character behavior, adjust pacing, or rewrite a beat mid-story.

---

## Quick Reference

**Default ON**
- Core Instructions
- Story Primers (Scenario, Avatar, Form)
- Third Person POV
- Modern Narrative
- Focus Lock
- No Flowery
- Act Not Tell
- Verbatim in Dialogue
- Monologue Breathing
- Sub-Text Scanner
- Emotional Restraint
- Expression Bursts
- Emotional Intensity
- Drama Reducer
- Character Autonomy
- NPC Insertion
- Autonomous NPC Agency
- Freaky Uncensored
- Violence Enhancer
- Reputation Ripple Feed
- Spoilers Mode 
- Ultra-Light Thinkk

**OFF** *(enable as needed)*
- More/Less User Agency 
- Hyper-Involved NPCs ADD-ON 
- User Failure Option 
- User Can't Die
- User is the MC
- Dead Dove Integrity
- Red Flag Integrity
- Moral Ambiguity
- All alternate POVs and tenses
- All Story Targets
- Hidden Ledger
- Global Position Tracker
- CYOA Choices
- Weave Reformatter
- Narrator Cards
- Light CoT

---

**Credits:**
- Based on **Lucid Loom 3**
- Main Prompt based on **Freaky Frankenstein**
- Jailbreak by **Freaky Frankenstein**

Made by Clowuds
