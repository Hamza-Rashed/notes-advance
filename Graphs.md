
# Graphs

A graph is a non-linear data structure that can be looked at as a collection of vertices (or nodes) potentially connected by line segments named edges.

Here is some common terminology used when working with Graphs:

    Vertex - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
    Edge - An edge is a connection between two nodes.
    Neighbor - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
    Degree - The degree of a vertex is the number of edges connected to that vertex.

# Directed vs Undirected
Undirected Graphs

An Undirected Graph is a graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.

For example, in the graph below, Node C is connected to Node A, Node E and Node B. There are no “directions” given to point to specific vertices. The connection is bi-directional.

![](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/UndirectedGraph.PNG)

Undirected Graph

The undirected graph we are looking at has 6 vertices and 7 undirected edges.

Vertices/Nodes = {a,b,c,d,e,f}

Edges = {(a,c),(a,d),(b,c),(b,f),(c,e),(d,e),(e,f)}

