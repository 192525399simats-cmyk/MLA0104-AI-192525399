Algorithm BFS(Graph, Start_Node)

1. Create an empty set called Visited.
2. Create an empty Queue.
3. Enqueue Start_Node into Queue.
4. Add Start_Node to Visited.
5. While Queue is not empty:
      a. Dequeue the front node.
      b. Visit (print) the node.
      c. For each Neighbour of the node:
            i. If Neighbour is not in Visited:
                 - Add Neighbour to Visited.
                 - Enqueue Neighbour into Queue.
6. End.
