# Tic-Tac-Toe Game
This is a simple Tic-Tac-Toe game built with React. It allows two players to take turns marking spaces on a 3x3 grid, with the goal of getting three marks in a row, column, or diagonal.

## Features
- Interactive game board with clickable squares.
- Tracks game history and allows players to go back to previous moves.
- Displays game status, including the current player and winner(if any).

## Installation
1. Clone the repository:
```js
git clone https://github.com/IgnatiusRitu/tic-tac-game.git
```
2. Navigate to the project directory:
```js
cd tic-tac-game
```
3. Install dependencies:
```js
npm install
```
4. Start the development server:
```js
npm run dev
```

## Usage
- Click on an empty square on the game board to make a move.
- The game will alternate between "X" and "O" marks for each player.
- The status section at the top of the board displays the current player and winner (if any).
- Use the list of moves on the right to navigate back to the previous game states.

## Code Structure
- `Game Component: `Contains the magic logic for managing game state, handling player moves, and rendering the game board and history.
- `Board Component: `Renders the game board and handles square click events.
- `Square Component: `Renders an individual square on the board.
- `calculateWinner function: `Utility function to determine the winner based on the current board state.

## Contribution 
Feel free to contribute to this project by opening issues or submitting pull requests. Any improvements or bug fixes are welcome!