# Book Cricket Game

This is a Python-based simulation of a **Book Cricket Game**, where players roll a die to score runs. The goal is to be the first player to reach the maximum score of 50.

## Features
- **Multiplayer Support:** Supports 2 to 4 players.
- **Turn-based Gameplay:** Players take turns rolling the dice.
- **Dynamic Scoring:** Players accumulate runs until they roll a 1, which ends their turn.
- **Simple Input Controls:** Roll the dice by typing `y` during your turn.

## How to Play
1. Run the script using Python.
2. Enter the number of players (2–4).
3. Each player takes turns rolling a dice:
   - **Roll a 1:** Your turn ends, and you score nothing for that turn.
   - **Roll 2-6:** Add the number rolled to your current score.
4. After each roll, decide whether to roll again or end your turn.
5. The first player to reach a total score of **50** wins!

## Installation
Ensure Python is installed on your system. You can download Python from [python.org](https://www.python.org/).

### Steps to Run:
1. Copy the game code into a Python file (e.g., `book_cricket_game.py`).
2. Open a terminal or command prompt.
3. Run the file with the command:
   ```bash
   python book_cricket_game.py
   ```

## Game Rules
- **Number of Players:** Minimum 2, Maximum 4.
- **Scoring:** Players roll a dice, with each roll adding runs to their score unless they roll a 1.
- **Winning:** The player who first reaches a score of 50 is declared the winner.

## Code Overview
The game uses:
- `random.randint` to simulate dice rolls.
- Lists to store player scores.
- Loops for turn management and score updates.
- Input validation to ensure correct player count.

## Example Gameplay
```plaintext
Enter the number of players (2-4): 3

Player 1's turn has started!
Your total score is: 0
Would you like to roll (y)? y
You rolled a: 4
Your score is: 4
Would you like to roll (y)? y
You rolled a: 1
You rolled a 1! Turn done
Your total score is: 0

Player 2's turn has started!
Your total score is: 0
Would you like to roll (y)? y
You rolled a: 6
Your score is: 6
```

## Customization Ideas
- Change the maximum score by modifying `max_score` in the code.
- Add penalties for specific rolls (e.g., rolling a 6 twice in a row).
- Add commentary or sound effects for a more interactive experience.

## License
This project is free to use and modify. No license restrictions apply. 🎲 Enjoy!
