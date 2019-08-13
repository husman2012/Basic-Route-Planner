# Basic-Route-Planner
Basic entry-level program to refresh C++ skills. Route Planner that takes a board object and determines the best route from start to end using A* search algorithm.

During program output, obstacles for the agent are displayed as mountains, open nodes are displayed by 0's, goals are flags, start point is the traffic light and the agent's route is the car. User may modify the board as needed by using 1's to place mountains and 0's to place open nodes.

<h1>Files</h1>
The following files are present and necessary to run the route planner: board and main.cpp.
Board is simply a text file that the user may edit to create new boards. 0's are open nodes while 1's are closed nodes. Main.cpp is the main file which will read in the board and utilize A* search to find the fastest path.

<h1>How to use</h2>
Running the program is relatively straightforward. Place both files into the same directory and run main.cpp in an IDE such as VS Code by calling the file in the terminal such as:

```
g++ main.cpp
```
Followed by:
```
./a.out
```

The program should output the solution to the terminal. 

<h1>Changing start and end states</h2>
The user may change the start and end states for the agent by changing the parameters in the main.cpp file. Init and goal are the variables to change and must be located within the board or the program will not run. Further functionality may be added later to support user input.
