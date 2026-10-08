# BFS / DFS Graph Search System

## SLE-3: Architectural Design – Full C4 Model

**Course:** 02AML204 – Introduction to Artificial Intelligence  
**Student Name:** Tejas Magdum  
**PRN:** 25UAM100  
**Division:** B

---

## 1. Project Overview

The BFS / DFS Graph Search System is a search-based system that finds a path
from a starting node to a goal node in a graph.

The system allows the user to:

- Provide a graph
- Select a starting node
- Select a goal node
- Choose BFS or DFS search
- Perform graph traversal
- Check whether the goal node is reached
- Generate the final search/path result

The system demonstrates the use of Artificial Intelligence search techniques
through Breadth-First Search (BFS) and Depth-First Search (DFS).

---

## 2. Search Algorithms

### Breadth-First Search (BFS)

BFS explores the graph level by level.

It uses a **Queue** as its frontier data structure.

Basic process:

1. Start from the starting node.
2. Add the starting node to the queue.
3. Remove a node from the queue.
4. Check whether it is the goal.
5. Visit its unvisited neighboring nodes.
6. Add them to the queue.
7. Continue until the goal is found or the queue becomes empty.

### Depth-First Search (DFS)

DFS explores one branch deeply before backtracking.

It uses a **Stack** as its frontier data structure.

Basic process:

1. Start from the starting node.
2. Add the starting node to the stack.
3. Remove a node from the stack.
4. Check whether it is the goal.
5. Visit an unvisited neighboring node.
6. Continue deeper into the graph.
7. Backtrack when required.
8. Continue until the goal is found or the stack becomes empty.

---

## 3. System Architecture – C4 Model

The system is represented using four levels of the C4 model.

### Level 1 – Context Diagram

The user interacts with the BFS / DFS Graph Search System.

The user provides:

- Graph
- Starting node
- Goal node
- Search method

The system processes the input and returns the search/path result.

### Level 2 – Container Diagram

The major containers/modules are:

1. **Input Module**
   - Accepts graph information.
   - Accepts start and goal nodes.
   - Accepts BFS/DFS selection.

2. **Search Engine**
   - Executes BFS or DFS.
   - Controls the search process.

3. **Visited / Memory**
   - Stores nodes that have already been visited.
   - Prevents repeated processing.

4. **Goal Test**
   - Checks whether the current node is the required goal.

5. **Output Module**
   - Displays traversal/path information.
   - Displays the final search result.

### Level 3 – Component Diagram

The Search Engine is divided into smaller components.

For BFS:

- Queue Frontier
- Explored / Visited Set
- Goal Test
- Path Reconstructor

For DFS:

- Stack Frontier
- Explored / Visited Set
- Goal Test
- Path Reconstructor

The visited set prevents repeated node visits and the path reconstructor
uses parent information to generate the final path.

### Level 4 – Code Level Overview

The main classes and functions are:

```text
class Node
