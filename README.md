# Pig Game 🐷

A simple and fun dice game for two players. The goal is to be the first player to reach 100 points!

## ℹ️ About this Project

This project is part of **The Complete JavaScript Course** by Jonas Schmedtmann.

- **HTML/CSS**: Provided as starter code (design & layout).
- **JavaScript**: Implemented by me (game logic & DOM manipulation).

My main focus in this project was to learn how to manipulate the DOM, handle events, and manage game state variables.

## 🎮 Game Rules

The game has 2 players, playing in rounds.

1. In each turn, a player rolls a dice as many times as they wish. Each result gets added to their **Current Score**.
2. **BUT**, if the player rolls a **1**: all their current score is lost, and the turn switches to the next player.
3. The player can choose to **"Hold"**, which means their current score is added to their **Global Score**. After that, it's the next player's turn.
4. The first player to reach **100 points** wins the game.

## ✨ Features Implemented (JS)

- **Game State Management**: Tracking active player, current scores, and total scores.
- **DOM Manipulation**: Updating the UI dynamically based on game events.
- **Event Handling**: Logic for "Roll Dice", "Hold", and "New Game" buttons.
- **Win Condition**: Checking if the total score is >= 100.

## 🛠 Technologies

- **JavaScript (ES6+)** - _My focus_
- HTML5 & CSS3 - _Starter code_

## 🚀 How to Run

1.  Clone this repository.
2.  Open `index.html` in your browser.

## 🌐 Live Demo

https://kyryl-h.github.io/pig-game/
