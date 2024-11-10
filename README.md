# BFS Graph Traversal in C++
This program implements the Breadth-First Search (BFS) algorithm to traverse an undirected graph. The graph is represented using an adjacency matrix.

# Getting Started
# Prerequisites
A C++ compiler, such as GCC
Basic knowledge of graph traversal concepts and C++ programming

# Program Details
**Input**
The program first asks for the number of vertices (v) and edges (e) in the graph.
It then prompts for e pairs of integers, where each pair represents an edge between two vertices.
Finally, it asks for the source vertex from which to start the BFS traversal.
**Output**
The program outputs the BFS traversal order, starting from the given source vertex.

#Example
Input:
Enter the number of vertices: 5
Enter the number of edges: 4
0 1
0 2
1 3
1 4
Enter the source element: 0
Output:

0 1 2 3 4
# Code Explanation
add() Function: Adds an undirected edge between two vertices in the adjacency matrix.
BFS() Function: Implements BFS using a queue and a visited array to track visited nodes, ensuring each vertex is visited only once.
main() Function: Reads input, sets up the adjacency matrix, and calls the BFS() function to start traversal from the specified source.
