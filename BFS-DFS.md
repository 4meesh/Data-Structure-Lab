# BFS-DFS
This C program implements Breadth-First Search (BFS) and Depth-First Search (DFS) for traversing a graph represented as an adjacency matrix. However, there are some errors in the code that need fixing, which I’ll point out along the way.

Key Components:
Graph Representation

The program stores the graph using an adjacency matrix (adj_matrix[MAX_SIZE][MAX_SIZE]).
total_vertices represents the number of vertices in the graph.
Queue for BFS

The queue (queue[MAX_SIZE]) is used to store the vertices for BFS.
enqueue(int vertex): Adds a vertex to the queue.
dequeue(): Removes and returns a vertex from the queue.
Stack for DFS

The stack (stack[MAX_SIZE]) is used for DFS traversal.
push(int vertex): Adds a vertex to the stack.
pop(): Removes and returns a vertex from the stack.
