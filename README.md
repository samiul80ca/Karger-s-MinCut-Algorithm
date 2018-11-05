# Karger-s-MinCut-Algorithm
In this part, we have implemented 5 functions. Firstly, we have initialized and load the graph.
The first task is random edge selection. After that it merges the edges with the corresponding vertices and update the references. Suppressing the graph nodes are more likely to produce self-loops, hence self-loop has been removed. The update of total edges as well the update of the cut grouping is performed afterwards. Then we have calculated the minimum cut and returned the minimum cut value along with the 2 super vertices.
