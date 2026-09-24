
# Tic-Tac-Toe

## 1. Overview: What does your project do?

This project is a two-player Tic-Tac-Toe game built with React. Players take turns placing X and O on a 3x3 board. The game detects when a player wins and displays the winner. It also allows users to restart the board after a game ends.

## 2. How to run it

### Installation

Make sure you have Node.js and npm installed.

Clone the repository or download the project, then navigate to the project directory:

cd tictactoe

Install the dependencies:

npm install

### Start the development server

Run the following command: 

npm start

Open the local URL provided in the terminal (usually http://localhost:3000).

## 3. Your contribution

I built the Tic-Tac-Toe game using React and implemented the core game functionality.

My contributions include:
- Creating reusable Square components to represent each cell on the board.
- Implementing click handling to allow players to place X and O.
- Developing a function to detect winning combinations across rows, columns, and diagonals.
- Implementing a restart button to reset the board after a game ends.
- Managing game state using React's useState.

## 4. What I learned

Coming from a Java and Spring Boot background, I was familiar with structuring backend applications using classes, services, and APIs, but I had less experience building interactive frontends. This project helped me understand how React manages UI state and responds to user interactions through components and event handlers. In particular, I learned how useState allows the interface to update dynamically when the game board changes. I also gained a better understanding of the relationship between application logic and the UI, since each move updates the game state and immediately reflects the result on the board.

## 5. References

- React Tic-Tac-Toe Tutorial: https://react.dev/learn/tutorial-tic-tac-toe