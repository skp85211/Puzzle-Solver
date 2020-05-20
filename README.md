# Puzzle-Solver
#####8 x 8 Puzzle Solve using cpp <br>
This project solves the famous 8-puzzle problem using A* Search and Manhattan distance heuristics. The solver takes in the input puzzle and returns the procedure for solving the problem.

<p align="center">
  <img src="8puzzle.png" width="825" height="200" title="8 x 8 Puzzle solver">
</p>

<h4>Salient features of the code are:</h4>
<ol>
<li>	A* search with iterative deepening implemented using the Manhattan distance heuristics.</li>
<li>	Repeat of searched states were avoided by keeping track of the visited states using a boolean vector.</li>
<li>	A state was represented using two parameters - The present state of the puzzle and number of moves needed to reach that state.</li>
<li>	A priority queue with priority based on Manhattan Distance heuristics was implemented using the STL containers.</li>
<li>	The feasibility for the solution of the puzzle was checked using equivalence classes with respect to reachability. This proves to be a critical optimization in the early stage of the code.</li>
</ol>

<h4>Repository contents:</h4>
<ol>
 <li>	A C++ code to solve an 8 puzzle</li>
 <li>	A sample input to check the code against testcases</li>
 <li>	The corresponding output for the given input.</li>

