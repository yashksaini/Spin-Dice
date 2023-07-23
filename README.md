# Spin Dice Game

Spin Dice Game is a fun and competitive web-based game for two players. The objective is to reach a score of 100 first by rolling the dice. Players can choose to save their current score and pass the chance to the other player. If a player rolls a 1 on the dice, the current turn's score is lost, and the chance shifts to the other player.

## Demo


https://github.com/yashksaini/Spin-Dice/assets/101442489/bbbe3c7f-4dea-479d-81b0-0b706a24ccff



## Features

- Two-player competitive gameplay
- Interactive dice rolling
- Score-saving and turn-passing mechanism
- Visual feedback for dice rolls and scores
- Winning message display

## Used For

- Practice JavaScript
- Create a multiplayer game
- Fun game for friends and family

## Technologies

- HTML
- CSS
- JavaScript

## About

The game starts with two players competing against each other. Players are randomly selected to take the first turn. On their turn, they click the 'Roll Dice' button to roll the 6-sided dice. If a player rolls a 1, they lose all their accumulated points for the current turn, and their turn ends. Otherwise, the rolled number is added to their current turn's score. Players have the option to 'Hold' their current score, which saves it to their total score, and passes the turn to the other player.

The game continues in this turn-based manner until one of the players reaches a total score of 100 or more. When this happens, a winning message is displayed, and players have the option to start a new game.

## Improvements

- Add animations for dice rolling
- Implement a single-player mode with an AI opponent
- Add sound effects for dice rolling and score-saving

## Problems Faced

1. Managing player turns and scores
   - Solution: Implemented a turn-based system to handle player turns and score tracking.

2. Handling dice rolling logic and showing random results
   - Solution: Used `Math.random()` to simulate dice rolls and update the visuals accordingly.

## Getting Started

To run the game locally, follow these steps:

1. Clone the repository: `git clone https://github.com/yashksaini/Spin-Dice.git`
2. Open the index.html file in your web browser.

Enjoy the game and have fun!
