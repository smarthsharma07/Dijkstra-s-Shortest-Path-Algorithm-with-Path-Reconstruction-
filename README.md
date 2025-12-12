# Dijkstra-s-Shortest-Path-Algorithm-with-Path-Reconstruction-
# Dijkstra's Shortest Path Algorithm (with Path Reconstruction)

This project implements **Dijkstra's algorithm** to compute the shortest paths from a starting node to all other nodes in a weighted graph.  
It supports:

- Shortest *distances*
- Full path reconstruction
- Optional selection of a specific `target_node`
- Clear, formatted output of each path

---

## 🚀 Features

- Uses an adjacency matrix as the graph representation.
- Computes:
  - Minimum distance from the start node to every other node
  - The actual nodes visited along each shortest path
- Allows printing either:
  - All node results
  - Only a specific `target_node`
- Handles unreachable nodes and avoids printing the start node.
- Clean and readable Python implementation.

---

## 📌 Example Graph (Adjacency Matrix)

```python
INF = float('inf')
adj_matrix = [
    [0, 5, 3, INF, 11, INF],
    [5, 0, 1, INF, INF, 2],
    [3, 1, 0, 1, 5, INF],
    [INF, INF, 1, 0, 9, 3],
    [11, INF, 5, 9, 0, INF],
    [INF, 2, INF, 3, INF, 0],
]
