### BFS (Breadth-First Search) - Pseudocode

```text
Algorithm BFS(Graph, Start_Node)

1. Create an empty set Visited.
2. Create an empty Queue.
3. Enqueue(Start_Node).
4. Add Start_Node to Visited.
5. While Queue is not empty:
   a. Node ← Dequeue()
   b. Visit(Node)
   c. For each Neighbor in Graph[Node]:
      i. If Neighbor is not in Visited:
         - Add Neighbor to Visited
         - Enqueue(Neighbor)
6. End
```
