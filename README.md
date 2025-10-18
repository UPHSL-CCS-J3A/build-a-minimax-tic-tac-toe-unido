# build-a-minimax-tic-tac-toe-unido
Tic Tac Toe (PLAYER vs AI)

# 🎮 Tic-Tac-Toe (Human vs AI)

This is a command-line Tic-Tac-Toe game where a human player competes against an AI powered by the Alpha-Beta Pruning algorithm. The board is displayed in a clean 3x3 grid format, with an additional position guide (1–9) to help players choose their moves.

# 🧠 How the Game Works
## How to Play
You'll be asked: Do you want to go first? (y/n)
On your turn, enter a number from 1 to 9 to place your X.
The AI will respond with O, using calculated strategy.

Game ends when:
Three in a row (win),
Board is full (draw).

# 🤖 AI Logic (Alpha-Beta Pruning)

The AI doesn't make random moves — it thinks.
It evaluates each possible outcome and chooses the optimal move using:

Minimax Algorithm → Predicts future outcomes

Alpha-Beta Pruning → Skips unnecessary calculations (faster decisions)


| Function        | Purpose                       |
| --------------- | ----------------------------- |
| `print_board()` | Displays the game board       |
| `winner()`      | Detects a win for X or O      |
| `moves()`       | Finds empty positions         |
| `alphabeta()`   | AI decision-making logic      |
| `play_game()`   | Main game loop and user input |



# Position Guide
'1 | 2 | 3'

'4 | 5 | 6'

'7 | 8 | 9'

Use these numbers to input your moves during gameplay.

# Game Result

At the end of the match, the program will announce:
You Win – if you outsmart the AI
AI Wins – if the AI blocks and completes a line
Draw – if no moves are left

# License

This project is open-source.
Feel free to use, modify, and improve it!
