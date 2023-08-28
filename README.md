# Lights Out Game

### Play the live game [here](https://strawhatrag.github.io/react-lightsOut-game).

![Lights Out Game Demo](public/lightsout.gif) 

A Lights Out game implemented using React. Toggle the cells to turn off all the lights and win the game!

## Features

- Customizable board size (number of rows and columns).
- Responsive design with neon lights bars styling.
- Randomly generated initial light configuration.

## How to Play

1. Clone this repository to your local machine.
2. Navigate to the project directory using the terminal.
3. Install the required dependencies by running `npm install`.
4. Start the development server with `npm start`.
5. Open your web browser and visit `http://localhost:3000` to play the Lights Out game.
6. Click on the cells to toggle their states. The goal is to turn off all the lights on the board.
7. You win when all the lights are turned off.

## Customization

You can customize the game by adjusting the following options:

- Board size (number of rows and columns).
- Initial probability of lights being turned on.

These options are defined as `defaultProps` at the beginning of the `Board.js` file.

## About

This project demonstrates building a Lights Out game using React components and styling.

Feel free to explore the code and make any improvements or modifications you'd like. If you find any issues or have suggestions, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
