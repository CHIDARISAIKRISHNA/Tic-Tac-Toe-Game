# Tic-Tac-Toe Game

This is a simple Tic-Tac-Toe game built using HTML, CSS, and JavaScript. The game allows two players to play a classic game of Tic-Tac-Toe in their browser. Players take turns to place 'X' or 'O' on a 3x3 grid, and the game ends when one player wins or the game results in a tie.

## Features

- Interactive 3x3 grid for playing the game.
- Alternating turns between Player X and Player O.
- A simple status display showing whose turn it is or if the game has ended with a winner or a tie.
- The game ends when there is a winner or when all cells are filled without a winner (tie).

## Technologies Used

- **HTML**: Used to structure the game layout (grid and status text).
- **CSS**: Used to style the game layout, including grid styling, cell appearance, hover effects, and overall page design.
- **JavaScript**: Used to handle the game logic, including player turns, board state management, winner checking, and updating the game status.

## How to Run the Game Locally

1. Clone the repository:
    ```bash
   git clone https://github.com/CHIDARISAIKRISHNA/Tic-Tac-Toe_Game
    ```
2. Navigate to the Project Folder
Move into the directory of the cloned project:
```bash
  cd Tic-Tac-Toe_Game
```
3.```bash
  open index.html  # For macOS
xdg-open index.html  # For Linux
start index.html  # For Windows

``
4. Start playing the game!

## Code Explanation

### HTML Structure

- The game consists of a grid of 9 cells, implemented as `<div>` elements with the class `.cell`.
- Each cell is clickable, and the board is represented as a 3x3 grid using CSS Grid.
- The status of the game (whose turn it is or if there is a winner/tie) is displayed in a `div` with the class `.status`.

### CSS Styling

- The page layout is centered vertically and horizontally using Flexbox.
- The grid has a 3x3 layout, and each cell is styled to appear as a square with an orange background and hover effects.
- Basic styling for text, fonts, and colors, with a background color of fuchsia for the page.

### JavaScript Logic

- The game alternates turns between Player X and Player O.
- A `board` array holds the state of each cell, which can be either 'X', 'O', or an empty string.
- Winning combinations are checked after every move.
- If a player wins or if there's a tie, the game status is updated accordingly, and the game stops.

## How to Contribute

If you'd like to contribute to this project, feel free to fork the repository, make changes, and submit a pull request with your improvements.

