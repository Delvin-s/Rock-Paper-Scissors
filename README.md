# 🪨📄✂ Rock Paper Scissors Game

This is a classic *Rock Paper Scissors* game built as part of the [FreeCodeCamp JavaScript course](https://www.freecodecamp.org/). The game allows a player to compete against a computer, and the first to reach 3 points wins!

## 🕹 How to Play

1. Select your option: Rock, Paper, or Scissors.
2. The computer will randomly select an option.
3. The result of each round is displayed:
   - 🎉 Player wins the round
   - 🤖 Computer wins the round
   - 🤝 It's a tie!
4. First to 3 points wins the game.
5. Once a winner is declared, click *Reset Game* to play again.

## 🧠 Game Logic

- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock

The game uses:
- innerText to update messages and scores
- style.display to show/hide elements
- Functions for round logic, score updates, and reset

## 📁 Project Structure

```plaintext
index.html       - Main HTML structure
styles.css       - Game styling (optional enhancement)
script.js        - Game logic using JavaScript
