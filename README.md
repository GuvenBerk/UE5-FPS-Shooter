# FPS Shooter — Enemy AI System

**Unreal Engine 5 · Blueprint · Team Capstone Project**

---

## 🎮 Play the Game

▶️ **[Download & Play on itch.io](https://guvenberk.itch.io/ue5-fps-shooter)**

📺 **[Watch Gameplay Video](https://youtu.be/hsQI28gD2Nk)**

---

## 👤 My Contribution: Enemy AI System

This was a **team-based capstone project** developed at university. My role 
was designing and implementing the **enemy AI system**, consisting of 3 
distinct enemy types:

- **BP_ArcherEnemy** — ranged enemy with a custom flee mechanic: retreats 
  to a calculated safe position when the player gets too close
- **BP_SwordEnemy** — melee enemy with chase and attack behavior
- **BP_SwordTankEnemy** — tankier melee variant with adjusted health/damage 
  values and behavior timing
- **Custom AI Controller** managing shared enemy logic across all types

### Technical Approach

- **Player detection** via Pawn Sensing component
- **State-driven behavior** using boolean flags (attacking, moving, 
  fleeing, dead)
- **Timer-based behavior updates** and custom events for state transitions
- **Health/damage system** implemented per enemy type
- Built entirely in **Blueprint** (visual scripting)

---

## 🤝 Team & Scope

This was developed as part of a **larger team** at university. Other 
systems — including weapons, enemy spawning, level design, and UI — were 
built by other team members and are **not part of my contribution**.

Working on this project also taught me:
- How to use **Perforce (P4V)** for version control in a team environment
- How to communicate and troubleshoot within a development team — both 
  asking for help when stuck, and supporting teammates when they needed it

---

## 🛠️ Tech Stack

`Unreal Engine 5` `Blueprint` `Perforce (P4V)`

---

## 📄 Source Code

Full project source is large (~23GB including content assets) and is 
available on request. A packaged Windows build is available via the 
itch.io link above.
