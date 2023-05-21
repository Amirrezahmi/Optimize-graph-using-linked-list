
# Optimize graph using linked list

We implemented the given graph as a greedy database using a linked list and optimized it.



## Description



Graph algorithms are a set of techniques used to solve problems on graphs. A graph is a collection of vertices (nodes) connected by edges. Graph algorithms can be used to solve problems such as finding the shortest path between two nodes, finding the minimum spanning tree of a graph, or detecting cycles in a graph.

One popular graph algorithm is the Kruskal's algorithm, which is used to find the minimum spanning tree (MST) of a graph. A minimum spanning tree is a tree that connects all the vertices in a graph with the minimum possible total weight. For example, if we have a graph with 5 vertices, the minimum spanning tree would be a tree with 4 edges that connects all 5 vertices with the minimum possible total weight.

Kruskal's algorithm works by sorting all the edges in the graph by weight and then adding the edges to the MST one by one, starting with the edge with the lowest weight. However, when adding an edge, we must make sure that it doesn't create a cycle in the MST. If adding an edge creates a cycle, we skip that edge and move on to the next edge.

In my jupyter notebook I explained everything needed to know for implementing.



## Used By

This project is used by computer science students who are studying algorithms.
