# Knight's Quest: 2D Godot 4 Platformer

A small, high-quality 2D platformer template created in **Godot 4**. This project showcases core game development pillars: character physics, enemy AI logic, scene unique names, and UI state management.

## 🖼️ Preview
![Game Preview](visual_sample/visual_sample.png)

## 🎮 Gameplay Features

* **Knight Controller:** Uses `CharacterBody2D` with logic for Idle, Run, and Jump states.
* **Patrolling Slimes:** AI enemies that use `RayCast2D` to detect walls/edges and automatically flip direction.
* **Coin System:** Collectibles that trigger a "pickup" animation and update a global score via the `%GameManager`.
* **Slow-Mo Death:** When hitting a `KillZone`, the game engine slows to `0.5x` speed and disables player collision for a dramatic "game over" effect before reloading.
* **Retro Aesthetics:** Integrated with **Pixel Operator 8** typography and **"Time for Adventure"** background music.
* **Level Design:** Includes moving platforms with one-way collisions and a detailed tileset.

## 🛠️ Technical Highlights

* **Engine:** Godot 4.x
* **Language:** GDScript
* **Scene Unique Names:** Uses `%GameManager` for clean, decoupled communication between coins and the UI.
* **Time Manipulation:** Demonstrates real-time `Engine.time_scale` adjustments for gameplay feel.

## 🚀 Getting Started

1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
    ```
2.  **Import:** Open Godot 4, click **Import**, and select the `project.godot` file.
3.  **Play:** Press **F5** to start your adventure.

## 🕹️ Controls
* **A / D** (or Arrows): Move
* **Space / W**: Jump

## 📂 Asset Credits
* **Music:** "Time for Adventure" (MP3)
* **Fonts:** Pixel Operator 8 by Jayvee Enaguas (CC0)
* **Art:** 16x16 Pixel Art Knight, Slimes, and World Tileset.

---
*Developed as a learning project to master Godot 4's 2D engine.*
