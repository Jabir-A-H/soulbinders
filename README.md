# Soulbinders

A game combining Metroidvania style exploration with Assassin’s Creed-inspired traversal elements adapted to fit the 2D/side-scrolling Metroidvania gameplay. Battles are fully real-time and free-flowing, inspired by Souls-like combat mechanics. The game also features Pokémon-style monster catching and training, blending action and collection seamlessly in a modern-fantasy setting.

# Prototype Plan

## 1. Prototype Scope (What We’re Making First)

Create **a single countryside region** with:

* Side-scrolling Metroidvania exploration for overworld movement.
* Real-time creature battles in **small 3D arenas** triggered on encounter, allowing full movement and positioning.
* Creature catching and training.
* One boss fight to demonstrate core gameplay loop.

---

## 2. Core Features to Implement

A **small but complete gameplay loop** in one rural area with:

### A. Player Movement & Exploration (Overworld – 2D Metroidvania)

* Walk, run, jump, dash, dodge roll, ladder climbing, small vaults over obstacles, wall climbing.
* Exploration in side-view, platform-based environments.

---

### B. Combat System (3D Arena – Souls-like Battling & Positioning)

* **Player Stats**: Health, stamina, weapon damage.
* **Combat Actions**:

  * Light attack (fast, low stamina cost).
  * Heavy attack (slower, higher stamina cost, staggers enemies).
  * Dodge roll (all directions).
  * Optional block/parry.
* **Enemy AI**:

  * Melee and ranged patterns.
  * Use of positioning (flanking, circling).
* **Stamina System**:

  * Attacks, rolls, and blocks consume stamina.
  * Slow stamina regen.

---

### C. Creature System

* **Encounter Flow**:

  * In 2D overworld, approach a wild creature.
  * On proximity, switch to a contained **3D battle arena**.
* **Creature Roster**:

  * 3–4 starter wild creatures with unique abilities.
* **Catching Mechanic**:

  * Weaken → capture with item.
  * Capture chances vary depending on various factors.
* **Switching Control**:

  * Swap between player and monster in battle.
  * Shows the player on a side with a speech balloon that shows the commands the user is inputting to the creatures.
* **Positioning in Combat**:

  * Flanking and movement direction matter for dodging, aiming, and attack angles.

---

### D. Boss Battle

* Boss fought in a larger, more complex 3D arena with hazards and has multiple attack phases.
* Boss uses positioning heavily (e.g., back attacks, chasing flanks).

---

## 3. World Setting & Level Design

* **Overworld Theme**: Countryside village + surrounding forest/farmland.
- **Areas**:
  - Safe village hub, wooden buildings, barns, windmill (NPCs, item shop).
  - Forest with platforming sections and hidden paths.
  - Farmland with roaming enemies and wild creatures to catch.

* **Battle Arenas**: Small 3D scenes themed after encounter location (forest glade, farm field, ruined barn interior).
* **Metroidvania structure** for exploration; certain areas require specific creature abilities or player abilities to access.

---

## 4. Art & Assets

* Free assets for both 2D overworld and 3D arenas.
* 2D tilesets for exploration; 3D low-poly environments for battles.
* UI for both exploration and combat.

---

## 5. Core Gameplay Loop

1. **Explore** overworld in 2D.
2. **Spot a creature** → trigger 3D battle.
3. **Battle in real-time**:

   * 3D arena background is same as encounter area.
   * User now controls their creature.
   * Souls-like real-time combat with dodge, flank, attacks, and special move.
4. **Win**:

   * Option to capture if HP is low.
   * Option to run from battle. But the creature might chase after the player if they are still nearby.
5. Return to hub to heal, train, and upgrade.

---

## 6. Gameplay Systems

### Overworld

* Platforming, climbing, dashing.
* NPCs, shop, quests.

### Battle Arena

* Free movement & dodge rolls in all directions.
* Light/heavy attacks, creature abilities.

### Creature Management

- Catch → Store in basic inventory.
- Summon your creature for battle.
- Simple stat growth (level up after battles).

### Hub Interaction

- Shop: Buy healing items.
- NPC Quest: Defeat X creature or find an item.
- Trainer NPC: Tutorial battle.

---

## 7. Step-by-Step Development Roadmap (Updated)

1. **Overworld movement** (2D Metroidvania).
2. **Creature spawn & encounter trigger**.
3. **Switch to 3D arena on battle start**.
4. **Implement basic combat in 3D** (player's creature vs. one creature).
5. **Add catching system**.
6. **Map & Progression**.
7. **Polish UI & feedback**.

---

## 8. Later Expansion Ideas

* More creatures with elemental types.
* Creature evolutions and special attacks.
* Multiple arena types.
* Multiplayer PvP and private room battles and tournaments.
* Better art & animation.
* Seamless 3D overworld.

---

## *The End*
