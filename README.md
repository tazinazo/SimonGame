# Simon Game

Welcome to the Simon Game! This simple web-based game challenges players to memorize and repeat a sequence of colors. The game features dynamic visual and auditory cues to engage players and test their memory skills.

## How to Play

1. **Start the Game**: Press any key on your keyboard to start the game. The initial level is displayed as "Level 0."

2. **Memorize the Sequence**: Watch the colors light up in a specific sequence. Your goal is to remember this sequence.

3. **Repeat the Sequence**: Click on the colored buttons in the same order as the sequence you observed.

4. **Level Up**: Successfully completing a round advances you to the next level. The level number is displayed at the top.

5. **Game Over**: If you make a mistake, the game ends. The background briefly flashes red, and a "Game Over" message is displayed. Press any key to restart the game.

## Features

- **Colorful Buttons**: Four buttons with different colors (red, blue, green, yellow) that light up during the game.

- **Sound Effects**: Each button press produces a unique sound, enhancing the gaming experience.

- **Dynamic Animations**: Buttons flash to indicate the sequence, and a brief animation plays when a button is pressed.

## Code Overview

### Variables

- `buttonColors`: Array containing the colors of the buttons.
- `gamePattern`: Array storing the randomly generated sequence for each level.
- `userClickedPattern`: Array holding the player's input.
- `started`: Boolean flag indicating whether the game has started.
- `level`: Variable tracking the current level.

### Event Listeners

- **Keypress Event**: Initiates the game when any key is pressed on the keyboard.

- **Button Click Event**: Handles button clicks, records user input, plays corresponding sounds, and checks for correct sequences.

### Functions

- `checkAnswer(currentLevel)`: Compares the player's input with the generated sequence and determines whether it's correct. Initiates the next level if the entire sequence is correct.

- `nextSequence()`: Generates the next level's sequence, displays it with button animations, and increments the level.

- `playSound(name)`: Plays a sound corresponding to the provided color or action.

- `animatePress(currentColor)`: Adds a visual "pressed" effect to the clicked button.

- `startOver()`: Resets the game state, allowing the player to restart.

## Dependencies

- **jQuery**: The code utilizes the jQuery library for simplified DOM manipulation and event handling.

## How to Use

1. Clone or download the repository.
2. Open the `index.html` file in a web browser.
3. Press any key to start the game.
4. Enjoy playing Simon!

Feel free to explore and modify the code to enhance or customize the game according to your preferences. Happy gaming!
