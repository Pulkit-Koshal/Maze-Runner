# Maze_Runner

The Program consists of 5 separate files.
  1 Main
  `To run the program.`
  
  2 Graphics
  `Using Tkinter Package along with canvas module, I created a small Interface ***Window***, along with 2 other classes ***Line and Point*** to draw on the canvas.`
  
  3 Cell
  `Using the classes present in ***Graphics.py***, i created 2 functions to draw a cubical cell and to draw a red & gray line for recording the moves.`
  
  4 Maze
  ```
Now using the Cell class, i created 4 functions
- Create Cells : To append cells generated on in grid pattern.
- Draw Cells : To Draw cells at a particular point and animate it.
- Break Entrace and Exit : Removes the top of the first Cell at (0,0) and Bottom wall at bottomost right cell.
- Break Walls : To calculate possible moves using the cartesian coordinate of cell and to randomly remove walls using ***Random*** Library methods.
- Solve : Simple Implementation of DFS search to find out the solution.
```

  5 Test
  `This consists of Unit tests to ensure the program in in-sync with the goal`
  
  
  

