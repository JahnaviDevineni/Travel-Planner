# Travel-Planner

This project implements Dijkstra’s algorithm in C++ to find the shortest path from a given source node to all other nodes in a weighted graph.


### 🚀 Features

- Dijkstra’s algorithm implemented from scratch  
- Supports undirected, weighted graphs  
- Displays:
  - Shortest distances from a source node
  - Shortest path to a specified destination node  
- Uses adjacency list representation for efficient graph storage

---

### 🛠️ File Overview

- **DijkstraShortestPath.cpp**: Main implementation file containing all logic for graph creation, Dijkstra’s algorithm, and output display

---

### 🧩 Key Components

- A `Graph` class to manage vertices and edges  
- An `EdgeNode` class to represent weighted edges  
- Functions to initialize variables, run the algorithm, and print results  
- A sample graph is hardcoded for demonstration purposes  

---

### 🧪 Sample Execution

The main function constructs a graph with 5 vertices and several weighted edges. The algorithm then finds the shortest paths from vertex 1 and prints:

- The shortest path from vertex 1 to vertex 5  
- The shortest distances from vertex 1 to all other vertices  

---

### 🧮 Time Complexity

The algorithm runs in O(n²) time due to the linear search used for selecting the next vertex with the smallest distance.
