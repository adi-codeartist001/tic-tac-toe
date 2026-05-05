# Tic-Tac-Toe

A tic-tac-toe game with two modes — play against a friend or against an unbeatable CPU opponent.

The CPU uses the minimax algorithm, which means it plays a perfect game every time. You can draw against it if you play correctly, but you cannot beat it.

## What's in it

- Two-player mode and CPU mode toggled from the UI
- Minimax algorithm for the AI — explores all possible game states to pick the optimal move
- Win detection across all 8 winning combinations
- Winning cells animate when the game ends
- Score tracking across games (X wins, O wins, draws)
- New game and full score reset controls

## How minimax works here

After every human move, the AI recursively simulates every possible move for both players until it reaches a terminal state (win, loss, or draw). It assigns scores — positive for CPU wins, negative for losses — and picks the move that leads to the best guaranteed outcome. Depth is tracked so it prefers faster wins over slower ones.

## Tech

HTML · CSS · JavaScript (no dependencies)

## Live demo

[adi-codeartist001.github.io/tic-tac-toe](https://adi-codeartist001.github.io/tic-tac-toe)

## Running locally

Open `index.html` in a browser.

---

Made by [Aditya Srivastava](https://github.com/adi-codeartist001)
