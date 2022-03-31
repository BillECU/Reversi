# Reversi

Implemented in Html, CSS, and JS


This game is a two people game. In order to play with wither AI, the second or the first hand needs 
to be replaced by “the pureMCT_move(people,game_board)” or “heuristicMCT_move(people,game_board)”.
In the heuristic one, I give the winning side additional 0.5 point per win.
Moreover, I replace the worst case and do another random move in order to check it the best move can be the same for the second round.
