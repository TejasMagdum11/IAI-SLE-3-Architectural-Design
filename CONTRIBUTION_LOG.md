### CONTRIBUTION_LOG.md

```markdown
# Contribution Log

## SLE-3: BFS / DFS Graph Search System

**Course:** 02AML204 – Introduction to Artificial Intelligence  
**Student Name:** Tejas Magdum  
**PRN:** 25UAM100  
**Division:** B

---

## Project Contribution

I worked on the architectural design of the BFS / DFS Graph Search System
using the Full C4 Model.

The main contribution was understanding the system requirements and
representing the system at four different architectural levels.

---

## Contribution Details

| Sr. No. | Activity | Contribution |
|--------:|----------|--------------|
| 1 | Project Selection | Selected the BFS / DFS Graph Search System |
| 2 | System Understanding | Studied how BFS and DFS search a graph |
| 3 | Context Diagram | Identified the user and system interaction |
| 4 | Container Diagram | Identified the major system modules |
| 5 | Component Diagram | Divided the Search Engine into smaller components |
| 6 | Code-Level Design | Identified classes and functions |
| 7 | BFS Design | Identified Queue Frontier and BFS responsibilities |
| 8 | DFS Design | Identified Stack Frontier and DFS responsibilities |
| 9 | Memory Design | Included visited/explored set to prevent repeated visits |
| 10 | Goal Test | Included goal checking component |
| 11 | Path Reconstruction | Included parent-based path reconstruction |
| 12 | Documentation | Prepared explanations for the C4 architecture |
| 13 | Review | Reviewed the architecture and diagrams |
| 14 | AI Assistance | Used ChatGPT for C4 structure and explanation support |

---

## C4 Model Contribution

### Level 1 – System Context

I identified the interaction between the user and the BFS / DFS Graph
Search System.

The user provides:

- Graph
- Starting node
- Goal node
- Search method

The system returns the search/path result.

### Level 2 – Containers

I identified the following major modules:

- Input Module
- Search Engine
- Visited / Memory
- Goal Test
- Output Module

### Level 3 – Components

I divided the Search Engine into smaller components:

- BFS Queue Frontier
- DFS Stack Frontier
- Explored / Visited Set
- Goal Test
- Path Reconstructor

### Level 4 – Code

I identified the main classes and functions:

- `Node`
- `Graph`
- `bfs()`
- `dfs()`
- `goal_test()`
- `reconstruct_path()`

---

## AI Contribution Log

### AI Tool Used

ChatGPT

### Purpose of AI Usage

AI was used as a supporting tool for:

1. Understanding the C4 model.
2. Understanding the difference between C4 levels.
3. Organizing the architectural components.
4. Improving explanations.
5. Improving diagram labels.
6. Structuring the documentation.

### What AI Helped With

AI suggested a clear four-level C4 structure and helped make the
documentation concise and understandable.

### What I Did Myself

I personally:

- Selected the BFS / DFS system.
- Understood the system requirements.
- Selected the required modules.
- Verified BFS and DFS responsibilities.
- Reviewed the diagrams.
- Reviewed the architecture.
- Ensured that I could explain the design.

---

## Verification

I reviewed the complete architecture and verified that:

- Input handling is separated from searching.
- BFS uses a queue frontier.
- DFS uses a stack frontier.
- Visited memory prevents repeated processing.
- Goal Test checks the target node.
- Path Reconstruction generates the final path.
- Output displays the search result.

---

## Final Statement

I contributed to the design and documentation of the BFS / DFS Graph Search
System using the Full C4 Model.

AI was used only as a supporting tool for understanding, organizing, and
improving the documentation. The final system selection, architecture
review, module verification, and understanding of the design were completed
by me.
