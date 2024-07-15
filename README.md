# Dice Game

This is a simple two-player dice game created using HTML, CSS, and JavaScript. The game allows players to take turns rolling a dice, holding their score, and trying to be the first to reach 100 points.

## Table of Contents

- [Features](#features)
- [Setup](#setup)
- [How to Play](#how-to-play)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Two-player game.
- Players take turns rolling a dice.
- Players can hold their current score to add it to their total score.
- The first player to reach 100 points wins the game.
- New game button to reset the game.

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/yonathandevpro/GUESS-MY-NUMBER.git
    ```

2. Navigate to the project directory:
    ```sh
    cd GUESS-MY-NUMBER
    ```

3. Open `index.html` in your web browser to start the game.

## How to Play

1. Player 1 starts the game.
2. Click the "Roll dice" button to roll the dice.
3. If the dice roll is not 1, the dice value is added to the current score.
4. If the dice roll is 1, the current score is lost, and it becomes the next player's turn.
5. Click the "Hold" button to add the current score to the total score and switch turns.
6. The first player to reach 100 points wins the game.
7. Click the "New game" button to reset the game and start over.

## Project Structure

```sh
GUESS-MY-NUMBER/
├── index.html
├── style.css
└── script.js
```
### index.html

The main HTML file that structures the game layout. It includes sections for both players, buttons for game actions, and a dice image.

### style.css

The CSS file for styling the game. It includes styles for the game layout, player sections, buttons, and the dice image.

### script.js

The JavaScript file that contains the game logic. It handles the game initialization, dice roll functionality, score holding, and player switching.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

1. Fork the Project.
2. Create your feature branch:
    ```sh
    git checkout -b feature/AmazingFeature
    ```
3. Commit your changes:
    ```sh
    git commit -m 'Add some AmazingFeature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature/AmazingFeature
    ```
5. Open a pull request.

## License

Distributed under the MIT License. See `LICENSE` for more information.
