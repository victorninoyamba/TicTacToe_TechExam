# TicTacToe_TechExam
# Tic-Tac-Toe React App

Welcome to the Tic-Tac-Toe React App! This is a simple implementation of the classic Tic-Tac-Toe game using React. It allows two players to take turns marking X and O on a 3x3 grid, aiming to get three marks in a row, column, or diagonal.



## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Compromises and Future Improvements](#compromises-and-future-improvements)
- [Error Cases](#error-cases)
- [Contributing](#contributing)
- [License](#license)

## Features

- Play the classic Tic-Tac-Toe game with a friend.
- Visual feedback for the current player's turn.
- Detection of winning conditions and a game draw.
- Reset the game to play again.

## Installation

To run this project locally, follow these steps:

1. Clone the repository: `(https://github.com/victorninoyamba/TicTacToe_TechExam.git)`
2. Change into the project directory: `cd TICTACTOE-REACT`
3. Install dependencies: `npm install`

## Usage

To start the development server, run the following command:

npm start


Visit `http://localhost:3000` in your web browser to play the game.

## Compromises and Future Improvements

In the interest of time, some compromises were made during the development of this project. Here are the main ones:

- **No AI or Single-player Mode**: The current implementation only allows two human players to play against each other. Adding an AI opponent or a single-player mode against the computer could enhance the user experience.

- **Minimal Styling**: While the game is fully functional, minimal emphasis was placed on styling the interface. Improving the user interface and making it more visually appealing could be a future improvement.

- **Unit Testing**: Comprehensive unit tests were not included in this version. Adding unit tests for components and game logic would ensure more robust and reliable code.

## Error Cases

The current version handles most common error cases gracefully. However, there are some unhandled error cases that might affect the user experience:

- **Invalid Moves**: The game doesn't prevent players from making invalid moves, such as selecting an already occupied cell or playing after the game has ended. Future versions should add proper validations to prevent such scenarios.

- **Browser Compatibility**: While this project was tested on modern browsers, there may be compatibility issues with older browsers. Ensuring cross-browser compatibility would be beneficial for a wider audience.

## Contributing

Contributions to this project are welcome! If you have any ideas, bug fixes, or feature implementations, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


