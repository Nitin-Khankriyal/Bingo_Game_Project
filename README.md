# Terminal Bingo Game in C

A lightweight, local 2-player Bingo game played directly inside your command line/terminal. This project demonstrates foundational programming concepts in C, including 2D arrays (matrices), nested loops, dynamic game states, and win-condition validation logic.

## How the Game Works

1. **Grid Setup:** Player 1 and Player 2 take turns entering their unique 5x5 grid layout using numbers from 1 to 25.
2. **Gameplay:** Players dynamically call out numbers they wish to "cross off" the board. 
3. **Tracking:** When a number is selected, the game automatically zeroes it out (`0`) on both players' boards if it exists.
4. **Winning:** The game continuously checks rows, columns, and both diagonals. The first player to successfully complete **5 lines** (rows, columns, or diagonals) wins the match!


## Features

- **Custom Matrix Setup:** Allows players to manually arrange their card numbers for strategic variety.
- **Simultaneous Tracking:** Crosses out selected numbers across both player grids seamlessly in a single turn.
- **Automated Win Checking:** Instantly evaluates rows, columns, and major/minor diagonals after every input.
  

## Getting Started

### Prerequisites
You will need a C compiler installed on your system (such as `gcc` or `clang`).

### Compilation
Open your terminal, navigate to the project directory, and compile the source file:

```bash
gcc bingo.c -o bingo
