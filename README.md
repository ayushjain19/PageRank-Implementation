# PageRank-Implementation

*The code implements the PageRank algorithm, which ranks the
pages in the corpus by considering inlinks and outlinks.*

Following are the packages used in the execution of the program:
* numpy
* operator
* networkx
* matplotlib
* pylab


Following are the steps taken in the implementation of the
algorithm:
1. Reading the data
1. Defining the Transition matrix and the v matrix which defines the probability
of the random surfer of being at any paricular node
1. Definining the teleport matrix which takes care of the Dead ends and Spider
traps
1. Iterating the formula v = M.v until v stops changing anymore
1. Incorporating the concept of Trust rank
1. Sorting nodes with respect to the rank of each node
1. Ploting the inlinks and outlinks for the top rated nodes
