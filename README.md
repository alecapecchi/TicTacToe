# Tic Tac Toe
A simple Tic Tac Toe game with a "spooky" Halloween theme. You can play it [here](https://alecapecchi.github.io/tictactoe/game.html)!

## MODES
The game supports 4 different game modes:
* **IMPOSSIBLE**: An AI agent performs a [minimax search](https://en.wikipedia.org/wiki/Minimax), with alpha beta optimization,
reaching the end of the game every time. 
It returns 1 for win, -1 for loss, 0 for a tie.  
The agent chooses the move that can lead to the best possible outcome. 
Tic Tac Toe, assuming best play from both players, will always end in a draw. 
The minimax algorithm (that assumes the best play from both players) finds
at least a draw strategy. A win strategy is possible only if the opponents makes a mistake.

* **MEDIUM**: Like the impossible level, the agent performs a minimax search (with alpha beta optimization). 
It will, however, play out only the 2 immediately next moves (the AI's and the 
opponent's). If the reached state is not game over, the move will be chosen 
according to a weight: center (weight=0.3), corners (0.2), middle (0.1)

* **EASY**: The AI chooses a random move out of all the available ones
* **PlayerVSPlayer**

## SCREENSHOT

## LIBRARIES and MORE
The project is written in Javascript, HTML and JQuery, and makes use of:
* [Bootstrap](https://getbootstrap.com/)
* [SweetAlert](https://sweetalert.js.org/)
* [Animate.css](https://animate.style/)
* And the following icons from iconfinder.com: [ghost](https://www.iconfinder.com/icons/6973617/ghost_scarry_spooky_sheet_entity_halloween_horror_icon) 
and [pumpkin](https://www.iconfinder.com/icons/1531922/halloween_lamp_pumpkin_icon)
