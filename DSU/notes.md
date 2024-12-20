# Notes on Detecting Cycles in a Graph and Minimum Spanning Tree

## Applications
- **Cycle Detection**: Can be used to detect cycles in a graph.
- **Minimum Spanning Tree**: 
  - Kruskal's Algorithm (also solvable using Prim's algorithm).
- **Checking Connected Components**: Can be used to check the number of connected graphs.

### Requirements
- The graph must be **undirected**.

---

## Steps
1. **Union**
2. **Find**

---

## Optimization Techniques

### Collapsing Find
- Reduces the time complexity for finding the parent to nearly constant time O(4)
- Achieved through the **inverse Ackermann function**.

### Union by Rank vs. Union by Size
- **Union by Rank**:
  - Ranks parents by the depth of their deepest child.
  - Becomes less intuitive after path compression as ranks do not change.
- **Union by Size**:
  - Ranks parents by the number of children.
  - Preferred method due to better consistency with path compression.

# Resources for Disjoint Set Union (DSU)

## 1. TakeUForward (TUF)
- [Disjoint Set (Union by Rank, Union by Size, Path Compression)](https://takeuforward.org/data-structure/disjoint-set-union-by-rank-union-by-size-path-compression-g-46/)  
- A detailed article explaining the concepts of DSU with:
  - Union by Rank
  - Union by Size
  - Path Compression
  - Examples and code snippets.

## 2. Abdul Bari (YouTube)
- [Disjoint Set Data Structure](https://youtu.be/wU6udHRIkcc?si=D7JSlRKqhCM3a7pc)  
- A comprehensive video tutorial covering the basics and implementation of DSU.
- Great for visual learners and beginners.