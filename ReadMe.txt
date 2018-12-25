Implementation-Of-Data-Structures-RobinHoodHashing
UTD CS5V81-001 - Short Project 8

Project By :Mythri Thippareddy (mxt172530) and Achyut Bhandiwad (aab180004)

Submitted on: 10/28/2018

This Project was implemented as part of the course CS5V81-001 Implementation of Data Structures and Algorithms at University of Texas at Dallas.

The goal of the project was to create the functionality of Depth First Search

Depth First Search

File Name: DFS.java Package name: mxt172530

The following methods are implemented: 1. depthFirstSearch 2. topologicalOrder1 3. connectedComponents 

Results:

______________________________________________
Graph: n: 7, m: 8, directed: false, Edge weights: false
1 :  (1,2) (1,3) (5,1)
2 :  (1,2) (2,4)
3 :  (1,3) (3,4)
4 :  (2,4) (3,4) (4,5)
5 :  (4,5) (5,1)
6 :  (6,7) (7,6)
7 :  (6,7) (7,6)
______________________________________________
Number of components: 2
u	cno
1	1
2	1
3	1
4	1
5	1
6	2
7	2

Output of Dfs:
Node	top	Parent
----------------------
1	3	null
2	4	1
3	7	4
4	5	2
5	6	4
6	1	null
7	2	6

Output of topological order
-----------------------------
Graph is cyclic. No topological order exists