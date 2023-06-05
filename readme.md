## Maze Generator Variant
### Description
This is a variant of the maze generator coding challenge as shown here https://youtu.be/HyK_Q5rrcr4. 
Every current cell has it's alpha incremented based on a mapped value to the size of the canvas.
### How to use
1. Clone the repository
2. Open the index.html file in your browser
3. Press F5 to generate a new maze
### How it works
The maze is generated using a recursive backtracking algorithm. The algorithm starts at a random cell and then randomly chooses a neighbour cell to visit. If the neighbour cell has not been visited yet, the algorithm will move to that cell and repeat the process. If the neighbour cell has been visited, the algorithm will backtrack to the previous cell and repeat the process. The algorithm will continue until all cells have been visited.
### Further reading
https://en.wikipedia.org/wiki/Maze_generation_algorithm







