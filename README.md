# tictactoe
Contains a modified version of the great old game of tic tac toe which needs 2 players to play.
1. In each square of the tic tac toe board, we have a smaller ti tac toe board.
2. Each turn, you mark one of the small squares.
3. When you get three in a row on a small board, you've won that board.
4. To win the game, you need to win three small boards in a row.
5. The cool thing is, you don't get to pick which of the nine boards to play on. That's determined by your opponent's previous move.
6. Whichever square he picks, that's the board you must play in next( And whichever square you pick will next determine which board he 
plays on next. e.g if the other player marked in the top right corner of the current board, then you have to move to the board on the top
left side of the actual bigger board and make a move there. This lends the game a strategic element.
7. If your opponent sends you to an already won board, you can go to any board of your choice and make a move there.
8. A tied board is NOT counted.
