# Graphs
This is an implementation of a directed graph (data structure), its traversals, and its complementary algorithms. These include:
* Breadth First Search (traversal)
* Depth First Search (traversal)
* Topological Sort (traversal)
* Algorithm to check if graph is cyclic
* Algorithm to check if graph is a tree
* Algorithm to check if graph is bipartite

The graphs are represented using an adjacency list as well as an adjacency matrix, and are generated by reading files. Currently, the program is set to read 4 files, therefore generating 4 graphs; but it may be changed to read up to any number
of files.

## Technologies
Project uses C++11

## Setting up
Place all files in the same folder and run main.cpp. The results will be shown in terminal.

## Making changes
### Changing number of files to be read
To read more or less files, and therefore test more or less graphs, simply change the value of the variable numberFiles in the main function. All files must be named in the following format: graph_#.txt, example: graph_4.txt.

## About the files
Here are the contents of one of the files:
4
4
0,1
0,3
1,3
3,2

The first line is for the number of vertices in the graph, the second for the number of adjacencies, and the rest represent the adjacencies. For example, there is an directed adjacency from vertex 0 to vertex 1. Notice every adjacency is written in its own line and is represented by two numbers seperated by a comma.
