# Tic-Tac-Toe

A simple game of tic-tac-toe. Lets you to play against the computer in three different levels.
## Tech
JavaScript.
## Run

### Option 1
- view demo [here](https://tic-tac-toe-five-sigma.vercel.app/)
### Option 2
- Download [here](https://github.com/t-a-s-h/tic-tac-toe/archive/refs/heads/main.zip).
- Unzip folder.
- Navigate to unzipped folder in terminal.
- Run `node server`.
- Navigate to http://localhost:8080/ in browser.
## Current status
 #complete
## Notes
This game uses minimax which is a decision strategy for AI. Basically, it evaluates several different games to some amount of moves (or depth), with the current game as the starting point, then picks the move that ends in the "best" move according to some rules. Because Tic-Tac-Toe is so simple, this game only evaluates game end states — that is wins, loses, and draws (evaluated as 1, -1, and 0 respectively).
## Future considerations
### UI / UX improvements
- When the dark theme changes as a result of predefined user preference, the toggle at the top-right remains switched to the old value. This could be fixed.
