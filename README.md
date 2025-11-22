# 🐍 Retro Snake

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Status](https://img.shields.io/badge/Status-Functional-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

A robust, arcade-style **Snake Game** built with Python's `turtle` graphics module. This project demonstrates game loop logic, coordinate-based movement, and real-time collision detection.

---

## 🕹️ Game Mechanics

* **Classic Gameplay**: Navigate the snake to eat food and grow longer.
* **Score Tracking**: Features a dynamic scoreboard that tracks your **Current Score** and maintains a **High Score** for the session.
* **Progressive Difficulty**: The game speed increases (delay decreases) slightly with every piece of food eaten, making the game harder as you progress.
* **Collision System**: 
    * **Wall Collision**: Hitting the screen edge resets the game.
    * **Self Collision**: Hitting your own tail resets the game.

## 📸 Features

| Feature | Description |
| :--- | :--- |
| **Responsive Controls** | Smooth handling using WASD keys. |
| **Dynamic Speed** | The `time.sleep()` delay reduces by `0.001` per score. |
| **Infinite Loop** | The game automatically resets upon death without restarting the script. |
| **Visuals** | High-contrast colors (Red/Pink on Black) for retro visibility. |

## 🚀 Installation & Run

1.  **Prerequisites**: Ensure you have Python installed. No external packages (like `pygame`) are required; this runs on the standard library.
2.  **Download**: Clone this repo or download the `main.py` file.
3.  **Execute**:
    ```bash
    python main.py
    ```

## 🎮 Controls

* **W**: Move Up
* **S**: Move Down
* **A**: Move Left
* **D**: Move Right

## 🛠️ Code Structure

The project utilizes a procedural approach with `turtle` objects:
* **Head**: The primary turtle object controlled by the user.
* **Segments**: A list `[]` managing the body parts that follow the head's coordinates in reverse order.
* **Game Loop**: A `while True` loop managing screen updates, movement ticks, and collision checks.

---

*Created for educational purposes to demonstrate Python logic and Turtle graphics.*
