# Recommendation Metro System

### Introduction
This project uses data from the Singapore MRT Map to analyze and visualize the transportation network.
It involves the implementation of a transportation network analysis using various algorithms and data structures. The main components of the project include:

1. **Union-Find Data Structure**: Used to manage and merge disjoint sets.
2. **Edge Class and EdgeList Class**: Represents the edges in the graph with weights, source, and destination nodes. Manages a collection of edges and provides utility functions.
3. **Data Processing**: Reads and processes data from files to create maps and coordinates for stations.
4. **Constructing the Edge List**: Creates an edge list for the transportation network by calculating distances between consecutive stations.
5. **Dijkstra's Algorithm**: Finds the shortest path between two nodes in the graph.
6. **Visualization**: Plots the transportation network and the shortest path using Matplotlib.

The project reads data from CSV files, processes it to create a graph representation of the transportation network, constructs an edge list, and then uses Dijkstra's algorithm to find and visualize the shortest path between two stations.
