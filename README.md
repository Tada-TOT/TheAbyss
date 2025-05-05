# **TheAbyss**  
*A First-Person Roguelike Dungeon Crawler*  
*(Inspired by Barony, Turning Wheel LLC)*  

![Title Banner](./placeholder_title_banner.png)  
*(high-res game banner)*  

---

## **📖 Table of Contents**  
1. [About the Game](#-about-the-game)  
2. [Gameplay Features](#-gameplay-features)  
3. [Story & Setting](#-story--setting)  
4. [How to Play](#-how-to-play)  
5. [Controls](#-controls)  
6. [Development](#-development)  

---

## **🎮 About the Game**  
**TheAbyss** is a **hardcore first-person roguelike** inspired by *Barony*, blending real-time combat, RPG progression, and permadeath in a dark fantasy world. Delve into procedurally generated dungeons, uncover secrets, and survive against monstrous foes—alone or with allies.  

### **Key Inspirations**  
- **Barony’s** brutal combat and class diversity.  
- **Minecraft Dungeons’** accessible but deep loot system.  
- **Daggerfall’s** sprawling, unpredictable dungeons.  

![Gameplay GIF](./placeholder_gameplay.gif)  
*(combat/exploration GIF)*  

---

## **⚔️ Gameplay Features**  

### **1. Core Mechanics**  
- **Permadeath**: Death is permanent—plan carefully!  
- **Procedural Dungeons**: Every run features unique layouts, traps, and loot.  
- **Real-Time Combat**: Swing swords in fluid first-person action.  

### **2. Classes & Progression**  
| Class       | Playstyle          | Unique Ability       |  
|-------------|--------------------|----------------------|  
| **Warrior** | Tank/Bruiser       | Shield Bash (Stun)   |  

![Class Showcase](./placeholder_classes.png)  
*(class artworks/in-game models)*  

### **3. Dungeon Dynamics**  
- **Secrets**: Hidden rooms with rare loot (e.g., *"The Necromancer’s Tome"*).  
- **Bosses**: Defeat the *"Lich King"* to ascend deeper.  

---

## **📜 Story & Setting**  
### **Lore**  
The kingdom of **Eldermire** fell when the *Veil of Shadows*—a barrier holding back the undead—was shattered. You are a **Dungeonborn**, a warrior cursed to resurrect in the dungeon’s depths until the Lich King is slain.  

### **Goal**  
- Survive 3 increasingly deadly dungeon levels.  
- Kill the **Lich King** to break the curse.

![Lich King Art](./placeholder_boss.png)  
*(final boss)*  

---

## **🕹️ How to Play**  
### **Web Version**  
Play now in your browser:  
🔗 [GitHub Pages Link](https://tada-TOT.github.io/TheAbyss)  

### **Local Build**  
1. Download the `WebGL` build from [Releases](https://github.com/tada-TOT/TheAbyss/releases).  
2. Extract and open `index.html` in a browser.  

---

## **🎛️ Controls**  
| Action          | PC               | Gamepad (Xbox)       |  
|----------------|------------------|----------------------|  
| Move           | `WASD`           | Left Stick           |  
| Attack         | `Left Click`     | `RT`                 |  
| Pause          | `ESC`            | `Start`              |  

---

## **🛠️ Development**  
### **Tech Stack**  
- **Engine**: Unity 6 (WebGL)  
- **Tools**:  
  - A* Pathfinding for AI.  
  - Probuilder for dungeon prototyping.  
  - FMOD for dynamic sound.  

### **Build Instructions**  
```sh
git clone https://github.com/tada-TOT/TheAbyss.git
# Open in Unity, set platform to WebGL, and disable compression.
