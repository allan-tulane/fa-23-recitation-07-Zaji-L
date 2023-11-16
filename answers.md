# CMPS 2200 Recitation 10## Answers

**Name:** Charlie Landman
**Name:**_________________________


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**
the work of reachable is O(n+m) where n is the number of nodes and m is the number of edges
- **4)**
the worst case is once, because if you are calling this function at all, it means that the nodes are all connected (and thus reachable) to each other. In other words, the best case and worst case are the same.
- **5)**
the work is also O(n+m) because it calls reachable and that function does most of the work internally.
- **7)**
with an adjacency matrix, the work of reachable would be O(n^2) because checking for edges between all pairs requires it to search the entire matrix which is n*m.