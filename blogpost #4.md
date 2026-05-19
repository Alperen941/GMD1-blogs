# Punch — Milestone 2 Development Report

## Introduction

In this second development milestone, we focused on expanding the core systems established in Milestone 1 and adding new gameplay features to make the prototype feel more complete. The goal was to move from a basic proof of concept to a more functional and polished game experience.

During this phase we transitioned the camera to a first-person perspective, introduced the Teddybear shield mechanic, began working on health and damage systems, and made significant progress on the game's user interface.

---

## Camera System — First-Person View

One of the most impactful changes in this milestone was switching from the previous camera setup to a proper first-person (FPS) camera controller. This change significantly affects how the game feels to play and aligns with the intended direction of the project.

The new camera is now directly tied to the player's perspective, making movement and throwing feel more immersive and intuitive. Input controls were also updated to match the new camera orientation.

### Features implemented

- FPS camera controller
- Camera-relative movement
- Arcade input controls
- Player rotation tied to aim

---

## Teddybear Shield System

A new power-up mechanic was introduced this milestone: the Teddybear shield. Teddybears now spawn into the level at set intervals, and the player can pick one up to gain temporary protection.

When picked up, the Teddybear creates a blue bubble of protection around the player that lasts for 7 seconds. Only one Teddybear can be active at a time. This system adds a defensive option to complement the existing stone-throwing mechanic.

### Features implemented

- Teddybear spawner with spawn interval
- One pickup active at a time
- Blue bubble protection around the player
- 7-second effect duration
- Teddybear model added to the game
<img width="2559" height="1387" alt="image" src="https://github.com/user-attachments/assets/471f5343-f469-40c9-9a0c-ebb380a09431" />

---

## Player Health and Damage

We began implementing a damage system for the player this milestone. Enemies that catch up to the player can now deal damage, with a knockback effect planned alongside it. The current implementation logs damage status to the console as a first step toward a full health system.

This system lays the groundwork for a proper death and game-over flow, which will be finalized in the next milestone.

### Features implemented

- Player taking damage from enemies
- Damage status logged in console
- Knockback (in progress)

---

## Stone Script Fix

A bug from the previous milestone was resolved: stones would previously cause enemies to despawn when hitting the ground, which was unintended behavior. The stone script has been updated so that only a direct collision with an enemy triggers the despawn, making gameplay more fair and consistent.

### Fix summary

- Stone colliding with the ground no longer kills enemies
- Enemy despawn only triggers on a direct stone hit

---

## Gameplay UI

A health and time/score display was added to the game during this milestone. This gives the player real-time feedback on their status during gameplay, which is essential for the game loop to feel meaningful.

The enemy model was also iterated on and is currently in review, and the stone model was finalized.

### Features implemented

- Health display
- Time and score display
- Stone model finalized
- Enemy model updated

---

## Challenges During Development

This milestone introduced more interconnected systems, which brought new integration challenges. Some of the main difficulties included:

- Making the enemy AI work correctly with the new FPS camera and player rotation
- Getting the stone collision logic to behave predictably across different situations
- Fixing the enemy scripting so all active enemies respond to thrown stones, not just the most recently spawned one
- Balancing the Teddybear spawn timing to feel rewarding without being too frequent

The enemy scripting issue in particular remains an ongoing challenge — currently only the latest spawned enemy is affected by stones, and this will need to be resolved in the next milestone.

---

## Reflection and Next Steps

This milestone pushed the project forward significantly. The game now has a clearer identity with its first-person perspective, a defensive mechanic in the Teddybear shield, and the beginning of a damage system that will lead to proper win/loss conditions.

The core gameplay loop now consists of:

1. Enemies spawn and chase the player
2. The player collects and throws stones to defeat enemies
3. The player picks up Teddybears for temporary protection
4. Enemies deal damage if they reach the player

In the next milestone we plan to complete the death and restart system, build out the main menu and death screen, add animations for player and enemies, implement sounds, and finish any remaining blocked tasks such as proper enemy scripting and the player model.

---

## Conclusion

Milestone 2 successfully extended the foundation built in the first phase. The transition to a first-person camera, the introduction of the Teddybear shield mechanic, and the early damage system all bring the game closer to its intended experience.

While several tasks are still in progress or blocked, the project remains on track and the most important new systems are now in place for further development.
