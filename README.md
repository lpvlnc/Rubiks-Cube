# Rubik's Cube
![Rubik's Cube banner](https://github.com/lpvlnc/rubiks-cube/blob/main/Screenshots/screenshot_01.png)

# 🏫 Academic Context

 This project was initially developed for the **Artificial Inteligence** course at Faculdade Dom Bosco de Porto Alegre. 
 Our task was to develop a program capable of silving a Rubik's cube, using either our own algorithm or an existing one. 
 To make the callenge more engaging, we decided to turn it into a game.
 
 After the version was presented in class, **additional improvements** were made to enhance gameplay experience.

---
## 🎮 About the Game

 The game was developed using **Unity (C#)**. 
 Its main goal is to solve a **Rubik's cube**, which can be done manually using the mouse.
   - **Left mouse button (drag)** - Rotates a cube face.
   - **Right mouse drag: (drag)** - Rotates the entire cube.

---
## 🧠 Game Features

- **Cube face map** - Displays all cube faces in real time.
- **Shuffle (Button)** - Randomly scrambles the cube with 10-30 moves.
- **Solve (Button)** - Automatically solve the cube using **Kociemba's** algorithm.
- **Moves list** -Displays the full list of moves used by **Kociemba's** algorithm during the solution.

---
## 🟩 Kociemba's Two-Phase Algorithm

 The algorithm used to solve the cube was made by [Herbert Kociemba](https://kociemba.org/). 
 Developed between 1991 and 1992, it solves the Rubik’s Cube in two stages using dynamic computation and subgroup G1.
 It can find solutions in **at mos 30 moves**, improving efficiency through pruning tables, symmetry reduction, and by eliminatig redudant paths.
 
 You can learn more about the algorithm on [this page](https://kociemba.org/math/imptwophase.htm).
 
---
## 🔄 Post-Submission Updates

  - Fixed animation bugs.
  - Improvements UI design and responsiveness.
  - Added sound effects.

---
## 🙌 Credit's to Megalomobile

 This project  was inspired by a tutorial playlist from [Megalomobile](https://www.youtube.com/@megalomatt) which teaches how to create a Rubik's Cube in Unity and implement a version of **Kociemba's Algorithm** in C#.
 
 You can check the playlist [here](https://www.youtube.com/watch?v=JN9vx0veZ-c&list=PLuq_iMEtykn-ZOJyx2cY_k9WkixAhv11n&ab_channel=Megalomobile).

---
## 📦 How to Run

### Option 1 - Download
Download the release package (.zip), extract it, run **Rubik's Cube.exe** and play!

### Option 2 - Build Locally
 1. Clone this repository
 2. Open it using Unity version6000.1.8f1.
 3. Run the project

If you encounter any issues running the project, feel free to contact me through my [LinkedIn page](https://www.linkedin.com/in/lpvalenca/).
