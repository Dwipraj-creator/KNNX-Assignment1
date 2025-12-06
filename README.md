# KNNX-Assignment1

# 🧭 Text Adventure Game — KN-Lang Assignment

## 🎮 Game Concept

You play as a brave (and slightly confused) human trapped in a sarcastic fantasy world.  
To escape, you'll explore rooms, solve riddles, and unlock shortcuts — all while the game makes fun of your decisions.

Your final goal:  
➡ Reach the **Freedom Gate** and escape with dignity (or as close as possible).

---

## 🧱 Game Structure

This project uses KN-Lang keywords:

| KN-Lang Term | Meaning |
|-------------|----------|
| **Squad** | Class |
| **Quark** | Variable |
| **Doodle** | Function |
| **SpinCycle** | Game loop |

The game includes the following squads:

- `Player`
- `Room`
- `GameManager`

---

## 🗺 World Layout

The game world consists of connected rooms:

| Room | Description | Special Feature |
|------|------------|----------------|
| Entrance | Starting point | Contains the map |
| Spooky Dungeon | Hub area | Contains rusty key |
| Locked Door | Blocked path | Requires rusty key |
| Crystal Chamber | Puzzle room | Riddle must be solved |
| Freedom Gate | Exit area | Winning room |

---

## 🧩 Puzzle System

The **Crystal Chamber** contains a magical riddle:

> *"What has keys but can't open doors?"*

Correct answer: **piano**  
Solving it unlocks access to the final room.

---

## 🎮 Available Commands

| Command | Example | Result |
|---------|---------|--------|
| `go <direction>` | `go north` | Moves to another room |
| `pick <item>` | `pick key` | Adds item to inventory |
| `inventory` | — | Shows collected items |
| `look` | — | Shows current room details |
| `interact` | — | Activates puzzle/room events |
| `quit` | — | Ends the game |

Invalid commands trigger… *sarcastic commentary.*

---

## 🏁 How You Win

The game ends successfully when:

✔ The key is collected  
✔ The riddle is solved  
✔ The player reaches **Freedom Gate**

A victory message is shown — slightly insulting, but celebratory.

---


