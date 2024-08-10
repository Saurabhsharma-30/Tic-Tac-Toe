# Tic-Tac-Toe with Minimax Algorithm

A simple console-based Tic-Tac-Toe game where a player competes against a computer. The computer uses the Minimax algorithm to make optimal moves, ensuring the best possible outcome.

## Features

- **Player vs. Computer:** Play against a computer that makes the best possible moves.
- **Minimax Algorithm:** The computer uses the Minimax algorithm to determine the optimal move.
- **Console-Based:** Interact with the game through a command-line interface.

## Getting Started

### Prerequisites

- Python 3.x installed on your machine.

### Running the Game

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/tic-tac-toe.git
   ```

2. **Navigate to the Directory**

   ```bash
   cd tic-tac-toe
   ```

3. **Run the Script**

   ```bash
   python tic_tac_toe.py
   ```

4. **Play the Game**

   - Input your moves as row and column numbers (0-2) separated by a space.
   - The computer will make its move automatically.

## Code Overview

- **`print_board(board)`**: Displays the Tic-Tac-Toe board.
- **`check_win(board, player)`**: Checks if the specified player has won.
- **`get_empty_cells(board)`**: Returns a list of empty cell coordinates.
- **`minimax(board, depth, is_maximizing)`**: Evaluates possible future board states for optimal moves.
- **`find_best_move(board)`**: Determines the best move for the computer.
- **`play_game()`**: Main game loop handling player and computer moves.

## Example Gameplay

```plaintext
Enter your move (row col): 0 0
X |   |  
---------
   |   |  
---------
   |   |  

Computer's turn...
X | O |  
---------
   |   |  
---------
   |   |  
```

## Contributing

Feel free to fork the repository, make changes, and submit pull requests. Contributions and feedback are welcome!

## Contact

For any questions or suggestions, please contact [your email address].

---

Replace `[saurabhsharma-30]` and `[saurabhsharma2346@gmail.com]` with your actual GitHub username and email address. You can also adjust any other details to better fit your project.
