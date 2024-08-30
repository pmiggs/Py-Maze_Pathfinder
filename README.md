<h2>Description</h2>
This was a major project I did during my undergraduate. It was the final test to get into one of the prominent research labs in my college (Physics). Essentially, I was an applicant to that research lab and the problem reads as follows:<br/>
<kbd>
<img src="Py_Maze_Problem_Statement.png" width="410" height="410">
</kbd>
<br/>
<br/>
It was all fine and dandy until I saw we were limited to using NumPy and Matplotlib. They were preventing us from using specialized libraries likely to assess our core programming know-how and problem-solving capabilities.

<h2>Programming Proper (WIP)</h2>
The instructions were clear:

- load the image as an array of 0s (walls) and 1s (spaces)
- find at least two paths from start (top-left) to end (bottom-right)
- output each path as a list of coordinates

But exactly how did I go about it? I had to use an algorithm. For context, we had programming courses in our curriculum so I wasn't a complete stranger to approaching this project. To name a few, there's the A* Search, Breadth-First Search (BFS), Depth-First Search, etc. that may be used for such maze-solving problems. At the time, I found BFS the most straight-forward and _subjectively_ more systematic so I decided to implement that. I wouldn't bore you with an elaboration, so here a GIF from Wikipedia describing BFS:
(INSERT GIF OF BFS)

Thus, the gameplan was to set up functions (lots of 'em) to 

We need to define functions... lots of functions. A function to load the maze (as binary), a function to check whether a move is 
