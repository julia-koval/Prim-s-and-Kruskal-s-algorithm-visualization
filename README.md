# Prim-s-and-Kruskal-s-algorithm-visualization
Step by step work of greedy algorithms that find a minimum spanning tree for a weighted undirected graph in Wolfram Mathematica

Prim's algorithm

Input - connected undirected graph. Weight is set for each edge.

First, an arbitrary vertex is taken and an edge is found that is incident to this vertex and has the least cost. The found edge and the two peaks connected by it form a tree. Then, we consider the edges of the graph, one end of which is a vertex already belonging to the tree, and the other is not; From these edges the edge of the least cost is selected. The edge selected at each step joins the tree. The tree grows until all the vertices of the original graph are exhausted.

The result of the algorithm is a spanning tree of minimum cost.

Kruskal's algorithm

At the beginning, the current set of edges is set empty. Then, while it is possible, the following operation is carried out: from all the edges, the addition of which to the existing set does not cause the appearance of a cycle in it, the edge of the minimum weight is selected and added to the existing set. When there are no more such edges, the algorithm is completed. The subgraph of this graph containing all its vertices and the set of edges found is its spanning tree of minimal weight.
