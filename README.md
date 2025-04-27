# Clash-of-Clans-Game 🏰⚔️

A strategic tower defense game with dynamic levels, special powers, and interactive gameplay elements.

## Game Features 🎮

### Core Mechanics
- **2 Unique Map Designs**  
  `0` Empty land | `1` Clan Castle | `2` Defense Unit | `3` Fence
- **Customizable Game Setup**  
  Preview maps & choose defense units (Cannon/Archer/Wizard) before starting
- **Animated Characters**  
  GIF-based enemies (attacking) & workers (repairing) for immersive gameplay
- **Progressive Difficulty**  
  5 challenging levels with unique map structures and escalating challenges

### Special Features
- ⏱️ **5-Minute Countdown Timer** with castle health bar
- 💎 **Gem Collection System** (3+ gems = extra life)
- ⚡ **Powerups** to revive fallen workers
- ⏸️ **Pause/Resume Functionality** in all levels
- 🧟 **"Larger Enemy"** appears after 3 minutes in hard levels
- 🌋 **Earthquake Events** (Level 4+) damaging castle & fences

## Technical Implementation 🛠️

### Class Structure
| Class              | Responsibility                          |
|--------------------|-----------------------------------------|
| `Castle`           | Health management & damage calculation  |
| `DefenseUnit`      | Tower behavior & attack patterns        |
| `Enemy`/`LargerEnemy` | Movement & attack logic              |
| `Citizen`          | Repair mechanics & resource collection  |
| `Fence`            | Damage absorption & repair states       |
| `Gem`/`Powerup`    | Special item spawning & effects         |
| `Menu`/`Settings`  | User interface & configuration          |
| `Level`            | Main game loop & difficulty scaling     |

### Architecture
