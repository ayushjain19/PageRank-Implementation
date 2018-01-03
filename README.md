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

**Design**
* Transition matrix and the v matrix are defined which defines the probability of the random surfer of being at any paricular node.
* Dead ends and Spider traps are handeled by the teleport matrix. 
* The formula v = M.V is iterated until v stops changing which gives us the final probability of the random surfer
being at any particular node. 
* After this, the concept of TrustRank is added to the existing
codebase. TrustRank considers the teleport matrix being biased only to certain trusted
pages.
* In the end top few node pages are plotted which represents the inlinks and outlinks from
the nodes.
