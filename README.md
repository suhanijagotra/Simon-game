# Simon-game
This project is a web-based implementation of the Simon game using HTML, CSS, and JavaScript with jQuery:

### HTML:
- Sets up the game interface with colored buttons (`green`, `blue`, `red`, `yellow`) that include directional arrow images (`up`, `left`, `right`, `down`).

### CSS (`styles.css`):
- Defines styles for buttons, game-over effects, and animations (`pressed` class).

### JavaScript (`game.js`):
- **Variables and Initialization:** 
  - `buttonColours`, `gamePattern`, `userClickedPattern`, `started`, `level`.
- **Event Listeners and Initialization:**
  - `$(document).keypress()`: Starts the game on key press.
  - `$(".btn").click()`: Handles button clicks to capture user input.
- **Game Logic Functions:**
  - `nextSequence()`: Generates the next game sequence and animates buttons.
  - `checkAnswer(currentLevel)`: Compares user input to the game sequence, progresses or ends the game accordingly.
  - `playSound(name)`, `animatePress(currentColor)`: Provides audio feedback and visual animations for button interactions.
- **Utility Functions:**
  - `startOver()`: Resets game variables to restart the game.

### Skills Demonstrated:
- **HTML/CSS:** Structuring and styling the game interface.
- **JavaScript/jQuery:**
  - Handling user input and game logic.
  - Manipulating DOM elements for dynamic behavior and animations.
- **Game Development Concepts:**
  - Sequential game logic, audio playback, and visual feedback mechanisms.

This project exemplifies fundamental web development skills in creating interactive and engaging games using front-end technologies.