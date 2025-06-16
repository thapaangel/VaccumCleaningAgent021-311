# 🧹 Vacuum Cleaning Agent Simulation

---

### 👤 Name: Aruna Thapa  
### 📚 CRN: 021-311  
### 🧠 Subject: Artificial Intelligence  

---

## 📌 Overview

This project is a **simulation of a Vacuum Cleaner Agent** implemented in **Python** using **Tkinter** for graphical visualization. The agent operates in a 2D grid-based environment and simulates intelligent behavior using three different AI approaches:  

1. **Simple Reflex Agent**  
2. **Utility-Based Agent**  
3. **Goal-Based Agent with Memory**

The agent navigates the environment to clean randomly scattered dirt patches on a grid. Each type of agent uses a different strategy to decide its next move.

---

## 🤖 Types of Agents Implemented

### ✅ 1. Simple Reflex Agent
- **Behavior**: Acts only on the current perception (i.e., whether the current tile is dirty).
- **Decision Logic**:
  - If the tile is dirty: Clean it.
  - If the tile is clean: Move randomly to an adjacent tile.
- **Limitation**: No memory or goal planning; it may visit the same tile repeatedly.

### ✅ 2. Utility-Based Agent
- **Behavior**: Chooses actions based on a **utility function**.
- **Decision Logic**:
  - Assigns higher utility to dirty tiles.
  - Penalizes revisiting clean tiles (based on visit count).
  - Always moves to the adjacent tile with the highest utility.
- **Advantage**: Smarter movement, avoids unnecessary revisits.

### ✅ 3. Goal-Based Agent with Memory
- **Behavior**: Uses internal memory and checks if the **goal (fully clean grid)** is achieved.
- **Decision Logic**:
  - Cleans dirty tiles.
  - Remembers visited tiles.
  - Uses directional logic to move systematically until all dirt is cleaned.
- **Advantage**: Avoids randomness and reaches the goal efficiently.

---

## 🛠 Tools & Technologies Used

- **Language**: Python 3.x  
- **GUI**: Tkinter (for real-time animation)  
- **IDE**: Visual Studio Code  

---

## 🖥 Features

- 🧼 **Real-time animation** of the vacuum agent cleaning a 6x6 grid.  
- 🎲 **Random dirt generation** for a dynamic environment each time.  
- 🧠 **Memory-aware decision making** in utility-based and goal-based agents.  
- 🧾 **Console output** logs steps, moves, and final path taken.  
- ⚙️ **Configurable settings**: grid size, delay, and dirt probability.

---

## 📸 Output Preview

### Simple Reflex Agent


