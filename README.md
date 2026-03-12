# Tic Tac Toe Collection 

We built this as a team of four for our OOP course — 13 different Tic Tac Toe variants, all in C++. Each game has its own twist on the classic rules, from boards that change shape to moves that disappear over time.

## The Games

| # | Game | What makes it different |
|---|------|------------------------|
| 1 | **SUS Game** | Spell "S-U-S" instead of getting three in a row |
| 2 | **Four-in-a-Row** | Think Connect Four, but on a flat grid |
| 3 | **5x5 Tic-Tac-Toe** | Bigger board, need four in a row to win |
| 4 | **Word Tic-Tac-Toe** | Place letters to form valid three-letter words |
| 5 | **Misère** | Don't get three in a row — the loser wins |
| 6 | **Diamond** | Diamond-shaped board, complete two lines to win |
| 7 | **4x4 Tic-Tac-Toe** | Same rules, just more room to think |
| 8 | **Pyramid** | Triangular board with rows of different lengths |
| 9 | **Numerical** | Place numbers — first to line up a sum of 15 wins |
| 10 | **Obstacles** | Some cells are blocked, plan around them |
| 11 | **Infinity** | Your oldest move vanishes every 3 turns |
| 12 | **Ultimate** | Every cell hides a full 3x3 board inside it |
| 13 | **Memory** | Marks get hidden after placement — remember where you played |

## How to Run

You need g++ (C++11 or later). Clone the repo and compile:
```bash
make
./game.out
```

Pick a game from the menu (1–13), choose your player types, and play. After each game you go back to the main menu automatically.

## Documentation

We used Doxygen for the full docs. To generate them locally:
```bash
doxygen Doxyfile
```

Then open `output/html/index.html` in your browser.

## The Team

- Asmaa Farouq
- Arwa Bshier  
- Mariam Sherif
- Mariam Ahmed