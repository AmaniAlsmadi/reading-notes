# Readings: Graphs

- **Graph** is a non-linear data structure consisting of nodes and edges. The nodes are sometimes also referred to as vertices and the edges are lines or arcs that connect any two nodes in the graph. More formally a Graph can be defined as, A Graph consisting of a finite set of vertices(or nodes) and a set of edges that connect a pair of nodes.

- **Types of Graphs:**

1. **Finite:** it has a finite number of vertices and a finite number of edges. 

2. **Infinite:** it has an infinite number of vertices as well as an infinite number of edges.  

3. **Trivial:** finite graph contains only one vertex and no edge.
4. **Simple:** a graph that does not contain more than one edge between the pair of vertices. 
5. **Multi:**Any graph which contains some parallel edges but doesn’t contain any self-loop is called a multigraph. has two type:

     -  Parallel Edges.
     - Loop.

6. **Null:** A graph of order n and size zero is a graph where there are only isolated vertices with no edges connecting any pair of vertices.
7. **Complete:** A simple graph with n vertices.
8. **Pseudo:** A graph G with a self-loop and some multiple edges.
9. **Regular :** A simple graph with all vertices of graph G of equal degree.
10. **Bipartite:**
11. **Labeled:**the vertices and edges of a graph are labeled with name, date, or weight .
12. **Digraph:**
13. **Subgraph:**
14. **Connected or Disconnected:**
     - Graph G is said to be connected if any pair of vertices (Vi, Vj) of a graph G is reachable from one another.
     - graph is said to be connected if there exists at least one path between each and every pair of vertices in graph G.
     -  A null graph with n vertices is a disconnected graph consisting of n components.
15. **Cyclic:** A graph G consisting of n vertices and n> = 3 that is V1, V2, V3- – – – Vn and edges (V1, V2), (V2, V3), (V3, V4)- – – – (Vn, V1) are called cyclic graph. 
16. **Types of Subgraphs:**

     - Vertex disjoint subgraph
     - Edge disjoint subgraph

- **properties of Graphs**
     - Distance between two Vertices: It is basically the number of edges that are available in the shortest path between vertex A and vertex B.

     - The eccentricity of a Vertex:Maximum distance from a vertex to all other vertices is considered as the Eccentricity of that vertex. 

     - Radius of a Connected Graph: The minimum value of eccentricity from all vertices is basically considered as the radius of connected graph.
     
     - Diameter of A Connected Graph:Unlike the radius of the connected graph here we basically used the maximum value of eccentricity from all vertices to determine the diameter of the graph. 

     - Central Point and Centre:The vertex having minimum eccentricity is considered as the central point of the graph.And the sets of all central point is considered as the centre of Graph.

## Difference between graph and tree

**Graph :**

A graph is a collection of two sets V and E where V is a finite non-empty set of vertices and E is a finite non-empty set of edges.

- Vertices are nothing but the nodes in the graph.
- Two adjacent vertices are joined by edges.
- Any graph is denoted as G = {V, E}.

**Tree :**

A tree is a finite set of one or more nodes such that –

- There is a specially designated node called root.
- The remaining nodes are partitioned into n>=0 disjoint sets T1, T2, T3, …, Tn 
where T1, T2, T3, …, Tn are called the subtrees of the root.
     
    