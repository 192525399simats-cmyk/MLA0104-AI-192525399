Algorithm BFS(Graph, Start_Node)

 Create an empty set called Visited.
 Create an empty Queue.
 Enqueue Start_Node into Queue.
 Add Start_Node to Visited.
 While Queue is not empty:
       Dequeue the front node.
       Visit (print) the node.
       For each Neighbour of the node:
             If Neighbour is not in Visited:
                 - Add Neighbour to Visited.
                 - Enqueue Neighbour into Queue.
 End.

Algorithm DFS(Graph, Node)

 Create an empty set called Visited.
 Define a function DFS(Node):
       If Node is not in Visited:
             Visit (print) the Node.
              Add Node to Visited.
              For each Neighbour of Node:
                   Call DFS(Neighbour).
 Call DFS(Start_Node).
 End.
