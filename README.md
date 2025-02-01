# Tic-Tac-Toe with Unbeatable AI 🤖

A classic Tic-Tac-Toe implementation featuring an unbeatable computer opponent using the Minimax algorithm. Developed in C++ for optimal performance.

![Tic-Tac-Toe Demo](https://via.placeholder.com/400x250?text=Tic-Tac-Toe+Demo+Preview)

## Features ✨
- **Unbeatable AI** using Minimax algorithm with alpha-beta pruning
- Interactive console-based interface
- Clear board visualization
- Turn indicator and move validation
- Win/draw detection
- Option to play first or let computer start

## How to Play 🎮
1. Choose who starts
2. Enter cell numbers (1-9) when prompted:
   ```
    1 | 2 | 3
   -----------
    4 | 5 | 6
   -----------
    7 | 8 | 9
   ```
3. Watch the AI respond with optimal moves
4. Game ends when someone wins or board is full

## Minimax Algorithm 🧠
The AI uses the Minimax algorithm with these key components:

```
int minimax(char board[][SIDE], int depth, bool isAI) {
    if (gameOver(board)) {
        return isAI ? -10 : +10;
    }
    // Recursive depth-first search
    // Maximizes computer's advantage
    // Minimizes human's opportunities
}
```

**Key characteristics:**
- Recursive depth-first search
- Brute-force evaluation of all possible moves
- Score evaluation (+10 for AI win, -10 for human win)
- Optimal move selection through backtracking

## Future Improvements 🔮
- [ ] Add GUI interface
- [ ] Implement difficulty levels
