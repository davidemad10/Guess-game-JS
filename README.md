# Guess My Number Game

This is a simple guessing game where the player tries to guess a secret number between 1 and 20. The game provides feedback on whether the guess is too high, too low, or correct. The goal is to guess the number with the highest score possible.

## Game Features

- Randomly generated secret number between 1 and 20.
- Feedback for the player's guess (too high, too low, correct).
- Score tracking, with a high score feature.
- Reset functionality to play again without refreshing the page.
- Simple and intuitive user interface.

## How to Play

1. Open the game in a web browser.
2. Enter a guess in the input field and click the "Check!" button.
3. The game will provide feedback:
   - If there is no input, it will display "⚠️No Number".
   - If the guess is too high, it will display "📈 Too High!".
   - If the guess is too low, it will display "📉 Too Low!".
   - If the guess is correct, it will display "🎉 Correct Number!" and change the background color to green.
4. The score will decrease with each incorrect guess. If the score reaches 0, the game will display "💥 You lost the game!" and change the background color to red.
5. Click the "Again!" button to reset the game and play again.

## Code Explanation

- The secret number is generated using `Math.trunc(Math.random() * 20) + 1`.
- The initial score is set to 20, and the high score is initially set to 0.
- The event listener on the "Check!" button processes the player's guess and updates the game state.
- The event listener on the "Again!" button resets the game to its initial state.

## HTML Structure

The HTML structure includes elements for displaying messages, the secret number, score, high score, input field for guesses, and buttons for checking the guess and resetting the game.

## CSS Styling

The CSS provides styling for the game, including colors, layout, and responsiveness.

## JavaScript Functionality

- Event listeners for the "Check!" and "Again!" buttons.
- Functions for handling the game logic, updating the score, and providing feedback.
- DOM manipulation to update the game interface based on the player's actions.

# License

-This project is licensed under the MIT License. See the LICENSE file for details.


