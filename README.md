# Dijkstra-and-A-Search-Algorithm-with-CoppeliaSim
Implementation Dijkstra and A* Search Algorithms in CoppeliaSim Robotics Simulation Program

In study 1, the Quadcopter was observed to follow the path manually added to the scene. 

In the 2nd study, Dijkstra's algorithm was applied on the Quadcopter and it was observed to reach the target point by avoiding obstacles and then returning to the shortest path it found.

In study 3, the same process was repeated for the A* search algorithm.

One of the most important points about this study is that the code file is added to the target object of the Quadcopter. Otherwise the Quadcopter will not move. 

In all three studies, operations were performed on matrices. Scene coordinates were converted into matrices. Then each point of the floor squares was defined as a node (121 nodes in total). Weights and costs were found according to Euclidean and Manhattan distance. Since these distances are the same, the shortest paths found are the same. 

This project is open source and I hope it will inspire fellow engineers friends like me.

For the contact: kayaliselman0@gmail.com
