# Implementation of Kruskal's and Prim's Algorithms for Minimum Spanning Tree (MST)

## Aim
To implement Kruskal's Algorithm and Prim's Algorithm to find the Minimum Spanning Tree (MST) of a weighted undirected graph.

## Description
This program implements two popular greedy algorithms for constructing a Minimum Spanning Tree:

1. **Kruskal's Algorithm**
   - Sorts all edges in increasing order of weight.
   - Uses the Union-Find (Disjoint Set) data structure to avoid cycles.
   - Adds the smallest edge that does not form a cycle until the MST is complete.

2. **Prim's Algorithm**
   - Starts from any vertex.
   - Uses a Priority Queue (Min Heap) to always select the minimum-weight edge.
   - Expands the tree by adding the nearest unvisited vertex.

## Requirements
- Python 3.x
- heapq module (built-in Python library)

## Input
- Number of vertices
- Weighted edges of the graph

## Output
- Minimum Spanning Tree using Kruskal's Algorithm
- Minimum Spanning Tree using Prim's Algorithm
- Total cost of the MST

## Algorithms Used
- Greedy Algorithm
- Union-Find (Disjoint Set)
- Priority Queue (Min Heap)

## Time Complexity

### Kruskal's Algorithm
- Sorting Edges: **O(E log E)**
- Union-Find Operations: **O(E α(V))**
- Overall: **O(E log E)**

### Prim's Algorithm
- Using Min Heap: **O(E log V)**

## Conclusion
Both Kruskal's and Prim's Algorithms successfully construct the Minimum Spanning Tree of a weighted graph. Although their approaches differ, both produce the same minimum total cost for the graph.
