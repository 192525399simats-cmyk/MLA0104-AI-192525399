# MLA0104-AI-192525399

**Breadth-First Search (BFS) – Pseudocode**

Algorithm BFS(Graph, StartNode)

1. Create an empty Queue Q
2. Create an empty Set Visited

3. Enqueue(StartNode) into Q
4. Add StartNode to Visited

5. While Q is not empty
      a. Node ← Dequeue(Q)
      b. Print(Node)

      c. For each Neighbor of Node
            If Neighbor is not in Visited
                  Add Neighbor to Visited
                  Enqueue(Neighbor) into Q
6. End

**Depth-First Search (DFS) – Pseudocode (Using Stack)**

Algorithm DFS(Graph, StartNode)

1. Create an empty Stack S
2. Create an empty Set Visited

3. Push(StartNode) onto S

4. While S is not empty
      a. Node ← Pop(S)

      b. If Node is not in Visited
            Print(Node)
            Add Node to Visited

            For each Neighbor of Node (in reverse order)
                  Push(Neighbor) onto S
5. End
