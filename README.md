Download Link: https://assignmentchef.com/product/solved-csi2110-lab10-dijkstras-algorithm
<br>
<h2>Dijkstra’s Algorithm</h2>

Download the archive Lab10.zip and extract the WeightGraph application. The application is similar to SimpleGraph except that it expects to read an edge-list from a file where the edges are weighted. The archive contains the airports’ example from the textbook in the file airports.txt. The Graph is again stored as AdjacencyMapGraph and the application simple prints all the vertices followed by all the edges for verification.

<h2>Study the Goodrich et al. Implementation</h2>

Study the Dijkstra implementation by Goodrich et al. (Chapter 14, page 660). The implementation follows closely our discussion in class. Notice that the algorithm assumes that the edges’ elements are now an integer wheigth, instead of a string.

<h2>Find the Shortest Path</h2>

The program WeightGraph has a routine void printAllShortestDistances( String vert ) which currently does nothing. Please implement this routine by constructing a GraphAlgorithms object and calling the shortestPathLengths method on it. After execution, the routine should print the distance between the source vertex and all other vertices with a name longer than 2 letters. In this way, you may define intermediate vertices for the graph but they will not be printed.

<h2>Expected output</h2>