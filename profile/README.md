# Game Design Document

> **A co-op survival FPS where every step forward comes at a price.**

---

##  Contents

- [Overview](#-overview)
- [Core Gameplay Loop](#-core-gameplay-loop)
- [World Structure](#️-world-structure)
  - [Main Hall (Central Hub)](#main-hall-central-hub)
  - [Connected Halls (Side Areas)](#connected-halls-side-areas)
- [The Host Creature](#-the-host-creature)
  - [Evolution Phases](#evolution-phases)
- [Antidote System](#-antidote-system)
  - [Materials](#materials)
  - [Retrieval Process](#retrieval-process)
  - [Crafting](#crafting)
- [Creature Attraction System](#-creature-attraction-system)
- [Environmental Escalation](#-environmental-escalation)
- [Final Boss Fight](#️-final-boss-fight)
- [Victory & Failure](#-victory--failure)
- [Solo vs Co-op Balance](#-solo-vs-co-op-balance)
- [Design Strengths](#-design-strengths)
- [Core Design Philosophy](#-core-design-philosophy)
- [Target Audience](#-target-audience)
- [Project Status](#-project-status)

---

##  Overview

*Setting the stage for survival horror*

**Genre:** Co-op Survival FPS | Horror / Sci-Fi | PvE  
**Players:** 1–4 (Solo or Co-op)  
**Setting:** Sealed research facility overrun by viral infection

### Core Concept

Players are trapped inside a massive research facility where a failed experiment has unleashed a powerful Host Creature. This organism spreads a viral infection throughout the complex, growing stronger as players progress. Teams must explore dangerous halls, collect antidote materials, and confront the evolving threat before the facility is completely overrun.

**You are not fighting a creature. You are fighting control, the environment, and the consequences of your decisions.**

---

##  Core Gameplay Loop

*The cycle of risk and reward*

```
Prepare → Risk → Escape → Escalate → Repeat → Final Showdown
```

1. **Explore** connected halls branching from the Main Hall
2. **Retrieve** one of four required antidote materials
3. **Survive** escalating threats as the Host evolves
4. **Return** to the Laboratory
5. **Craft** the antidote once all materials are collected
6. **Confront** the Host Creature in a final battle

---

##  World Structure

*A facility that becomes more dangerous with every step*

### Main Hall (Central Hub)
- Territory of the Host Creature
- Contains the Laboratory for antidote assembly
- Environmental danger increases throughout the match
- Cannot be avoided — remains critical from start to finish

### Connected Halls (Side Areas)
- Multiple halls branch from the Main Hall
- Each hall contains one antidote material
- Unique infection patterns and enemy types per hall
- Locked rooms requiring keys found in high-risk locations

**Design Principle:** Progress makes the world more hostile.

---

##  The Host Creature

*The facility's nervous system*

### Evolution Phases

#### Phase 1: Dormant Spread
- Host remains mostly stationary
- Focuses on spreading infection
- Establishes tension with minimal interference

#### Phase 2: Active Control
- Increases virus output
- Spawns stronger enemies
- Expands patrol routes
- Destabilizes environment

#### Phase 3: Predatory State
- Actively hunts players
- Alters map layout
- Aggressively controls the facility
- Final escalation before confrontation

**The Host evolves based on player actions, not just time.**

---

##  Antidote System

*Four materials, one cure, escalating danger*

### Materials
Four unique components required:
- **Material A**
- **Material B**
- **Material C**
- **Material D**

**Rules:**
- One material per hall
- All materials mandatory
- No substitutions

### Retrieval Process
1. Enter assigned hall
2. Survive infected zones
3. Locate the correct key
4. Unlock secured room
5. Escape with material

**Consequence:** Each material collected permanently increases Host activity and enemy aggression.

### Crafting
- All materials must be returned to the Laboratory
- Crafting unlocks the final confrontation
- Host cannot be defeated until antidote is complete

---

##  Creature Attraction System

*The facility watches, listens, and responds*

The Host emits a viral signal that intensifies based on player activity:

**Triggers:**
- Movement
- Combat
- Door unlocking
- Material collection

**Effects:**
- Increased enemy spawns
- Expanded patrol routes
- Shift from wandering to active hunting
- Faster, smarter, more aggressive enemies

**The facility reacts to noise, progress, and player density.**

---

##  Environmental Escalation

*A living, collapsing world*

As the Host evolves, the facility deteriorates:
- Lights flicker or fail completely
- Doors malfunction or seal shut
- New infected zones emerge
- Enemy variants appear

The environment feels alive and collapsing, creating urgency without timers.

---

##  Final Boss Fight

*Three phases of escalating intensity*

### Phase 1: Control
- Host is invulnerable
- Attacks indirectly through spawned enemies, door seals, infection waves
- Players must activate biological injection nodes
- Each node weakens Host control

### Phase 2: Exposure
- Host core becomes visible
- Limited damage windows
- Aggressive direct attacks
- Teams split roles: distraction and antidote preparation

### Phase 3: Antidote Deployment
- Inject antidote into core
- Hold position under heavy pressure
- Arena collapses as infection surges

**Outcome:** Host dies or becomes inert. The facility stabilizes. Silence returns.

---

##  Victory & Failure

*Earned triumph or overwhelming defeat*

### Victory Conditions
- Antidote successfully deployed
- Viral spread halted
- Enemy activity fades
- Host neutralized

**Emotional Arc:** From chaos and pressure to calm and control. Victory feels earned.

### Failure Conditions
- Team wipe
- Host reaches maximum dominance
- Facility becomes fully overrun

Failure reinforces urgency and encourages replayability.

---

## 👥 Solo vs Co-op Balance

*Survival focus vs coordination focus*

### Enemy Scaling
- **Solo:** Fewer enemies, manageable pressure
- **Co-op:** More enemies, multi-zone threats
- Damage does not scale excessively

### Objective Scaling
- **Solo:** Closer objectives, faster interactions
- **Co-op:** Multi-position objectives, faster escalation

### Revives
- **Solo:** Limited self-revive charges
- **Co-op:** Teammate revives under pressure

### Boss Scaling
- **Solo:** Slower patterns, fewer waves
- **Co-op:** Multi-directional attacks, heavier waves

**Core Principle:**  
Solo = Survival Focus | Co-op = Coordination Focus

Teamwork is rewarded, not required.

---

## 🎮 Design Strengths

*Why this design works*

- ✅ Clear risk vs reward
- ✅ Strong central objective
- ✅ Natural difficulty escalation
- ✅ Interconnected systems that reinforce each other
- ✅ Player-driven tension
- ✅ Final boss as culmination, not gimmick

**Players are responsible for the danger they face.**

---

## Core Design Philosophy

*Progress comes at a price*

> The game does not punish progress — it charges a price for it.

Every decision matters. Every material collected makes the facility more dangerous. Every door opened draws the Host's attention. Players must weigh the risk of exploration against the need for resources, creating meaningful choices throughout the experience.

---

## 📝 Target Audience

*Who will play this game*

- Solo players seeking tense survival gameplay
- 2–4 player co-op teams focused on coordination and strategy
- Fans of horror, sci-fi, and PvE experiences
- Players who appreciate consequences-driven game design

---
