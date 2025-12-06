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






# 🎮 Quiz Master — Console-Based Quiz Game (KN-Lang Styled JS)

Welcome to **Quiz Master**, a terminal quiz game with personality.  
This snarky console will test your knowledge and roast you at the same time — because pain builds character 🤡.

---

## 📌 Project Description

This project is inspired by the assignment requirements for building a quiz game using the **KN-Lang structure** (Squads, Quarks, Doodles) — but implemented in **JavaScript** so it can run in real life.

The game allows players to:

- Choose a **category**
- Select a **difficulty**
- Answer 10 randomly selected questions
- Earn (or lose) points based on difficulty
- Receive sarcastic commentary
- Get a final ranking based on score

---

## 🧠 Features

✔ Multiple question categories:  
`Science`, `History`, `Fun Facts`

✔ 3 difficulty levels:  
`Easy`, `Medium`, `Hard`

✔ Dynamic scoring based on difficulty:

| Difficulty | Correct | Wrong |
|-----------|---------|--------|
| Easy      | +5      | -2     |
| Medium    | +10     | -5     |
| Hard      | +15     | -7     |

✔ Humorous responses

✔ Final rank based on performance:

| Score Range | Title |
|------------|--------|
| 80+        | 👑 Quiz Royalty |
| 50–79      | 🧠 Quiz Master in Training |
| Below 50   | 🤡 Better Luck Next Time |

---

## 🛠️ Tech Used

- JavaScript (Node.js runtime)
- Console I/O (`readline-sync`)
- KN-Lang mapping to JavaScript:
  - **Squad → Class**
  - **Doodle → Method**
  - **Quark → Variable**

---


