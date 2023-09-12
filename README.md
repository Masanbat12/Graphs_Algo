# Graph Implementation in C

This repository contains an implementation of a graph data structure in C. This implementation is a collaborative effort by Aaron Luchan and Masanbat Mulo.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Compilation](#compilation)
- [Function Descriptions](#function-descriptions)
- [Contribution](#contribution)

## Features

- Creation of a graph using nodes and edges.
- Capability to add and remove nodes.
- Capability to add and remove edges.
- Dijkstra algorithm implementation for shortest path computation.
- Command-based functions for building and printing the graph.
- Memory-efficient, leveraging dynamic memory allocation.

## Usage

This graph implementation is equipped with functionalities to manage nodes and edges. You can add, remove nodes, and edges, as well as find the shortest path using Dijkstra's algorithm.

1. Use the function `add_node(pnode head)` to add a node to the graph.
2. Use `add_edges(pedge edges, pnode head)` to add edges to the graph.
3. `deleteNode(pnode *graph)` is used to remove a node from the graph.
4. If you wish to find the shortest path between two nodes, use `dijkstra(pnode head, int src, int dest,int flag)` where the flag determines if the path should be printed or not.

## Compilation

To compile the code, use the provided Makefile with the following commands:

```bash
$ make all      # Compile all source files and produce the executable 'graph'
$ make clean    # Clean all compiled objects and the 'graph' executable

## Function Descriptions

char build_graph_cmd(pnode head): TBD (Description not provided in the initial code).
char add_edges(pedge edges,pnode head): Adds edges to the specified node in the graph.
char add_node(pnode head): Adds a new node to the graph.
void remove_edges(pedge edges): Removes all edges connected to the given node.
int dijkstra(pnode head, int src, int dest,int flag): Computes the shortest path from source to destination using Dijkstra's algorithm.
void deleteNode(pnode *graph): Deletes a specified node from the graph.
void printGraph_cmd(pnode head): Print the graph (for debugging purposes).
Contribution
The main contributors to this project are:

Masanbat Mulu
Aaron Luchan

# מימוש של גרף בשפת C
פרויקט זה מכיל ביצוע של מבנה נתונים של גרף בשפת התכנות C

### תכנים

- יצירה וניהול של גרף באמצעות צמתים וקשתות.
- אפשרות להוספה והסרה של צמתים וקשתות.
- ביצוע של אלגוריתם דייקסטרה לחישוב המסלול הקצר ביותר.
- פונקציות בסטייל פקודות לבניית והדפסה של הגרף.

הקוד נעשה על ידי :
מסנבט מולו
אהרון לוחן