# Flappy Bird Game

This is a simple implementation of the classic Flappy Bird game in Java using Swing for the GUI.

## Table of Contents

- [Features](#features)
- [How to Run](#how-to-run)
- [Controls](#controls)
- [Project Structure](#project-structure)
- [Libraries Used](#libraries-used)

## Features

- Simple and intuitive gameplay.
- Bird physics with gravity and jumping.
- Randomly generated pipes with collision detection.
- Score tracking with a high score feature.
- Basic sound effects for actions (jump, score, game over).
- Game over screen with an option to retry.

## How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Shubhambhagat3226/Flappy-Bird.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Shubhambhagat3226-Flappy-Bird
    ```
3.  **Compile the Java files:**
    ```bash
    javac src/App.java
    ```
    *Make sure you have JDK installed and `javac` is available in your system path.*
4.  **Run the application:**
    ```bash
    java App
    ```
    *This assumes your main class `App` is packaged in the default directory.* If not, the you can run with `java -cp src App`


## Controls

-   **Spacebar:** Makes the bird jump upwards.

## Project Structure
```
 Shubhambhagat3226-Flappy-Bird/
 ├── resource/
 │   └── META-INF/
 │       └── MANIFEST.MF
 ├── Flappy Bird.iml
 └── src/
     ├── META-INF/
     │   └── MANIFEST.MF
     ├── FlappyBird.java
     ├── gameElement/
     │   ├── Pipe.java
     │   └── Bird.java
     ├── Retry.java
     ├── App.java
     └── MyFrame.java
```


-   **`resource/`:** Contains images and sound files used in the game.
-   **`src/`:** Contains the Java source code.
    -   **`FlappyBird.java`:**  The main game logic panel.
    -   **`gameElement/`:** Contains classes representing game elements like `Pipe` and `Bird`.
    -   **`Retry.java`:**  The dialog displayed after the game ends.
    -   **`App.java`:** The main entry point of the application.
    -   **`MyFrame.java`:** The main application window.

## Libraries Used

-   **Java Swing:** Used for creating the graphical user interface.
-   **Java Sound API:** Used for playing sound effects.
