Algorithm DFS(Graph, StartNode)

Initialize Stack S
Initialize Visited as an empty set

Push(StartNode)

while Stack is not empty do
    Node ← Pop(Stack)

    if Node is not in Visited then
        Print(Node)
        Add Node to Visited

        for each Neighbor in reverse(Graph[Node]) do
            Push(Neighbor)
        end for
    end if
end while
