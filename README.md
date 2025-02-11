# Flappy Bird Game

A complete implementation of the classic Flappy Bird game using **HTML**, **CSS**, and **JavaScript**. This project includes customizable characters, fullscreen mode, pause functionality, and a progressive level system.

---

## **Key Features**

1. **Game Mechanics**:
   - The bird falls due to gravity and can be lifted by pressing the spacebar or clicking.
   - Pipes are generated at regular intervals, and the player must navigate the bird through the gaps.
   - Collision detection with pipes or the ground ends the game.
   - The score increases as the bird passes through pipes.

2. **Customizable Characters**:
   - Players can choose from predefined bird characters (yellow, blue, red).
   - Custom characters can be added via image URLs or file uploads.
   - Custom characters are saved in `localStorage` for persistence.

3. **Fullscreen Mode**:
   - The game can be toggled between fullscreen and windowed modes.
   - The canvas resizes dynamically to fit the screen.

4. **Pause Functionality**:
   - The game can be paused and resumed using the "Pause" button or the `Escape` key.
   - A pause overlay is displayed when the game is paused.

5. **Level System**:
   - The game gets progressively harder as the player scores more points.
   - Every 20 points, the gravity and pipe speed increase.

6. **Responsive Design**:
   - The game adapts to different screen sizes, especially in fullscreen mode.

---

## **How It Works**

### **HTML Structure**
- The game is rendered on a `<canvas>` element.
- A character selection screen allows players to choose or add custom characters.
- Buttons for fullscreen, pause, and starting the game are provided.

### **CSS Styling**
- The game is centered on the screen with a clean, modern design.
- Animations and transitions enhance the user experience.

### **JavaScript Logic**
- The game loop (`requestAnimationFrame`) handles updates and rendering.
- Collision detection, score tracking, and level progression are managed in the `update` function.
- Custom characters are loaded and saved using `localStorage`.

---

## **How to Play**

1. **Start the Game**:
   - Click the "Start Game" button or press the spacebar to begin.
   - Choose a bird character or upload a custom one.

2. **Controls**:
   - Press the **spacebar** or **click** to make the bird flap and rise.
   - Press the **Escape** key or click the "Pause" button to pause/resume the game.
   - Toggle fullscreen mode using the "Fullscreen" button.

3. **Objective**:
   - Navigate the bird through the gaps in the pipes.
   - Avoid colliding with the pipes or the ground.
   - Score points by successfully passing through pipes.

4. **Level Progression**:
   - Every 20 points, the game becomes harder with increased gravity and pipe speed.

---

## **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flappy-bird-game.git