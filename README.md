# Approximation Algorithms to solve Minimum Feedback Vertex Set Problem in Python

A feedback vertex set (FVS) of a graph is a set of vertices whose removal leaves a graph without a cycle. The minimum FVS problem is an NP-complete problem. The problem stated that "Given an undirected graph $G=(V,E)$, find the smallest set of vertices such that removing them from the graph makes it acyclic (a forest)." In this project, we are dealing with an undirected simple graph.

The minimum-FVS problem is used in the study of deadlock recovery. Each cycle is the deadlock situation that we are trying to solve, and the minimum feedback vertex set is the minimum number of processes that need to be aborted.

In this project, we will be looking at approximation algorithms to find the minimum feedback vertex set and comparing the approximate solution to the optimal solution.

Algorithms:

1. Naive Algorithm $O(2^V(V+E))$

2. Local Ratio Feedback Vertex Set Algorithm: $O(V^3)$

3. Improved Local Ratio Feedback Vertex Set Algorithm: $O(V^3C)$

4. Greedy Algorithm: $O(V^3)$

References:

1. Bafna, V., Berman, P., & Fujito, T. (1999). A 2-approximation algorithm for the undirected feedback vertex set problem. *SIAM Journal on Discrete Mathematics*, *12*(3), 289-297.

2. GeeksforGeeks. (2022, September 15). Print all the cycles in an undirected graph. GeeksforGeeks. [Link](https://www.geeksforgeeks.org/print-all-the-cycles-in-an-undirected-graph/)

3. Ravi, R. (2005, October 10). Minimum Feedback Vertex Set. Carnegie Mellon University. [Link](https://www.cs.cmu.edu/afs/cs/academic/class/15854-f05/www/scribe/lec9.pdf)

4. Wikimedia Foundation. (2023, December 11). Feedback vertex set. Wikipedia. [Link](https://en.wikipedia.org/wiki/Feedback_vertex_set)

