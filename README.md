# Java Snake Game

This is a classic Snake game implemented in Java using Swing for the GUI.

## Project Structure

```
java_snake_game/
├── src/
│   └── game/
│       ├── Snake.java
│       └── Board.java
├── resources/
│   ├── apple.png
│   ├── dot.png
│   └── head.png
```

## How to Run

1. Open a terminal in the project root directory.
2. Compile the source files:
   ```
   javac -sourcepath src src/game/*.java
   ```
3. Run the game:
   ```
   java -cp src game.Snake
   ```

## Game Description

- The game window is created by `Snake.java`.
- The main game logic, rendering, and user input are handled in `Board.java`.
- Images for the snake and apple are loaded from the `resources` folder.
- Use arrow keys to control the snake.
- Eat apples to grow longer. The game ends if the snake hits the wall or itself.

## Requirements

- Java JDK 8 or higher

## Tech Stack

- **Java**: Programming language used for the entire project.
- **Swing**: Java GUI toolkit for creating the game window and handling graphics.
- **AWT**: Used for basic graphics and event handling.

## Data Structures and Algorithms Used

- **Arrays**: The snake's body positions are stored in arrays (`x[]` and `y[]`).
- **Event Queue**: Used for thread-safe GUI updates.
- **Timer**: Implements the game loop for regular updates.
- **Collision Detection**: Checks for snake collision with itself and walls using array comparisons.
- **Randomization**: Places the apple at random positions on the board.

---

Enjoy playing the Snake game!
