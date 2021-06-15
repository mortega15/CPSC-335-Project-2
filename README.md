# CPSC-335-Project-2
__Group Members: Maria Ortega and Neal Vaghasia__

                                                    Introduction
This project asks you to use a library that implements a graph data structure to implement the Prim-Jarnik algorithm. There are three components:

1. Executing the Prim-Jarnik algorithm by hand in order to generate baseline results
2. Setting up code to reproduce the example graphs using the NGraph library
3. Implementing the Prim-Jarnik algorithm and running your implementation on the example graphs

The project must be completed working together in a pair with another student.


                                      Part 1: Executing the Prim-Jarnik Algorithm by hand

For this first part of the project we completed exercises 6-3 (b) and 6-3 (c) from _Algorithm Design in Three Acts_. These exercises required us to show our work and execute the Prim-Jarnık algorithm by hand on the indicated graphs.

![image](https://user-images.githubusercontent.com/79822470/122002137-36855c80-cd66-11eb-820c-b2ea692425e8.png)


                                    Part 2: Reproducing the example graphs in C++
 For part 2 we downloaded the two source files:
* ngraph.hpp from ngraph_4_2.zip
* set_ops.hpp from ngraph_toolkit_4_5.zip

Utilizing these two source files we implemented two programs for both exercises in C++17. Each of the programs includes the folowing:

* NGraph::Graph instance representing the graph in the exercise
* a weight matrix
* print out each vertex, edge, and weight

![image](https://user-images.githubusercontent.com/79822470/122003450-f7580b00-cd67-11eb-9fa1-9fc0e599f613.png)



                                  Part 3: Implementing the Prim-Jarnik Algorithm

For part 3 of this project we created a separate source file to implement the Prim-Jarnik algorithm as a function on NGraph::Graph objects and weight matrices. For the output we displayed each edge in the minimum spanning tree and its total weight. We saved the output for each in a .txt file. We also compared our output to our hand-written answers from part 1 of the project. 
                                        
