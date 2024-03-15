# C++ Dijkstra Algorithm

## Overview
This repository contains a C++ implementation of Dijkstra's shortest path algorithm. It's designed as a library (`dijkstra.cpp`) with an accompanying header file (`dijkstra.hpp`), intended for calculating the shortest path in directed graphs.

## Usage

### Input
- **vector<int>**: Represents the edges and weights in the graph (e.g., `{1, 2, 3, 1, 4, 2}` indicates an edge from vertex 1 to vertex 2 with a weight of 3, and from vertex 1 to vertex 4 with a weight of 2).
- **int vsize**: Number of vertices in the graph.
- **int startv**: ID of the starting vertex.
- **int endv**: ID of the ending vertex.

### Output
The function returns a string indicating the shortest distance and the path taken (e.g., `"1; 1 2"` signifies the shortest path from vertex 1 to 2 with a distance of 1).

## Compilation Instructions

### For Linux
`g++ yourfile.cpp dijkstra.cpp -o yourfile.out`. And run `yourfile.out`

### Windows
`g++ yourfile.cpp dijkstra.cpp -o yourfile.exe`. And then `start yourfile.exe`