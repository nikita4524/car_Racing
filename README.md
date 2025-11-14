#  Endless Car Racing Game

A simple yet exciting **Endless Car Racing Game** built using **Unity**, where the player drives through an infinite city, avoids traffic, collects coins, and tracks distance covered. The game is easy to play, visually engaging, and perfect for showcasing fundamentals of game development.


##  **Game Overview**

* **Type:** Endless Racing Game
* **Engine:** Unity
* **Player Controls:** Left/Right movement
* **Environment:** Endless city road
* **Features:**

  * Player car movement (left/right)
  * Opponent/traffic cars moving forward
  * Coin collection system
  * Distance counter
  * Coin counter
  * Smooth endless-road mechanic

---

## 🕹️ **Gameplay Mechanics**

### ✔ Player Movement

* Use **Left Arrow (←)** to move left
* Use **Right Arrow (→)** to move right

### ✔ Opponent Cars

* other cars move toward the player
* Collision with an opponent car ends the game

### ✔ Coin Collection

* Golden coins are placed randomly on the road
* Rotating coin animation makes collection noticeable
* Coin count is displayed on the UI

### ✔ Distance Counter

* The game measures how far the player has traveled
* Distance increases automatically over time
* Shown at the top of the screen

### ✔ Endless Environment

* The city road tiles repeat to create an **infinite road effect**
* Player feels like moving forward continuously

---

##  **Scripts Used**

### 1. **Player Movement Script**

Handles left-right movement and boundary limits.

### 2. **Enemy Car Movement Script**

Controls traffic cars moving toward the player.

### 3. **Coin Rotation Script**

Coin spins continuously to grab player's attention.

### 4. **Game Over Script**

Detects collision and triggers game‑over UI.

### 5. **Distance Counter Script**

Calculates and updates distance during gameplay.

### 6. **Coin Collection Script**

Adds to player's score when a coin is collected.

---

##  **UI Elements**

* **Distance Display** (top-left or top-center)
* **Coin Counter** (top-right)
* **Game Over Panel** with Restart option

---

##  **Folder Structure**

```
Assets/
 ├─ Scripts/
 │   ├─ PlayerMovement.cs
 │   ├─ EnemyMovement.cs
 │   ├─ CoinRotation.cs
 │   ├─ GameOverManager.cs
 │   ├─ DistanceCounter.cs
 │   └─ CoinCollect.cs
 │
 ├─ Prefabs/
 │   ├─ PlayerCar.prefab
 │   ├─ EnemyCar.prefab
 │   ├─ Coin.prefab
 │   └─ RoadTile.prefab
 │
 ├─ Materials/
 ├─ Textures/
 ├─ UI/
 │   ├─ GameOverPanel
 │   ├─ DistanceText
 │   └─ CoinText
```

---

##  **How to Play**

1. Start the game.
2. Use left/right arrow keys to dodge enemy cars.
3. Collect coins to increase your score.
4. Survive as long as possible to cover maximum distance.
5. Avoid collisions — or it's GAME OVER!

---

##  **Technologies Used**

* **Unity 2022/2023**
* **C# Scripts** for game logic
* **UI Toolkit / Unity UI** for score and distance display

---

##  **Future Improvements (Optional)**

* Add multiple levels
* Add car selection menu
* Add boost/powerups
* Add sound effects and background music

---
# **Installation & How to Run

Clone the repository:

git clone 

Open the project in Unity 2022+.

Open the MainScene.

Press Play to start the game

##  **Conclusion**

This Endless Car Racing Game demonstrates the basics of Unity game development, including movement mechanics, environment looping, UI updates, collision detection, and collectible systems. It is a perfect project for learning or showcasing beginner‑friendly game development skills.


.
