# Undefeatable-TIC-TAC-TOE-using-AI-in-python
Minimax is a backtracking algorithm that can be used in decision-making and game theory to find the optimal move for a player, assuming that your opponent also plays optimally,it is widely used in two-player turn-based games.

Every state in the game has a value associated with it. In a given state, if the maximizer has the upper hand, then the score of the board will tend to be some positive value. If the minimizer has the upper hand in that board state, then it will tend to be some negative value.
The values of the board are calculated by heuristics which are unique for every type of game.

Here the heuristic values are: 
If the opponent wins = +10 (Required solution as here we are making the opponent rational(AI))
If the player wins   = -10 (The condition that must be avoided)
If no one wins or no more spaces left  = 0 (Draw match condition)




