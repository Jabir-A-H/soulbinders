# Soulbinders

A genre-fusing monster battling game

# Prototype Plan

**prototype plan** for the **Modern-Fantasy Wild Frontier RPG**.
with *Metroidvania* + *RDR2 countryside vibes* + *Ghost of Tsushima scenery* + *Souls-like creature battles* + *Pokémon-style catching/training*.

---

## 1. Prototype Scope (What We’re Making First)

Create **a single countryside region** with exploration, Souls-like combat, creature catching, and one boss — enough to show off the core gameplay loop and world vibe.

## 2. Core Features to Implement

A **small but complete gameplay loop** in one rural area with:

### A. Player Movement & Exploration

- Side-scrolling **Metroidvania controls**:
  - Walk, run, jump, parkour, dodge roll, ladder climbing, small vaults over obstacles, wall climbing, dash.

---

### B. Combat System (Souls-like 2D)

- **Player Stats**: Health, stamina, weapon damage.
- **Combat Actions**:
  - Light attack (fast, low stamina cost).
  - Heavy attack (slow, higher stamina cost, staggers enemies).
  - Dodge roll with i-frames.
  - Block (optional for prototype, can be added later).
- **Enemy AI**:
  - Simple melee and ranged attacks.
  - Telegraphing attack animations for dodge timing.
- **Stamina System**:
  - Attacks, rolls, and blocks consume stamina.
  - Stamina regenerates slowly.

### C. Creature System

- **Creature Encounters**: Metroidvania-style 2D Souls-like real-time battles.
- **3–4 starter wild creatures**:
  - Each with basic attacks and a unique ability (combat or exploration).
- **Catching Mechanic**:
  - Weaken enemy → use capture item → creature joins your roster.
- **Creature Swap**:
  - Switch between player and creature in real-time (tag-team combat).
  - Creature fights with same controls as player but has unique moves.
- **Creature Utility Abilities**:
  - Example: A burrowing creature that opens tunnels to shortcuts.

### D. Boss Battle

- **Mini-Boss**: Optional fight to introduce mechanics.
- **Main Boss**: Stronger enemy with multiple attack phases.
- Boss arena has environmental hazards to encourage mobility.

---

## 3. World Setting & Level Design

- **Theme**: Countryside village + surrounding forest/farmland.
- **Areas**:
  - Safe village hub, wooden buildings, barns, windmill (NPCs, item shop).
  - Forest with platforming sections and hidden paths.
  - Farmland with roaming enemies and wild creatures to catch.
  - Ruined barn (mini-boss arena).
  - Cliffside area (main boss arena).
- **Metroidvania structure**:
  - Early paths blocked by obstacles.
  - Require dash ability or specific creature’s help to proceed.
  - Shortcuts unlock for backtracking.

---

## 4. Art & Assets

- Temporary free assets (Itch.io, OpenGameArt, Kenney.nl).
- Player sprite with:
  - Idle, walk, jump, attack, dodge animations.
- Creature sprites:
  - Idle, attack, hit animations.
- Simple background tilesets (village, forest, farmland).
- Basic UI:
  - Health + stamina bars.
  - Creature roster display.

---

## 5. Core Gameplay Loop

1. **Explore** the hub and countryside.
2. **Spot a creature** → approach.
3. If close enough, **trigger battle mode**:
   - Camera shifts, player now controls their creature.
   - Souls-like real-time combat (dodge, light attack, heavy attack, special move).
   - Battle area is limited in the encounter area environment.
4. **Win the battle**:
   - Option to “catch” if creature’s health is low.
   - Caught creatures stored in inventory.
   - Option to run from battle. But the creature might chase after the player if they are still nearby.
5. Return to home to **heal, train, and upgrade**.
6. Repeat with harder creatures.

---

## 6. Gameplay Systems

### A. Player (Human) Movement

- Walk/Run/Sprint.
- Vault fences.
- Climb small ledges/boulders.
* Stealth crouch + hide in grass.

### B. Creature Battles

- Lock-on targeting.
- Dodge roll + stamina bar.
- Light/heavy attacks.
- Special ability (cooldown).
- HP bar & simple enemy AI.

### C. Creature Management

- Catch → Store in basic inventory.
- Summon your creature for battle.
- Simple stat growth (level up after battles).

### D. Hub Interaction

- Shop: Buy healing items.
- NPC Quest: Defeat X creature or find an item.
- Trainer NPC: Tutorial battle.

---

## 7. Art & Atmosphere

- Semi-realistic rural setting.
- Dynamic weather: Sunny, cloudy, light rain.
- Environmental sound: Birds, wind, distant animals.

---

## 8. Step-by-Step Development Roadmap

### Step 1 – Core Player Controls

- Movement, dash, vault, climb, jump, dodge roll.
- Camera follows player smoothly.

### Step 2 – Map & Progression

- Build small countryside level layout.
- Add village hub and one explorable forest area.
- Place barriers for locked areas.

### Step 3 – Creature System

- Add wild creature with idle/walk animations.
- Make it roam in wild zone.
- Simple capture mechanic.
- Creature swap in combat.

### Step 4 – Battle Mode

- Switch control from player to creature.
- Player attacks + stamina bar.
- Add dodge, light/heavy attack.
- Simple enemy AI with health.

### Step 5 – Catching & Inventory

- Catch system when HP < X%.
- Store creature in basic UI list.

### Step 6 – Quest & Shop

- One quest from NPC (defeat 1 wild creature).
- Shop for healing items.

### Step 7 – Basic UI

- Health/stamina bars.
- Creature inventory list.

### Step 8 – Boss Fight

- Script mini-boss and main boss with patterns.
- Add health bar UI for bosses.

### Step 9 – Polish & Feedback

- Add sound effects and placeholder music.
- Add hit effects and screen shake.
- Test gameplay loop: Explore → Fight → Catch → Progress → Boss.

---

### 9. Later Expansion Ideas (Post-Prototype)

- More creatures with elemental types.
- Creature evolutions and special attacks.
- Larger interconnected regions (mountains, rivers, ruins).
- Multiplayer PvP creature battles.
- Better art & animation.

---

## *The End*
