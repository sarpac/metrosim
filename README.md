Metro Simulation

In this project I used BFS and A* algorithm to find the most optimal solution.

Libraries used:
  1) Collections: The collection Module in Python provides different types of objects that is used to store different objects         and provide a way to access those objects and iterate over them.
  
      a) deque: It is a data structure that allows adding and removing elements from both ends efficiently.
      b) heapq: It is a data structure that allows us to quickly access the smallest or largest element.

  2) typing: Allows us to use Dict, List, Set, Tuple and many more.

       a) Dict: Dictionaries are used to store data values.
       b) List: Lists are used to store multiple items in a single variable.
       c) Set: Sets are used to store multiple items in a single variable.
       d) Tuple: Tuples are used to store multiple items in a single variable.
       e) Optional: It is telling us that either an object of the specific type is required, or None is required.

How BFS works?
  BFS works by visiting all nodes at the current level before moving to the next level. Which allows us to find the shortest      path because BFS always looks for the closest path to itself. (Unweighted)

  1) Starting node: Selects a node and starts visiting all children of that node before moving to the next level.
  2) Exploring neighbours: Visits unvisited nodes.
  3) Repeat
  
How A* works?
  A* works with Dijkstra and Greedy Best-First so it is both optimal and efficient.

  1) Calculates the cost of a node.
  2) Calculates the weight of all neighbours and visits the node with the least cost.
  3) Repeat
