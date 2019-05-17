TicTacToe game
===============

Tic Tac Toe game, which is also called **noughts and crosses(British)** and **Xs and Os** is popular paper-and-pencil game.

There are two players in this game. Player who takes turn should mark O or X in **3X3 grid.**

Player who fills the horizontal, vertical, diagnoal row first win the game.
If you want to see more information about game, please visit 

> <https://en.wikipedia.org/wiki/Tic-tac-toe>

----------------------------------------------------------------------------------------------------------------------------

- Strategy


Win: If the player has two in a row, they can place a third to get three in a row.
Block: If the opponent has two in a row, the player must play the third themselves to block the opponent.
Fork: Create an opportunity where the player has two ways to win (two non-blocked lines of 2).
Blocking an opponent's fork: If there is only one possible fork for the opponent, the player should block it. Otherwise, the player should block any forks in any way that simultaneously allows them to create two in a row. Otherwise, the player should create a two in a row to force the opponent into defending, as long as it doesn't result in them creating a fork. For example, if "X" has two opposite corners and "O" has the center, "O" must not play a corner in order to win. (Playing a corner in this scenario creates a fork for "X" to win.)
Center: A player marks the center. (If it is the first move of the game, playing on a corner gives the second player more opportunities to make a mistake and may therefore be the better choice; however, it makes no difference between perfect players.)
Opposite corner: If the opponent is in the corner, the player plays the opposite corner.
Empty corner: The player plays in a corner square.
Empty side: The player plays in a middle square on any of the 4 sides.
