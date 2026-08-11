# Nimbus v7.2 – User Guide

A storytelling preset that fixes how AI writes by default: passive NPCs, melodrama, sanitized consequences, purple prose.

- v7.1 - Small formatting fixes.
- v7.2
  - Added **Jailbreak - Nimbus**,
  - Small formatting fixes in **Narrator CoT**,
  - **Hidden Ledge** activated by default
  - Updated **Nimbus Utilities - Regex**

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
12. [AI Behavior – Character](#ai-behavior--character)
13. [AI Behavior – Psychology](#ai-behavior--psychology)
14. [Nimbus Utilities](#Nimbus-utilities)
15. [The Think System](#the-think-system)
16. [OOC Protocol](#ooc-protocol)
17. [Quick Reference](#quick-reference)

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

- 🔵 **Third Person**
- Stays on the active character's shoulder; other characters' inner worlds are hidden.
- ⚪️ **Third-Person Omniscient**
- God's-eye view; access to all characters' thoughts.
- ⚪️ **Second Person**
- Addresses the user directly as "you."
- ⚪️ **First Person Direct**
- Narrates strictly through `{{char}}`'s senses as I/Me.
- ⚪️ **First Person Character**
- Internal monologue; breaks fourth wall only if the character would.

**Past / Present / Future Tense** Tense modifiers – none active by default, enable one if needed.

---

## Narrative Styles

Pick one, default Modern Narrative.

- 🔵 **Modern Narrative**
- Lean, naturalistic, immediate. Authentic dialogue, raw beats.
- ⚪️ **Roleplay**
- Fast exchanges; asterisks for action, quotes for dialogue.
- ⚪️ **AO3-Style**
- Fan Fiction. Layered drama, serialized saga energy, emotional hooks.
- ⚪️ **Anime-Style**
- Rhythmic pacing, dramatic reveals, expressive character moments.
- ⚪️ **Traditional Narrative**
- Literary, measured, thematic.
- ⚪️ **Japanese Web Novel**
- Conversational first-person; trope-aware, status notifications if relevant.
- ⚪️ **Doujinshi**
- Pervasive sexual tension in every scene; specific erotic tropes always active.
- ⚪️ **Co-Writing Desk**
- Equal partnership; AI pitches beats, you fill placeholders, meta discussed in italics.
- ⚪️ **Bratty Narrative**
- Varied sentence architecture; bans predictable patterns; trusts subtext.

---

## Story Targets

None active by default, can have multiple ON.

- ⚪️ **Deep Questions**
- Poses a hard moral/existential question but never answers it.
- ⚪️ **Cautionary Tales**
- Illustrates dangerous paths through consequences.
- ⚪️ **Absurdity Focused**
- Chaos and meaninglessness; humor and tragedy in equal measure.
- ⚪️ **Atmosphere Focused**
- Mood and sensory immersion above plot.
- ⚪️ **Cathartic Narrative**
- Emotional purging that resolves into clarity.
- ⚪️ **Hedonistic Pursuit** NSFW
- Sexual gratification as the primary lens; varied scenarios.
- ⚪️ **Taboo Transgression** NSFW
- Forbidden dynamics, psychological tension, moral blurring.
- ⚪️ **Degradation & Humiliation** NSFW
- Power exchange, systematic humiliation, heavy content.
- ⚪️ **Natural Weaving**
- Balanced difficulty; challenges organic, failures tangible but surmountable.

---

## Narrative Focus

Pick one. Default is Focus Lock.

- 🔵 **Focus Lock**
- Camera stays within the active character's sensory radius; no cutaways or floating perspectives; every beat emerges causally from the last.
- ⚪️ **Multi Focus World Canvas**
- The world moves independently; background NPCs, overheard conversations, and lore surface every few responses whether or not you're watching.

---

## Response Length

Pick one based on preferred pacing. Check which is currently active in your preset.

---

## AI Behavior – Prose & Dialogue

- 🔵 **No Flowery**
- Bans poetic narration, weather-mirroring, narrating how words "land," recapping prior turns; the AI states what happens next, nothing more.
- 🔵 **Act Not Tell**
- Characters never announce their own personality in dialogue; habits and opinions emerge through behavior only.
- 🔵 **Verbatim in Dialogue**
- Accents and speech patterns are written phonetically; voice quality comes from diction and punctuation.
- 🔵 **Monologue Breathing**
- Every 3+ consecutive spoken sentences must be broken by a physical beat (gesture, glance, pause); 1-2 sentences flow freely.
- 🔵 **Sub-Text Scanner**
- Before writing dialogue, the AI internally tags stakes, biases, and grudges; every line carries something underneath the surface.

---

## AI Behavior – Emotional

- 🔵 **Emotional Restraint**
- At emotional peaks: one sharp physical detail, then stop; no metaphor piling, no repeated realizations, no philosophical spiraling.
- 🔵 **Expression Bursts**
- Off-beat physical gestures accompany emotional moments, always paired with the dialogue that triggered them; language stays raw and unpolished.
- 🔵 **Emotional Intensity**
- Dialogue uses fervent, vivid phrasing to convey passion and vulnerability; heartfelt moments aren't smoothed over.
- 🔵 **Drama Reducer**
- Default texture is low-stakes everyday life; high stakes must be earned through accumulated consequence.

---

## AI Behavior – Autonomy & NPCs

- 🔵 **Character Autonomy**
- `{{char}}` pursues their own agenda and causes friction; they exist alongside you.
- 🔵 **NPC Insertion**
- Every introduced NPC acts or speaks immediately on arrival; NPCs interact with each other.
- 🔵 **Autonomous NPC Agency**
- Recurring NPCs have off-screen lives, remember past interactions, evolve over time, and can surprise you with independent outcomes.
- ⚪️ **More User Agency**
- Narrative waits for you; the AI honors your choices and doesn't override your pace. *(Enable for slower, deliberate play.)*
- ⚪️ **Less User Agency**
- The world propels itself forward using lore and NPCs. *(Enable when you want to be reacted to.)*
- ⚪️ **Hyper-Involved NPCs ADD-ON**
- NPCs can solve the plot without you, reject your plans, develop grudges, steal loot, and drive scenes when you stall. *(Escalates NPC agency further.)*
- ⚪️ **User Failure Option**
- Your decisions can genuinely fail and compound; you are not protected from your own choices.
- ⚪️ **User Can't Die**
- You survive, but never unscathed; plot armor must be earned or explained.
- ⚪️ **User is the MC**
- You are explicitly the protagonist; your choices carry physical toll and your arc runs through consequence and recovery.

---

## AI Behavior – Moral & NSFW

- 🔵 **Intimacy Uncensored**
- Intimacy is earned through buildup; physical and sensory detail is tracked throughout; characters speak during sex; clinical language is banned.
- 🔵 **Violence Uncensored**
- Combat is messy and exhausting; injuries compound; psychological aftermath follows lethal violence; outcomes follow physical logic.
- ⚪️ **Dead Dove Integrity**
- Dark characters stay dark; remorse requires story justification; traits don't soften through proximity to you.
- ⚪️ **Red Flag Integrity**
- Manipulative/possessive characters behave like actual red flags; manipulation works, charm is a weapon.
- 🔵 **Moral Ambiguity**
- Grey characters stay grey; the narrative doesn't resolve moral tension for comfort; discomfort is the point.

---

## AI Behavior – Character

- 🔵 **Character Behavioral Realism**
- Every character filters the world through their own history and bias; no shared neutral perspectives.
- ⚪️ **Emotional Response Realism**
- Reactions trace back to established psychology; vulnerability is earned.
- ⚪️ **Deep Emotional Depth**
- Feelings drive decisions and accumulate; emotions that don't alter behavior are banned.
- 🔵 **Character Growth**
- Growth requires a legitimate trigger and must internalize visibly into behavior.
- 🔵 **Evolving Relationships**
- Shared experiences shift bonds; conflict leaves residue, affection requires history.
- 🔵 **Trauma Responses**
- Trauma surfaces through sensory triggers and reflexive recoil; wounds are discovered organically.
- 🔵 **Trauma Guards**
- Emotional paralysis is capped at 1-2 beats; the character begins internal reorganization within the same scene.

---

## AI Behavior – Psychology

- 🔵 **Mental Disorders Realism**
- Disorders affect cognition and behavior; symptoms wax with stress, good days exist, psych realism serves depth.
- ⚪️ **Emotional Disorders** *(depression, bipolar, anxiety)*
- Depression is flatness and executive failure; bipolar crashes are visible; anxiety manifests as avoidance and physical symptom.
- ⚪️ **Personality Disorders** *(BPD, ASPD, NPD)*
- BPD splits in real time; ASPD is functional and charming with genuine absent remorse; NPD cracks under narcissistic injury; all are pervasive.
- ⚪️ **Neurodevelopmental** *(autism, ADHD)*
- Autism is individual sensory and social processing; ADHD is dysregulation, hyperfocus then full crash.
- ⚪️ **Amnesia**
- Personality survives; procedural memory outlasts episodic; gaps surface as wrongness; memory returns fragmentary and out of useful order.
- ⚪️ **Brain Damage** *(TBI, stroke, post-surgery)*
- Deficits are region-specific; pre-injury identity coexists with post-injury reality; fatigue is a hard ceiling.
- ⚪️ **Dementia**
- Emotional memory outlasts factual; lucid windows make surrounding loss sharper; confabulation is filling gaps, sundowning is a daily rhythm; dignity is non-optional.

---

## Nimbus Utilities

Supplementary tools layered on top of the core system.

- 🔵 **Jailbreak - FF5**
- More heavy Jailbreak direct from Freaky Frankenstein 5.
- ⚪️ **Jailbreak - Nimbus**
- Less intrusive Jailbreak, try one or another if receiving refusals.

- 🔵 **Reputation Ripple Feed**
- Every 2-3 public scenes, your reputation surfaces through background detail (whispers, glances, wanted posters).
- 🔵 **Spoilers Mode**
- Future plot questions answered inside a collapsible spoiler tag.
- 🔵 **Hidden Story Ledger**
- Tracks active plot threads and recent resolutions in a hidden HTML block at the end of each response.
- ⚪️ **Global Position Tracker**
- Appends time, date, and each character's attire/location/status/condition at the end of every response.
- ⚪️ **Weave Reformatter**
- Reformats a prior response on OOC command without changing the plot or character voice.
- ⚪️ **CYOA Choices**
- Presents branching path options after each response; paths can be wondrous, perilous, tender, wicked, or final.

---

## The Think System

An internal planning phase the AI runs before writing – never visible in output. Only enable one at a time.

- 🔵 **Ultra-Light Think**
- 10-point checklist covering scene state, character condition, plot, knowledge limits, beat plan, spatial logic, active directives, and style before every response.
- ⚪️ **Ultra-Light CoT**
- Identical to Think but uses `<CoT>` tags; some models respond better to one or the other.
- ⚪️ **Light Think / CoT**
- More detailed version with expanded character and plot tracking; useful for complex long-running stories.
- ⚪️ **Narrator Card (Think / CoT)**
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
- Character Behavioral Realism
- Character Growth
- Evolving Relationships
- Trauma Responses
- Trauma Guards
- Mental Disorders Realism
- Character Autonomy
- NPC Insertion
- Autonomous NPC Agency
- Freaky Uncensored
- Violence Enhancer
- Reputation Ripple Feed
- Spoilers Mode
- Hidden Ledger
- Ultra-Light Think

**OFF** *(enable as needed)*
- Emotional Response Realism
- Deep Emotional Depth
- Emotional Disorders
- Personality Disorders
- Neurodevelopmental
- Amnesia
- Brain Damage
- Dementia
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
