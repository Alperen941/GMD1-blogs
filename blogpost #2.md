# Punch – Game Design Document

## Overview

**Punch** is a small 3D platform survival game where the player controls a monkey named Punch who is attacked by other monkeys. The goal of the game is to survive as long as possible and score points by defeating enemy monkeys.

The player can collect stones scattered around the level and throw them at enemies. A teddy bear power-up occasionally spawns and grants temporary immunity, allowing the player to survive attacks.

Enemies continuously spawn around the edges of the map and chase the player, increasing the difficulty over time.

The game focuses on simple mechanics, fast gameplay, and increasing challenge.

---

## Genre

- 3D Platformer  
- Survival / Arcade

---

## Target Audience

The game is aimed at:

- Casual players
- Students and hobby gamers
- Players who enjoy short arcade-style survival games

The gameplay is simple and easy to understand, making it accessible to most players.

---

## Core Gameplay

The main gameplay loop is:

1. Move around the arena.
2. Pick up stones.
3. Throw stones at enemy monkeys.
4. Avoid enemy attacks.
5. Collect teddy bears for temporary immunity.
6. Survive as long as possible and increase your score.

Enemies continuously spawn and become more frequent as time progresses, increasing the challenge.

---

## Player Character

The player controls **Punch**, a monkey that can move freely around the scene.

### Player Abilities

- Move around the arena
- Pick up stones
- Throw stones at enemies
- Pick up teddy bears for temporary protection

### Player Limitations

- The player can only carry **one stone at a time**
- The player can only carry **one teddy bear at a time**

### Player Animations

- Movement
- Attack / throw
- Death
- Holding shield (teddy bear)
- Holding stone

---

## Enemies

Enemy monkeys spawn around the edges of the level and chase the player.

### Enemy Behavior

- Enemies move toward the player
- Enemies attack when close enough
- Enemies deal **10 HP damage per attack**

### Difficulty Scaling

As the game progresses:

- Enemies spawn **more frequently**
- The game becomes increasingly difficult

### Enemy Animations

- Movement
- Attack
- Death

---

## Objects and Pickups

### Stones

Stones appear randomly in the level and can be picked up by the player.

**Functionality**

- Player can carry **one stone**
- Stones can be thrown at enemies
- A successful hit defeats an enemy
- Each defeated enemy increases the player's score

**Animation**

- Throw (projectile animation)

---

### Teddy Bear (Shield Power-Up)

Teddy bears appear randomly in the level.

**Functionality**

- Grants **temporary immunity**
- Protects the player from enemy damage
- Lasts for a limited amount of time

When active, the player has a visible shield effect.

---

## Game World / Scene

The game takes place in a **zoo-like arena environment**.

### Scene Elements

- A central playable area
- Objects placed around the environment
- Enemy spawn points at the edges of the map
- Random spawn locations for stones and teddy bears

---

## Camera

The game uses a **top-down bird's-eye perspective**.

Camera behavior:

- Fixed viewing angle
- Follows the player
- Keeps the player centered on screen

This perspective helps the player maintain situational awareness.

---

## User Interface (UI)

### In-Game UI

Displays:

- **Time survived**
- **Score**
- **Health**

---

### Main Menu

The main menu contains:

- Play
- Settings
- High Score
- Credits
- Quit

---

### Settings Menu

Settings include:

- Audio settings
- Input settings

---

### Pause Menu

When the game is paused:

- Resume game
- Give up / quit

---

### Death Screen

When the player dies:

- Game Over message
- Final score displayed
- Top high scores list

---

## Scenes

The game contains several scenes:

1. **Main Menu**
2. **Main Game**
3. **Pause Menu**
4. **Death Screen**

---

## Game Progression

The game uses a **survival scoring system**.

Players gain points by:

- Defeating enemy monkeys
- Surviving longer

Difficulty increases over time due to faster enemy spawning.

---

## Visual Style

The game uses a **simple and stylized visual design**.

Characters and objects are exaggerated and readable to make gameplay clear from a top-down view.

The focus is on clarity and gameplay rather than realism.

---

## Audio

Audio elements may include:

- Background music
- Enemy sounds
- Stone throw sound effects
- Hit sound effects
- Power-up sounds

These sounds help reinforce player actions and game feedback.

---

## Future Improvements

Possible improvements could include:

- Additional enemy types
- More power-ups
- Multiple arenas
- Leaderboards
- Improved animations
- Sound effects and music variety

---

## Summary

Punch is a small arcade-style survival game built around simple mechanics and increasing difficulty. The player must manage resources (stones and power-ups), defeat enemies, and survive as long as possible.

The game focuses on fast gameplay, simple controls, and replayability.
