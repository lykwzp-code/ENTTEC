# Product Specialist Master Plan

## 1. Executive summary

The Product Specialist role can be more valuable than conventional product support if it sits at the intersection of four loops:

1. **Creator discovery** — understand how musicians, designers and other creators actually think about light.
2. **Product experimentation** — turn repeated creative problems into testable workflows or lightweight prototypes.
3. **Portfolio translation** — decide which creator-facing ideas belong in EMU, which professionalised capabilities belong in ELM, and which should remain separate.
4. **Market storytelling** — turn authentic co-creation into education, community, case studies and demand generation.

The goal is not to make every user a lighting designer. The goal is to reduce the translation distance between:

**creative intent → visual language → executable lighting system**

A strong Product Specialist should therefore own a problem space, not merely support a list of products.

---

## 2. Product thesis

### 2.1 The problem

A musician may know exactly what they want the audience to feel:

> “The verse should feel empty and distant. The chorus should open the space, but it must not look like a nightclub.”

That intent still has to be translated into lighting concepts, parameters, timing logic and control workflows.

Traditional sound-to-light systems often begin lower in the stack:

**audio signal → triggers → lighting behaviour**

That is useful, but it does not fully answer:

**What is the artist trying to express, and what visual relationship with the music would serve that expression?**

### 2.2 Product opportunity

Create a higher-level creator workflow:

1. **Creative intent**
2. **Musical / dramatic structure**
3. **Relationship between media**
4. **Visual grammar**
5. **Lighting execution**

Possible relationships between music and light should include more than simple synchronisation:

- synchronized
- delayed
- drifting
- restrained
- counterpoint
- stochastic / partially generative
- section-aware variation

The product should not decide what the music “means.” It should help the artist express what **they** mean.

---

## 3. Proposed role mission

### Mission

**Turn real creator intent into validated product decisions across ENTTEC’s software ecosystem.**

### Core responsibilities

#### A. User / creator discovery
- Interview musicians, DJs, producers, lighting designers, integrators and venue users.
- Observe actual workflows rather than relying only on feature requests.
- Identify repeated friction: concept creation, setup, mapping, timing, control, collaboration and handoff.
- Build problem statements around user outcomes, not requested buttons.

#### B. Product ownership / decision participation
- Maintain a problem backlog separated from the feature backlog.
- Write concise hypotheses, acceptance criteria and success metrics.
- Rank opportunities using user frequency, severity, strategic fit, technical cost and cross-product leverage.
- Own small experiments from idea to user validation.
- Participate in product trade-offs with Engineering, Sales, Support and Marketing.

#### C. Cross-product portfolio thinking
- Distinguish creator-first experiments from production-grade professional features.
- Identify capabilities that could be shared across EMU / ELM without making the products converge into the same UX.
- Document when an EMU experiment should remain EMU-only, graduate into ELM, or become part of a shared creative engine.

#### D. Go-to-market learning
- Convert authentic creator work into case studies, tutorials and launch content.
- Partner with creators as design partners first, endorsers second.
- Use public content to explain product thinking and teach creative workflows.

---

## 4. What the role should NOT become

Avoid turning Product Specialist into:

- “support every product when anyone needs help”
- demo-only sales enablement
- a product-information relay between teams
- a backlog secretary
- a content marketer without product decision participation
- a pseudo-PM who owns outcomes without access to Engineering / user research / decision forums

A healthy role needs explicit answers to:

- What do I **own**, rather than support?
- Which decisions can I make independently?
- Which decisions do I influence?
- Who gives final approval?
- Which Engineering / Design / Data resources are available?
- What happens when priorities conflict?

---

## 5. Product portfolio proposal

### EMU — Creator Lab

EMU becomes the fastest place to explore creator-first interactions.

Design principles:
- musician-first vocabulary
- low setup cost
- rapid experimentation
- DAW / MIDI / audio-native workflow
- safe place for experimental features
- co-created with artists
- creative freedom over technical complexity

What belongs here first:
- intent-driven workflow experiments
- section-aware behaviour
- artist-defined visual grammar
- assisted scene generation
- stem / musical-role experiments
- creator templates and “visual language” systems
- AI-assisted ideation

### ELM — Professional Spatial Production

ELM remains production-first:

- spatial mapping
- very large pixel systems
- professional content workflows
- deterministic control
- installation / touring reliability
- monitoring and commissioning
- precise repeatability
- performance at scale

Creative features graduate here only when they have:
- clear professional value
- deterministic controls
- reliable performance
- editable parameters
- reproducible output
- integration with professional workflows

### S-PLAY — Automated / Permanent Playback

Where appropriate, finished experiences can transition from creative design into unattended, scheduled or triggered playback for permanent installations.

---

## 6. Shared Creative Engine — longer-term architecture hypothesis

Instead of repeatedly “porting features” product to product, ENTTEC could evaluate a shared internal creative layer.

Possible shared capabilities:

- shader / generative effect library
- audio analysis
- BPM / section awareness
- visual grammar primitives
- colour / transition systems
- intent-to-parameter translation
- AI-assisted creation services

Then expose different UX:

### EMU UX
- song / session / artist oriented
- DAW / MIDI / live-performance mental model
- simple rigs
- creator language

### ELM UX
- spatial / stage / install oriented
- mapping / layers / network mental model
- huge pixel counts
- deterministic production controls

The products retain distinct identities while sharing selected primitives.

---

## 7. AI strategy: assist expression, do not automate taste

Avoid shallow AI positioning such as:

> sad song = blue lights

AI should be a **creative translator**, not the creative authority.

Possible interaction:

Artist:
> “The final chorus should feel much larger than the first, but I don’t want more flashing.”

System:
- identifies relevant musical sections
- proposes several visual strategies
- explains what changes
- exposes editable controls
- lets the artist reject / refine / lock choices

Potential pipeline:

**artist intent  
→ musical structure / semantics  
→ perceptual / dramatic language  
→ visual grammar  
→ EMU / ELM controls**

Human control requirements:
- artist can override all output
- uncertainty should be visible
- suggestions should be editable
- deterministic recall should be available
- AI output should never silently replace project logic

See [AI Creative Intelligence Layer](AI_CREATIVE_INTELLIGENCE.md).

---

## 8. Artist co-creation as product infrastructure

Create **EMU Artist Lab**.

Do not treat artists as endorsement inventory. Treat them as design partners.

Each collaboration:

1. artist explains one song and intended visual experience
2. Product Specialist translates intent into testable visual language
3. artist tries EMU
4. team observes friction
5. current product produces the best possible Version 1
6. unresolved needs are documented
7. useful repeated needs become experiments
8. artist may return later when capability improves
9. final creative output becomes authentic product content

The unfinished parts are valuable. A public “we cannot do this well yet” moment can become the setup for a future return episode.

See [EMU Artist Lab](EMU_ARTIST_LAB.md).

---

## 9. Content and community flywheel

### Long-form
YouTube:
- artist story
- creative intent
- workflow
- failures / compromises
- product discussion
- final audiovisual work

### Short-form
TikTok / Reels / Shorts:
- polished light-show / MV cut
- best visual moment
- concise creative insight
- before / after

### Community
Use comments as **hypothesis generation**, not direct roadmap voting.

Possible responses:
- “We’ll test this.”
- “This is interesting; we want to understand the underlying need.”
- “We’re adding it to the exploration backlog, not committing to a release yet.”
- “We tested it and it didn’t improve the workflow.”
- “You were right — here’s the new prototype.”

This makes the product team visible without turning every public suggestion into a promise.

See [Content, Community & Creator Growth](CONTENT_COMMUNITY_GROWTH.md).

---

## 10. Feature graduation model

### Stage 0 — Observation
Repeated creative friction appears in artist sessions, support, community or sales.

### Stage 1 — Problem validation
Confirm:
- who has the problem
- how often
- current workaround
- why existing product is insufficient

### Stage 2 — EMU experiment
Build the smallest useful concept:
- prototype
- workflow mock
- limited beta
- manual service-assisted test if needed

### Stage 3 — Creator validation
Use in real songs / sessions / live shows.

### Stage 4 — EMU productisation
If creator value is repeatable:
- stable UI
- documented behaviour
- measurable activation / retention signal

### Stage 5 — Professional suitability review
Ask:
- does this solve a professional ELM user problem?
- can it be deterministic?
- can it scale?
- is it controllable / automatable?
- does it fit professional mental models?

### Stage 6 — ELM production-grade implementation
Rebuild / expose appropriately for professional workflows.

This is not “everything in EMU eventually goes to ELM.” Graduation is selective.

---

## 11. Six-month Product Specialist operating plan

### Days 0–30 — Learn
- use EMU and ELM end-to-end
- shadow Support / Sales / Product / Engineering
- review top support themes
- map current users and workflows
- build product taxonomy and decision map
- identify what the role owns vs supports

### Days 31–60 — Discover
- conduct 10–15 structured creator interviews
- conduct 5–10 professional ELM user interviews
- document top workflow friction
- identify 3 cross-product hypotheses
- define Artist Lab pilot

### Days 61–90 — Experiment
- recruit first 3–5 artist design partners
- produce first Artist Lab sessions
- test one creator-workflow hypothesis
- publish internal findings
- recommend first product experiment

### Months 4–6 — Prove
- run repeatable Artist Lab cadence
- measure activation / completion / retention
- validate at least one feature concept with multiple artists
- decide: kill / iterate / ship
- evaluate whether any mature creative primitive has ELM relevance

Detailed metrics and gates are in [180-Day Roadmap & Metrics](ROADMAP_METRICS_180_DAY_PLAN.md).

---

## 12. Success metrics

Do not optimise only for views.

### Product discovery
- number of validated problems
- repeated pain across creators
- time from insight to test
- percentage of hypotheses killed early
- number of experiments reaching real-user use

### Creator activation
- time to first useful show
- first-project completion rate
- percentage of users able to create without expert assistance
- return creation rate
- number of reusable creator workflows

### Product impact
- feature adoption
- repeat usage
- reduction in setup / programming time
- improved user confidence
- retention / upgrade signal

### Artist Lab / content
- qualified EMU downloads from content
- episode completion rate
- creator applications to participate
- community suggestions that become validated product problems
- follow-on creations shared by users

### Portfolio
- reusable creative primitives
- capabilities successfully shared with ELM
- professional adoption of graduated capabilities
- reduction in duplicated engineering work where shared architecture is appropriate

---

## 13. Risks and safeguards

### Risk: product becomes “AI gimmick”
Mitigation:
- start from creator intent and workflow pain
- keep artist control
- validate output quality with real creators

### Risk: roadmap dominated by loud commenters
Mitigation:
- comments generate hypotheses, not priorities
- validate with broader user evidence

### Risk: celebrity dependency
Mitigation:
- build program around strong independent creators
- use larger artists as occasional amplification, not operational dependency

### Risk: Product Specialist becomes support generalist
Mitigation:
- explicit owned domain
- measurable product outcomes
- defined decision rights

### Risk: EMU and ELM converge into confusing products
Mitigation:
- different primary users
- different UX
- selective feature graduation
- shared primitives only where useful

### Risk: creator content overwhelms product work
Mitigation:
- every episode must serve a discovery / education / adoption objective
- content production owned jointly with Marketing

### Risk: music / image / rights complexity
Mitigation:
- clear artist and recording licences
- explicit rights for full episodes, short-form cuts and derivative product demonstrations
- consent for reuse of feedback in product research

---

## 14. The Product Specialist’s most important decision

Not:

> “What feature should we add next?”

But:

> **“Which user problem is important enough to deserve product investment, and where in the portfolio should it live?”**

That is the bridge between customer input and product decision participation.
