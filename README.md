# Tic-Tac-Toe-in-python
A board game (such as Tic-tac-toe) is typically programmed as a state machine. Depending on  the  current-state  and  the  player's  move,   the  game   goes  into  the  next-state.  Tic-tac-      toe (or Noughts and crosses, Xs and Os) is a paper and pencil for two players, X and O, who take turns marking the spaces in a 3×3 grid. The player who succeeds in placing three respective marks in a horizontal, vertical, or diagonal row wins the game. 

Using A* Algorithm
A* Algorithm

•	The A* algorithm combines features of uniform-cost search and pure heuristic search to efficiently compute optimal solutions.
•	A* algorithm is a best-first search algorithm in which the cost associated with a node is f(n) = g(n) + h(n), where g(n) is the cost of the path from the initial state to node n and h(n) is the heuristic estimate or the cost or a path from node n to a goal.
•	Thus, f(n) estimates the lowest total cost of any solution path going through node n. At each point a node with lowest f value is chosen for expansion.
•	Ties among nodes of equal f value should be broken in favor of nodes with lower h values.
•	The algorithm terminates when a goal is chosen for expansion.

