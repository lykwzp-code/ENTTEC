# AI Creative Intelligence Layer

## Product question

Can AI help a creator translate artistic intent into an editable lighting starting point **without taking authorship away from the creator**?

---

## 1. Design principle

Bad model:

> detect emotion → choose colour

Better model:

> understand creator's stated intent → understand structure → suggest several editable visual strategies → let the artist refine

The system should never claim objective knowledge of what a song “means.”

---

## 2. Proposed stack

### Layer 1 — Creative intent
User input:
- text
- conversation
- references
- mood / narrative description
- “do / don’t” constraints

Example:

> “The chorus should feel like the room opens up, but not become more aggressive.”

### Layer 2 — Musical understanding
Potential signals:
- sections
- tempo
- beat
- stems / musical roles
- energy
- harmonic tension
- vocal entry
- texture changes

### Layer 3 — Perceptual / dramatic language
Translate into concepts such as:
- intimate / expansive
- restrained / explosive
- still / fluid / aggressive
- sparse / saturated
- near / distant
- stable / drifting

### Layer 4 — Relationship model
Define how light relates to music:
- sync
- delayed response
- counterpoint
- drift
- stochastic variation
- selective silence
- section-aware repetition / variation

### Layer 5 — Visual grammar
Translate into:
- intensity
- colour
- spatial distribution
- movement
- density
- transition speed
- effect parameters

### Layer 6 — Execution
Generate:
- EMU looks / mappings / automation suggestions
- ELM creative primitives where appropriate
- editable project configuration

---

## 3. Human control requirements

- always show editable parameters
- allow the artist to lock / reject suggestions
- show uncertainty where relevant
- preserve manual authoring
- provide multiple alternatives, not one “correct” answer
- enable deterministic recall after a choice is accepted
- keep provenance of artist decisions vs machine suggestions

---

## 4. MVP experiments

### Experiment A — Intent-to-look brief
No automation.

AI converts artist language into a structured visual brief.

Measure:
- does the brief help artist + lighting operator align faster?

### Experiment B — Section-aware variation
Detect song sections and suggest different lighting structures for repeated sections.

Measure:
- does it reduce repetitive programming?
- do artists perceive the result as more expressive?

### Experiment C — Relationship presets
Instead of “mood presets,” offer:
- synchronized
- restrained
- drifting
- counterpoint
- generative

Measure:
- can non-lighting users understand and use the concept?

### Experiment D — Artist-defined visual grammar
Let artist build a reusable vocabulary for their own project / album / tour.

Measure:
- reuse across songs
- creative consistency
- reduced programming time

---

## 5. Dataset / research opportunity

Artist Lab can create a valuable qualitative corpus:

**artist language → visual decision → actual EMU / ELM parameters → artist evaluation**

Examples:
- “make the space feel emptier”
- “don’t let the bass look aggressive”
- “the second chorus should feel wider, not brighter”

This should be treated as research material with appropriate creator consent and data governance.

---

## 6. Risks

### Generic AI taste
Risk:
- outputs converge to cliché.

Mitigation:
- learn artist-specific vocabulary
- preserve ambiguity
- prioritise editability

### Hallucinated technical output
Mitigation:
- validate against actual product / fixture constraints
- never emit unverified control configuration directly to production

### Loss of authorship
Mitigation:
- position AI as translator / collaborator
- make human decisions explicit

### Feature complexity
Mitigation:
- validate workflow value before building full automation
